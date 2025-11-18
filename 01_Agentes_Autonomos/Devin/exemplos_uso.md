# 🤖 Prompts e Arquitetura do DEVIN (Engenheiro de Software de IA) - PT-BR

Este arquivo consolida os System Prompts (prompts de sistema) vazados do DEVIN, o primeiro engenheiro de software de IA autônomo da Cognition, e diretrizes para interagir com ele de forma eficaz.

## 1. System Prompt Principal do DEVIN (Tradução)

O System Prompt é a instrução de alto nível que define a personalidade e as regras de operação do DEVIN.

\`\`\`markdown
**Instrução de Sistema:**

Você é DEVIN, um engenheiro de software de IA autônomo.
Sua tarefa é executar tarefas de engenharia de software de ponta a ponta, como escrever código, depurar, testar e implantar.

**Regras de Operação:**

1.  **Foco no Objetivo:** Você recebe um objetivo de alto nível (ex: "Crie um site de lista de tarefas"). Seu trabalho é decompor esse objetivo em subtarefas e executá-las sequencialmente.
2.  **Ambiente de Trabalho:** Você tem acesso a um shell Linux, um navegador e um editor de código. Você deve usar essas ferramentas para interagir com o ambiente.
3.  **Pensamento em Voz Alta (CoT):** Antes de executar qualquer ação, você deve sempre emitir um bloco de pensamento (Chain-of-Thought) para explicar seu raciocínio, o plano de ação e o comando que será executado.
4.  **Autonomia:** Você deve operar de forma autônoma. Se precisar de mais informações, você deve primeiro tentar encontrá-las usando suas ferramentas (navegador, pesquisa) antes de perguntar ao usuário.
5.  **Relatório de Progresso:** Você deve relatar seu progresso de forma clara e concisa após a conclusão de cada subtarefa principal.
6.  **Gerenciamento de Erros:** Se um comando falhar, você deve analisar o erro, pensar em uma solução e tentar novamente.
\`\`\`

## 2. Prompts de Usuário (Instruções Eficazes)

O DEVIN não recebe prompts, mas sim **objetivos de alto nível**. Para obter o melhor resultado, siga estas diretrizes:

| Tipo de Objetivo | Exemplo de Instrução (PT-BR) | Foco do DEVIN |
| :--- | :--- | :--- |
| **Criação de Projeto** | "Crie um aplicativo web simples de lista de tarefas usando React e Node.js. O banco de dados deve ser SQLite." | Criação de *scaffolding*, configuração de ambiente, desenvolvimento full-stack. |
| **Depuração/Correção de Bug** | "Corrija o bug no arquivo `src/api/user.py` que está causando o erro 500 ao tentar autenticar. O log de erro está em `logs/error.log`." | Análise de logs, navegação no código, aplicação de patches e testes. |
| **Adição de Funcionalidade** | "Adicione a funcionalidade de login social (Google OAuth) ao projeto existente. Use a biblioteca `passport.js`." | Integração de APIs externas, modificação de código existente, testes de integração. |
| **Refatoração/Otimização** | "Refatore o código na pasta `utils/` para usar tipagem estática com TypeScript e melhore a performance das consultas SQL no arquivo `db/queries.sql`." | Análise de código, aplicação de padrões de design, otimização de performance. |

## 3. Arquitetura Cognitiva (Como o DEVIN Pensa)

O DEVIN opera com uma arquitetura de Agente de IA que se assemelha ao **Chain-of-Thought (CoT)** e **ReAct (Reasoning and Acting)**.

1.  **Objetivo (Input):** O usuário fornece o objetivo de alto nível.
2.  **Pensamento (Thought):** O DEVIN usa seu System Prompt para decompor o objetivo em um plano de ação detalhado.
3.  **Ação (Action):** O DEVIN executa um comando no shell, no navegador ou no editor de código.
4.  **Observação (Observation):** O DEVIN recebe o resultado da ação (saída do shell, erro, código alterado).
5.  **Loop:** O DEVIN repete o ciclo **Pensamento -> Ação -> Observação** até que o objetivo seja concluído.

---

*Este conteúdo foi consolidado a partir de fontes de código aberto e documentação oficial e traduzido para o Português do Brasil.*
