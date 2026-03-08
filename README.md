# 🚀 TechJobs API Mock & Dashboard

![License](https://img.shields.io/github/license/flaviare1s/json-server?style=for-the-badge)
![Repo Size](https://img.shields.io/github/repo-size/flaviare1s/json-server?style=for-the-badge)
![Last Commit](https://img.shields.io/github/last-commit/flaviare1s/json-server?style=for-the-badge)

O **TechJobs** é uma solução completa para simulação de APIs REST e visualização de dados. O projeto utiliza o `json-server` para criar um ecossistema de backend fictício robusto, acompanhado de um dashboard interativo para gerenciamento das informações contidas no banco de dados JSON. Desenvolvido durante o curso de Full Stack do Geração Tech, com o objetivo de aprender a biblioteca json-server.

## 🛠️ Tecnologias Utilizadas

A stack foi escolhida para garantir agilidade no desenvolvimento e leveza na execução:

| Frontend | Backend (Simulado) | Requisições | Estilização |
| :---: | :---: | :---: | :---: |
| <img src="https://skillicons.dev/icons?i=js,html" /> | <img src="https://skillicons.dev/icons?i=nodejs" /> | <img src="https://img.shields.io/badge/axios-5a29e4?style=for-the-badge&logo=axios&logoColor=white" /> | <img src="https://skillicons.dev/icons?i=css" /> |

## 📦 Estrutura do Projeto

*   `db.json`: Nosso "banco de dados" que armazena os objetos da API.
*   `index.html` & `dashboard.html`: Interfaces de usuário para interação com os dados.
*   `main.js`: Lógica principal, manipulação de DOM e integração com Axios.
*   `style.css`: Identidade visual moderna e responsiva.

## 🚀 Como Executar

Siga os passos abaixo para rodar o projeto localmente:

### Pré-requisitos
*   [Node.js](https://nodejs.org/) instalado.
*   Um gerenciador de pacotes (NPM ou Yarn).

### Instalação
1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/flaviare1s/json-server.git
    cd json-server
    ```

2.  **Instale as dependências:**
    ```bash
    npm install
    ```

### Executando a API
Para subir o servidor que disponibiliza os dados do arquivo `db.json`:
```bash
npm start
```
A API estará disponível em: `http://localhost:3000`

### Acessando o Dashboard
Após iniciar o servidor, basta abrir o arquivo `index.html` no seu navegador (recomendado usar a extensão *Live Server* do VSCode).

## 📡 Endpoints Disponíveis

O JSON Server gera automaticamente rotas baseadas na estrutura do seu `db.json`. Exemplos comuns:

*   `GET /jobs`: Lista todos os itens.
*   `POST /jobs`: Cria um novo registro.
*   `PUT /jobs/:id`: Atualiza um registro existente.
*   `DELETE /jobs/:id`: Remove um registro.

## 🎨 Funcionalidades

- [x] **API Full REST:** Suporte a todos os métodos HTTP.
- [x] **Persistência Local:** As alterações são salvas automaticamente no `db.json`.
- [x] **Dashboard:** Interface limpa para visualização de métricas/dados.
- [x] **Integração Axios:** Comunicação eficiente entre frontend e backend simulado.

---

*Este projeto é para fins de estudo e prototipagem rápida.*