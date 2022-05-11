# -Node-RED-ngrok-LINE-Bot-

ローカル環境でNode-REDとngrokを立ち上げてLINE Botのやり取りをするの記事の中で使用するNode-REDのフローです。<br>

parroting AnotherWords.jsonはオウム返しボットのフローになっています。<br>
Node-REDに取り込んでいただいて、オウム返しという名前のfunctionノードの中を書き換えます。<br>
チャンネルアクセストークンとユーザーIDを変更してデプロイすることで、オウム返しボットが使用できるようになります。<br>
<br>
<br>
![image](https://user-images.githubusercontent.com/33050174/167836799-8b5d9606-6939-4d18-9fea-bc6c74cffa2c.png)

<br>
<br>
<br>

quickreplyBot.jsonはLINEのクイックリプライ機能を利用したボットを使用するフローになっています。
クイックリプライノード、日付ノード、時間ノードの中の、チャンネルアクセストークンとユーザーIDを変更してデプロイすることで、クイックリプライボットが使用できるようになります。<br>
<br>
<br>
![image](https://user-images.githubusercontent.com/33050174/167836864-48e7698f-722f-4759-8eb8-deb7dd28054e.png)

<br>

## Node-REDにデフォルトで入っているノードのみを使用していますので、新にノードを追加する必要はありません。




