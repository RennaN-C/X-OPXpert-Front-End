# X-OPXpert (Frontend) 🖥️

[![X OPXpert Logo](https://raw.githubusercontent.com/RennaN-C/X-OPXpert/main/X-OPXpert/assets/img/logo.png)](https://raw.githubusercontent.com/RennaN-C/X-OPXpert/main/X-OPXpert/assets/img/logo.png)

[![Status Em Desenvolvimento](https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-green)](https://github.com/RennaN-C/x-opxpert-frontend)
[![Built with React](https://img.shields.io/badge/Built%20with-React-61DAFB?logo=react)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-B73BFE?logo=vite&logoColor=FFD62E)](https://vitejs.dev/)
[![GitHub last commit](https://img.shields.io/github/last-commit/RennaN-C/x-opxpert-frontend)](https://github.com/RennaN-C/x-opxpert-frontend)

---

## 💻 Sobre o projeto

**X-OPXpert (Frontend)** é a interface de usuário (cliente web) do sistema de **gestão de ordens de produção**. Esta aplicação é construída com **React** e **Vite** para consumir a API fornecida pelo [**https://github.com/RennaN-C/X-OPXpert-Back-End**](https://github.com/RennaN-C/X-OPXpert-Back-End).

A interface permite que os usuários criem, acompanhem e gerenciem ordens de produção, controlem materiais e equipes de forma visual e intuitiva.

### Backend

O código-fonte do servidor (API) está em um repositório separado.

➡️ **Acesse o repositório do Backend aqui: [https://github.com/RennaN-C/X-OPXpert-Back-End](https://github.com/RennaN-C/X-OPXpert-Back-End)**

---

## 🛠 Tecnologias Utilizadas

* **React**: Biblioteca para construção da interface de usuário.
* **Vite**: Ferramenta de build e servidor de desenvolvimento rápido.
* **JavaScript**: Linguagem principal da aplicação.
* **CSS / (ou SASS/Styled-Components?)**: Estilização dos componentes.
* **(Axios?)**: Cliente HTTP para realizar requisições à API.
* **(React Router DOM?)**: Para gerenciamento de rotas na aplicação.

---

## 🖼️ Telas da Aplicação

*(Sugestão: Mova as imagens do repositório backend para este, ou atualize os links se elas estiverem em outro lugar)*

### Web
[![X OPXpert Web ](https://raw.githubusercontent.com/RennaN-C/X-OPXpert/main/assets/web_dark.png)](https://raw.githubusercontent.com/RennaN-C/X-OPXpert/main/assets/web_dark.png)

### Mobile
[![X OPXpert Mobile Light](https://raw.githubusercontent.com/RennaN-C/X-OPXpert/main/assets/mobile_light.png)](https://raw.githubusercontent.com/RennaN-C/X-OPXpert/main/assets/mobile_light.png)
[![X OPXpert Mobile Dark](https://raw.githubusercontent.com/RennaN-C/X-OPXpert/main/assets/mobile_dark.png)](https://raw.githubusercontent.com/RennaN-C/X-OPXpert/main/assets/mobile_dark.png)

---

## 🛣️ Como executar o projeto (Frontend)

### Pré-requisitos

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/en/) (v18 ou superior)
* O [**Servidor Backend (X-OPXpert)**](https://github.com/RennaN-C/X-OPXpert) deve estar em execução.

### Rodando o Frontend (Cliente Web)

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/RennaN-C/X-OPXpert-Front-End](https://github.com/RennaN-C/X-OPXpert-Front-End)
    cd x-opxpert-frontend
    ```

2.  **Instale as dependências:**
    ```bash
    npm install
    ```

3.  **Configure a URL da API:**
    * Verifique se existe um arquivo `.env` ou `.env.local` na raiz do projeto.
    * Caso não exista, crie-o.
    * Adicione a variável de ambiente que aponta para o seu backend (que está rodando em `http://localhost:8080`). O nome da variável no Vite geralmente começa com `VITE_`.

    *Exemplo de `.env.local`:*
    ```env
    VITE_API_BASE_URL=http://localhost:8080/api
    ```
    *(Nota: Ajuste `VITE_API_BASE_URL` e o caminho `/api` conforme a necessidade do seu código)*

4.  **Inicie o servidor de desenvolvimento:**
    ```bash
    npm run dev
    ```

5.  Abra seu navegador e acesse `http://localhost:5173` (ou a porta indicada pelo Vite no seu terminal).
