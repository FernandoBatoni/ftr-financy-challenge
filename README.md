# Desafio de Pós-Graduação – Financy

**Financy** is a full-stack application for personal finance management, developed with a focus on a modern and scalable architecture using GraphQL.

## 💻 Tecnologias

Este repositório contém:

- **Backend**
  - TypeScript
  - Express
  - API: GraphQL (Type-GraphQL + Apollo Server)
  - ORM: Prisma
  - SQLite
  - JWT

- **Frontend**
  - React (Vite)
  - GraphQL: Apollo Client
  - Zustand
  - Tailwind CSS + Shadcn/ui

## ⚙️ Prerequisites

- Node.js (v18 ou superior)
- bun

## 🛠️ Installation

1. **Clone repo**

   ```bash
   git clone <url-do-repositorio>
   ```

2. **Configure as variáveis de ambiente**
   Create `.env` file based on `.env.example`.

3. **Install dependencies**

   ```bash
   cd backend
   bun i
   ```

4. **Execute migrations**

   ```bash
   bun migrate
   ```

5. **Optional: Execute seed**
   Popula o banco com dados de exemplo.

   ```bash
   bun seed
   ```

6. **Install front-end deps**

   ```bash
   cd ../frontend
   bun i
   ```

7. **Execute**
   Você precisará de dois terminais:

   **Backend:**

   ```bash
   cd backend
   bun dev
   ```

   **Frontend:**

   ```bash
   cd frontend
   bun dev
   ```

   Back-end URL: `http://localhost:4000/graphql`
   Front-end URL: `http://localhost:5173`
