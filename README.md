Overview

BarberShop Scheduler é um sistema de agendamento online para barbearias, desenvolvido com TypeScript e Next.js. Este projeto tem como objetivo facilitar a marcação de horários para clientes e a gestão de agendamentos para os barbeiros. O sistema inclui autenticação via Google, permitindo que os usuários façam login rapidamente e com segurança.

Features

	•	Autenticação com Google: Os usuários podem se autenticar usando suas contas do Google, garantindo um processo de login simples e seguro.
	•	Agendamento de Horários: Os clientes podem visualizar a disponibilidade dos barbeiros e agendar horários de acordo com suas preferências.
	•	Gerenciamento de Barbeiros: Permite que barbeiros configurem suas disponibilidades e gerenciem seus agendamentos diretamente na plataforma.
	•	Responsividade: Interface otimizada para dispositivos móveis e desktops, proporcionando uma experiência de usuário consistente em qualquer tela.
	•	Painel Administrativo: Um painel para os administradores da barbearia gerenciarem todos os agendamentos, barbeiros e horários disponíveis.

Tech Stack

	•	Next.js: Framework de React para renderização no lado do servidor e rotas dinâmicas.
	•	TypeScript: Superset de JavaScript que adiciona tipagem estática ao código, melhorando a manutenibilidade e reduzindo erros.
	•	Google Auth: Integração com Google OAuth 2.0 para autenticação segura dos usuários.
	•	Tailwind CSS: Framework de CSS utilitário para estilização rápida e eficiente.
	•	Prisma: ORM para interagir com o banco de dados de forma segura e tipada.
	•	ostgreSQL: Banco de dados leve e embutido para desenvolvimento local, via Neon.tech, banco de dados serverless.

Installation

npm install - instale as dependencias

Configure as variáveis de ambiente:

Crie um arquivo .env.local na raiz do projeto e adicione as seguintes variáveis:
DATABASE_URL=postgresql://user:password@localhost:5432/mydb
NEXTAUTH_URL=http://localhost:3000
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret

Execute as migrações do banco de dados:

npx prisma migrate dev

Inicie o servidor de desenvolvimento:

npm run dev

Next.js para a estrutura incrível que facilita a criação de aplicativos web modernos.
Google OAuth por fornecer uma solução de autenticação simples e segura.
Tailwind CSS por permitir o desenvolvimento de interfaces de usuário elegantes e responsivas com facilidade.
