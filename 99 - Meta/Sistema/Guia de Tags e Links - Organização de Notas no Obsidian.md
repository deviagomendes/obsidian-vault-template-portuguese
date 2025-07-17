---
aliases:
  - Tags e Links no Obsidian
  - Sistema de Organização
tags:
  - context/studies
  - type/study
  - theme/organization
  - theme/productivity
  - status/completed
date: 2024-10-30
---

# **Guia de Tags e Links - Organização de Notas no Obsidian**

## **1. Tags de Tipo de Nota**
Identificam a natureza primária da nota, ajudando na categorização básica do conteúdo.

### Exemplos:
- `#type/task` → Itens de tarefas
- `#type/project` → Projetos em desenvolvimento
- `#type/daily` → Notas diárias
- `#type/study` → Material de aprendizado
- `#type/idea` → Insights e brainstorming
- `#type/reflection` → Pensamentos pessoais e análise
- `#type/habits` → Rotinas e hábitos

## **2. Tags de Contexto**
Indicam o ambiente ou circunstância onde a nota se aplica.

### Exemplos:
- `#context/studies` → Material de aprendizado geral
- `#context/work` → Atividades profissionais
- `#context/personal` → Desenvolvimento pessoal
- `#context/academic` → Estudos universitários
- `#context/hobbies` → Atividades recreativas

## **3. Tags de Tema**
Organizam conteúdo por área de conhecimento ou interesse.

### Computação e Tecnologia
- `#theme/cybersecurity` → Segurança da informação
- `#theme/dev` → Desenvolvimento de software
- `#theme/os` → Sistemas operacionais
- `#theme/algorithms` → Algoritmos e estruturas de dados
- `#theme/AI` → Inteligência artificial

### Humanidades
- `#theme/psychology` → Comportamento humano
- `#theme/stoicism` → Filosofia estoica
- `#theme/history` → Estudos históricos
- `#theme/mythology` → Estudos mitológicos

### Saúde e Bem-estar
- `#theme/muay-thai` → Artes marciais
- `#theme/fitness` → Exercício e nutrição

### Cultura e Entretenimento
- `#theme/music` → Estudos musicais
- `#theme/movies` → Cinema e séries
- `#theme/drawing` → Artes visuais
- `#theme/games` → Jogos e desenvolvimento de jogos
- `#theme/literature` → Livros e leitura

## **4. Tags de Metadados**
Controlam status, prioridade e necessidades de revisão das notas.

### Status e Progresso
- `#status/completed` → Finalizado
- `#status/in-progress` → Em desenvolvimento
- `#status/planning` → Fase inicial
- `#status/idea` → Conceito inicial

### Priorização
- `#priority/high` → Urgente
- `#priority/medium` → Importante
- `#priority/low` → Pode esperar

### Controle de Revisão
- `#review/pending` → Aguardando revisão
- `#review/completed` → Já revisado
- `#review/needed` → Precisa de revisão

## 5. Melhores Práticas de Uso de Tags

#### Tags Mínimas Obrigatórias
Para manter consistência e facilitar a busca, cada nota deve incluir no mínimo:
1. Uma tag de tipo (`#type/...`)
2. Uma tag de contexto (`#context/...`)
3. Uma tag de tema (`#theme/...`)
4. Uma tag de status/prioridade quando aplicável

## **6. Usando Links**
Links são fundamentais para criar conexões entre notas, formando uma rede interconectada de conhecimento.

### Tipos de Links

1. **Links Diretos**
   - Sintaxe: `[[Nome da Nota]]`
   - Uso: Conecta diretamente a outra nota
   - Exemplo: `[[Algoritmos de Criptografia]]`

2. **Links com Alias**
   - Sintaxe: `[[Nome da Nota|Texto Exibido]]`
   - Uso: Mostra texto diferente do título da nota
   - Exemplo: `[[Algoritmos de Criptografia|Métodos de Criptografia]]`

3. **Links de Seção**
   - Sintaxe: `[[Nome da Nota#Seção]]`
   - Uso: Leva você a uma seção específica de uma nota
   - Exemplo: `[[Criptografia#RSA]]`

### Práticas Recomendadas para Links

1. **Conexões Significativas**
   - Crie links apenas quando houver uma relação relevante
   - Evite links excessivos que possam distrair

2. **Notas Índice (MOCs)**
   - Crie notas que sirvam como mapas de conteúdo
   - Use links para organizar temas relacionados
   - Exemplo: Uma nota "[[Projetos de Segurança]]" com links para todos os projetos relacionados

3. **Links Bidirecionais**
   - Aproveite os backlinks automáticos do Obsidian
   - Revise periodicamente os backlinks para descobrir novas conexões

4. **Hierarquia através de Links**
   - Use links para criar estruturas hierárquicas flexíveis
   - Exemplo: `[[Programação]]` → `[[Algoritmos]]` → `[[Ordenação]]`

## **7. Exemplo de Uso Completo**

### Título: **Implementação RSA**
**Tags**: 
- `#theme/cybersecurity`
- `#context/studies`
- `#type/study`
- `#priority/high`
- `#status/in-progress`
- `#review/pending`

**Links Relacionados**:
- [[Criptografia Assimétrica]]
- [[Projetos de Segurança]]
- [[Matemática da Criptografia#Números Primos]]

**Conteúdo**:
Detalhes sobre implementação RSA, com referências a conceitos fundamentais através de links.
