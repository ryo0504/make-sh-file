# make-sh-file

shファイルを作成してくれます。g16用です。改行コードが \r\n となっている場合があるので、\r を取り除くには次のページを参照してください。
http://memobe.blog.fc2.com/blog-entry-120.html

## ファイルの扱いと環境構築について

### env_build
Dockerfileが入ってます。

### src
ソースコードが入っています。


### 環境構築の基本的な手順
- git clone <urlを入力>
- cd env_build
- docker-compose up