# 📚 FAQ - Perguntas Frequentes

> **Respostas para as dúvidas mais comuns dos estudantes**

## 🤔 Perguntas Gerais

### É realmente gratuito?

**Sim!** O GitHub Pages oferece hospedagem gratuita para sites estáticos. Você só paga se quiser:

- Repositórios privados (mas para blogs, público é melhor)
- Domínio personalizado (opcional)
- Recursos avançados de organizações

### Preciso saber programar?

**Não!** Este template foi feito para ser usado apenas com Markdown. Você precisa saber:

- ✅ Editar texto simples
- ✅ Markdown básico (aprende em 10 minutos)
- ❌ HTML, CSS ou JavaScript

### Posso usar no celular?

**Sim!** Você pode criar e editar posts diretamente pelo GitHub no navegador do celular. Não é a experiência mais confortável, mas funciona.

### Meu blog pode crescer e ficar profissional?

**Absolutamente!** Muitos desenvolvedores e empresas usam Jekyll. Você pode:

- Adicionar domínio personalizado
- Customizar design
- Adicionar funcionalidades
- Migrar para hospedagem paga quando necessário

## 🛠️ Problemas Técnicos

### "Meu blog não aparece"

**Checklist básico:**

1. Repositório é público? ✅
2. GitHub Pages está ativado? ✅
3. Aguardou 10 minutos? ✅
4. URL está correta? `https://usuario.github.io/repositorio`

**Se ainda não funciona:**

- Vá em Settings → Pages
- Verifique se há mensagens de erro
- Tente desativar e reativar o Pages

### "Post não aparece na página inicial"

**Verifique:**

1. **Nome do arquivo**: `YYYY-MM-DD-titulo.md` ✅
2. **Localização**: Pasta `_posts/` ✅
3. **Data**: Não pode ser futura ✅
4. **Frontmatter**: Completo e correto ✅

### "Layout está quebrado"

**Possíveis causas:**

- Erro no `_config.yml` (espaçamento, sintaxe)
- Frontmatter malformado em algum post
- Caracteres especiais sem aspas

**Solução:**

- Compare com o template original
- Use um validador YAML online
- Reverta mudanças recentes

### "Erro 404 no meu blog"

**Verificar:**

1. URL correta: `usuario.github.io/nome-repositorio`
2. Se o repo se chama `usuario.github.io`, a URL é só `usuario.github.io`
3. GitHub Pages ativado corretamente
4. Aguardar tempo de propagação

## 📝 Sobre Escrita e Conteúdo

### "Não sei sobre o que escrever"

**Ideias por área:**

**👨‍💻 Programação:**

- "Meu primeiro Hello World em [linguagem]"
- "5 erros que cometi aprendendo X"
- "Projeto: Criando uma calculadora"
- "Comparando X vs Y"

**📚 Estudos Gerais:**

- "Como organizo minha agenda de estudos"
- "Resenha: Livro/curso que fiz"
- "Técnica de memorização que funciona"
- "Meu setup de estudos"

**🎯 Carreira:**

- "Por que decidi mudar de área"
- "Minha rotina de estudos"
- "Networking para iniciantes"
- "Como busco vagas"

### "Meus posts ficam muito pequenos"

**Não há problema!** Posts pequenos são ótimos:

- Mais fáceis de escrever
- Leitores preferem conteúdo direto
- Você escreve com mais frequência

**Dicas para expandir:**

- Adicione exemplos práticos
- Conte sua experiência pessoal
- Inclua links para recursos
- Faça perguntas ao leitor

### "Meus posts ficam muito grandes"

**Quebrar em partes:**

- Série de posts: "Aprendendo Python - Parte 1"
- Usar mais subtítulos
- Criar posts separados para cada conceito

### "Ninguém lê meu blog"

**É normal no início!** Estratégias:

- Escreva com frequência
- Compartilhe nas redes sociais
- Comente em outros blogs
- Participe de comunidades online
- Seja paciente - crescimento é gradual

## 🎨 Personalização

### "Como mudar as cores?"

O tema Minima tem cores fixas, mas você pode:

1. **Mudar tema**: `theme: cayman` no `_config.yml`
2. **CSS customizado**: Criar arquivo de estilo próprio (avançado)
3. **Escolher tema diferente**: Vários disponíveis no GitHub Pages

### "Como adicionar imagens?"

**Opção 1 - Upload no repositório:**

```markdown
![Descrição da imagem](caminho/para/imagem.jpg)
```

**Opção 2 - Hospedar externamente:**

```markdown
![Descrição](https://imgur.com/link-da-imagem.jpg)
```

**Dicas:**

- Use images de qualidade mas não muito pesadas
- Sempre adicione texto alternativo (para acessibilidade)
- Prefira PNG para screenshots, JPG para fotos

### "Como adicionar comentários?"

O template inclui suporte para **Disqus**:

1. Crie conta no [Disqus](https://disqus.com)
2. Adicione no `_config.yml`:

```yaml
disqus:
  shortname: seu-shortname-disqus
```

## 📊 Analytics e SEO

### "Como saber quantas pessoas visitam?"

**Google Analytics** (gratuito):

1. Crie conta no [Google Analytics](https://analytics.google.com)
2. Adicione o código no `_config.yml`:

```yaml
google_analytics: UA-XXXXXXXX-X
```

**Alternativas:**

- Plausible Analytics
- Simple Analytics
- Fathom Analytics

### "Como aparecer no Google?"

O template já inclui **SEO básico**:

- Meta tags automáticas
- Sitemap gerado automaticamente
- Feed RSS

**Para melhorar:**

- Títulos descritivos
- Conteúdo original e útil
- Links para outros sites relevantes
- Postagem regular

## 🔧 Funcionalidades Avançadas

### "Como adicionar busca?"

Opções:

1. **Jekyll Search** (plugin)
2. **Google Site Search**
3. **Lunr.js** (JavaScript)

### "Como fazer backup?"

Seu código já está no GitHub (backup automático)!

**Backup adicional:**

- Download periódico do repositório
- Clone local: `git clone https://github.com/usuario/repo.git`

### "Como usar domínio próprio?"

1. **Compre um domínio** (GoDaddy, Namecheap, etc.)
2. **Configure DNS** para apontar para GitHub Pages
3. **Adicione arquivo CNAME** no repositório com seu domínio
4. **Ative HTTPS** nas configurações

## 💬 Onde Buscar Ajuda

### Comunidades brasileiras

- **Discord** - Comunidades de programação
- **Telegram** - Grupos de estudos
- **Reddit** - r/brasil, r/programacao

### Documentação oficial

- [Jekyll Docs](https://jekyllrb.com/docs/)
- [GitHub Pages](https://docs.github.com/pages)
- [Markdown Guide](https://www.markdownguide.org/)

### Canais YouTube

- Procure por "Jekyll tutorial português"
- "GitHub Pages tutorial"
- "Blog com Jekyll"

---

**💡 Não encontrou sua dúvida?**

Abra uma [issue no repositório](https://github.com/usuario/repo/issues) ou me mande uma mensagem!
