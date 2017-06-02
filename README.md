# mac-zip-windows
macで作ったZIPファイルを送ったら、お客様からこんな問い合わせ受けたことありませんか？
* ZIPファイルが文字化けしていて読めない
* __MACOSXフォルダは何の意味があるの？
* もらったZIPファイルをすべて展開すると予期しないエラーになって解凍できない
* テキストファイルが詰まっていて読みにくい。

mac-zip-windowsのwindowszipで解決できます。

# windowszipって何？
macで圧縮ファイル(zip形式)を作るPHPプログラムです。
* windowsで文字化けしません
* __MACOSXフォルダを作りません、.DS_storeファイルを除外します
* windowsの禁止文字が含まれたファイルを自動で検出します。
* ShiftJISにない文字を自動で検出します。
* .txtファイルを自動でwindowsの改行に変換します。

# どうやって使うの？
windowszipをダウンロードまたはコピペしてください。

パスの通った場所にファイルをコピーしてください。

以下コマンドで実行許可を与えます。

<code>$ chmod +x windowszip </code>

ターミナルから以下のように圧縮ファイル(zip形式)を作ることができます。

<code>$ windowszip 圧縮したいフォルダ または　圧縮ファイル</code>

圧縮対象のフォルダ、またはファイルが存在するパスに、同じファイル名に拡張子.zipを付与したファイルを作成します。

# macOSのサービスに追加することでさらに便利になります。

こちらのサイトで詳しいやり方をご紹介しています。

<a href="http://fanblogs.jp/macyarounanoka/archive/274/0">fanblogs.jp/macyarounanoka</a>
