## 環境構築
`pip install --upgrade pip`

`pip install -r requirements.txt`

## DB
`python manage.py migrate`

## サーバー起動
`python manage.py runserver`

URL:  `localhost:8000`

## Dir構造
```
djnago_poll_app/
  .gitignore
  db.sqlite3
  manage.py
  READEME.md
  requirements.txt
  polls/
    migrations/
      0001_initial.py
      __init__.py
    templates/
      polls/
        detail.html
        index.html
        results.html
      admin/
        base_site.html
    static/
      polls/
        style.css
        images/
    __init__.py
    admin.py
    apps.py
    models.py
    tests.py
    urls.py
    views.py
  mysite/
    __init__.py
    settings.py
    urls.py
    wsgi.py 
```
