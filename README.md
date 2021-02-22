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

### Atalho para criar o banco e rodar as migrates
```bash
mix ecto.setup
```

### Criando arquivo de lint do projeto
```bash
mix credo gen.config
```
