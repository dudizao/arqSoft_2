# 📰 Blog API – Gerenciador de Conteúdo Inteligente

Uma poderosa API REST desenvolvida com **Node.js**, projetada para gerenciar um sistema de blog completo com autenticação segura e arquitetura escalável.

---

## ✨ O que você encontra aqui?

- 🔐 **Login Seguro com JWT**  
- 👤 **CRUD de Usuários**  
- ✍️ **Autoria e Controle de Posts**  
- 🔎 **Busca por Palavras-chave**  
- 🧱 **Arquitetura Limpa em Camadas**  
- 📄 **Documentação via Swagger**  
- ✅ **Validação de Dados com Mongoose**  
- 🔒 **Criptografia de Senhas (bcrypt)**

---

## 🚀 Tecnologias Empregadas

| Tecnologia   | Versão     | Finalidade                  |
|--------------|------------|-----------------------------|
| Node.js      | 18+        | Ambiente de execução JS     |
| Express      | ^4.21.2    | Framework web leve          |
| MongoDB      | Atlas/Local| Banco de dados NoSQL        |
| Mongoose     | ^8.x       | ODM para MongoDB            |
| Bcrypt       | ^5.x       | Hash de senhas              |
| JSON Web Token | ^9.x     | Autenticação e Autorização  |
| Swagger UI   | ^4.x       | Documentação interativa     |

---

## 🛠️ Como rodar o projeto

### 1️⃣ Clonando o repositório

```bash
git clone https://github.com/seu-usuario/blog-api.git
cd blog-api
```

### 2️⃣ Instalando dependências

```bash
npm install
```

### 3️⃣ Configurando variáveis de ambiente

Crie um arquivo `.env` e adicione:

```env
PORT=3000
DB_URI=mongodb://localhost:27017/blog
SECRET_KEY=sua_chave_jwt
```

### 4️⃣ Iniciando o servidor

```bash
npm start
```

> Acesse em `http://localhost:3000`

---

## 🔗 Rotas disponíveis

- `POST /auth/login` → Login e geração de token  
- `GET /users` → Listar todos os usuários  
- `POST /posts` → Criar uma nova postagem  
- `GET /posts?q=termo` → Buscar por termo  
- `GET /docs` → Swagger (documentação da API)

---

## 🧠 Organização do Código

- `src/controllers/` → Lida com requisições e respostas
- `src/services/` → Lógica de negócio
- `src/repositories/` → Acesso ao banco
- `src/dtos/` → Transferência e padronização de dados
- `src/models/` → Modelos Mongoose
- `src/routes/` → Rotas Express
- `src/config/` → Conexão e configurações

---

## 📑 Licença

Este projeto está licenciado sob os termos da **MIT License**.

Feito com 💡 para fins educacionais e de desenvolvimento.

---

