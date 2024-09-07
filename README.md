# kyopro-container

## 理想

環境構築を楽ちんした〜い

主にAtCoderに参加するための環境をDevContainerにぶち込んで、オンサイトコンテストのときにGitHub Codespaces等で使えたらうれしい。

## 構成

基本的にVSCode想定

### C++

- debianについてくるg++を（とりあえず）使う
- gdbは自分で入れる
- VSCodeの拡張機能としてC/C++（ms-vscode.cpptools）が入っている

### Python

- システムのPythonは使わず、uvに面倒を見てもらう
- uvはDevContainerのfeatureとして入れる
- VSCodeの拡張機能もぼちぼち入ってる。
- Numpyとか、使いそうなライブラリが入っている
- Ruffにフォーマットしてもらう

状況に応じてPyPyも使えるようにしたいが、どうもうまいことできず。

## やりたい

- デバッグをちゃんとしたい。今はふわっとしてる
- スニペットや自作のライブラリを使いたい
