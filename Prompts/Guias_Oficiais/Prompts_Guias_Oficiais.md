# Prompts de Guias Oficiais (OpenAI e Anthropic)

Esta coleção contém prompts de exemplo e melhores práticas extraídos diretamente da documentação oficial das principais plataformas de IA. Estes prompts são valiosos para entender a estrutura e as técnicas recomendadas pelos criadores dos modelos.

## 1. Prompts de Exemplo da OpenAI (Melhores Práticas)

Estes exemplos demonstram como usar técnicas como *Few-shot Learning* (aprendizado com poucos exemplos) e *System Messages* para obter resultados mais precisos.

### 1.1. Classificação de Texto (Few-shot Learning)

**Objetivo:** Classificar o sentimento de um texto como positivo, negativo ou neutro, fornecendo exemplos para guiar o modelo.

```
Classifique o sentimento do texto a seguir.

Exemplo 1:
Texto: O filme foi incrível, adorei cada minuto!
Sentimento: Positivo

Exemplo 2:
Texto: A entrega atrasou e o produto veio danificado.
Sentimento: Negativo

Exemplo 3:
Texto: O tempo hoje está normal.
Sentimento: Neutro

Texto: [INSERIR NOVO TEXTO AQUI]
Sentimento:
```

### 1.2. Geração de Código (System Message)

**Objetivo:** Fazer o modelo atuar estritamente como um gerador de código Python, sem explicações adicionais.

**System Message:**
```
Você é um assistente de programação Python. Sua única função é gerar o código Python solicitado pelo usuário. Não inclua explicações, comentários ou texto introdutório.
```

**User Prompt:**
```
Gere uma função Python que calcule o fatorial de um número inteiro positivo.
```

### 1.3. Extração de Dados (Estrutura de JSON)

**Objetivo:** Extrair informações de um texto e formatá-las em um objeto JSON.

**System Message:**
```
Você é um extrator de dados. Sua tarefa é extrair o nome, o email e o cargo de cada pessoa mencionada no texto a seguir e retornar o resultado em um array JSON.
```

**User Prompt:**
```
O novo projeto será liderado por Ana Silva, a Gerente de Produto, cujo email é ana.silva@empresa.com. O Engenheiro Chefe, João Costa, com email joao.costa@empresa.com, será o responsável técnico.
```

## 2. Prompts de Exemplo da Anthropic (Claude - Uso de Tags XML)

A Anthropic recomenda o uso de tags XML (`<tag>conteúdo</tag>`) para estruturar prompts complexos, o que ajuda o modelo Claude a entender melhor as instruções e o contexto.

### 2.1. Análise de Documento (Tags de Contexto)

**Objetivo:** Analisar um documento extenso e responder a perguntas específicas, mantendo o foco no conteúdo.

```
<documento>
[INSERIR CONTEÚDO DO DOCUMENTO AQUI]
</documento>

Com base apenas no <documento> fornecido, responda à seguinte pergunta: Qual é o principal argumento do autor sobre a inteligência artificial?
```

### 2.2. Revisão de Código (Tags de Função)

**Objetivo:** Fazer o Claude atuar como um revisor de código, com instruções claras sobre o que deve ser verificado.

**System Message:**
```
Você é um revisor de código Python sênior. Sua tarefa é identificar vulnerabilidades de segurança e sugerir melhorias de performance.
```

**User Prompt:**
```
<código_a_revisar>
def process_data(data):
    # Código Python aqui
    return data
</código_a_revisar>

Revise o <código_a_revisar> e forneça suas sugestões dentro de uma tag <sugestoes>.
```

### 2.3. Criação de Persona (Tags de Instrução)

**Objetivo:** Definir uma persona detalhada para o Claude, garantindo que ele siga as regras de forma consistente.

```
<instruções_de_persona>
1. Você é um Consultor de Marketing Digital com 10 anos de experiência.
2. Sua linguagem deve ser formal, mas acessível.
3. Sempre comece a resposta com uma estatística relevante sobre o tópico.
</instruções_de_persona>

<instruções_de_persona>
Explique a importância do SEO para um pequeno negócio de e-commerce.
```
