# Orkest

Sistema para gestao e organizacao de freelancers.

## Estrutura do projeto

- `apps/web` -> frontend Angular
- `apps/api` -> backend Spring Boot

## Como rodar o backend

Entre em `apps/api` e execute a aplicacao com Maven:

```bash
cd apps/api
./mvnw spring-boot:run
```

Se o projeto nao incluir o Maven Wrapper, use a instalacao local do Maven:

```bash
cd apps/api
mvn spring-boot:run
```

## Como rodar o frontend

Entre em `apps/web`, instale as dependencias e inicie o servidor de desenvolvimento do Angular:

```bash
cd apps/web
npm install
npm start
```

Se o projeto estiver configurado para usar o Angular CLI diretamente, o comando alternativo comum e:

```bash
cd apps/web
npm install
npx ng serve
```
