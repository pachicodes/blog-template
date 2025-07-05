# 📚 Guia Completo para Iniciantes

> **Este é um guia detalhado para quem nunca usou GitHub ou Jekyll antes!**

## 🎯 O que você vai aprender

Ao final deste guia, você terá:

- ✅ Seu próprio blog educacional online
- ✅ Conhecimento para criar e publicar posts
- ✅ Entendimento básico de como funciona
- ✅ Dicas para personalizar seu blog

## 🚀 Passo 1: Criando sua conta no GitHub

Se você ainda não tem uma conta no GitHub:

1. Acesse [github.com](https://github.com)
2. Clique em **"Sign up"**
3. Escolha um nome de usuário (será parte da URL do seu blog)
4. Use um email válido
5. Confirme sua conta pelo email

## 📋 Passo 2: Obtendo o template

### ✅ Método recomendado: "Use this template"

1. **Acesse o repositório** deste template no GitHub
2. **Clique no botão verde "Use this template"** (localizado no topo da página)
3. **Selecione "Create a new repository"**
4. **Preencha as informações**:
   - **Repository name**: `meu-blog-educacional` (ou outro nome de sua escolha)
   - **Description**: "Meu blog de estudos" (opcional, mas recomendado)
   - **✅ Marque "Public"** (necessário para GitHub Pages gratuito)
   - **❌ NÃO marque** "Include all branches" (deixe desmarcado)
5. **Clique em "Create repository"**

> **💡 Por que "Use this template"?** Este método é mais limpo que o Fork, pois cria um repositório independente sem histórico de commits do template original.

## ⚙️ Passo 3: Configuração inicial

### Editando o arquivo de configuração

1. **No seu novo repositório**, clique no arquivo `_config.yml`
2. **Clique no ícone de lápis** (✏️) para editar
3. **Modifique as informações** para as suas:

```yaml
# Configuração do Blog Educacional
title: Blog da Ana Silva                    # ← Mude para o nome do seu blog
description: Minha jornada aprendendo programação  # ← Sua descrição
author: Ana Silva                           # ← Seu nome
email: ana.silva@email.com                  # ← Seu email

# Não mexa nestas configurações (são técnicas)
baseurl: ""
url: ""
theme: minima
markdown: kramdown
# ... resto do arquivo
```

1. **Role até o final da página**
2. **Escreva uma mensagem** em "Commit changes": `"Atualizei minhas informações"`
3. **Clique em "Commit changes"**

### Personalizando a página "Sobre"

1. **Clique no arquivo `about.md`**
2. **Clique no ícone de lápis** (✏️) para editar
3. **Substitua o conteúdo exemplo** pelas suas informações:

```markdown
---
layout: page
title: Sobre Mim
permalink: /about/
---

## Quem sou eu

Olá! Meu nome é Ana Silva e sou estudante de Ciência da Computação. 
Este blog é onde documento minha jornada de aprendizagem.

## Minha história

Comecei a estudar programação em 2024 e tenho me apaixonado cada 
vez mais por tecnologia. Aqui compartilho:

- O que estou aprendendo
- Dificuldades que enfrento
- Projetos que desenvolvo
- Dicas que descubro

## Entre em contato

📧 Email: ana.silva@email.com
🐙 GitHub: @anasilva
```

1. **Faça commit** das mudanças com uma mensagem: `"Personalizei página sobre"`

## 🚀 Passo 4: Ativando o GitHub Pages

1. **No seu repositório**, clique em **"Settings"** (no topo da página)
2. **Na barra lateral esquerda**, role até encontrar **"Pages"**
3. **Em "Source"**, selecione **"Deploy from a branch"**
4. **Em "Branch"**, escolha **"main"**
5. **Deixe a pasta como "/ (root)"**
6. **Clique em "Save"**

### ⏰ Aguardando o blog ficar online

- O GitHub mostrará uma mensagem: "Your site is ready to be published"
- Aguarde 5-10 minutos
- Acesse: `https://seuusuario.github.io/nome-do-repositorio`
- Se apareceu seu blog, parabéns! 🎉

## ✍️ Passo 5: Criando seu primeiro post

### Como criar um novo post

1. **No seu repositório**, entre na pasta **`_posts`**
2. **Clique em "Create new file"**
3. **Nome do arquivo**: `2025-07-05-meu-primeiro-post-original.md`

   > **⚠️ IMPORTANTE**: O nome deve seguir o padrão `YYYY-MM-DD-titulo.md`

4. **Cole este conteúdo** no arquivo:

```markdown
---
layout: post
title: "Meu Primeiro Post Original"
date: 2025-07-05 15:00:00 +0000
categories: pessoal reflexao
---

## Olá, mundo!

Este é meu primeiro post no meu blog educacional! Estou muito animado(a) 
para começar a documentar minha jornada de aprendizagem.

### Por que criei este blog?

Decidi criar este blog porque:

- Quero organizar melhor meus estudos
- Acredito que ensinar ajuda a aprender
- Quero conectar com outras pessoas que estão aprendendo
- É uma forma de criar um portfólio dos meus conhecimentos

### O que vem por aí?

Nos próximos posts, pretendo escrever sobre:

- Conceitos que estou aprendendo
- Projetos que estou desenvolvendo
- Livros e cursos que recomendo
- Desafios que encontro no caminho

### Vamos juntos!

Se você também está aprendendo algo novo, deixe um comentário ou 
entre em contato. Vamos trocar experiências!

---

*Até o próximo post!* 📚✨
```

1. **Role até o final**
2. **Escreva uma mensagem**: `"Adicionei meu primeiro post"`
3. **Clique em "Commit new file"**

### 🎉 Vendo seu post online

- Aguarde 2-3 minutos
- Acesse seu blog: `https://seuusuario.github.io/nome-do-repositorio`
- Seu post deve aparecer na página inicial!

## 🎨 Passo 6: Personalizações básicas

### Alterando cores e tema

No arquivo `_config.yml`, você pode mudar o tema:

```yaml
theme: minima  # Tema atual
# theme: cayman  # Tema alternativo
```

Temas disponíveis: `minima`, `cayman`, `architect`, `slate`, `midnight`

### Adicionando redes sociais

No `_config.yml`, adicione suas redes:

```yaml
minima:
  social_links:
    github: seuusuario
    twitter: seuusuario
    linkedin: seuusuario
```

## 📝 Dicas para escrever bons posts

### 1. Estrutura recomendada

```markdown
---
layout: post
title: "Título Descritivo"
date: YYYY-MM-DD HH:MM:SS +0000
categories: categoria1 categoria2
---

## Introdução
Explique brevemente o que o post vai abordar.

## Desenvolvimento
Desenvolva o conteúdo com subtítulos.

### Subtópico 1
Conteúdo...

### Subtópico 2
Conteúdo...

## Conclusão
Resuma os pontos principais.

---

*Mensagem final para o leitor*
```

### 2. Usando Markdown

```markdown
**Texto em negrito**
*Texto em itálico*
`código inline`

- Lista com marcadores
- Item 2

1. Lista numerada
2. Item 2

> Citação importante

[Link para um site](https://exemplo.com)

![Imagem](url-da-imagem)
```

### 3. Códigos de programação

````markdown
```python
def hello_world():
    print("Hello, World!")
```
````

### 4. Categorias úteis

- `programacao` - Posts sobre código
- `estudos` - Dicas de estudo
- `projetos` - Seus projetos
- `reflexoes` - Pensamentos sobre aprendizagem
- `tutoriais` - Guias passo a passo
- `resenhas` - Reviews de livros/cursos


## 📚 Recursos adicionais

- [Guia de Markdown](https://guides.github.com/features/mastering-markdown/)
- [Documentação Jekyll](https://jekyllrb.com/docs/)
- [GitHub Pages](https://pages.github.com/)
- [Temas Jekyll](https://pages.github.com/themes/)

---

**🎉 Parabéns! Você agora tem seu próprio blog!**

*Continue aprendendo e compartilhando conhecimento!* 📚✨
