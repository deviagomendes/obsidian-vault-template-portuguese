---
aliases:
  - Diretrizes do Vault
  - Diretrizes do Vault
tags:
  - context/studies
  - type/study
  - theme/organization
  - theme/productivity
  - status/completed
date: 2024-10-20
last_updated: 2024-10-29
---

## **Guia de Uso Prático**

### **1. Criando Novas Notas**

#### **Processo de Decisão**
1. Identifique o tipo principal da nota (tarefa, estudo, reflexão, etc.)
2. Escolha a pasta principal apropriada:
   - Conhecimento pessoal → 02 - Conhecimento
   - Reflexões/diário → 01 - Pessoal
   - Material de referência → 04 - Referências
   - Projetos ativos → 03 - Projetos

#### **Convenção de Nomenclatura**
- Use nomes descritivos e concisos
- Evite caracteres especiais
- Exemplos:
  - `Introdução aos Algoritmos`
  - `2024-01-01 Reflexão Diária`
  - `Projeto Motor de Jogo`

### **2. Usando Tags Efetivamente**
Para exemplos mais detalhados de uso de tags, confira [[Guia de Tags e Links - Organização de Notas no Obsidian|Sistema de Organização de Tags]]

#### **Estrutura de Tags Recomendada**
Sempre inclua no mínimo:
1. Uma tag de tipo (`#type/...`)
2. Uma tag de contexto (`#context/...`)
3. Uma tag de tema (`#theme/...`)
4. Uma tag de status/prioridade quando aplicável

Exemplo:
```markdown
tags:
  - type/study
  - context/academic
  - theme/algorithms
  - status/in-progress
  - priority/high
```

### **3. Criando Conexões**

#### **Links Efetivos**
- Use links bidirecionais (`[[]]`) para conectar conceitos relacionados
- Crie MOCs (Mapas de Conteúdo) para temas principais
- Exemplo de MOC:
```markdown
# MOC - Algoritmos
## Fundamentos
- [[Complexidade de Algoritmos]]
- [[Estruturas de Dados Básicas]]

## Algoritmos Específicos
- [[Algoritmos de Ordenação]]
- [[Algoritmos de Busca]]
```

### **4. Fluxo de Trabalho Diário**

#### **Rotina Recomendada**
1. **Início do Dia**
   - Revisar notas com `#review/pending`
   - Atualizar status de projetos
   - Criar nota diária se necessário

2. **Durante o Dia**
   - Usar notas rápidas para captura imediata
   - Processar notas rápidas regularmente
   - Atualizar status e tags conforme necessário

3. **Final do Dia**
   - Revisar notas criadas
   - Verificar conexões necessárias
   - Planejar revisões futuras

### **5. Manutenção do Sistema**

#### **Revisão Semanal**
1. Processar todas as notas rápidas
2. Atualizar status de projetos
3. Verificar tags pendentes
4. Planejar revisões da próxima semana

#### **Revisão Mensal**
1. Arquivar projetos concluídos
2. Atualizar MOCs principais
3. Verificar consistência de tags
4. Identificar áreas para expansão/melhoria

### **6. Problemas Comuns e Soluções**

#### **Quando Não Souber Onde Colocar uma Nota**
1. Considere o uso principal da nota
2. Use tags para múltiplas categorias
3. Crie links para contextos relacionados
4. Se ainda não tiver certeza, use a pasta mais genérica e tags específicas

#### **Quando uma Nota Crescer Demais**
1. Divida em notas menores e mais específicas
2. Crie uma nota MOC para conectá-las
3. Mantenha apenas o resumo na nota original
4. Use links para notas detalhadas

### **7. Dicas de Produtividade**

#### **Atalhos Recomendados**
- Configure teclas de atalho para templates
- Crie atalhos para tags comuns
- Use o seletor rápido para navegação

#### **Plugins Essenciais**
- Calendar para visualização temporal
- Dataview para consultas
- Kanban para projetos
- Graph View para visualizar conexões

### **8. Exemplos de Uso**

#### **Nota de Estudo**
```markdown
---
aliases: [Algoritmos de Ordenação]
tags:
  - type/study
  - context/academic
  - theme/algorithms
  - status/in-progress
date: 2024-01-01
---

# Algoritmos de Ordenação

## Objetivo
Compreender os principais algoritmos de ordenação e suas complexidades.

## Conteúdo
1. Bubble Sort
2. Quick Sort
3. Merge Sort

## Conexões
- [[Complexidade de Algoritmos]]
- [[Estruturas de Dados]]

## Notas
[Conteúdo...]
```

#### **Nota de Projeto**
```markdown
---
aliases: [Projeto: Motor de Jogo]
tags:
  - type/project
  - context/work
  - theme/dev
  - status/planning
date: 2024-01-01
---

# Projeto: Motor de Jogo

## Objetivo
Criar motor de jogo 2D básico.

## Etapas
1. [ ] Configuração básica
2. [ ] Sistema de renderização
3. [ ] Sistema de física

## Recursos Necessários
- C++
- OpenGL

## Conexões
- [[Desenvolvimento de Jogos]]
- [[Básicos do OpenGL]]
```

## **Conclusão**

Este sistema foi projetado para crescer organicamente com o uso. A chave é manter consistência na aplicação dos princípios básicos enquanto permite flexibilidade suficiente para adaptação às necessidades individuais. Comece com as estruturas básicas e expanda conforme necessário, sempre mantendo o foco na simplicidade e usabilidade.