# Docker + Laravel + Apache のサンプルアプリケーション

## 初期構築

以下コマンドを実行すると、`laravel`ディレクトリが作成され、Laravel アプリケーションが構築されます。

```sh
docker run -w /laravel -v .:/laravel --rm composer composer create-project laravel/laravel laravel
```

## ローカル起動

```sh
docker compose up
```

http://localhost:8000/ で Laravel が起動します。
