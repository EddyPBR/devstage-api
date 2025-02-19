# 🚀 devstage-api

## 📌 Sobre o Projeto

O **DevStage API** é a API responsável por gerenciar:

- Inscrições de usuários no evento;
- Controle de links de convite e contagem de acessos e inscrições;
- Ranking dos TOP 3 usuários com mais inscritos.

Essa API serve ao frontend do projeto, disponível em [(devstage-web)](https://github.com/EddyPBR/devstage-web).

---

## 🛠️ Como Rodar o Projeto

### 🔽 1. Clone o Repositório

```bash
git clone https://github.com/EddyPBR/devstage-api.git
cd devstage-api
```

### 📦 2. Instale as Dependências

```bash
npm install
```

### ⚙️ 3. Configure as Variáveis de Ambiente

O projeto utiliza o arquivo `.env.development` na raiz do projeto por padrão:
> Ajuste as credenciais caso necessário.

### 🐳 4. Suba os Containers Docker

Certifique-se de ter o **Docker** instalado e execute:

```bash
docker compose up -d
```

### 🚀 5. Rode as Migrações do Banco

```bash
npm run db:migrate
```

### ▶️ 6. Inicie o Servidor

```bash
npm run dev
```

A API estará disponível em: [http://localhost:3333](http://localhost:3333)

---

## 🎨 Tecnologias Utilizadas

- **Node.js**
- **Fastify**
- **Drizzle ORM**
- **PostgreSQL**
- **Redis**
- **Docker**

---

💙 **Gostou do projeto? Deixe uma ⭐ para apoiar!**
