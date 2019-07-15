# MyFinance

## GraphQL API using Prisma

### Documentation
https://www.prisma.io/docs/1.34/get-started/01-setting-up-prisma-new-database-TYPESCRIPT-t002/

### Setup
  - Start Docker containers
    - docker-compose up -d
  - Start Prisma
    - prisma init --endpoint http://localhost:4466
  - Deploy Prisma
    - prisma deploy

### Updates API
  - Edit file `datamodel.prisma`
  - Deploy Prisma
    - prisma deploy
  
### Generate Client
  - Run the command
    - prisma generate

### Look and edit data
  - Run GraphQL Playground
    - http://localhost:4466
  - Run Prisma Admin
    - http://localhost:4466/_admin