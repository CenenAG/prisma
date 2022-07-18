# prisma

--create packaje.json
npm init -y

-- install dependencies
npm i --save-dev prisma typescript ts-node @types/node nodemon

--initialize prisma
npx prisma init --datasource-provider mysql

--migrate / create the tables
npx prisma migrate dev --name init

--client for prisma
npm i @prisma/client
