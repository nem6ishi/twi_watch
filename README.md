# twi_watch
streamを監視して、つい消しを記録します。


###watch.py
streamのうち、
ツイート通知はツイートをsqliteをつかったデータベースに保存し、　　
つい消し通知を受けたら、そのツイートのデータのdeletedの値を0から1に変えます。　　
個人的には最近10件だけを個人HPで見れるようにしています。　　
