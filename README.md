# ✅ Prova Prática - 17/06

## Integrantes:
- Rafael Manso Campigotto - RA: 22014205-2
- João Henriue Salvalagio - RA: 23123581-2
- Eduardo Navarro - RA: 22014553-2
- Eduardo Voltatone - RA: 22207439-2
- Luciano Giraldi - RA: 22228890-2
- Pedro Gomes - RA: 22087525-2

Aplicação RESTful desenvolvida com NestJS que permite o gerenciamento de usuários com JWT. Ideal para integrar com front-ends web ou mobile, a API oferece recursos robustos como autenticação JWT, e controle de usuários.

---

## 🔧 Funcionalidades

### 🔹 Autenticação
- Cadastro e login de usuários
- JWT com expiração configurável
- Guardas de rota para proteger endpoints privados

---

## 📦 Estrutura de Módulos

- `auth`: Login, registro e autenticação
- `users`: Gerenciamento de usuários

---

## ⚙️ Tecnologias Utilizadas

- **NestJS** – Framework backend principal
- **PostgreSQL** – Banco de Dadoss
- **JWT** – Autenticação
- **Docker** – Containerização para facilitar o deploy

---

## 🔐 Segurança

- Criptografia de senhas com Bcrypt
- Autenticação JWT protegendo todas as rotas privadas
- CORS configurado para integração com aplicações externas

---

## 🚀 Como Executar

```bash
# Clonar o projeto
git clone https://github.com/seuusuario/todo-list-api

# Entrar no diretório
cd todo-list-api

# Instalar dependências
npm install

# Rodar o banco via Docker
docker compose up -d

# Iniciar a API
npm run start:dev
```