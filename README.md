ここはなに
===
データサイエンス100本ノック（構造化データ加工編）をpysparkでも行えるようにしました。書いていることは9割100本ノックのパクリです。


Description
====
- Dockerfile(Dockerfile.pyspark)
- docker-compose.yml
- スーパーの架空購買データと架空個人情報(csv)

Requirement
====
- Docker(Windows 10 proffesional Edition, macOS)
- Docker Toolbox(Windows 10 home edition)

Install
====
- $ git clone git@gitlab.datumstudio.jp:y.mukai/practice-pyspark.git
- $ cd practice-pyspark
- $ docker-compose up -d --build

再起動は`docker-compose start`, 撤収は`docker-compose stop`


Usage
====
sparkが複数ポート必要なため100本ノックとはポートが違うので注意
- Docker Desktopの場合
http://localhost:8890

- Docker Toolboxの場合
http://192.168.99.100:8890

Document
====
- work配下に設問notebookを配置
- work/data配下に使用したデータを配置


macで動くかは確認していないです。