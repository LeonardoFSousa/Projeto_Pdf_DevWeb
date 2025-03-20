# 📌 Projeto: Gerenciador de Tarefas com React

---

## 🚀 Descrição
Este projeto é uma aplicação simples desenvolvida em React para gerenciamento de tarefas. Ele utiliza **React Hooks**, **localStorage** e manipulação de **arrays** para criar uma experiência interativa e persistente para o usuário.

---

## 🎯 Funcionalidades
- ✅ Cadastro de tarefas
- 📌 Lista dinâmica de tarefas usando `map`
- 💾 Persistência de dados no `localStorage`
- ⚛️ Utilização de `useState` e `useEffect`
- 🎨 Personalização da interface com escolha de cores
- 👤 Pergunta inicial ao usuário para salvar seu nome e exibir na tela

---

## 🛠 Tecnologias Utilizadas
- ⚛️ React.js
- 📜 JavaScript (ES6+)
- 🎨 HTML5 / CSS3

---

## 📂 Estrutura do Projeto
```
📂 src
 ┣ 📂 components
 ┃ ┗ 📜 Cadastro.js
 ┣ 📜 index.js
 ┣ 📜 App.js
 ┣ 📜 styles.css
 ┗ 📜 index.html
```

---

## 📥 Instalação e Execução
### ✅ Pré-requisitos
- [Node.js](https://nodejs.org/) instalado
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/) instalado

### 📌 Passos para rodar o projeto
1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```
2. Entre na pasta do projeto:
   ```sh
   cd nome-do-repositorio
   ```
3. Instale as dependências:
   ```sh
   npm install
   ```
4. Inicie o servidor de desenvolvimento:
   ```sh
   npm start
   ```
5. Acesse o projeto no navegador: `http://localhost:3000/`

---

## 🎮 Como Usar
1. **👤 Nome do Usuário:** Ao abrir o site, um `alert` perguntará o seu nome. Esse nome será salvo no `localStorage`.
2. **📝 Cadastro de Tarefas:** Insira o nome da tarefa no campo de entrada e clique em "Registrar" para adicioná-la à lista.
3. **💾 Lista Persistente:** As tarefas adicionadas permanecerão salvas, mesmo que a página seja recarregada.
4. **🎨 Escolha de Cor:** Selecione uma cor nos radio buttons para mudar o fundo da página.

---

## ⚛️ Hooks Utilizados
- `useState`: Gerenciamento de estados para tarefas, nome do usuário e cor do fundo.
- `useEffect`: Sincronização de estados com `localStorage` para manter os dados persistentes.
