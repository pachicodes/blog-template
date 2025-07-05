# 📚 Blog Educacional - Template Jekyll

> **Template completo e didático para criar blogs educacionais usando Jekyll e GitHub Pages**

Este é um template de blog educacional criado especialmente para **estudantes** que querem documentar e compartilhar sua jornada de aprendizagem.

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
- ❌ Conhecer programação
- ❌ Pagar por hospedagem

## 🚀 Como começar em 3 passos simples

### 1️⃣ Crie seu repositório

1. **Clique no botão verde "Use this template"** no topo desta página
2. **Selecione "Create a new repository"**
3. **Nomeie seu repositório**:
   - Exemplo: `blog`
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
5. **Personalize a página "Sobre"** editando o arquivo `about.md`

### 3️⃣ Ative o GitHub Pages

1. **Vá em "Settings"** (aba no topo do repositório)
2. **Role até "Pages"** na barra lateral esquerda
3. **Em "Source"**, selecione **"Deploy from a branch"**
4. **Escolha "main"** como branch
5. **Clique em "Save"**

🎉 **Pronto!** Seu blog estará disponível em: `https://seuusuario.github.io/nome-do-repositorio`

> ⏰ **Aguarde 5-10 minutos** para o blog ficar online na primeira vez.

## 📖 Documentação Completa

Este template inclui documentação detalhada para diferentes níveis:

- **📚 [GUIA-INICIANTES.md](GUIA-INICIANTES.md)** - Guia passo a passo para quem nunca usou GitHub ou Jekyll
- **✍️ [GUIA-ESCRITA.md](GUIA-ESCRITA.md)** - Como escrever posts envolventes e educacionais


## 📝 Criando posts

Para criar posts, consulte o **[GUIA-INICIANTES.md](GUIA-INICIANTES.md)** que contém instruções detalhadas passo a passo.

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

**Temas suportados pelo GitHub Pages** ([veja todos aqui](https://pages.github.com/themes/)):

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

> **💡 Dica**: Clique no link acima para ver a aparência de cada tema e escolher o que mais combina com seu estilo!

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

## 🔧 Funcionalidades incluídas

- ✅ **Responsivo**: Funciona bem em mobile e desktop
- ✅ **SEO otimizado**: Meta tags automáticas
- ✅ **Feed RSS**: Gerado automaticamente
- ✅ **Sintaxe highlighting**: Para códigos de programação
- ✅ **Comentários**: Suporte para Disqus (opcional)
- ✅ **Google Analytics**: Suporte incluído (opcional)

## 🆘 Solução de problemas

Para soluções detalhadas de problemas comuns, consulte o **[GUIA-INICIANTES.md](GUIA-INICIANTES.md)**.

**Problemas mais comuns:**
- Blog não aparece: Verifique se é público e o GitHub Pages está ativado
- Erros no _config.yml: Verifique indentação (use espaços, não tabs)
- Post não aparece: Verifique nome do arquivo (YYYY-MM-DD-titulo.md)

## 🤝 Contribuindo

Se você encontrar algum problema ou tiver sugestões de melhoria, fique à vontade para abrir uma issue ou pull request!

---

**Happy blogging!** 📚✨

*Template criado com ❤️ para a comunidade educacional*
