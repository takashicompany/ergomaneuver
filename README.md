# Ergo Meneuver

<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/01.jpg?raw=true" width = "600px" />


## 組み立てに必要な部品

キットに含まれていないものはご自身でご用意ください。  

### キットに含まれているもの
|部品|個数|備考|
|:--|:--|:--|
|PCB|1||
|スイッチプレート|1||
|ボトムプレート|1||
|[ダイオード(リードタイプ)](https://shop.yushakobo.jp/products/a0800di-01-100)|44|PCBは[SMDタイプのダイオード](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a0800di-02-100)にも対応しております。|
|[タクタイルスイッチ](https://shop.yushakobo.jp/products/a0800ts-01-1)|1||
|[滑り止めシール](https://shop.yushakobo.jp/products/a0800ur-01-6?_pos=1&_sid=6f6f85716&_ss=r)|8||
|[小型アナログジョイスティック](https://www.switch-science.com/products/2892)|1||
|[OLEDモジュール](https://shop.yushakobo.jp/products/oled)|1||
|スペーサー(M2 9mm)|6||
|ネジ(M2 5mm)|12||


### ご自身で用意頂くもの
|部品|個数|備考|
|:--|:--|:--|
|[キースイッチ用ソケット(MX用)](https://shop.yushakobo.jp/products/a01ps)|44||
|[Cherry MX互換キースイッチ](https://shop.yushakobo.jp/collections/all-switches)|44||
|キーキャップ|44|全て1uサイズ|
|[Pro Micro](https://talpkeyboard.net/?category_id=59e2ad48c8f22c3720001301)|1|動作確認済みのものは[こちら](https://talpkeyboard.net/items/62e24e6f8a0bd07fe2d38137)|

### お好みで
|部品|個数|備考|
|:--|:--|:--|
|[コンスルー](https://talpkeyboard.net/?category_id=5e451917cf327f255e6ae3ba)|2|Pro Microにハンダ付けを行うことでPCBとのハンダ付けが不要になります。Pro Microが壊れた際などに交換が容易になりますので、可能な限り取り付けをオススメします。|

## 組み立て方

### 1. PCBの表裏の確認

表  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7832.JPG?raw=true" width = "600px" />

裏  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7834.JPG?raw=true" width = "600px" />

### 2. ダイオードのハンダ付け

ダイオードは基板の`▷|`マークの縦線とダイオードの中央の黒線が同じ方向になるようにPCBの裏面に配置します。  
写真を例に上げると縦線と黒線が右側に来るように並べています。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7836.JPG?raw=true" width = "600px" />

ダイオードがPCBの穴に入るようにダイオードの足を折り曲げます。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7837.JPG?raw=true" width = "600px" />

ダイオードの足をPCBの穴に挿します。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7838.JPG?raw=true" width = "600px" />

PCBを表にして、ダイオードの足が出ていることを確認します。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7840.JPG?raw=true" width = "600px" />

PCBとダイオードの足をハンダ付けします。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7841.JPG?raw=true" width = "600px" />

ニッパーでダイオードの足を切ります。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7842.JPG?raw=true" width = "600px" />

全部で44箇所にダイオードを取り付けたら完了です。  

尚、当PCBはSMD型のダイオードの取り付けにも対応しております。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7844.JPG?raw=true" width = "600px" />

### 3. キースイッチソケットのハンダ付け

キースイッチを取り付けるためのソケットをハンダ付けします。  
ソケットはPCBの裏面に配置します。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7855.JPG?raw=true" width = "600px" />

ソケットのハンダ付け位置の片側に溶かしたハンダを載せておきます。(予備ハンダといいます。）  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7856.JPG?raw=true" width = "600px" />

ピンセットなどでソケットを持ちながら予備ハンダを溶かしてソケットの片側とPCBをハンダ付けします。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7857.JPG?raw=true" width = "600px" />

もう片方のハンダ付け箇所もハンダ付けします。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7858.JPG?raw=true" width = "600px" />

全部で44箇所にソケットをハンダ付けしたら完了です。  

### 4. Pro Microの取り付け

キーボードの頭脳部分であるPro Microを取り付けます。  
PCBの裏面奥側にPro Microの回路部分が内側になるように配置し、ピンソケットやコンスルーでハンダ付けをします。  
やり直しのしやすさや故障した時の修理のしやすさの観点から**コンスルーの利用を強く推奨します。**
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7860.JPG?raw=true" width = "600px" />

[こちらの説明](https://yushakobo.zendesk.com/hc/ja/articles/360044233974-%E3%82%B3%E3%83%B3%E3%82%B9%E3%83%AB%E3%83%BC-%E3%82%B9%E3%83%97%E3%83%AA%E3%83%B3%E3%82%B0%E3%83%94%E3%83%B3%E3%83%98%E3%83%83%E3%83%80-%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91%E6%96%B9%E3%82%92%E6%95%99%E3%81%88%E3%81%A6%E4%B8%8B%E3%81%95%E3%81%84)を参考にコンスルーをPro Microに挿します。
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7863.JPG?raw=true" width = "600px" />

Pro Microが付いたコンスルーをPCBに挿します。  
この時USBの取り付け口が外側に向くようにします。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7865.JPG?raw=true" width = "600px" />

**Pro Microとコンスルー**をハンダ付けします。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7866.JPG?raw=true" width = "600px" />

### 5. リセットスイッチの取り付け

ファームウェアを書き込む際に利用するリセットスイッチを取り付けます。  
取り付け位置はPCBの裏面の奥側にある「RESET」と書かれた箇所になります。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7867.JPG?raw=true" width = "600px" />

リセットスイッチの足をPCBの穴に通します。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7868.JPG?raw=true" width = "600px" />

PCBの表面からリセットスイッチの足が出ていることを確認します。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7869.JPG?raw=true" width = "600px" />

リセットスイッチの足とPCBをハンダ付けします。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7870.JPG?raw=true" width = "600px" />

### 6. OLEDの取り付け

キーボードの情報を表示するOLEDディスプレイを取り付けます。  
尚、既にPCBに取り付けられている場合はこの項は省略してください。

取り付け位置は、PCB表面の手前側になります。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7871.JPG?raw=true" width = "600px" />

**⚠ 従来の自作キーボードのOLEDの取り付け方法とは若干異なります。**

PCB表面にOLEDを重ねた状態で**基板の裏側**からPCBとOLEDにピンソケットを通します。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7873.JPG?raw=true" width = "600px" />

PCBの表面はこのようにピンソケットが少しだけ出ているようになります。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7874.JPG?raw=true" width = "600px" />

PCBの裏面はピンソケットのゴム部分からピンソケットの端子が出ているようになります。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7875.JPG?raw=true" width = "600px" />

外れやすいのでマスキングテープなどで固定すると作業がスムーズに進められます。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7877.JPG?raw=true" width = "600px" />

表面からピンソケットとOLEDをハンダ付けします。  
OLEDがズレないようにマスキングテープなどで固定すると出来上がりがキレイになります。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7878.JPG?raw=true" width = "600px" />

PCBを裏面にします。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7889.JPG?raw=true" width = "600px" />

ピンソケットのゴム部分を取り外して端子のみの状態にします。  
ニッパーなどでゴム部分を細かくして、ペンチなどで抜くのがやりやすいかと思います。  
基板や端子を傷つけないように注意すると良いかと思います。  
端子が抜けてしまった場合はOLEDとのハンダ付けを再度やり直してください。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7880.JPG?raw=true" width = "600px" />

端子とPCBをハンダ付けします。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7881.JPG?raw=true" width = "600px" />

端子の飛び出た部分をニッパーなどで切ります。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7882.JPG?raw=true" width = "600px" />

### 7. ジョイスティックの取り付け

ジョイスティックはPCBの表面中央に取り付けます。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7887.JPG?raw=true" width = "600px" />

PCBの穴とジョイスティックの足が合うように挿し込みます。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7888.JPG?raw=true" width = "600px" />

PCBの裏側からrジョイスティックの足が出ていることを確認して、PCBとハンダ付けします。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7889.JPG?raw=true" width = "600px" />

### 8. ファームウェアの書き込み

[Remap](https://remap-keys.app/catalog/dVkjiqBWOWYEa49WNYW3/firmware)からファームウェアを書き込むことができます。

ソースコードは[こちら](https://github.com/takashicompany/qmk_firmware/tree/ergomaneuver/1/keyboards/takashicompany/ergomaneuver)です。

当ファームウェアは、トラックポインタを一定時間内に一定の距離を移動させるとマウスレイヤーが有効になります。
デフォルトではマウスレイヤーは9番目(index:8)に設定されております。
マウスレイヤーの詳細は以下の記事を御覧ください。

*[トラックボール付き自作キーボードをさらに使いやすくするファームウェア](https://zenn.dev/takashicompany/articles/69b87160cda4b9#minizone%E3%83%88%E3%83%A9%E3%83%83%E3%82%AF%E3%83%9C%E3%83%BC%E3%83%AB%E3%83%95%E3%82%A1%E3%83%BC%E3%83%A0%E3%82%A6%E3%82%A7%E3%82%A2)*

Remap上でキーマップの変更が可能です。

<img src = "https://github.com/takashicompany/ergomaneuver/assets/4215759/5cd583c3-e94e-478c-ae04-f3d6ed2f5060" width = "600px" />

以下は、ErgoManeuver独自のキーです。Remapキーマップを設定する際に利用します。

|Keycode|[enum](https://github.com/takashicompany/qmk_firmware/blob/ergomaneuver/1/keyboards/takashicompany/ergomaneuver/ergomaneuver.h)での定義|名称|機能|
|:--|:--|:--|:--|
|User 0|KC_MY_BTN1|左クリック|押下すると左クリックになります。|
|User 1|KC_MY_BTN2|右クリック|押下すると右クリックになります。|
|User 2|KC_MY_BTN3|第3クリック|押下すると第3クリックになります。挙動はOS等に準拠します。|
|User 3|KC_MY_SCR|スクロールクリック|押している間にトラックポインタを動かすとスクロール入力になります。|
|User 4|KC_TO_CLICKABLE_INC|マウスレイヤー設定減|マウスレイヤーが有効になるまでのポインター移動距離を増加させます。最大値は256です。|
|User 5|KC_TO_CLICKABLE_DEC|マウスレイヤー設定増|マウスレイヤーが有効になるまでのポインター移動距離を減少させます。最低値は5です。|
|User 6|KC_SCROLL_DIR_V|垂直スクロール反転|スクロールクリック中の垂直スクロールの方向を反転させます。|
|User 7|KC_SCROLL_DIR_H|水平スクロール反転||スクロールクリック中の水平スクロールの方向を反転させます。|
|User 8|KC_OLED|OLED表示切り替え|OLEDの表示を情報/ロゴに切り替えます。|
|User 9|KC_JS_INC|トラックポインタ速度減|トラックポインタの移動量を遅くします。|
|User 10|KC_JS_DEC|トラックポインタ速度増|トラックポインタの移動量を早くします。|



### 9. キースイッチとスイッチプレートの取り付け

キースイッチを取り付けます。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7891.JPG?raw=true" width = "600px" />

スイッチプレートとPCBを重ねた状態でキースイッチをPCBの表面からソケットに挿します。  
一つずつ取り付けていくと、作業がスムーズに進みます。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7892.JPG?raw=true" width = "600px" />

### 10. ボトムプレートの取り付け

ネジとスペーサーを用いて、ボトムプレートとスイッチプレートを固定します。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7893.JPG?raw=true" width = "600px" />

ネジをスイッチプレート表側の穴に取り付けます。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7894.JPG?raw=true" width = "600px" />

PCBの裏側からネジにスペーサーを取り付けます。
全部で6箇所です。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7895.JPG?raw=true" width = "600px" />

PCBの裏側にスペーサーが出ていることを確認します。  
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7896.JPG?raw=true" width = "600px" />

ボトムプレートを載せてスペーサーとネジで固定したら完了です。
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7897.JPG?raw=true" width = "600px" />

### 11. ゴム足シールをボトムプレートに貼る

ゴム足シールをボトムプレートに貼ります。  

<img src = "https://github.com/takashicompany/minidivide/raw/master/images/build/IMG_3748.jpg?raw=true" width = "600px" />


### 12. キーキャップを取り付ける

キースイッチにキーキャップを取り付けます。

<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />

### 13. PCBの外周と縁を塗る

**こちらの工程は必須ではありません。**

PCBの外周と縁をスイッチプレートの表面と同じ色に塗りますと一体感が増します。  
完成後でも行える作業ですので、お好みで実施してください。
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_7926.JPG?raw=true" width = "600px" />


### 14. 完成した後の楽しみ方

完成しましたら、ぜひSNSなどに写真を投稿頂ければと思います。
Twitterのハッシュタグは [`#ErgoManeuver #自作キーボード`](https://twitter.com/search?q=%23%E8%87%AA%E4%BD%9C%E3%82%AD%E3%83%BC%E3%83%9C%E3%83%BC%E3%83%89%20%23ErgoManeuver&src=typed_query) を付けていただけると幸いです。
キットを組み立てた感想や、キーボードを使った所感などをお待ちしております！

また、毎週日曜日の１9時より実施されている[#KEEP_PD](https://twitter.com/hashtag/KEEB_PD?f=live)に投稿頂くこともオススメです。  
開催の告知は[@KEEB_PD](https://twitter.com/KEEB_PD)にて行われております。

ご不明な点などございましたら、[@takashicompany](https://twitter.com/takashicompany)にメンションやDM頂ければ回答できるかと思います。


<!--
<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />


<img src = "https://github.com/takashicompany/ergomaneuver/blob/master/images/build/IMG_ .JPG?raw=true" width = "600px" />

->
