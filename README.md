# Docker + Laravel + Apache のサンプルアプリケーション

## 初期構築

以下コマンドを実行すると、`app/`ディレクトリが作成され、Laravel アプリケーションが構築されます。

```sh
docker run -w /app -v .:/app --rm composer composer create-project laravel/laravel app
```

## ローカル起動

```sh
docker compose up
```

http://localhost:8000/ で Laravel が起動します。
