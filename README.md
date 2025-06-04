# 🎓 Projeto UNIESP - Front-End com React

Este projeto simula a interface de um site institucional da Faculdade UNIESP, utilizando **ReactJS**, **React Router** e **React-Bootstrap**. Ele permite navegação entre páginas, visualização de conteúdos estáticos e dinâmicos (como notícias), além de uma estrutura preparada para integração com uma API fake via JSON Server.

---

## 🚀 Tecnologias Utilizadas

- [ReactJS](https://reactjs.org/)
- [React Router DOM](https://reactrouter.com/)
- [React-Bootstrap](https://react-bootstrap.github.io/)
- [Bootstrap 5](https://getbootstrap.com/)
- [Axios](https://axios-http.com/)
- [JSON Server (fake API)](https://github.com/typicode/json-server)
- [Vite](https://vitejs.dev/)

---

## 📁 Estrutura do Projeto
src/
├── components/
│   ├── CustomNavbar.jsx         # Barra de navegação responsiva
│   └── Bannerad.jsx             # (Em construção)
├── pages/
│   ├── Inicial.jsx              # Página inicial
│   ├── Faculdade.jsx            # Página “A Faculdade”
│   ├── DpoLgpd.jsx              # Página “DPO LGPD”
│   ├── Noticias.jsx             # Listagem de notícias (requisição à API)
│   └── VisualizaNoticia.jsx     # Visualização de notícia (rota dinâmica)
├── App.jsx                      # Componente principal com rotas
└── main.jsx                     # Ponto de entrada da aplicação
---

## 📌 Funcionalidades Implementadas

- ✅ SPA com React Router
- ✅ Navbar com responsividade (Offcanvas em telas pequenas)
- ✅ Página inicial com cards institucionais
- ✅ Página "A Faculdade"
- ✅ Página "DPO LGPD"
- ✅ Página de listagem de notícias (GET via Axios)
- ✅ Página de visualização de notícia individual (useParams)
- ✅ Integração com API fake (JSON Server)

---

## 🧪 Requisitos para rodar o projeto

- Node.js
- npm ou yarn

---

## 🛠️ Como executar o projeto localmente

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/uniesp-react.git

# 2. Acesse a pasta do projeto
cd uniesp-react

# 3. Instale as dependências
npm install

# 4. Inicie o servidor de desenvolvimento run dev

---
##Rodando o JSON Server (fake API)
# 1. Instale o JSON Server globalmente (se ainda não tiver)
npm install -g json-server

# 2. Crie um arquivo db.json com estrutura semelhante a:
{
  "noticias": [
    {
      "id": 1,
      "titulo": "Nova Biblioteca Inaugurada",
      "imagem": "URL_DA_IMAGEM",
      "texto": "Texto completo da notícia"
    }
  ]
}

# 3. Inicie o servidor
json-server --watch db.json --port 3000

👨‍🏫 Projeto Acadêmico

Este projeto faz parte do curso de Sistemas de Informação da Faculdade UNIESP, sob orientação do professor Kelson Almeida.

