# Create-Secret-Key
32byte Hex Strings

ベースとなる文字列をSHA256によるハッシュを指定回数繰り返すことで32byte HEX文字列を作成。

ローカルにhtmlファイルとして保存し、以下の2か所を各自変更してください。


let word = "password";

let loopcount = 10000;


ローカルファイルとしてブラウザで開くことで秘密鍵を作成します。


