# 🚀 Referência Rápida

> **Consulta rápida para quem já tem o blog configurado**

## ✍️ Criando um novo post

### 1. Nome do arquivo

```
_posts/YYYY-MM-DD-titulo-do-post.md
```

### 2. Template base

```markdown
---
layout: post
title: "Título do Post"
date: 2025-07-05 12:00:00 +0000
categories: categoria1 categoria2
---

## Introdução

Conteúdo do post aqui...

### Subtítulo

Mais conteúdo...

## Conclusão

Resumo e considerações finais.

---

*Mensagem final* ✨
```

## 🎯 Categorias sugeridas

| Categoria | Uso |
|-----------|-----|
| `estudos` | Dicas de estudo e organização |
| `programacao` | Posts sobre código e desenvolvimento |
| `projetos` | Projetos pessoais e acadêmicos |
| `reflexoes` | Pensamentos sobre aprendizagem |
| `tutoriais` | Guias passo a passo |
| `resenhas` | Reviews de livros, cursos, ferramentas |
| `carreira` | Desenvolvimento profissional |
| `tecnologia` | Novidades e tendências tech |

## 📝 Markdown essencial

```markdown
# Título 1
## Título 2
### Título 3

**Negrito** ou __negrito__
*Itálico* ou _itálico_
`código inline`

- Lista não ordenada
- Item 2

1. Lista ordenada
2. Item 2

> Citação ou destaque

[Texto do link](https://exemplo.com)

![Alt da imagem](url-da-imagem)
```

## 💻 Blocos de código

### Código simples

````markdown
```
código sem syntax highlighting
```
````

### Código com linguagem

````markdown
```python
def hello():
    print("Hello, World!")
```
````

### Linguagens suportadas

- `python`, `javascript`, `html`, `css`
- `java`, `cpp`, `c`, `csharp`
- `bash`, `sql`, `yaml`, `json`
- E muitas outras...

## 🔧 Configurações rápidas

### Alterando título do blog

No `_config.yml`:

```yaml
title: "Novo Título do Blog"
```

### Adicionando descrição

```yaml
description: "Nova descrição do blog"
```

### Mudando tema

```yaml
theme: cayman  # ou minima, architect, slate
```

### Redes sociais

```yaml
minima:
  social_links:
    github: seuusuario
    twitter: seuusuario
    linkedin: seuusuario
```

## 📅 Datas e horários

### Formato da data

```yaml
date: 2025-07-05 14:30:00 +0000
```

### Fusos horários comuns

- `+0000` - UTC (padrão)
- `-0300` - Brasília (BRT)
- `-0200` - Brasília (BRST, horário de verão)

## 🎨 Customizações visuais

### Emoji úteis

- 📚 📖 📝 ✍️ (estudo)
- 💻 🖥️ ⌨️ 🖱️ (tecnologia)
- 🚀 ⚡ 💡 ✨ (progresso)
- 🎯 🎨 🔧 ⚙️ (ferramentas)
- ✅ ❌ ⚠️ ℹ️ (status)

### Formatação especial

```markdown
> **💡 Dica**: Use esta formatação para destacar informações importantes.

> **⚠️ Atenção**: Para avisos importantes.

> **✅ Sucesso**: Para indicar algo que deu certo.
```

## 🔗 Links úteis

- **Seu blog**: `https://seuusuario.github.io/nome-repositorio`
- **Editor online**: Directly no GitHub (clique no lápis ✏️)
- **Markdown Guide**: [markdownguide.org](https://www.markdownguide.org/)
- **Emoji Cheat Sheet**: [github.com/ikatyang/emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet)

## 🚨 Checklist antes de publicar

- [ ] Nome do arquivo segue padrão `YYYY-MM-DD-titulo.md`
- [ ] Frontmatter completo (layout, title, date, categories)
- [ ] Data não está no futuro
- [ ] Título é descritivo e interessante
- [ ] Texto revisado (ortografia e gramática)
- [ ] Links funcionam corretamente
- [ ] Categorias fazem sentido

## ⏰ Cronograma sugerido

### Para iniciantes

- **1x por semana**: Um post pequeno sobre o que aprendeu
- **Temas**: O que estudou, dificuldades, conquistas

### Para intermediários

- **2-3x por semana**: Posts variados
- **Temas**: Tutoriais, projetos, reflexões

### Para avançados

- **Posts regulares** + séries temáticas
- **Temas**: Conteúdo técnico profundo, análises

## 📊 Ideias de posts por nível

### Iniciante

- "Minha primeira semana estudando X"
- "5 coisas que aprendi hoje"
- "Como organizo meus estudos"
- "Ferramentas que uso para aprender"

### Intermediário

- "Tutorial: Como fazer X passo a passo"
- "Comparação entre X e Y"
- "Projeto: Criando uma aplicação Z"
- "Resenha: Curso/Livro sobre X"

### Avançado

- "Análise profunda do conceito X"
- "Série: Construindo um sistema completo"
- "Performance: Otimizando X para Y"
- "Arquitetura: Decisões de design em projetos reais"

---

**💡 Dica final**: Mantenha consistência! É melhor um post pequeno por semana do que um post gigante por mês.
