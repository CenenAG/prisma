# prisma

--create packaje.json
npm init -y

-- install dependencies
npm i --save-dev prisma typescript ts-node @types/node nodemon

--initialize prisma
npx prisma init --datasource-provider mysql

--migrate / create/modify schema to DB
npx prisma migrate dev --name init

--client for prisma
npm i @prisma/client


-- regenera el cliente para manejo en desarrollo de los objetos del orm
npx prisma generate

--arranca por lote el ambiente de desarrollo al grabar lo ejecuta
npm run devStart
