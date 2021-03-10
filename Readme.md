# docker-compose build

# docker-compose run --rm node sh -c "npm install -g create-react-app && create-react-app [好きなアプリ名]"
こちらはDockerfileのRUNに書こうとしたが、プロジェクト作成後、volumesでマウントしようとするとせっかく作ったアプリが消えてしまうため断念
大人しくコマンドを実行する。