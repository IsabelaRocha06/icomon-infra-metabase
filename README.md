# Infra Metabase - Icomon
>Estrutura para rodar o Metabase com Postgres usando Docker Compose.

# 🚀 Requisitos:
- Docker 24+
- Docker Compose v2+
- Porta 3000 livre (ou altere no .env)
  

# 📦 Estrutura

```bash
├─ docker-compose.yml
├─ .env              # NÃO comitar (use o exemplo)
├─ .env.example      # Modelo de variáveis
├─ .gitignore
└─ README.md
```

# ⚙️ Como usar
```bash
# Subir containers
docker compose up -d

# Parar containers
docker compose down

# Parar e apagar volumes (reset total)
docker compose down -v

# Ver logs em tempo real
docker compose logs -f
```
Acesse: http://localhost:3000

