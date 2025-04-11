# app-template

.gitを除く、コピーコマンド
```
rsync -av --progress app-template/ chatEnglish2/ --exclude='.git' --exclude='README.md'
```
Dockerコマンド

```
docker-compose up --build
```

Laravelインストール
```
docker-compose exec api bash
```
```
composer create-project laravel/laravel:^11.0 .
```

next.jsインストール
```
npx create-next-app@14.2.0 . \
  --ts \
  --tailwind \
  --eslint \
  --app \
  --import-alias "@/*"
```
