
# 📝 Task Manager

Um pequeno gerenciador de tarefas desenvolvido com **Vue.js 3** utilizando a API de composição (`setup`, `ref`, `watch`, `computed`) e **LocalStorage** para persistência de dados no navegador.

> 🚀 Totalmente frontend, sem necessidade de backend ou banco de dados.

---

## ✨ Funcionalidades

- ✅ Adicionar tarefas com nível de prioridade (Alta, Média, Baixa)
- 🔍 Filtrar tarefas em tempo real
- ☑️ Marcar tarefas como concluídas
- ❌ Remover tarefas
- 💾 Persistência automática via `localStorage`

---

## 🧪 Tecnologias Utilizadas

- [Vue.js 3](https://vuejs.org/)
- HTML5, CSS3
- LocalStorage

---

## 📂 Como executar

1. Clone este repositório:

```bash
git clone https://github.com/Andreeoak/TaskManager.git
````

2. Abra o arquivo `index.html` em seu navegador (não há dependências externas ou backend):

```bash
cd TaskManager
open index.html  # ou use o live server do VSCode
```

---

## 📁 Estrutura do Projeto

```
TaskManager/
├── index.html         # HTML principal
├── styles.css         # Estilos customizados
└── README.md          # Este arquivo
```

---

## 📦 Futuras Melhorias (ideias)

* Armazenamento offline com IndexedDB
* Suporte a deadlines com datas
* Organização por categorias ou tags
* Deploy como PWA (Progressive Web App)

---

## 📌 Observações

* Este projeto é apenas frontend.
* Os dados são salvos no navegador usando `localStorage`. Ao limpar os dados do navegador, as tarefas serão perdidas.



