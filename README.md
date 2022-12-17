# postgree_setup

Download Postgree

```
brew update
```

```
brew install postgresql
```

- [Start](https://medium.com/@viviennediegoencarnacion/getting-started-with-postgresql-on-mac-e6a5f48ee399)

```
brew services start postgresql
```

```
brew services stop postgresql
```

```
psql postgres
```

```
CREATE ROLE zein WITH LOGIN PASSWORD 'zein';
```

```
ALTER ROLE zein CREATEDB;
```

```
psql postgres -U zein
```

- [download](https://www.pgadmin.org/download/)

- [Laravel](https://tonyfrenzy.medium.com/using-postgresql-with-laravel-c4c320ca7f34)

```
DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=test-zein
DB_USERNAME=zein
DB_PASSWORD=
```
