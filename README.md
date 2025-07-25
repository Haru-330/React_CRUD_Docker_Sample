# 概要
ViteとDockerを使用して作成されたフロントエンドです。

# 詳細

以下の記事にて、作り方を解説しているため、詳しくは以下を参考にしてください。

https://zenn.dev/haru330/articles/859d6a7982d06d

`npm run build`を実行してから、`docker-compose up -d`をすると実行できます。
実行後、`http://localhost:5173/`にアクセスすると、以下のようなページにアクセスできます。

<img width="645" height="88" alt="image" src="https://github.com/user-attachments/assets/3d195791-a39c-4f7b-aa62-49a6ea805e0f" />

APIは、https://github.com/Haru-330/.NET_API_Docker_Sample/tree/main のAPI前提のため、適宜適切なAPIに変更してください。
