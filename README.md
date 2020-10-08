# Tinnova test

## ⚠ Requisitos projeto
-  Docker
-  Yarn

## 👩🏻‍💻 Como rodar o projeto: backend?

  -  Clone este projeto
  -  Digite `yarn` na raiz do projeto para instalar as dependências.
  -  Execute `docker-compose -f docker-compose.yml up --build`
  -  Acesse `http://localhost:16543/` para ter acesso ao banco postgres com o PgAdmin
  -  Para acessar o PgAdmin: 
      - Email: `admin@admin.com`
      - Senha: `docker`
  -  Digite `yarn typeorm migration:run` dentro da pasta `server` para criação das tabelas no banco.
  -  Digite `yarn start` para executar o projeto.

- [Veja as rotas da api aqui](routes.md)

## Autora:

<table>
    <tr>
        <td style="text-align:center">
            <a href="https://github.com/tabaesso" target="blank" rel="noopener"><img src="https://avatars1.githubusercontent.com/u/43206830?s=115&v=4"><br><sub>@tabaesso</sub></a>
        </td>
    </tr>
</table>

