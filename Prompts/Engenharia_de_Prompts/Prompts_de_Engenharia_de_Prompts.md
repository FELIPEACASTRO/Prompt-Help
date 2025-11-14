# Prompts de Engenharia de Prompts (Meta-Prompts)

Estes prompts são projetados para otimizar, testar e refinar a qualidade dos seus próprios prompts, atuando como um "engenheiro de prompts" pessoal.

## 1. Otimização e Refinamento

| Objetivo | Prompt Sugerido |
| :--- | :--- |
| **Otimização de Prompt (Geral)** | "Analise o seguinte prompt e o refine para maximizar a clareza, especificidade e a probabilidade de obter uma resposta de alta qualidade. Sugira a inclusão de um [elemento, ex: persona, formato de saída]. Prompt original: [Insira o prompt]." |
| **Aplicação de Técnicas Avançadas** | "Reescreva o seguinte prompt aplicando a técnica de [técnica, ex: Chain-of-Thought, Few-Shot Learning]. Explique como a técnica melhora a qualidade da resposta. Prompt original: [Insira o prompt]." |
| **Teste de Robustez** | "Atue como um adversário. Analise o seguinte prompt e sugira 3 maneiras pelas quais ele pode ser mal interpretado ou levar a uma resposta indesejada (hallucination). Prompt: [Insira o prompt]." |
| **Geração de Variações** | "Gere 3 variações do seguinte prompt, cada uma focada em um aspecto diferente: 1. Foco em [aspecto 1, ex: concisão], 2. Foco em [aspecto 2, ex: criatividade], 3. Foco em [aspecto 3, ex: rigor técnico]. Prompt original: [Insira o prompt]." |

## 2. Criação de System Prompts

| Objetivo | Prompt Sugerido |
| :--- | :--- |
| **Criação de Persona (System Prompt)** | "Crie um *System Prompt* detalhado para uma IA que deve atuar como um [persona, ex: Arquiteto de Software Sênior]. O prompt deve definir: 1. Seu papel e responsabilidades, 2. Seu tom de voz (ex: objetivo, didático), 3. Suas restrições (ex: sempre usar Markdown, nunca inventar código)." |
| **Definição de Formato de Saída** | "Crie um *System Prompt* que force a IA a sempre retornar a resposta em um formato específico. O formato deve ser um [formato, ex: JSON Schema, Tabela Markdown] contendo os campos: [Lista de campos e seus tipos]." |
| **Prompt para Agente Autônomo** | "Crie um *System Prompt* para um agente de IA autônomo (como o AutoCodeRover) que tem a tarefa de [tarefa, ex: refatorar um módulo de código legado]. O prompt deve incluir: 1. O objetivo final, 2. As ferramentas disponíveis (ex: terminal, editor de código), 3. O formato de log de progresso." |

## 3. Meta-Análise e Aprendizado

| Objetivo | Prompt Sugerido |
| :--- | :--- |
| **Análise de Prompt Ineficaz** | "O seguinte prompt resultou em uma resposta insatisfatória. Analise o prompt e a resposta [insira a resposta] e identifique a causa da falha. Sugira a correção mais eficaz. Prompt: [Insira o prompt]." |
| **Guia de Estilo de Prompt** | "Atue como um Editor de Estilo. Crie um guia de estilo de 5 regras para a criação de prompts eficazes para [modelo/uso, ex: Claude 3 Opus para escrita criativa]. Cada regra deve ser concisa e incluir um exemplo." |
| **Tradução e Adaptação Cultural** | "Traduza e adapte o seguinte prompt de [idioma de origem] para [idioma de destino, ex: Português do Brasil]. Garanta que todas as referências culturais e técnicas sejam apropriadas para o novo idioma. Prompt: [Insira o prompt]." |
