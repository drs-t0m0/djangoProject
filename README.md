# Django

## Ref

- https://docs.djangoproject.com/ja/4.1/contents/

## プロジェクト作成

```sh
$ django-admin startproject mysite
```

## 開発用サーバー

```sh
$ python manage.py runserver
```

```sh
$ python manage.py runserver 0.0.0.0:8000
```

## アプリケーションをつくる

```sh
$ python manage.py startapp polls
```

## マイグレーション

```sh
$ python manage.py migrate
```

## マイグレーションファイル作成

```sh
$ python manage.py makemigrations polls
```

## マイグレーションのSQLを確認(実行しない)

```sh
$ python manage.py sqlmigrate polls 0001
```

## 管理ユーザーを作成

```sh
$ python manage.py createsuperuser
```