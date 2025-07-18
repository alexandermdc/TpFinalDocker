# 📚 WebAcademy

Aplicação full-stack para cadastro e visualização de livros. Utiliza React no frontend, Node.js com Prisma no backend, banco de dados MySQL, phpMyAdmin e está totalmente containerizada com Docker Compose.

---

---

## 🚀 Instruções de Execução

### ✅ Pré-requisitos

- Docker
- Docker Compose

---

### ▶️ Subindo os contêineres

```bash
docker compose up --build

docker compose up -d
docker compose exec backend sh
npx prisma migrate dev --name init ## para iniciar o prisma no banco de dados

exit ## para sair do container

```

---

