# JobFinder

O **JobFinder** é uma aplicação web para cadastro e visualização de vagas de emprego na área de tecnologia.  
Permite que empresas divulguem vagas e que candidatos visualizem oportunidades filtradas, com foco especial em vagas home office.

## 🚀 Funcionalidades

- Cadastro de vagas (Título, descrição, empresa, salário, e-mail para contato)
- Listagem de vagas em ordem de criação
- Marcação de vagas como "Nova"
- Visualização da vaga selecionada.
- Busca de vagas por título.
- Interface responsiva usando Bootstrap

## 🛠 Tecnologias Utilizadas

- **Node.js** – Runtime JavaScript no servidor
- **Express** – Framework web para Node.js
- **Express-Handlebars** – Template engine para renderização de páginas
- **Sequelize** – ORM para integração com banco de dados
- **SQLite3** – Banco de dados relacional leve
- **Bootstrap** – Framework CSS responsivo

## 📂 Estrutura do Projeto

```
projetosJS/jobfinder/
│
├── db/
|   ├── app.db               # Banco de dados local (SQLite3)
│   └── connection.js        # Configuração de conexão com o banco de dados
├── models/
│   └── Job.js                # Modelo Sequelize para as vagas
├── routes/
│   └── jobs.js               # Rotas relacionadas a vagas
├── views/
│   ├── layouts/
│   │   └── main.handlebars   # Layout principal
│   ├── index.handlebars      # Página inicial (listagem)
|   ├── view.handlebars       # Visualização da vaga selecionada.
│   └── add.handlebars        # Formulário para adicionar vaga
├── public/                   # Arquivos estáticos (CSS, imagens)
├── app.js                    # Configuração principal do servidor
└── package.json              # Dependências e scripts
```

## 💻 Como Rodar o Projeto

1. **Clone este repositório**:

   ```bash
   git clone https://github.com/carvalhosete/Job-Finder.git
   cd JobFinder
   ```

2. **Instale as dependências**:

   ```bash
   npm install
   ```

3. **Inicie o servidor**:
   ```bash
   npm start
   ```
   O servidor rodará em: [http://localhost:3000](http://localhost:3000)

## 📌 Observações

- Este projeto foi desenvolvido com foco em aprendizado de **JavaScript**, **Node.js**, **Express** e integração com banco de dados via **Sequelize**.
- O banco de dados SQLite3 já está configurado para uso local, sem necessidade de instalação adicional.
