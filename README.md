# TaskFlow — Lista de Tarefas Profissional

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-green?style=flat)

> Uma to-do list elegante e 100% funcional, feita com HTML, CSS e JavaScript puro — sem frameworks, sem dependências externas.

---

## Prompt Original Usado para Criar o Projeto

> *"Faça uma todo list em html e em CSS, quero que você faça uma to do list de forma profissional com as seguintes funções: Adicionar e concluir a fazeres. data e hora de cada ação. e quero que fique bonito e 100% funcional pensando em tudo que alguem precisa em uma to do list."*

---

## Sobre o Projeto

O **TaskFlow** é uma aplicação de gerenciamento de tarefas criada inteiramente com tecnologias web nativas. O foco foi entregar uma experiência visual refinada e uma experiência de uso completa, sem abrir mão da simplicidade de um único arquivo HTML.

---

## Funcionalidades

### Gerenciamento de Tarefas
- Adicionar tarefas com título, categoria, prioridade e prazo
- Concluir e reabrir tarefas com um clique
- Editar o texto de qualquer tarefa
- Excluir tarefas individualmente

### Registro de Data e Hora
- Data e hora de **criação** registradas automaticamente em cada tarefa
- Data e hora de **conclusão** exibidas ao marcar como feita
- Relógio ao vivo no cabeçalho atualizado em tempo real

### Organização e Filtros
- Filtrar por: Todas, Pendentes, Concluídas, Com prazo hoje
- Ordenar por: Mais recentes, Mais antigas, Alfabética, Prioridade, Prazo
- Indicador visual de tarefas **vencidas** (overdue)

### Ações em Lote
- Concluir todas as tarefas de uma vez
- Remover apenas as tarefas concluídas
- Limpar toda a lista

### Estatísticas e Progresso
- Cards com contagem de: Total, Pendentes e Concluídas
- Barra de progresso do dia calculada automaticamente

### UX e Visual
- Toasts de feedback para cada ação realizada
- Design responsivo para mobile e desktop
- Dados salvos automaticamente no `localStorage` do navegador (persiste ao fechar a aba)
- Tarefas de exemplo carregadas na primeira visita

---

## Categorias e Prioridades

| Categoria | Prioridade |
|-----------|-----------|
| 🏠 Pessoal | 🔴 Alta |
| 💼 Trabalho | 🟡 Média |
| 💚 Saúde | 🟢 Baixa |
| 📚 Estudos | |
| 📌 Outro | |

---

## Como Usar

Por ser um único arquivo `.html`, não há instalação ou dependências.

1. Baixe o arquivo `todo-list.html`
2. Abra no navegador (Chrome, Firefox, Edge, Safari)
3. Comece a adicionar suas tarefas

---

## Tecnologias Utilizadas

- **HTML5** — estrutura semântica da aplicação
- **CSS3** — estilização completa com variáveis CSS, animações e design responsivo
- **JavaScript (ES6+)** — lógica de toda a aplicação, sem bibliotecas externas
- **localStorage** — persistência de dados no navegador
- **Google Fonts** — tipografia com DM Serif Display e DM Sans

---

## Estrutura do Arquivo

```
todo-list.html
├── <head>         → meta tags, fontes e variáveis CSS
├── <style>        → todo o CSS da aplicação (~400 linhas)
├── <body>         → estrutura HTML da interface
└── <script>       → lógica JS: estado, renderização e eventos
```

---

## Compatibilidade

Funciona em todos os navegadores modernos com suporte a ES6+:

| Chrome | Firefox | Edge | Safari |
|--------|---------|------|--------|
| ✅ | ✅ | ✅ | ✅ |

---

## Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.

---

*Gerado com assistência do Claude (Anthropic) — abril de 2026*
