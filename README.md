### この課題はマイナビにアクセスしてキーワード検索を行い結果を取得するものです。
当方のサンプルを用意していますので、追記する形で始めていただければと思います。

説明動画：https://youtu.be/vNJ5DcrdvhM<br>
Seleniumの基本：https://techacademy.jp/magazine/28392<br>
Seleniumの応用：https://tanuhack.com/selenium/#URL<br>
Pandasの基本：https://note.nkmk.me/pandas/<br>
ログ出力(テキストファイル出力)：https://note.nkmk.me/python-file-io-open-with/<br>

サンプルコードは、検索結果の１番上の会社名を取得するようになっています。
下記の課題に従って、レベルアップさせてみましょう。

Seleniumは副業案件においては、非常に重要な技術です。これを習得すれば月５万円程度の収入を得ることが可能です。
頑張って学習してみましょう！

## ０  難易度★☆☆☆☆
Chromeのバージョンを、URLにchrome:://version と入力して確認し  
これとメジャーバージョン（先頭の91等の数字）が一致するdriverを以下よりダウンロードしてください。  
https://chromedriver.chromium.org/downloads

## １　難易度★★☆☆☆
会社名を取得して画面にprint文で表示してみましょう。

## ２　難易度★★★☆☆
for文を使って、１ページ内の３つ程度の項目（会社名、年収など）を取得できるように改造してみましょう

## ３　難易度★★★☆☆
２ページ目以降の情報も含めて取得できるようにしてみましょう

## ４　難易度★★☆☆☆
任意のキーワードをコンソール（黒い画面）から指定して検索できるようにしてみましょう

## ５　難易度★★★★☆
取得した結果をpandasモジュールを使ってCSVファイルに出力してみましょう

## ６　難易度★★☆☆☆
エラーが発生した場合に、処理を停止させるのではなく、スキップして処理を継続できるようにしてみましょう<br>
(try文)

## ７　難易度★★☆☆☆
処理の経過が分かりやすいようにログファイルを出力してみましょう<br>
ログファイルとは：ツールがいつどのように動作したかを後から確認するために重要なテキストファイルです。
ライブラリを用いることもできますが、テキストファイルを出力する処理で簡単に実現できるので、試してみましょう。
(今何件目、エラー内容、等を表示)

## ８　難易度★☆☆☆☆
Chromeドライバーがバージョンアップの際に自動で更新されるようにしてみましょう。  
参考：https://qiita.com/YoshikiIto/items/000f241f6d917178981c

### ９ 難易度★★☆☆☆
検索時等にWeb画面を更新する処理はurlにより制御されます。
そのため、検索窓を使用せずにURLを直接変更することでも検索結果を取得することが可能です。
URLのうち、検索ワードを制御している部分を見つけて、直接プログラムにて修正し
検索結果を表示させてみましょう。
参考：https://webtan.impress.co.jp/e/2012/04/26/12663

