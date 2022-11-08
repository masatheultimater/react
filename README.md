# 作成
コンテナイメージ作成
```
$ docker-compose build
```
コンテナ上でReactアプリ作成
```
$ docker exec -it react sh

# yarn create react-app <プロジェクト名> --template typescript
or
# npx create-react-app . --template typescript
```




以下はパッケージ依存解決のための予約語のためプロジェクトの名前に使用できない
- react
- react-dom
- react-scripts

ES lintの設定
```
```