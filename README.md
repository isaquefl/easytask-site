<div align="center">

# 💰 EasyTask

### Controle financeiro pessoal com inteligência artificial

Organize gastos, acompanhe dívidas e converse com um assistente de IA que entende as suas finanças — tudo em um só lugar, em PT/EN.

[![version](https://img.shields.io/badge/version-1.0.0-6C5CE7.svg)](https://easytaskbetter.vercel.app)
[![license](https://img.shields.io/badge/license-MIT-green.svg)](#-licença)
[![Next.js](https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white)](https://www.prisma.io/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Groq AI](https://img.shields.io/badge/AI-Groq%20%2F%20LLaMA%203.1-F55036.svg)](https://groq.com/)
[![Live](https://img.shields.io/badge/Live-easytaskbetter.vercel.app-2ECC71.svg)](https://easytaskbetter.vercel.app)

[**🌐 Acessar o app**](https://easytaskbetter.vercel.app)

</div>

---

> 💬 Saber para onde vai cada centavo não precisa ser uma planilha chata. O EasyTask transforma seu controle financeiro em uma conversa.

> 💬 Pergunte "quanto gastei esse mês?" ou "quanto falta pra quitar minha dívida?" e deixe a IA responder com base nos seus próprios dados.

> 💬 Dívidas com juros calculados automaticamente, dashboard visual e um assistente sempre à mão — em português ou inglês.

---

## ✨ Funcionalidades

- 📊 **Dashboard financeiro** — gráficos e métricas da sua vida financeira em tempo real
- 💳 **Controle de dívidas** — acompanhamento de dívidas com cálculo automático de juros
- ✅ **Gestão de tarefas** — organize pendências e compromissos
- 🤖 **Assistente de IA** — tire dúvidas sobre suas finanças com IA (Groq / LLaMA 3.1)
- 🔐 **Autenticação segura** — login protegido com Better Auth
- 💸 **Pagamentos via PIX** — integração com Mercado Pago
- 🌎 **Bilíngue** — interface em Português e Inglês (PT/EN)

## 🚀 Como rodar

> Projeto Next.js + TypeScript. Requer Node.js 18+ e um banco PostgreSQL.

```bash
# 1. Clone o repositório do app
git clone https://github.com/isaquefl/easytask-site.git
cd easytask-site

# 2. Instale as dependências
npm install

# 3. Configure as variáveis de ambiente
cp .env.example .env.local
# preencha: DATABASE_URL, GROQ_API_KEY, credenciais do Mercado Pago,
# segredos do Better Auth, etc.

# 4. Aplique o schema do banco com o Prisma
npx prisma migrate dev

# 5. Rode em modo de desenvolvimento
npm run dev
```

A aplicação ficará disponível em `http://localhost:3000`.

> ⚠️ Nunca versione o arquivo `.env` — mantenha chaves de API e segredos fora do controle de versão.

## 🛠️ Stack

| Camada | Tecnologia |
|--------|-----------|
| Framework | **Next.js** |
| Linguagem | **TypeScript** |
| ORM | **Prisma** |
| Banco de dados | **PostgreSQL** |
| Estilização | **Emotion** |
| IA | **Groq / LLaMA 3.1** |
| Autenticação | **Better Auth** |
| Pagamentos | **Mercado Pago (PIX)** |
| Deploy | **Vercel** |

## 🔗 Links

- 🌐 **App ao vivo:** https://easytaskbetter.vercel.app
- 👤 **Portfólio do autor:** https://isaquefl.vercel.app

## 📄 Licença

Distribuído sob a licença **MIT**. Sinta-se livre para usar, estudar e adaptar.

---

## 🇬🇧 English (short)

**EasyTask** is an AI-powered personal finance platform (PT/EN). Track your spending on a visual dashboard, manage debts with automatic interest calculation, organize tasks, and chat with an AI assistant (Groq / LLaMA 3.1) that answers questions about your own finances. Secure auth via Better Auth and PIX payments through Mercado Pago. Built with **Next.js**, **TypeScript**, **Prisma** and **PostgreSQL**, deployed on **Vercel**.

👉 Live: **https://easytaskbetter.vercel.app**

---

<div align="center">

**v1.0.0** · feito por **Isaque Félix**

[isaquefl.vercel.app](https://isaquefl.vercel.app)

</div>
