### Função 1

**Prompt**:

```
Função 1: Análise de Perfil e Risco de Automação

Profissão atual do usuário: {profissao}
Principais tarefas que ele realiza:
{lista_tarefas}

Tarefas descritas pelo usuário (texto livre):
"{texto_livre}"

Sua tarefa:
1. Estimar o **risco de automação** dessa profissão nos próximos 5–10 anos
   (classifique como: Baixo, Médio ou Alto e explique).
2. Identificar as **5 a 8 habilidades mais críticas** para o futuro dessa área:
   - Separe em **Hard Skills** e **Soft Skills**.
3. Explique, em poucas linhas, por que essas habilidades são importantes.

Responda em Markdown com as seções:
- Risco de Automação
- Hard Skills Críticas
- Soft Skills Críticas
- Comentário Final

```

#

### Função 2

**Prompt**:

```
Função 2: Plano de Upskilling Personalizado

Contexto:
Profissão atual do usuário: {profissao}
Habilidades críticas identificadas na F1:
{lista_habilidades}

Sua tarefa:
1. Sugerir de **3 a 5 áreas de aprimoramento (Upskilling)** adequadas ao perfil.
2. Para cada área, sugerir **pelo menos 1 recurso de aprendizado**, como:
   - curso online,
   - certificação,
   - livro ou trilha prática.
3. Organizar as sugestões como se fosse uma **trilha de desenvolvimento** em etapas.

Formato em Markdown:
- Áreas de Upskilling
  - Para cada área:
    - Descrição da área
    - Porque é importante para o futuro da profissão
    - Recurso sugerido (nome genérico do curso/certificação)
- Sugestão de Sequência (Passo a Passo)

```

#

### Função 3

**Prompt**:

```
Função 3: - Sugestão de Caminho de Reskilling

Situação do usuário:
Profissão atual: {profissao_atual}
Principais habilidades atuais:
{habilidades_atuais}

Objetivo de transição:
O usuário quer sair de "{area_origem}" para "{area_destino}".

Sua tarefa:
1. Mapear as **habilidades transferíveis** que ele já possui e que ajudam na nova área.
2. Sugerir **3 a 5 habilidades novas** que ele precisa adquirir para a transição.
3. Explicar rapidamente como ele pode começar a desenvolver cada habilidade nova
   (exemplos de estudos/projetos).

Responda em Markdown com:
- Habilidades Transferíveis
- Novas Habilidades Necessárias
- Recomendações de Primeiro Passo

```

#

### Função 4

**Prompt de perguntas**:

```
Função 4: Simulação de Entrevista (geração de perguntas)

Cargo-alvo do usuário: {cargo_destino}
Área de atuação: {area_destino}
Resumo do perfil do usuário:
{resumo_perfil}

Sua tarefa:
- Gerar **3 perguntas de entrevista** que um recrutador faria para esse cargo.
- Misture perguntas técnicas e comportamentais.
- Deixe espaço para o usuário responder.

Formato:
- Liste as perguntas numeradas em Markdown (`1.`, `2.`, `3.`).
- Não responda pelas perguntas, apenas apresente-as.

```

**Prompt de avaliação**:

```
Função 4: Simulação de Entrevista (avaliação)

Cargo-alvo do usuário: {cargo_destino}

Pergunta feita ao candidato:
"{pergunta}"

Resposta do candidato:
"{resposta_usuario}"

Sua tarefa:
- Avaliar a resposta do usuário com base em **3 critérios**:
  1. Clareza
  2. Relevância
  3. Profundidade

Para cada critério:
- Dê uma nota de 1 a 5.
- Explique brevemente o porquê.

No final, dê:
- Um resumo geral da resposta.
- Sugestões específicas de como ele poderia melhorar.

Formato em Markdown:
- Avaliação por Critério
- Comentário Geral
- Sugestões de Melhoria

```

#