# Prompts de Análise de Dados

Estes prompts são projetados para extrair insights, limpar dados e realizar análises estatísticas rigorosas usando LLMs.

## 1. Análise e Interpretação de Dados

| Objetivo | Prompt Sugerido |
| :--- | :--- |
| **Resumo de Conjunto de Dados** | "Atue como um Cientista de Dados. Forneça um resumo estatístico e insights chave para o seguinte conjunto de dados (ou resumo de dados): [Insira o resumo do CSV ou os dados]. Inclua a média, mediana, desvio padrão e os 3 principais insights de negócios." |
| **Identificação de Tendências e Padrões** | "Analise o conjunto de dados fornecido (ou resumo) para identificar tendências, padrões e correlações significativas entre as colunas [Coluna A] e [Coluna B]. Explique a implicação dessas descobertas para [contexto de negócio]." |
| **Detecção de Anomalias** | "Identifique quaisquer outliers ou anomalias no conjunto de dados (ou resumo) e explique suas possíveis causas. Sugira um método estatístico (ex: Z-Score, IQR) para lidar com essas anomalias." |
| **Comparação de Conjuntos de Dados** | "Compare os dois conjuntos de dados (ou resumos) a seguir: [Dados 1] e [Dados 2]. Identifique as principais diferenças e semelhanças, e determine se a diferença é estatisticamente significativa (assuma um p-value de 0.05)." |

## 2. Limpeza e Pré-processamento (Foco em CSV)

| Objetivo | Prompt Sugerido |
| :--- | :--- |
| **Limpeza de Dados (CSV)** | "Atue como um Engenheiro de Dados. Sugira e aplique etapas de limpeza e pré-processamento para o seguinte arquivo CSV (ou resumo de colunas): [Insira as primeiras linhas do CSV ou o esquema]. Foco em: 1. Tratamento de valores ausentes, 2. Padronização de formatos de data, 3. Remoção de duplicatas." |
| **Geração de Código de Limpeza** | "Escreva um script em [linguagem, ex: Python com Pandas] para carregar o arquivo CSV '[nome_do_arquivo.csv]' e realizar as seguintes tarefas de limpeza: [Lista de tarefas, ex: converter a coluna 'Preço' para float, preencher 'Idade' com a mediana]." |
| **Feature Engineering** | "Com base no seguinte esquema de dados [insira o esquema], sugira 3 novas *features* (colunas) que podem ser criadas para melhorar a performance de um modelo de [tipo de modelo, ex: regressão]. Forneça o código para criar essas *features*." |

## 3. Visualização e Comunicação de Resultados

| Objetivo | Prompt Sugerido |
| :--- | :--- |
| **Sugestão de Visualização** | "Com base nos insights [insira os insights] e no tipo de dados [insira o tipo de dados], sugira o tipo de gráfico mais eficaz (ex: histograma, gráfico de dispersão) para comunicar o resultado para um público [público, ex: executivo, técnico]. Descreva o que o gráfico deve destacar." |
| **Explicação Estatística** | "Explique o conceito de [conceito estatístico, ex: Regressão Linear, Teste T] em termos simples para um público não técnico. Use uma analogia de negócios para ilustrar o conceito." |
| **Criação de Dashboard** | "Atue como um Designer de Dashboard. Projete a estrutura de um dashboard (usando [ferramenta, ex: Tableau, Power BI]) para monitorar [métrica de negócio]. Descreva os 5 principais KPIs e os tipos de visualização para cada um." |
