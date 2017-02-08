# ros　パブリッシャとサブスクライバの確認
count.py:ノードからトピックにパブリッシャするスクリプト
twice.py:トピックからノードにサブスクライブするスクリプト

# コマンド
```
$ roscore
$ rosrun ros_start count.py
$ rostopic echo /count_up
$ rosrun ros_start twice.py
$ rqt_graph #トピックの通信を可視化
```

# 動画URL
https://youtu.be/4ovSnRZhlLE
