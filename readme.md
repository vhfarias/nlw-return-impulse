<div align="center">
<h1>Feedget</h1>

<h5>Projeto desenvolvido na Next Level Week edição Return, trilha Impulse</h5>
</div>

## Sobre

O nome do projeto vem da junção das palavras _feedback_ e _widget_ e resume muito bem sua ação: receber _feedbacks_ e armazená-los em um banco de dados para que o sistema no qual for inserido possa ser melhorado cada vez mais.

Durante a implementação desse projeto foi possível conhecer em detalhe todas as etapas do desenvolvimento, incluindo a integração entre o front e o back-end e a parte de deploy, conteúdos que geralmente não são abordados em outros cursos e semanas de desenvolvimento.

Você pode conferir a versão web aqui: <a href="https://nlw-return-impulse-gilt.vercel.app/">![Website](https://img.shields.io/website?down_color=c43b3b&down_message=Offline&label=Feedget&logo=vercel&style=flat-square&up_color=5fab38&up_message=Online&url=https%3A%2F%2Fnlw-return-impulse-gilt.vercel.app%2F)</a>

## Estrutura

O projeto é composto de três partes:
- Back-end, desenvolvido com Node.js, express.js, Prisma
- Web, desenvolvido com React e Tailwind CSS
- Mobile, desenvolvido com React Native e Expo

<div align="center">
<img src=".github/tela_web_01.png" alt="tela da versão web" />
<img src=".github/tela_web_02.png" alt="tela da versão web" />
</div>

Através do site ou do app mobile o usuário pode selecionar o tipo de comentário (bug, ideia ou outro), digitar um texto, gerar uma captura de tela com um clique e enviar para o servidor, que recebe as informações, armazena em banco de dados e conta com sistema de envio de e-mail automático para o dono do projeto.

## Tecnologias

- ### Base
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

- ### Web
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)![Vite](https://img.shields.io/badge/Vite-9547bf?style=for-the-badge&logo=vite&logoColor=FFD62E)

- ### Back-end
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)

- ### Mobile
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)![Expo](https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37)

- ### Deployment
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)![Railway](https://img.shields.io/badge/Railway-%23000000?style=for-the-badge&logo=railway)

## Instalação e Utilização
- Clonar este repositório
- Instalar as dependências do projeto usando <code>npm install</code>
- Navegar até a pasta "server" e iniciar o servidor com o comando <code>npm run dev</code>
- Na pasta "web" iniciar o cliente com o comando <code>npm run dev</code>
- Para o app mobile você precisa usar um emulador ou ter o aplicativo Expo Go instalado em seu smartphone. Na pasta "mobile" utilizar o comando <code>expo start</code> e seguir as instruções.

## Próximos passos
- Tema light/dark
- Aprimorar o serviço de envio de email (HTML/CSS e serviço de envio em produção)
- Dashboard para visualização dos feedbacks, com autenticação
