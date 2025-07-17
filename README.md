# 🗃️ Template de Vault do Obsidian

Um template minimalista e poderoso para organizar seu vault do Obsidian, focando em simplicidade e eficiência. A característica principal deste sistema é sua **estrutura intencionalmente controlada** com hierarquia de dois níveis de profundidade, complementada por um sistema robusto de propriedades e tags.

> **Nota**: Este é um fork traduzido e adaptado para português brasileiro do template original. Créditos ao criador original do sistema de organização.

## ✨ Características

- 📁 **Hierarquia Controlada**: Máximo de dois níveis de profundidade - mantém as coisas organizadas e simples!
- 🏷️ Organização baseada em propriedades com sistema abrangente de tags
- 🔗 Uso estratégico de links e MOCs (Mapas de Conteúdo)
- 📝 Templates prontos para uso para diferentes tipos de notas
- 🚀 Fácil de começar, poderoso para escalar

## 🎯 Por Que Usar Este Template?

### Principais Benefícios
- **Simplicidade**: Máximo de dois cliques para acessar qualquer informação
- **Eficiência**: Reduz a "paralisia de análise" ao decidir onde armazenar notas
- **Flexibilidade**: Cresce organicamente com seu uso
- **Manutenção**: Fácil de manter e reorganizar quando necessário

## 🚀 Como Começar

1. Clone este repositório ou baixe como ZIP
2. Abra o Obsidian
3. Selecione "Abrir pasta como vault" e escolha a pasta do template
4. Confira `99 - Meta/Sistema/` para guias detalhados sobre como usar o sistema

## 📁 Estrutura de Pastas

```
.
├── 00 - Dashboard/         # Hub central do vault
├── 01 - Pessoal/          # Conteúdo pessoal e diário
│   ├── Diário/
│   ├── Notas Rápidas/
│   ├── Planos/
│   ├── Reflexões/
│   └── Saúde/
├── 02 - Conhecimento/      # Notas de estudo por área
│   ├── Computação/         # Exemplos de áreas de conhecimento
│   ├── Filosofia/
│   ├── História/
│   ├── Literatura/
│   └── Saúde/
├── 03 - Projetos/          # Projetos em desenvolvimento
│   ├── Projeto1/
│   ├── Projeto2/
│   └── Projeto3/
├── 04 - Referências/       # Material de referência e bibliografia
│   ├── Artigos/
│   ├── Cursos/
│   ├── Livros/
│   └── Tutoriais/
└── 99 - Meta/              # Sistema e templates
    ├── Templates/
    └── Sistema/
```

## 📑 Estrutura de Propriedades das Notas

Cada nota no sistema usa essas propriedades padrão no frontmatter YAML:

```yaml
---
aliases: [Nomes Alternativos]
tags:
  - type/study
  - context/academic
  - theme/algorithms
  - status/in-progress
date: 2024-01-01
last_updated: 2024-01-10
---
```

### Exemplo de Estrutura de Nota

[Confira aqui](02%20-%20Conhecimento/Computação/Algorithm_complexity.md)

## 🏷️ Sistema de Tags
As tags são implementadas dentro do sistema de propriedades como mostrado nos exemplos acima. Confira o [guia de tags](99%20-%20Meta/Sistema/Guia%20de%20Tags%20e%20Links%20-%20Organização%20de%20Notas%20no%20Obsidian.md) para uma lista completa.

### 1. Tags de Tipo
Identificam a natureza da nota:
```
#type/task       → Tarefas
#type/project    → Projetos
#type/daily      → Notas diárias
#type/study      → Material de estudo
#type/idea       → Insights
#type/reflection → Reflexões
#type/habits     → Rotinas e hábitos
```

### 2. Tags de Contexto
Indicam o ambiente da nota:
```
#context/studies     → Aprendizado
#context/work        → Profissional
#context/personal    → Desenvolvimento pessoal
#context/academic    → Universidade
#context/hobbies     → Interesses pessoais
```

### 3. Tags de Tema
Organizam por área de conhecimento:
```
Computação:
#theme/cybersecurity → Segurança
#theme/dev           → Desenvolvimento
#theme/os            → Sistemas operacionais
#theme/algorithms    → Algoritmos e estruturas
#theme/AI            → Inteligência artificial

...e muito mais (veja o guia completo de tags)
```

### 4. Tags de Metadados
Controlam status e prioridade:
```
#status/[completed|in-progress|planning|idea]
#priority/[high|medium|low]
#review/[pending|completed|needed]
```

### Melhores Práticas de Uso de Tags

#### Tags Mínimas Obrigatórias
Para manter consistência e facilitar a busca, cada nota deve incluir no mínimo em suas propriedades:
1. Uma tag de tipo (`#type/...`)
2. Uma tag de contexto (`#context/...`)
3. Uma tag de tema (`#theme/...`)
4. Uma tag de status/prioridade quando aplicável

## 🔗 Sistema de Links

### Tipos de Links
1. **Links Diretos**: `[[Nome da Nota]]`
2. **Links com Alias**: `[[Nome da Nota|Texto Exibido]]`
3. **Links de Seção**: `[[Nome da Nota#Seção]]`

### Práticas Recomendadas
- Criar conexões significativas
- Usar MOCs (Mapas de Conteúdo) para organizar temas
- Aproveitar backlinks para descobrir relacionamentos
- Construir hierarquias flexíveis através de links

## 📚 Métodos Integrados

O sistema incorpora práticas de:
- **Zettelkasten**: Notas atômicas interconectadas
- **PARA**: Projetos, Áreas, Recursos, Arquivos
- **Building a Second Brain**: Captura e organização de conhecimento
- **GTD**: Getting Things Done para gerenciamento de tarefas
- **Técnica Feynman**: Ensinar para aprender
- **Elaboração Interrogativa**: Aprendizado baseado em perguntas
- **Método Cornell**: Anotações sistemáticas e revisão

## ⚙️ Plugins Sugeridos

Este template foi projetado para funcionar sem plugins da comunidade, permitindo que você comece limpo e construa baseado em suas necessidades. Aqui estão algumas ótimas sugestões de plugins que podem melhorar sua experiência:

### Melhoradores de funcionalidade principal:
- Dataview: Para consultas avançadas de dados e conteúdo dinâmico, aproveitando ao máximo as propriedades
- Calendar: Melhor gerenciamento de datas e notas diárias
- Tag Wrangler: Gerenciamento aprimorado de tags
- Homepage: Página inicial personalizada
- Iconize: Melhoria visual com ícones

### Extensões opcionais:
- Natural Language Dates: Entradas de data mais intuitivas
- Kanban: Gerenciamento visual de tarefas
- Templater: Funcionalidade avançada de templates

Todos os plugins são opcionais - sinta-se livre para instalar apenas o que se adequa ao seu fluxo de trabalho!

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se livre para:
1. Criar Issues com sugestões
2. Enviar Pull Requests com melhorias
3. Compartilhar suas experiências usando o template
4. Reportar bugs ou problemas

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🙏 Agradecimentos

Este template foi inspirado por vários sistemas de gerenciamento de conhecimento e pela comunidade do Obsidian. Agradecimentos especiais para:
- Metodologia Zettelkasten
- Sistema PARA do Tiago Forte
- Comunidade r/Obsidian
