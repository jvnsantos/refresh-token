<h1 align="center">
  Refresh Token Sample
</h1>

## :memo: Sobre o projeto
Projeto template de criação de API para autenticação de usuário com o tema <bold>Refresh Token</bold>

## :construction: Arquitetura
<p align="center">
  Em elaboração...
</p>

## :hammer_and_wrench: Tecnologias utilizadas
- NodeJs
- TypeScript
- Prisma
- Husky
- PostGres

Está sendo utilizada a lib `git-commit-msg-linter` para a padronização de commits. Por isto, é necessário o Husky.

## :gear: Como executar
Antes de iniciar os scripts é necessário que tenha sido instalado o Postgres e o PgAdmin.

Também será necessário a inserção das variaveis de ambiente
 ```
   DATABASE_URL="postgresql://usuario:senha@localhost:porta/nome_banco?schema=public"
   SECRET_TOKEN="seu_secret"
   ```
1. Instalação das dependências do projeto:
   ```
   yarn i
   ```
2. Instalação do Prisma globalmente:
   ```
   yarn add prisma --global
   ```
3. Gerando as migrates:
     ```
     yarn prisma generate
     yarn prisma migrate dev
     ```
4. Executando o projeto:
     ```
     yarn dev
     ```

#### Contribuidores:
  - [@jvnsantos](https://github.com/jvnsantos)