# Retravel サーバー

# 動かし方
## サーバー
```
python manage.py
```
## テストコード
```
python -m unittest discover tests -v
```

## セットアップ
```
heroku plugins:install git://github.com/ddollar/heroku-config.git
```

## Herokuの更新
```
pip freeze > ../requirements.txt
heroku config:push
# 変更のコミット
git push heroku master
```

# 大事なこと
緯度  いど    latitude   ←短い
経度  けいど  longitude  ←長い