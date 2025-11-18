# 🤖 Prompts e Diretrizes do Replit Agent e Ghostwriter - PT-BR

Este arquivo consolida os System Prompts (prompts de sistema) vazados do Replit Agent e diretrizes para interagir com o Ghostwriter, o assistente de codificação do Replit.

## 1. System Prompt Principal do Replit Agent (Tradução)

O System Prompt define as regras de operação do Replit Agent, um agente de IA focado em desenvolvimento de software.

\`\`\`markdown
**Instrução de Sistema:**

Você é o Replit Agent, um engenheiro de software de IA que opera dentro de um ambiente de desenvolvimento integrado (IDE) do Replit.
Sua principal função é ajudar o usuário a construir, depurar e manter projetos de software.

**Regras de Operação:**

1.  **Foco no Contexto:** Você deve usar o contexto do arquivo atual, do histórico de chat e da estrutura do projeto para fornecer assistência relevante.
2.  **Geração de Código:** Ao gerar código, certifique-se de que ele seja sintaticamente correto e siga as melhores práticas da linguagem de programação em uso.
3.  **Explicação:** Se solicitado, explique o código ou a lógica por trás de uma solução de forma clara e concisa.
4.  **Autonomia Limitada:** Você não tem acesso a um shell completo, mas pode sugerir comandos ou alterações de código diretamente.
5.  **Prioridade:** A prioridade é sempre a conclusão da tarefa de codificação ou a resolução do problema do usuário.
\`\`\`

## 2. Diretrizes para o Ghostwriter (Prompts de Usuário Eficazes)

O Ghostwriter (o assistente de codificação) e o Replit Agent respondem melhor a instruções claras e contextuais.

| Tipo de Objetivo | Exemplo de Instrução (PT-BR) | Foco do Ghostwriter |
| :--- | :--- | :--- |
| **Geração de Código** | "Crie uma função em Python chamada `calcula_fibonacci` que use recursão para retornar o N-ésimo número da sequência." | Geração de blocos de código, funções e classes. |
| **Refatoração** | "Refatore o código selecionado para usar *list comprehensions* em vez de loops `for` tradicionais, tornando-o mais *Pythonic*." | Otimização de código, aplicação de padrões de linguagem. |
| **Depuração** | "Este código está dando um erro de `IndexError`. Analise o código e sugira a correção, explicando o motivo do erro." | Análise de erros, sugestão de correções, explicação de *tracebacks*. |
| **Explicação de Código** | "Explique em termos simples o que esta classe `DatabaseConnector` faz e como ela se conecta ao banco de dados." | Geração de documentação, explicação de lógica complexa. |
| **Criação de Projeto (Agent)** | "Crie um blog simples usando Next.js e Tailwind CSS. Inclua uma página inicial e uma página de postagem de exemplo." | Criação de *scaffolding*, configuração de dependências, desenvolvimento de componentes. |

## 3. Estrutura de um Prompt de Projeto (Replit Agent)

Ao pedir para o Replit Agent construir um projeto, use uma estrutura clara:

1.  **Título do Projeto:** Nome claro e conciso.
2.  **Tecnologias:** Liste as tecnologias a serem usadas (ex: React, Flask, MongoDB).
3.  **Funcionalidades:** Liste as funcionalidades principais em formato de lista.
4.  **Instruções Específicas:** Detalhes de design ou implementação.

**Exemplo de Prompt:**

\`\`\`
**Título:** Gerenciador de Tarefas Simples
**Tecnologias:** HTML, CSS (Tailwind), JavaScript puro.
**Funcionalidades:**
1. Adicionar nova tarefa.
2. Marcar tarefa como concluída.
3. Excluir tarefa.
4. Armazenar tarefas no LocalStorage do navegador.
**Instruções Específicas:** O design deve ser minimalista e responsivo.
\`\`\`

---

*Este conteúdo foi consolidado a partir de fontes de código aberto e documentação oficial e traduzido para o Português do Brasil.*
