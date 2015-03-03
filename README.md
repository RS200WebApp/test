# ORMapperの実行結果
（10章に対応）
http://nbviewer.ipython.org/github/RS200WebApp/test/blob/master/ORMapper_trial.ipynb

# 簡単なWebアプリを作ってみた  
（３章と４章に対応）  
今回はポケモンの名前を入力窓に入力して送信すると、そのポケモンの図鑑番号を返すようなWebアプリを作りました.動かし方は以下.  
1. testごと、どっかのローカルにプル（ダウンロード）する.  
2. Macの場合はターミナルなどで「pokemon_number.py」の実行権限を与えておく（<http://coreblog.org/ats/stuff/minpy_web/03/02.html>参照、コマンドは`chmod 755`）. Windowsの場合は無視してよいらしい.  
3. ローカルの中の「cgiserver.py」を実行する（Macの場合はターミナルなどで`cd`でローカルまで移動して`python cgiserver.py`で動くはず）.  
4. 適当なブラウザで<http://127.0.0.1:8000>を開く.  
5. 適当なポケモンを入力して、遊ぶ.