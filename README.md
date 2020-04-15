# AutoBlocker
A program to auto-block spam and troll on YouTube.<br>

This program is beta version now!<br>
本プログラムは試験運用が不足しているためベータ版として公開しています。<br>
そのため、バグや問題点、改善点等がございましたら是非issueをお願いします。<br>

## インストール
インストーラはありません。適当なフォルダーにファイルを解凍してください。<br>

## アンインストール
配置したファイル・フォルダーを削除してください。<br>

## ファイル構成(無いものは作成されます)
|-AutoBlocker.exe &ensp; 本体<br>
|-BlackList.dict &emsp; &nbsp; &nbsp; ブロックされたユーザー名とIDの一覧<br>
|-config.ini &emsp; &emsp; &ensp; &nbsp; クッキーを読み込むブラウザの選択<br>
|-Log.txt &emsp; &emsp; &emsp; &ensp; &nbsp; ログファイル<br>
|-Readme.txt &emsp; &emsp; &nbsp; 説明書<br>
|-URLBlackList.dict &nbsp; ブロックされたスパムから取得したbit.lyリンクの一覧<br>
|-URLGrayList.dict &ensp; ブロックされたスパムと思われるユーザー名とそのID、及びそこから取得したbit.lyリンクの一覧<br>
|-WhiteList.dict &emsp; &nbsp; 処理対象としてとして除外するユーザー名とIDの一覧<br>

.dictファイルは、同じ構成であれば手動で調整することも可能です。<br>

### WhiteList.dict
UserName:ChannelID<br>
### URLBlackList.dict
bit.lyリンク<br>

## 使用方法
プログラムを開き、配信URL(アーカイブの場合は読み込み開始時間も選択可能)を入力して下さい。<br>
URLはクリップボードからの貼り付けにも対応。(ボタンを押すと入力をクリップボードで上書きします)<br>
読み込み開始ボタンを押すと読み込みを開始します。<br>
後は自動で荒らし・スパムを判別し、ブロックを行います。<br>
ただし、荒らしの完璧な判別は不可能なため、誤判定を行う可能性もあります。<br>
その場合は対象を選択し、⇔ボタンを押すことで移動出来ます。<br>
読み込みを停止したい場合は読み込み停止ボタンを押して下さい。<br>

## 注意
⇔ボタンを押すたびにブロック・ブロック解除処理が行われるため、<br>
同一人物を何度も移動させるような事はしない事を強く推奨します。<br>

## 製作者について
製作者(さやまめ)<br>
メールアドレス(sayamame.beans0011@gmail.com)<br>

## その他
本プログラムによって生じた障害・損失等には一切責任を負いません。<br>
バグ報告等は製作者までお願いします。<br>
再配布禁止(ただし許可した場合を除く)<br>
商用利用禁止<br>
This program uses pytblocklib (copyright 2020 taizan-hokuto URL: https://github.com/taizan-hokuto/pytblocklib  pytblocklib license is LGPL-3.0)<br>

## 更新履歴
2020/04/11 Ver.0.1.0 ツール完成(ベータ版)<br>
2020/04/14 Ver.0.2.0 入力を配信IDから配信URLに変更。内部処理を一部変更。<br>
2020/04/15 Ver.0.2.1 位置ずれ問題に対応するため、GUIを調整しました。
