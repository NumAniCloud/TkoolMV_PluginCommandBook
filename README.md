# TkoolMV_PluginCommandBook  
RPGツクールMVの有志によるプラグインコマンド集  
  
# コンセプトはこちら  
<http://qiita.com/triacontane/items/7a3e6b169b0f94a7d1a6>  

このリポジトリは、プログラムに詳しくなくできれば触りたくないツクラーさんのために、  
わかりやすく使いやすいプラグインコマンドを作ってみんなで共有しよう、という目的で作りました。  
自分のゲームを作る際に作ったいい感じのプラグインコマンドをぜひ追加していって下さい。  
そしてこのプラグインが使われたゲームがリリースされるたびにみんなで喜びましょう。  
せっかく作るなら使ってもらいたいものね。  

# 暫定ルール  
1.プラグインコマンドの追加、修正はPullRequestにて行う  
2.未完成気味でもPullRequestはOK。みんなでメンテナンスしましょう。  
3.ただし引数だけは使う人のことも考えてできるだけ変えないように。  
4.このルールさえも、みんなで更新していきましょう。

# 現在のプラグインコマンド
「名前の変更」  
 主人公の名前を変更する  
 製作者 Alec  

「呼び出し元アイテム取得」  
 コモンイベントを呼び出したアイテムのIDを変数に入れる  
 製作者 Alec  

「呼び出し元スキル取得」  
 コモンイベントを呼び出したスキルのIDを変数に入れる  
 製作者 Alec  

「レベルの変更」  
 アクターのレベルを変更します。増減ではなく変更後のレベルを指定できます。  
 製作者 Alec  

「バイブレーション(English:Vibration)」  
 実行中のAndroid端末を振動させます。  
 製作者 トリアコンタン  

「指定位置の通行情報取得(English:Get_Location_Pass)」  
 指定した座標のマップ通行情報を取得して、変数に格納します。  
 製作者 トリアコンタン  

「変数の初期化(English:Init_Variables)」  
 全ての変数を初期化します。（例外指定可能）  
 製作者 トリアコンタン  

「スイッチの初期化(English:Init_Switches)」  
 全てのスイッチを初期化します。（例外指定可能）  
 製作者 トリアコンタン  

「セルフスイッチの初期化(English:Init_Self_Switch)」  
 全てのセルフスイッチを初期化します。  
 製作者 トリアコンタン  
 
「セルフスイッチの遠隔操作(English:Remote_Control_Self_Switch)」  
 マップID、イベントID、種別（A, B, C, D）を指定してセルフスイッチを操作します。  
 製作者 トリアコンタン  

「ピクチャの読み込み(English:Load_Picture)」  
 指定したファイル名のピクチャを事前に読み込んでキャッシュに保存します。  
 製作者 トリアコンタン  

「戦闘アニメの読み込み(English:Load_Animation)」  
 指定したファイル名の戦闘アニメを事前に読み込んでキャッシュに保存します。  
 製作者 トリアコンタン  

「シャットダウン(English:Shutdown)」  
 ゲームウィンドウを閉じて強制終了します。  
 この操作はブラウザ実行、スマホ実行では無効です。  
 製作者 トリアコンタン  

「ウェブサイト起動(English:Startup_Website)」  
 別ウィンドウで指定されたURLのウェブサイトを起動します。  
 この操作はブラウザ実行、スマホ実行では無効です。  
 製作者 トリアコンタン  

「変数の操作(English:ControlVariable)」  
 指定の変数の値を操作(代入、加算、減算、乗算、除算、剰余)します。  
 制御文字の使用により、変数の値のIndexへの変数の代入や、アイテム  
 名の一斉セットなど、汎用的な使用が可能です。  
 製作者 fftfantt  

「タッチ座標の取得(English:Get_Touch_Info)」  
 タッチ位置のX座標とY座標を指定された変数に格納します。  
 画面上の実座標とマップ上のタイル座標の二種類が取得できます。  
 製作者 トリアコンタン  

「マップタッチ禁止の変更(English:Change_Map_Touch)」  
 マップタッチによるプレイヤーの移動禁止を変更します。  
 製作者 トリアコンタン  

「マップタッチ移動中判定(English:Get_Map_Touch_Moving)」  
 マップタッチによるプレイヤーの移動中かどうかを  
 指定されたスイッチに格納します。  
 製作者 トリアコンタン  

「マップタッチ移動(English:Map_Touch_Move)」  
 マップをタッチしたのと同じ要領で指定位置にプレイヤーを移動します。  
 障害物やキー入力により移動は中断されます。  
 製作者 トリアコンタン  

「ピクチャの移動(English:Move_Picture)」  
 イベントコマンド「ピクチャの移動」と同じ動作をします。  
 それぞれのパラメータを制御文字で変数指定できるのが特徴で減算合成も可能です。  
 製作者 トリアコンタン  

