# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

## 🚀 Início Rápido com "Use this template"

### 1️⃣ Crie seu repositório

1. **Clique no botão verde "Use this template"** no topo desta página
2. **Selecione "Create a new repository"**
3. **Nomeie seu repositório**: 
   - Exemplo: `meu-blog-educacional`
   - ✅ Use letras minúsculas e hífens
   - ❌ Evite espaços e caracteres especiais
4. **Marque como "Public"** (necessário para GitHub Pages gratuito)
5. **Clique em "Create repository"**

### 2️⃣ Personalize suas informações

1. **No seu novo repositório**, clique no arquivo `_config.yml`
2. **Clique no ícone de lápis (✏️)** para editar
3. **Altere suas informações**:

   ```yaml
   title: "Blog da Maria Silva"        # Nome do seu blog
   description: "Minha jornada aprendendo programação"  # Descrição
   author: "Maria Silva"               # Seu nome
   email: "maria.silva@email.com"      # Seu email
   ```

4. **Role até o final** e clique em **"Commit changes"**

### 3️⃣ Ative o GitHub Pages

1. **Vá em "Settings"** (aba no topo do repositório)
2. **Role até "Pages"** na barra lateral esquerda
3. **Em "Source"**, selecione **"Deploy from a branch"**
4. **Escolha "main"** como branch
5. **Clique em "Save"**

🎉 **Pronto!** Seu blog estará disponível em: `https://seuusuario.github.io/nome-do-repositorio`

> ⏰ **Aguarde 5-10 minutos** para o blog ficar online na primeira vez.

---

## 📝 Instruções Detalhadas

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

---

# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem. O template é otimizado para GitHub Pages e foi projetado para ser **extremamente simples de usar** - você só precisa saber editar arquivos Markdown!

## ✨ Por que usar este template?

- 🎯 **Feito para estudantes**: Interface limpa e foco no conteúdo educacional
- 🚀 **Deploy automático**: Publica automaticamente no GitHub Pages
- 📱 **Responsivo**: Funciona perfeitamente em celular, tablet e desktop
- 🆓 **Totalmente gratuito**: Hospedagem gratuita no GitHub Pages
- ⚡ **Super rápido**: Não precisa instalar nada para começar
- 🎨 **Personalizável**: Fácil de customizar cores, layout e informações
- 📖 **Bem documentado**: Guia completo para iniciantes

## 🎯 Para quem é este template?

- **Estudantes universitários** documentando projetos e pesquisas
- **Pessoas em transição de carreira** compartilhando o processo de aprendizagem
- **Autodidatas** criando um portfólio de conhecimento
- **Professores** querendo criar blogs para suas disciplinas
- **Qualquer pessoa** que quer um blog simples e elegante

## 📋 Pré-requisitos

**Boa notícia**: Você não precisa instalar nada no seu computador! Tudo funciona direto no navegador.

**O que você precisa ter**:
- Uma conta no [GitHub](https://github.com) (gratuita)
- Conhecimento básico de Markdown ([aprenda em 5 minutos](https://guides.github.com/features/mastering-markdown/))
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

**O que você NÃO precisa**:
- ❌ Instalar Ruby, Jekyll ou outras ferramentas
- ❌ Usar linha de comando
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar (Passo a passo detalhado)

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

### Erros