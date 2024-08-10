Stack: - **Next.js**
- **React.js**
- **PostgreSQL**
- **Tailwind CSS**
- **Prisma** /nosso ORM 
- **Node.js**
- **ShadCN**
- **TypeScript**
- **JavaScript**

Deploy: Vercel.js

Passo a passo: 

npx create-next-app@latest fsw-barber 

Dar enter no default 

Abrir VS code 

Acessar: https://console.neon.tech/app/projects/twilight-cake-92699722?database=neondb&branchId=br-spring-resonance-a50dus46 (Neon é a database postgresql para Next.js Serveless)

No terminal, comece com:

npm install prisma --save-dev

Depois, no arquivo .env, coloque no databaseurl a url da database no neon

prisma migrate dev --name init_db

npx prisma migrate dev --name init_db

Agora, pra adicionar dados na base de dados: 

npm install -D ts-node

npx prisma db seed

Agora, sobre o Next.js:

npm run dev (abrirmos nossa pagina index e rodarmos a aplicação no localhost)

Instalar prettier 

npm install -D prettier-plugin-tailwindcss

