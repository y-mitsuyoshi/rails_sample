# rails_sample

```
docker compose run web rails new . --force --no-deps --database=mysql --skip-test --webpacker
docker compose build
```

```
docker compose run web rake db:create
```

```
docker compose up
```

下記で起動確認
http://localhost:3000/
