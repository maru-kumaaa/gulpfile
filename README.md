# gulpfile
使い方<br>
・Vscode（https://azure.microsoft.com/ja-jp/products/visual-studio-code/）をインストール<br>
・node.js(https://nodejs.org/ja/)をインストール<br>
・ファイルをダウンロードし、適当にフォルダを作りその中にファイルを入れる<br>
・作ったフォルダを右クリックし、vscodeで開くをクリック<br>
・Vscodeが開くので、ターミナル→新しいターミナルを起動<br>
・ターミナル画面でnpm installと入力し、エンターを押して必要ファイルのインストール<br>
・インストールが終わったらnpx gulpと入力し、ブラウザにテストサイトが表示されたら成功<br>
<br>
例として、gulpというフォルダを作ったときの流れです
https://gyazo.com/d7c5d798aaf1b608edee5e6e7b4c3336
External: http://192alhost.168.1.143:3000となっているURLはwifiを接続していればスマホでも表示できます。
<br><br>

このgulpでできること<br>
・ローカルサーバー構築(SSIインクルードも表示可能)<br>
・SCSSコンパイル（Dartsass）<br>
・画像の自動圧縮、webp化<br>
・ファイルが変更（修正）されたときにテストサイトの自動リロード