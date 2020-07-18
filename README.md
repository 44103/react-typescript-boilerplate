# React環境構築

## 使い方
1. アプリ名変更  
アプリ名を決め、docker-compose.ymlのアプリ名を変更する  
1. Reactアプリ生成  
以下のコマンドでアプリの生成を行う。ただし、アプリ名は先程決めたものに変更するのを忘れないこと。  
`docker-compose run --rm app npx create-react-app react-sample --template typescript`

1. コンテナ起動  
`docker-compose up -d`

1. アタッチ
