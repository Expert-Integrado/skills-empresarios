# 📊 Skills para Empresários

**[→ Como funciona o pack Skills para Empresários](https://expert-integrado.github.io/skills-empresarios/)** — a página do projeto, com o sistema explicado visualmente.

Um pack de skills prontas para **Claude Code** que automatizam as tarefas mais comuns do dia a dia de um empresário — de e-mails e propostas a reuniões e feedback de equipe.

## 🚀 O que é?

Este repositório contém um conjunto de **15 skills** (prompts estruturados) que transformam Claude em um assistente pessoal para empresários. Cada skill resolve uma tarefa específica e recorrente, economizando tempo e garantindo qualidade.

**Perfeito para:**
- 📧 Comunicações profissionais
- 💼 Documentos e propostas
- 👥 Gestão de equipes
- 📈 Planejamento e análise
- 🎯 Estratégia e vendas

## 📚 Skills Disponíveis

| Skill | O que faz | Use quando... |
|-------|-----------|---------------|
| **email-profissional** | Escreve e-mails em qualquer situação | Precisa enviar follow-up, cobrança, proposta ou resposta difícil |
| **proposta-comercial** | Estrutura propostas vencedoras | Vai apresentar um serviço/produto a um cliente |
| **responder-cliente** | Respostas rápidas e eficazes | Cliente faz uma pergunta ou tem uma objeção |
| **feedback-equipe** | Feedback construtivo e claro | Precisa orientar um colaborador |
| **resumir-reuniao** | Resumo estruturado de reuniões | Quer documentar o que foi combinado |
| **relatorio-semanal** | Relatório de resultados semanais | Precisa compilar resultados para a equipe |
| **plano-de-acao** | Planos com metas e prazos | Quer estruturar uma iniciativa |
| **pesquisa-mercado** | Pesquisa rápida de concorrentes/mercado | Precisa entender o cenário antes de decidir |
| **analise-documento** | Análise profunda de documentos | Recebeu um contrato, proposta ou relatório para analisar |
| **script-vendas** | Script para prospecção/vendas | Vai fazer prospecção ou apresentação |
| **preparar-apresentacao** | Estrutura de apresentação + roteiro | Precisa preparar uma pitch ou apresentação |
| **post-redes-sociais** | Posts alinhados com marca/tom | Quer criar conteúdo para LinkedIn, Instagram, etc |
| **descrever-produto** | Descrição de produto/serviço | Precisa vender melhor seu produto |
| **briefing-fornecedor** | Brief estruturado para fornecedores | Vai contratar um freelancer ou agência |
| **onboarding-colaborador** | Plano de onboarding para novos | Vai receber um novo membro na equipe |

## ⚡ Como Usar

### Instalação no Claude Code

1. Clone este repositório ou baixe as skills
2. No Claude Code (CLI, Desktop ou Web), acesse **Settings → Skills**
3. Aponte para a pasta deste repositório ou copie as skills individuais
4. Cada skill está pronta para usar — sem configuração extra

### Uso Básico

```
User: "Preciso escrever um e-mail para cobrar um cliente"
Claude: [ativa skill email-profissional]
→ Pede contexto e gera e-mail profissional
```

```
User: "Faz um resumo da reunião que tive hoje"
Claude: [ativa skill resumir-reuniao]
→ Pede detalhes e estrutura o resumo
```

## 📖 Estrutura de uma Skill

Cada skill é um arquivo `SKILL.md` com:

- **Nome e descrição** — O que a skill faz
- **Triggers** — Quando Claude a ativa automaticamente
- **Processo passo a passo** — Como a skill resolve o problema
- **Diretrizes** — Tons, estilos e variações
- **Outputs** — Formato da resposta

Exemplo:

```markdown
---
name: email-profissional
description: Escreve e-mails profissionais em qualquer situação
---

## Processo

### Passo 1 — Entender a situação
[perguntas focadas]

### Passo 2 — Escrever o e-mail
[template + diretrizes]

### Passo 3 — Oferecer variações
[opcões para refinar]
```

## 🎯 Diferenciais

✅ **Pronto para usar** — Não precisa de setup complexo
✅ **Genérico e flexível** — Adapta a qualquer situação
✅ **Foco em qualidade** — Cada skill garante output profissional
✅ **Dirigido a empresários** — Linguagem e contexto do mundo real
✅ **Tarefas do dia a dia** — Resolve problemas recorrentes

## 💡 Exemplos de Uso

### Cenário 1: Vendas
```
"Preciso de um script para ligar para prospectos hoje"
→ skill: script-vendas
→ Claude gera script personalizado, com objeções comuns
```

### Cenário 2: Gestão de Equipe
```
"Como dou um feedback para meu dev que entrega atrasado?"
→ skill: feedback-equipe
→ Claude estrutura feedback construtivo
```

### Cenário 3: Comunicação
```
"Vou apresentar meu produto para um cliente grande"
→ skill: preparar-apresentacao
→ Claude cria roteiro + slides
```

## 🔧 Personalizando

Cada skill pode ser customizada:

- **Tone** — Ajuste formalidade, agressividade, tom
- **Contexto** — Adicione infos sobre sua empresa/mercado
- **Formato** — Peça variações (mais curto, mais direto, etc)

Exemplo:
```
"Escreve um e-mail de cobrança, mas bem mais firme"
→ Claude adapta o tom baseado no feedback
```

## 📝 Contribuindo

Encontrou um jeito de melhorar uma skill? Tem uma tarefa que deveria ter skill própria?

1. Faça um fork deste repositório
2. Crie uma branch com sua melhoria (`git checkout -b melhoria/nova-skill`)
3. Envie um pull request

## 📄 Licença

Este projeto está licenciado sob a licença MIT — sinta-se livre para usar, modificar e distribuir.

## 🤝 Suporte

Dúvidas ou sugestões?
- 📧 Abra uma [issue](https://github.com/expertintegrado/skills-empresarios/issues)
- 💬 Sugira melhorias na discussão

---

**Feito para ajudar empresários a ganhar tempo e melhorar qualidade.**
Comece agora — escolha uma skill e teste! 🚀
