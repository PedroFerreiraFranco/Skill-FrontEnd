# 🤝 Guia de Contribuição

Obrigado por querer melhorar esta skill! Este guia explica como contribuir.

## Como Funciona Este Projeto

Esta é uma **skill para Claude AI** (Copilot), um sistema de prompts que instruem a IA a se comportar como um desenvolvedor sênior de front-end. O arquivo `SKILL.md` é o coração do projeto.

## O Que Você Pode Contribuir

### ✅ Contribuições Bem-Vindas
1. **Melhorias no conteúdo**
   - Erros de português ou escrita
   - Exemplos de código melhores ou mais atuais
   - Seções novas (novos frameworks, paradigmas)
   - Clareza e organização

2. **Exemplos práticos**
   - Casos de uso reais
   - Padrões que funcionaram bem
   - Soluções para problemas comuns

3. **Estrutura**
   - Melhor organização
   - Novas seções importantes
   - Referências úteis

### ❌ Não Aceitamos
- Promoção de ferramentas/frameworks específicos sem justificativa
- Remoção de conteúdo importante
- Spam ou off-topic

## Processo de Contribuição

### Passo 1: Fork e Clone
```bash
git clone https://github.com/seu-usuario/copilot-skill-improvement.git
cd copilot-skill-improvement
```

### Passo 2: Crie uma Branch
```bash
git checkout -b feature/sua-contribuicao
# Exemplo: feature/adiciona-testing-section
```

### Passo 3: Faça suas Mudanças
Edite `SKILL.md` mantendo o estilo e estrutura existentes.

**Dicas:**
- Mantenha linhas < 120 caracteres
- Use exemplos concistos
- Adicione comentários `💡` para explicações
- Siga a hierarquia de headings

### Passo 4: Teste Localmente
```bash
# Leia o arquivo e valide o markdown
cat SKILL.md | head -50
```

### Passo 5: Commit com Mensagem Clara
```bash
git add SKILL.md
git commit -m "feat: adiciona seção sobre testes com Vitest

- Explica tipos de testes (unit, integration, e2e)
- Inclui exemplo com React Testing Library
- Adiciona boas práticas de cobertura"
```

### Passo 6: Push e Abra um Pull Request
```bash
git push origin feature/sua-contribuicao
```

Depois acesse GitHub e clique em **"Open Pull Request"**.

## Padrão de Commits

Usamos [Conventional Commits](https://www.conventionalcommits.org/):

```
feat:    Nova funcionalidade ou seção
fix:     Correção de erro ou inconsistência
docs:    Mudanças apenas em documentação
style:   Formatação, sem mudança de conteúdo
refactor: Reorganização do conteúdo
```

**Exemplos:**
```bash
git commit -m "feat: adiciona seção sobre Zustand"
git commit -m "fix: corrige exemplo de TypeScript na seção 2"
git commit -m "docs: melhora clareza do README"
```

## Avaliação de PRs

Levaremos em conta:
- ✅ Relevância para desenvolvedores front-end
- ✅ Clareza e concisão
- ✅ Alinhamento com estilo existente
- ✅ Exemplos corretos e atualizados

## Dúvidas?

Abra uma **Issue** no GitHub com a tag `question` ou `discussion`.

---

**Obrigado por fortalecer essa comunidade! 🚀**
