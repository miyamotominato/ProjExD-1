# 第6回
## あぶない！こうかとん（ex06/dagerous_kokaton.py）
### ゲーム概要
- ex06/dangerous_kokaton.pyを実行すると，600x900のスクリーンに溶岩と地面が描画され，こうかとんを地面から落ちないように移動させ、飛んでくる爆弾を避けるゲーム
- こうかとんが爆弾と接触するとゲームオーバーで終了する
### 操作方法
- 矢印キーでこうかとんを上下左右に移動する
- マウスカーソルによる移動
### 追加機能
- C0A21049担当
- マップの外に出るとゲームオーバー
- 着弾時、爆弾もこうかとんもすべて停止する
- ゲームオーバー時にPress the 'r' key and try again!と表示されリセットを促す

- C0A21035担当
- 爆弾：爆弾が四方向から飛んでくる
- 新しい爆弾：画面端に行った爆弾は消え、新しく爆弾が飛んでくる
- 爆弾がぶつかった際に、こうかとんの画像を切り替える
- バリアの生成：ゲーム開始と同時に操作キャラの周りにバリアが展開。爆弾がバリアにぶつかった時、爆弾を消す。また、3回ぶつかった際にバリアがはがれる
- ゲーム終了：ゲームオーバーになった際、Press the 'r' key and try again!と表示し、"e"ボタンが押された時ゲームを終了する

- C0A21089
- マウスカーソルの位置に合わせて移動する

- C0A21099
- タイトル画面を追加した(global関数でTITLE, STAGEの判断をさせる)
- タイトル画面で、スペースキーを押すとゲームを開始するようにした

- C0A21121
- 画面上部に経過時間を表示させる
- ゲームオーバー時に、経過時間とゲームのスコア(経過時間×100)を表示させる
### ToDo（実装しようと思ったけど時間がなかった）
- [ ] アイテム：シールドを回復するアイテムの追加
- [ ] 爆弾の速度変化
- [ ] 爆弾の飛翔方向の変化
- [ ] BGMの追加
- [ ] マウスカーソルでのスムーズな移動
- [ ] 画面上方に敵の追加
### メモ