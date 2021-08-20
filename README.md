

<div align="center">
    <img src="https://user-images.githubusercontent.com/65665108/130161952-4d51b054-9995-4353-b72f-9935c3e690ff.png" width="150"/> 
        <img src="https://user-images.githubusercontent.com/65665108/130164664-0e252330-a5a2-4c5c-84ff-76d656617a99.png" width="170"/>

</div>

<h3 align="center">
  CNI API  - Strapi
</h3>

## :bulb: Sobre o projeto
O CNI Website API é um projeto desenvolvido utilizando o Strapi, um CMS de código aberto feito 100% em JavaScript que possibilita a criação de uma API em minutos, entregando no final uma estrutura REST ou GraphQl.
<div align="center">
    <img src="https://user-images.githubusercontent.com/65665108/130167106-91226569-dd3f-47bc-b1c4-de8d18538108.png" width="600"/> 
</div>

## 🚀 Tecnologias

Tecnologias que foram utilizadas no projeto:

- [Strapi](https://strapi.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [GraphQl](https://graphql.org/)

<div align="center">
    <img src="https://user-images.githubusercontent.com/65665108/130167220-1c388733-123c-4507-bfda-00a67e9ca45a.png" width="600"/> 
</div>

## 👀 Observação

O projeto foi desenvolvido para gerenciar o conteúdo do CNI Website, para testar 100% o projeto será necessário clonar o repositório do website.  [Repositório CNI Website](https://github.com/Ueslen-dev/cni-website-api)


## 💻 Começando
Para começar precisamos instalar algumas coisas

### Requerimentos

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/)
- [PostgreSQL](https://www.postgresql.org/)


```bash
$ git https://github.com/Ueslen-dev/cni-website-api.git && cd cni-website-api
```

**Siga esses passos**
1. Dentro da pasta do projeto navegue até `config/database.js`;
2. Insira as as informações da sua base de dados PostgreSQL;
```bash
settings: {
client: 'postgres',
host: env('DATABASE_HOST', '127.0.0.1'),
port: env.int('DATABASE_PORT', 5432),
database: env('DATABASE_NAME', 'nome_do_db'),
username: env('DATABASE_USERNAME', 'usuario_do_db'),
password: env('DATABASE_PASSWORD', 'senha_do_db'),
ssl: env.bool('DATABASE_SSL', false),
}
```
3. Dentro da pasta do projeto rode `yarn`;
4. Execute o projeto com `yarn develop`;
## 📝 Licença

Esse projeto é licenciado pelo MIT License

---

Feito com amor 💙&nbsp; por Ueslen Santana 👋 &nbsp;[Veja meu linkedin](https://www.linkedin.com/in/ueslen-santos)
