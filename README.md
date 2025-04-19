# 📋 Lista de Tarefas Angular

Este repositório contém um projeto prático de uma aplicação **To-Do List** desenvolvida com **Angular**, com o objetivo de aplicar na prática os principais conceitos do framework, incluindo:

- Criação e organização de componentes
- Estilização com SCSS
- Comunicação entre componentes
- Armazenamento de dados no `localStorage`
- Interação com o usuário
- Feedbacks visuais com SweetAlert2

---

## 🚀 Funcionalidades

- ✅ Adicionar tarefas
- 📝 Editar itens da lista
- ☑️ Marcar tarefas como concluídas
- ↺ Atualizar valores dos itens
- ❌ Excluir itens individualmente
- 🩹 Limpar todos os itens da lista
- 📂 Separar tarefas **pendentes** e **concluídas**
- 🔍 Filtros e organização automática da lista
- 📀 Persistência de dados no navegador via `localStorage`
- 🎨 Interface moderna e responsiva com SCSS
- 🔔 Diálogos de confirmação com Sweet Alert 2

---

## 🧠 Tecnologias e conceitos aplicados

- Angular CLI
- Angular Standalone Components
- Diretivas estruturais (`*ngIf`, `*ngFor`)
- Property e Event Binding
- Componentes reutilizáveis
- Inputs e Outputs para comunicação
- SCSS para organização de estilos
- LocalStorage API
- Enum e Interface para tipagem forte
- SweetAlert2 para notificações

---

## 📂 Estrutura de Pastas

```
src/
├── app/
│   ├── modules/
│   │   └── to-do-list/
│   │       ├── components/
│   │       │   ├── input-add-item/
│   │       │   └── input-list-item/
│   │       ├── pages/list/
│   │       ├── enum/
│   │       └── interface/
│   ├── app.component.ts
│   └── app.routes.ts
├── assets/
│   ├── img/
│   └── icons/
└── styles.scss
```

---

## 📸 Demonstração

> A seguir, algumas telas da aplicação em funcionamento:

### Tela Inicial - Lista vazia
![Tela inicial](./src/assets/img/tasklist.jpg)

### Adicionando e listando tarefas
![Lista com itens](./demo/demo1.png)

### Confirmação de exclusão
![SweetAlert2](./demo/demo2.png)

---

## 📦 Instalação e uso

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/lista-de-tarefas-angular.git
cd lista-de-tarefas-angular

# Instale as dependências
npm install

# Rode o projeto localmente
ng serve

# Acesse em http://localhost:4200
```

---
