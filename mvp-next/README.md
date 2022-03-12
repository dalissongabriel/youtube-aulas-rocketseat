This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## MVP: React + Next + Prisma JS

### Tecnologias:

- TailwindCSS;
- Prisma;
- Next;
- Next Auth;

### Requisitos

- PostgresSQL;
- Conta no github para autenticação;

### Como rodar

- Clone este repositório e instale as dependências;
- Configure a autenticação da aplicação na sua conta do github, pegue secrets e preencha o .env.local;
- Configure no .env o acesso ao seu banco postgres;
- Execute as migrações: npx prisma migrate dev;
- Rode o projeto com: npm run dev;
