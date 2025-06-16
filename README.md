# 📰 Blog API – Gerenciador de Conteúdo Inteligente

Uma poderosa **API RESTful** desenvolvida com **Node.js**, ideal para gerenciar um sistema de blog completo com autenticação segura, arquitetura escalável e boas práticas de desenvolvimento.

---

## ✨ Funcionalidades Principais

- 🔐 **Login Seguro com JWT**
- 👤 **CRUD de Usuários**
- ✍️ **Criação e Gerenciamento de Posts**
- 🔎 **Busca Inteligente por Palavras-chave**
- 🧱 **Arquitetura Limpa e em Camadas**
- 📄 **Documentação Interativa com Swagger**
- ✅ **Validação de Dados com Mongoose**
- 🔒 **Criptografia de Senhas com Bcrypt**

---

## 🚀 Tecnologias Utilizadas

| Tecnologia         | Versão     | Finalidade                        |
|--------------------|------------|-----------------------------------|
| Node.js            | 18+        | Ambiente de execução JavaScript   |
| Express            | ^4.21.2    | Framework web leve                |
| MongoDB (Atlas/local) | -       | Banco de dados NoSQL              |
| Mongoose           | ^8.x       | ODM para MongoDB                  |
| Bcrypt             | ^5.x       | Hash e verificação de senhas      |
| JSON Web Token     | ^9.x       | Autenticação e autorização        |
| Swagger UI         | ^4.x       | Documentação interativa da API    |

---

## 🛠️ Como Executar o Projeto

### 1️⃣ Clonar o Repositório

```bash
git clone https://github.com/seu-usuario/blog-api.git
cd blog-api
```

### 2️⃣ Instalar as Dependências

```bash
npm install
```

### 3️⃣ Configurar as Variáveis de Ambiente

Crie um arquivo `.env` na raiz do projeto e adicione:

```env
PORT=3000
DB_URI=mongodb://localhost:27017/blog
SECRET_KEY=sua_chave_jwt
```

### 4️⃣ Iniciar o Servidor

```bash
npm start
```

Acesse via navegador ou ferramenta REST: [http://localhost:3000](http://localhost:3000)

---

## 🔗 Principais Rotas da API

- `POST /auth/login` → Realiza login e gera token JWT  
- `GET /users` → Lista todos os usuários  
- `POST /posts` → Cria uma nova postagem  
- `GET /posts?q=termo` → Busca posts por palavra-chave  
- `GET /docs` → Acessa a documentação via Swagger  

---

## 🧠 Estrutura do Projeto

```
src/
├── controllers/      → Manipulação de requisições e respostas
├── services/         → Regras de negócio
├── repositories/     → Interações com o banco de dados
├── dtos/             → Padronização de dados e validações
├── models/           → Modelos Mongoose
├── routes/           → Definição de rotas da API
├── config/           → Configurações e conexão com o banco
```

---

## 📑 Licença

Este projeto está licenciado sob os termos da **MIT License**.

---

Feito com 💡 para fins educacionais e de desenvolvimento.