# Requirements


## Command line tools needed:
- ghost
- gh
- psql
- wb (optional)


## Install Ghost CLI
From [ghost.build](https://ghost.build/)

```bash
curl -fsSL https://install.ghost.build | sh
```

## Install GitHub CLI
```bash
brew install gh
```

## Install Postgres `psql`
```bash
brew install libpq
```

```bash
which psql
```

## Install Worbooks cli:

From [workbooks.dev](https://workbooks.dev/)

```bash
curl -fsSL https://get.workbooks.dev | sh
```
Run markdown as code with workbooks and:
```bash
wb run runbooks/1-google-bookmarks.md
wb run runbooks/2-github.md
```
