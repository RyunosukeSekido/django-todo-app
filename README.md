# django-todo-app

## 概要

簡単なCRUD操作を行うDjangoのアプリケーションです。
ユーザーがTODOのタスクを作成、編集、削除できるシンプルなDjangoのタスク管理アプリです。
ユーザーはアカウントを作成し、個別のTODOリストを管理できます。

## システム要件

- Python バージョン: 3.11.3
- Django バージョン: 4.2.6

## ファイルの配置

- モデル: `todo_app/models.py`
- ビュー: `todo_app/views.py`
- テンプレート: `todo_app/templates/todo_app`


## データベースの確認

このアプリのデータベースを確認するには、Django管理サイトを使用します。以下の手順に従ってアクセスしてください：

1. ターミナルでプロジェクトのルートディレクトリに移動します。

2. ローカル開発サーバーを起動します（もし起動していない場合）：
```
python manage.py runserver
```

3. ウェブブラウザを開き、次のURLにアクセスします：[http://localhost:8000/admin/](http://localhost:8000/admin/)

4. ユーザー名とパスワードを使用してDjango管理サイトにログインします。
