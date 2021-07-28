venvのインストール
 PS mkdir DjangoTutorial
 PS py -m venv DjangoTutorial
 PS cd DjangoTutorial

venvのアクティベート方法
 PS Set-ExecutionPolicy RemoteSigned -Scope CurrentUser -Force
 PS Scripts\activate.ps1

Djangoのインストール
 PS py m pip install Django

Django開発サーバーの起動
 py mysite/manage.py runserver
 (http://127.0.0.1:8000/)
