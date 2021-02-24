[![Elixir CI](https://github.com/tiago154/rocketpay/actions/workflows/elixir.yml/badge.svg)](https://github.com/tiago154/rocketpay/actions/workflows/elixir.yml)

# Rocketpay

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix

## Iniciando o projeto

### Criando um novo diretório sem html e css (api)
```bash
mix phx.new rocketpay --no-webpack --no-html
```

## Credo
### Criando arquivo de lint do projeto
```bash
mix credo gen.config
```

## Ecto

#### Atalho para criar o banco e rodar as migrates
```bash
mix ecto.setup
```

#### Cria o banco de dados
```bash
mix ecto.create
```

#### Deleta o banco de dados
```bash
mix ecto.drop
```

#### Cria uma migration
```bash
mix ecto.gen.migration create_blablabla_table
```

#### Executa as migrations
```bash
mix ecto.migrate
```

## PostGres Docker

```bash
docker run --name postgres-dev -e POSTGRES_PASSWORD=postgres -e POSTGRES_USER=postgres -p 5432:5432 -d postgres
```

```bash
docker start postgres-dev
```
