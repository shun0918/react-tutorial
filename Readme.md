# ビルドする

```
docker-compose build
```

# create-react-appをインストールし、reactのプロジェクトを作成する。

```
docker-compose run --rm node sh -c "npm install -g create-react-app && create-react-app [アプリ名]"
```

アプリ名はご自由に
こちらはDockerfileのRUNに書こうとしたが、プロジェクト作成後、volumesでマウントしようとするとせっかく作ったアプリが消えてしまうため断念。
大人しくコマンドを実行する。

# アプリを立ち上げる

```
yarn start [アプリ名]
```