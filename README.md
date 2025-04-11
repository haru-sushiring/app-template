# app-template

## .gitを除く、コピーコマンド
```
rsync -av --progress app-template/ コピー先ディレクトリ/ --exclude='.git' --exclude='README.md'
```
## Dockerコマンド

```
docker-compose up --build
```

## Laravelインストール
```
composer create-project laravel/laravel:^11.0 app
```

## next.jsインストール
```
npx create-next-app@14.2.0 src \
  --ts \
  --tailwind \
  --eslint \
  --app \
  --import-alias "@/*"
```
