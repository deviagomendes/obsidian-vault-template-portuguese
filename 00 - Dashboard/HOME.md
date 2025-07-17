# 🎯 Dashboard Pessoal

> [!quote] Pensamento do Dia
> "A vida é o que acontece enquanto você está ocupado fazendo outros planos." - John Lennon

> [!warning] **Aviso Importante**
> - Este dashboard é apenas um exemplo, que assume notas que não existem no seu vault e o plugin "Dataview".
> - Por favor, adapte-o ao seu uso.
> - Use isto como inspiração para criar seu próprio dashboard.


## 🌅 Links Rápidos
- [[Routine|Minha Rotina]] 
- [[Training|Programa de Treino]] 
- [[Diet|Dieta]] 
- [[01 - Pessoal/Diário/{{date}}|Entrada de Hoje]] 
- [[Tasks|Tarefas Pendentes]]

## 🎯 Áreas de Foco

> [!info] Estudos Ativos
> - [[02 - Conhecimento/Computação/Cybersecurity|🔒 Cibersegurança]]
> - [[02 - Conhecimento/Computação/Development|💻 Desenvolvimento]]
> - [[02 - Conhecimento/Filosofia/Stoicism|📚 Estoicismo]]

> [!tip] Projetos em Andamento
> - [[03 - Projetos/Projeto1|🚀 Projeto Principal]]
> - [[03 - Projetos/Projeto2|🎮 Desenvolvimento de Jogos]]
> - [[Tasks#In Progress|📋 Ver Todos]]

## 💪 Saúde & Bem-estar

> [!success] Rotinas & Hábitos
> ```dataview
> TASK FROM "01 - Pessoal/Routine"
> WHERE !completed
> LIMIT 5
> ```

> [!note] Próximos Treinos
> ```dataview
> LIST FROM #type/workout AND #status/in-progress
> LIMIT 3
> ```

## 📚 Aprendizado Contínuo

> [!note] Últimas Notas de Estudo
> ```dataview
> TABLE file.ctime as "Criado"
> FROM "02 - Conhecimento"
> SORT file.ctime DESC
> LIMIT 3
> ```

---
## ⚡ Captura Rápida
- [ ] Nova Tarefa
- [ ] Nova Ideia
- [ ] Novo Projeto

---
*Última atualização: {{date}}*