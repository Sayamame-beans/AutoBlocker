# AutoBlocker
A program to auto-block spam and troll on YouTube.  

This program is beta version now!  
本プログラムは試験運用が不足しているためベータ版として公開しています。  
そのため、バグや問題点、改善点等がございましたら是非issueをお願いします。  

## インストール
インストーラはありません。適当なフォルダーにファイルを解凍してください。  

## アンインストール
配置したファイル・フォルダーを削除してください。  

## ファイル構成(無いものは作成されます)
|-AutoBlocker.exe &ensp; 本体  
|-BlackList.dict &emsp; &nbsp; &nbsp; ブロックされたユーザー名とIDの一覧  
|-config.ini &emsp; &emsp; &ensp; &nbsp; クッキーを読み込むブラウザの選択  
|-Log.txt &emsp; &emsp; &emsp; &ensp; &nbsp; ログファイル  
|-Readme.txt &emsp; &emsp; &nbsp; 説明書  
|-URLBlackList.dict &nbsp; ブロックされたスパムから取得したbit.lyリンクの一覧  
|-URLGrayList.dict &ensp; ブロックされたスパムと思われるユーザー名とそのID、及びそこから取得したbit.lyリンクの一覧  
|-WhiteList.dict &emsp; &nbsp; 処理対象としてとして除外するユーザー名とIDの一覧  

.dictファイルは、同じ構成であれば手動で調整することも可能です。  

### WhiteList.dict  
UserName:ChannelID  
### URLBlackList.dict  
bit.lyリンク  

## 使用方法
プログラムを実行し、配信ID(アーカイブの場合は読み込み開始時間も選択可能)を入力。  
読み込み開始ボタンを押すと読み込みを開始します。  
後は自動で荒らし・スパムを判別し、ブロックを行います。  
ただし、荒らしの完璧な判別は不可能なため、誤判定を行う可能性もあります。  
その場合は対象を選択し、⇔ボタンを押すことで移動出来ます。  

## 注意
⇔ボタンを押すたびにブロック・ブロック解除処理が行われるため、  
同一人物を何度も移動させるような事はしない事を強く推奨します。  

## 製作者について
製作者(さやまめ)  
メールアドレス(sayamame.beans0011@gmail.com)  

## その他
本プログラムによって生じた障害・損失等には一切責任を負いません。  
バグ報告等は製作者までお願いします。  
再配布禁止(ただし許可した場合を除く)  
商用利用禁止  
This program uses pytblocklib (copyright 2020 taizan-hokuto URL:  https://github.com/taizan-hokuto/pytblocklib  pytblocklib license is LGPL-3.0)  

## 更新履歴
2020/04/11 Ver.0.1.0 ツール完成(ベータ版)  
