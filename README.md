## Content

- [Phoenix](https://phoenixframework.org), the battle-tested production-ready web framework
- Database integration using [Ecto](https://hexdocs.pm/ecto/Ecto.html)
- Translations with [Gettext](https://hexdocs.pm/gettext/Gettext.html)
- [ExUnit](https://hexdocs.pm/ex_unit/ExUnit.html) tests and code coverage using [ExCoveralls](https://hexdocs.pm/excoveralls/api-reference.html)
- CORS management with [Corsica](https://github.com/whatyouhide/corsica)
- Opinionated linting with [Credo](http://credo-ci.org)
- OTP release using [Distillery](https://hexdocs.pm/distillery/home.html) and [Docker](https://www.docker.com)
- Useful utilities for web features: _basic auth_, _canonical host_, etc…
- Error reporting with [Sentry](https://hexdocs.pm/sentry/readme.html)

## Usage

### With GitHub template

1. Click on the [**Use this template**]button to create a new repository
2. Clone your newly created project (`git clone https://github.com/you/repo.git`)
3. Run the boilerplate setup script (`./boilerplate-setup.sh YourProjectName`)
4. Commit the changes (`git commit -a -m "Rename elixir-boilerplate parts"`)

### Without GitHub template

1. Clone this project
2. Delete the internal Git directory (`rm -rf .git`)
3. Run the boilerplate setup script (`./boilerplate-setup.sh YourProjectName`)
4. Create a new Git repository (`git init`)
5. Create the initial Git commit (`git commit -a -m "Initial commit"`)