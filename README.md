# ゲーム のタイトル
避けろ！こうかとん

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公キャラクターこうかとんが敵機の避けながらコインを集めるゲームである
操作方法は上下キーでこうかとんが縦方向に移動する。画面右側から敵機とコインが出現し、敵機をうまくかわしながらコインを集めるゲームである。

## ゲームの実装
###共通基本機能
* 画面内か画面外かを判定する関数
* 主人公キャラクターに関するクラス
* 敵機に関するクラス
* コインに関する関数
### 担当追加機能
* 難易度表示、難易度変更（初めはnormlモード、キーボードの1を押すことでHardモード、キーボードの2を押すことでLunaticモードに変更する）
* 難易度に応じて敵敵機の出現速度の変更
### ToDo
- [ ] 敵機が重なって出現しないようにしたい
### メモ
* 難易度変更にはflagを用いて処理を変更している
* 敵機の出現間隔は難易度によって変更している
