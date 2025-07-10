# 🧠 NLW Agents 2025

Projeto desenvolvido durante o **Next Level Week (NLW)** da [Rocketseat](https://www.rocketseat.com.br/), com foco em integração de inteligência artificial para interações em tempo real com transmissões ao vivo.

> Crie salas, transcreva lives e permita que a IA responda perguntas automaticamente com base no conteúdo da transmissão.

---

## ✨ Funcionalidades

- 🎥 Criação de salas para streamers
- 📝 Transcrição automática da live em tempo real
- 🤖 Respostas geradas por IA com base na transcrição
- 💬 Interação entre espectadores e IA durante a transmissão

---

## 🧰 Tecnologias Utilizadas

### 🔧 Backend

- [Node.js](https://nodejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Fastify](https://www.fastify.io/)
- [Drizzle ORM](https://orm.drizzle.team/)
- [PostgreSQL](https://www.postgresql.org/)
- [Google GenAI](https://ai.google.dev/)
- [Ultracite](https://github.com/ultracite/ultracite)
- [Zod](https://zod.dev/)
- [Docker](https://www.docker.com/)
- [BiomeJS](https://biomejs.dev/)

### 🎨 Frontend

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [ShadCN UI](https://ui.shadcn.dev/)
- [Radix UI](https://www.radix-ui.com/)
- [React Query](https://tanstack.com/query/latest)
- [Day.js](https://day.js.org/)
- [Zod](https://zod.dev/)
- [BiomeJS](https://biomejs.dev/)

---

## 🚀 Como Rodar o Projeto Localmente

### Pré-requisitos

- Node.js
- Docker
- Yarn ou npm

### Passo a passo

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/nlw-agents-2025.git
cd nlw-agents-2025

# Suba o banco de dados com Docker
docker-compose up -d

# Instale as dependências do backend
cd server
npm install

# Rode as migrações e inicie o servidor
npm run dev

# Em outro terminal, inicie o frontend
cd ../web
npm install
npm run dev
```
<img width="1036" height="724" alt="image" src="https://github.com/user-attachments/assets/5539969d-ca82-4d68-8601-948fe1c354f2" />
<img width="1070" height="1248" alt="image" src="https://github.com/user-attachments/assets/d86e2836-c693-404a-9dda-3895b848edb3" />
<img width="705" height="701" alt="image" src="https://github.com/user-attachments/assets/c99cfef6-ee01-44e8-97e9-4a6482a0e506" />
