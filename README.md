### GoBarber

Este é o back-end da aplicação GoBarber que foi desenvolvida durante o bootcamp da RocketSeat

Nesta aplicação são aplicados desde os conceitos de padrão de código como, por exemplo, EsLint e Prettier
até conceitos de ORM, padrões de projeto, metodologia de desenvolvimento e é claro, conceitos e fundamentos de desenvolvimento utilizando Node.JS.

Este projeto utiliza a conceitos de DDD (domain drive design), isto é, a aplicação está estruturada conforme o domínio de cada informação.

Como framework ORM, foi optado pelo uso do TypeORM.

### Executando a aplicação

Versões:
`YARN 1.22.4`
`NODE 12.16.3`
`POSTGRES 12.2`

Execução

`yarn`

`yarn typeorm migration:run`

`yarn test`

`yarn dev:server`


A API da aplicação pode ser encontrada no arquivo go-barber.json exportado pelo aplicativo Insomnia


