# Blog Educacional - Template Jekyll

Este é um template de blog educacional criado com Jekyll e otimizado para GitHub Pages. O objetivo é fornecer uma base simples e intuitiva para estudantes criarem seus próprios blogs educacionais.

## 🚀 Como começar

### 1. Configuração inicial

1. **Fork este repositório** ou **baixe os arquivos**
2. **Edite o arquivo `_config.yml`** com suas informações:

   ```yaml
   title: Seu Nome do Blog
   description: Sua descrição
   author: Seu Nome
   email: seuemail@exemplo.com
   ```

3. **Personalize a página "Sobre"** editando o arquivo `about.md`

### 2. Publicando no GitHub Pages

1. Crie um repositório no GitHub
2. Faça upload dos arquivos do template
3. Vá em **Settings** → **Pages**
4. Selecione **Deploy from a branch** → **main**
5. Seu blog estará disponível em: `https://seuusuario.github.io/nome-do-repositorio`

## 📝 Como criar posts

### Estrutura dos posts

Os posts devem ser criados na pasta `_posts/` seguindo o padrão de nome:

```
YYYY-MM-DD-titulo-do-post.md
```

### Frontmatter obrigatório

Todo post deve começar com o frontmatter (metadados) no formato YAML:

```yaml
---
layout: post
title: "Título do Seu Post"
date: YYYY-MM-DD HH:MM:SS +0000
categories: categoria1 categoria2
---
```

### Exemplo de post completo

```markdown
---
layout: post
title: "Minha Experiência Aprendendo Python"
date: 2025-07-05 10:00:00 +0000
categories: programacao python
---

## Introdução

Neste post vou compartilhar minha jornada aprendendo Python...

### O que aprendi

- Conceitos básicos de programação
- Estruturas de dados
- Como criar projetos práticos

## Conclusão

Python é uma linguagem incrível para iniciantes...
```

## 📁 Estrutura do projeto

```
blog-template/
├── _config.yml          # Configurações do Jekyll
├── _posts/              # Pasta dos posts
│   ├── 2025-07-05-meu-primeiro-post.md
│   └── 2025-07-05-como-organizar-estudos.md
├── index.md             # Página inicial
├── about.md             # Página "Sobre"
└── README.md            # Este arquivo
```

## 🎨 Personalização

### Mudando o tema

O template usa o tema `minima` por padrão. Para mudar, edite o `_config.yml`:

```yaml
theme: cayman  # ou outro tema suportado pelo GitHub Pages
```

Temas suportados pelo GitHub Pages:

- `minima` (padrão)
- `cayman`
- `architect`
- `slate`
- `time-machine`
- `leap-day`
- `merlot`
- `midnight`
- `minimal`
- `modernist`
- `tactile`
- `dinky`

### Adicionando redes sociais

No `_config.yml`, na seção `minima`, adicione seus perfis:

```yaml
minima:
  social_links:
    twitter: seuusuario
    github: seuusuario
    linkedin: seuusuario
    instagram: seuusuario
```

## 📚 Dicas para escrever bons posts

### 1. Use títulos descritivos

- ✅ "Como Organizar Seus Estudos Usando a Técnica Pomodoro"
- ❌ "Dicas de Estudo"

### 2. Organize com subtítulos

Use `##` e `###` para criar uma hierarquia clara no seu conteúdo.

### 3. Adicione categorias relevantes

```yaml
categories: programacao tutorial iniciante
```

### 4. Use markdown para formatação

```markdown
**Negrito**, *itálico*, `código inline`

- Lista com marcadores
- Item 2

1. Lista numerada
2. Item 2

> Citação importante

[Link para algum site](https://exemplo.com)
```

## 🔧 Funcionalidades incluídas

- ✅ **Responsivo**: Funciona bem em mobile e desktop
- ✅ **SEO otimizado**: Meta tags automáticas
- ✅ **Feed RSS**: Gerado automaticamente
- ✅ **Sintaxe highlighting**: Para códigos de programação
- ✅ **Comentários**: Suporte para Disqus (opcional)
- ✅ **Google Analytics**: Suporte incluído (opcional)

## 🆘 Solução de problemas

### Meu blog não aparece no GitHub Pages

1. Verifique se o repositório é público
2. Confirme que o GitHub Pages está habilitado nas configurações
3. Aguarde alguns minutos para o build ser processado

### Erros no _config.yml

- Certifique-se de que a indentação está correta (use espaços, não tabs)
- Verifique se todos os dois pontos têm um espaço depois deles

### Post não aparece na página inicial

- Verifique se o nome do arquivo segue o padrão `YYYY-MM-DD-titulo.md`
- Confirme se o frontmatter está correto
- Verifique se a data não está no futuro

## 📝 Exemplos de categorias

Organize seus posts com categorias relevantes:

- `programacao` - Para posts sobre código e desenvolvimento
- `dicas` - Para dicas de estudo e produtividade
- `reflexoes` - Para pensamentos e insights
- `tutoriais` - Para guias passo-a-passo
- `resenhas` - Para reviews de livros, cursos, etc.
- `projetos` - Para mostrar seus projetos pessoais

## 🤝 Contribuindo

Se você encontrar algum problema ou tiver sugestões de melhoria, fique à vontade para abrir uma issue ou pull request!

---

**Happy blogging!** 📚✨

*Template criado com ❤️ para a comunidade educacional*
