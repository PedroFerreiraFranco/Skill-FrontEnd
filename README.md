# 🎯 Senior Frontend Developer Skill

Uma **skill para qualquer IA** (Claude AI, ChatGPT, Gemini, GitHub Copilot, etc.) que ensina boas práticas profissionais de desenvolvimento front-end. Use para receber mentoria, code reviews, arquitetura de projetos e tudo sobre front-end moderno.

---

## 📚 O Que Você Encontra

Um guia completo cobrindo:

✅ **HTML Semântico** — Tags com significado, acessibilidade e SEO  
✅ **CSS Moderno** — Flexbox, Grid, Container Queries, Animações  
✅ **JavaScript ES6+** — Padrões modernos, async/await, fetch  
✅ **TypeScript** — Interfaces, types, utility types, boas práticas  
✅ **React** — Componentes, hooks, React 18+, compound components, Zustand  
✅ **Next.js** — App Router, Server/Client Components, Server Actions, cache  
✅ **Formulários** — react-hook-form, zod, validação acessível  
✅ **Arquitetura** — Cliente-servidor, APIs REST, BFF  
✅ **Node.js & NPM** — Setup, scripts, dependências  
✅ **Clean Code** — Nomes, estrutura, padrões  
✅ **Testing** — Unit, integration, E2E  
✅ **Performance** — Otimizações, debugging, Core Web Vitals  
✅ **Segurança** — XSS, CSRF, variáveis de ambiente  
✅ **Acessibilidade** — WCAG, ARIA, teclado  
✅ **SEO** — Meta tags, Open Graph, schema.json  

---

## 🚀 Como Usar

### 🎯 Compatibilidade
Esta skill funciona em **qualquer ferramenta IA**:
- ✅ Claude.ai
- ✅ ChatGPT / OpenAI
- ✅ Google Gemini
- ✅ GitHub Copilot (VS Code)
- ✅ Qualquer chatbot IA

**⚠️ Nota técnica:** O bloco YAML no topo (linhas 1-11) é específico do GitHub Copilot. Em outras IAs, ele será ignorado automaticamente ou pode ser removido.

---

### Opção 1: Claude.ai (Recomendado)
1. Abra [claude.ai](https://claude.ai)
2. Inicie um novo chat
3. Copie todo o conteúdo de `SKILL.md` (incluindo ou não o YAML)
4. Cole como primeira mensagem
5. Faça sua pergunta sobre front-end

**Exemplo:**
```
[Cole aqui o conteúdo de SKILL.md]

Agora crie um componente Button em React com TypeScript, 
acessível e com variantes de estilo.
```

### Opção 2: ChatGPT / Google Gemini
1. Acesse [chat.openai.com](https://chat.openai.com) ou [gemini.google.com](https://gemini.google.com)
2. Copie `SKILL.md` (pode pular as primeiras 11 linhas do YAML se preferir)
3. Cole no chat
4. Faça suas perguntas

**Dica:** Se quiser remover o YAML antes de colar:
- Comece a copiar a partir de `# Senior Frontend Developer`

### Opção 3: GitHub Copilot (VS Code)
1. Baixe este repositório como ZIP ou clone
2. Extraia na sua máquina
3. Abra VS Code
4. Instale/ative a extensão **GitHub Copilot Chat**
5. Abra `SKILL.md` e copie tudo
6. Abra o Copilot Chat (Ctrl+Shift+I)
7. Cole e comece a usar

**Vantagem:** O GitHub Copilot reconhece automaticamente o frontmatter YAML como skill.

### Opção 4: Arquivo Local
```bash
# Clone ou baixe
git clone https://github.com/seu-usuario/copilot-skill-frontend.git
cd copilot-skill-frontend

# Copie para seu projeto
cp SKILL.md ../meu-projeto/
```

---

## 💡 Exemplos de Uso

### Receber Mentoria
```
🎯 Tenho um componente React que está ficando complexo (150+ linhas).
Como devo refatorar? Que padrões usar?
```

### Code Review
```
🔍 Revise meu código seguindo os padrões de um dev sênior:
[Cole seu código]
```

### Arquitetura
```
🏗️ Estou começando um novo projeto Next.js com TypeScript e Tailwind.
Como devo estruturar as pastas?
```

### Debug
```
🐛 Por que meu componente re-renderiza toda vez que o pai renderiza?
[Cole o componente]
```

---

## 📦 Stack Coberto

| Tecnologia | Nível | Observações |
|---|---|---|
| **HTML5** | Completo | Semântica, acessibilidade |
| **CSS3** | Completo | Flexbox, Grid, Modern CSS |
| **JavaScript** | Completo | ES6+, async/await, APIs |
| **TypeScript** | Completo | Interfaces, types, patterns |
| **React** | Completo | Hooks, React 18+, compound components |
| **Next.js** | Completo | App Router, Server Actions, cache |
| **Formulários** | Completo | react-hook-form, zod, validação |
| **Tailwind CSS** | Completo | Utility-first, variantes |
| **Node.js** | Fundacional | Scripts, environment |
| **Testing** | Intermediário | Vitest, RTL |
| **Performance** | Intermediário | Core Web Vitals, otimizações |

---

## 🎯 Triggers (Quando Usar)

A skill se ativa automaticamente quando você menciona:

- `componente`, `component`, `layout`, `landing page`, `dashboard`
- `formulário`, `form`, `design system`, `UI`, `UX`
- `responsivo`, `mobile-first`, `refatorar`, `refactor`, `code review`
- `fetch`, `REST`, `clean code`, nomes de frameworks
- `useState`, `useEffect`, `hook`, `props`, `context`
- `Server Component`, `Server Action`, `App Router`
- `zod`, `react-hook-form`, `Zustand`, `TanStack`

Mas você pode **sempre ativar manualmente** pedindo "use a skill de frontend sênior".

---

## 🤝 Contribuições

Quer melhorar a skill?

### Tipos de Contribuição
- 🐛 **Correções**: Erros, exemplos desatualizados
- ✨ **Melhorias**: Novas seções, exemplos melhores
- 📚 **Documentação**: Clareza, organização
- 🔄 **Otimizações**: Remover redundâncias

### Como Contribuir

1. **Leia** [CONTRIBUTING.md](CONTRIBUTING.md)
2. **Fork** este repositório
3. **Crie** uma branch: `git checkout -b feature/sua-melhoria`
4. **Commit** suas mudanças: `git commit -m "feat: melhoria X"`
5. **Push** e abra um **Pull Request**

### Workflow de Contribuição
```bash
# 1. Clone seu fork
git clone https://github.com/seu-usuario/copilot-skill-frontend.git
cd copilot-skill-frontend

# 2. Crie uma branch temática
git checkout -b feature/adiciona-vitest-examples

# 3. Edite SKILL.md
# (seu editor aqui)

# 4. Commit com mensagem descritiva
git add SKILL.md
git commit -m "feat: adiciona exemplos de testes com Vitest"

# 5. Push
git push origin feature/adiciona-vitest-examples

# 6. Abra PR no GitHub
```

**Padrão de Commits:**
- `feat:` Nova seção ou conteúdo
- `fix:` Correção de erro
- `docs:` Melhoria de documentação
- `refactor:` Reorganização

---

## 📋 Checklist de Qualidade

Antes de usar a skill, certifique-se que:

- [ ] Você definiu o escopo claro (o que quer fazer)
- [ ] Você compartilhou código relevante (quando pedir review)
- [ ] Você mencionou a stack do seu projeto (React? Next? Vue?)
- [ ] Você descreveu o contexto (é um projeto novo? Refatoração?)

A skill será mais útil com mais contexto! 🎯

---

## ⚡ Dicas de Uso

### Para Máximo Proveito
1. **Seja específico**: "Ajude-me a criar um form de login com validação" > "Crie um form"
2. **Compartilhe contexto**: "Estou em um projeto Next.js com Tailwind" > "Crie um componente"
3. **Peça explicações**: "Por quê dessa forma?" — A skill explica o raciocínio
4. **Itere**: Refine com feedback: "Pode ser mais acessível?" ou "Pode usar Zustand?"

### Use a Skill Para
✅ Arquitetura de projetos  
✅ Code reviews e mentoria  
✅ Escolha de stack  
✅ Refatoração  
✅ Debugging  
✅ Boas práticas  
✅ Padrões de design  

### Não Use Para
❌ Geração de conteúdo copyrightado  
❌ Problemas que precisam de debugger real  
❌ Stack que não é covered (Svelte, Vue em detalhe)  
❌ Decisões de negócio  

---

## 📢 Aviso Importante

Esta skill foi criada **apenas para fins de estudo do Claude Code**. Até o momento, só foi testada no Claude. Pode funcionar em outras IAs, mas não há garantia.

- **Suporte:** Não pretendo dar suporte ativo. Sugestões são bem-vindas, mas não espere respostas rápidas.
- **Contribuições:** Pull requests e sugestões são aceitas, mas serão avaliadas conforme minha disponibilidade.

## 📞 Suporte

### Problemas com a Skill?
- Não há suporte ativo. Use issues apenas para sugestões ou discussões.

---

## 📄 Licença

MIT — Use livremente, modifique, compartilhe. Veja [LICENSE](LICENSE).

---

## 🙌 Créditos

Desenvolvida para maximizar produtividade de devs frontend com **Claude AI** e **GitHub Copilot**.

Inspirada em padrões profissionais da comunidade frontend.

---

## ⭐ Gostou? Deixe uma Estrela!

Se esta skill foi útil, **marque com ⭐** para ajudar outros devs a descobrir!

---

**Pronto para melhorar seu código frontend? 🚀**

[Comece Agora](#-como-usar) | [Veja Contribuições](CONTRIBUTING.md) | [Issues & Sugestões](../../issues)
