# Full backend setup (prisma & node)

- **npm init -y**
- **npm install --save-dev nodemon**
- **npm install prisma --save-dev**
- **npm install express @prisma/client body-parser dotenv**
- **npx prisma init**
- **npx prisma migrate dev --name initial_migration**
- **npx prisma generate**
- **npx nodemon index.js**
