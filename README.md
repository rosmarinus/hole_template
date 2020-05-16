
# フェイスシールドの穴開けガイド用紙

## 目次

* 動機
* 用意するもの
* 使い方
* 注意事項
* 主なフェイスシールド
* ガイドファイル
* ソースファイル
* ライセンス


## 動機

3Dプリンタがあるので、自宅でもフェイスシールドの生産ができないか、どのフェイスシールドが作りやすいかいくつか作って試してみました。
やってみると、フレームの3D印刷よりも、フェイスシールドの透明シートの穴開けが面倒なので、穴開け用のガイド線付きの型紙を作りました。

## 用意するもの

* コンピュータ もしくは PDFをプリンタで印刷可能なスマホなど
* プリンタ
* A4用紙
* 2穴パンチ
* 固定するためのセロハンテープなど
* A4からA3の透明シート（透明なクリアファイル、プラバン、空でラミネートしたラミネートフィルムなど）

シールドの種類によっては
* 1穴パンチ
* デザインナイフもしくはカッターナイフなど
* カッターマットもしくはそれに代わるもの

## 使い方

1. 下記のガイドファイルにあるPDFファイルをA4用紙に印刷します。
PDFの印刷でサイズオプションを「実際のサイズ」にしておきます。
用紙内の数字はミリメートルです。
念のため、実際に印刷したものを測ってみて値が出てるか確認してください。

2. 中央の長い線に沿って、用紙を半分に折ります。

3. 透明シートを折り曲げた用紙で挟み込み、テープで固定します。
紙の上に置いて線に合わせるよりも挟んだ方が早くて正確です。テープも一カ所で済みます。
A4の場合は長い方を上辺にします。A3の場合は短い方を上辺にします。

4. 用紙の印にパンチのガイドを合わせて、打ち抜きます。
2穴パンチ用に▲の印、1穴パンチ用に十字線を付けています。

5. 透明シートに角がある場合は、角を丸めてください。

パンチの限界まで透明シートを重ねて、一気に打ち抜いても構いません。
テープを貼り付けるとき、シートに貼り付ける側の端を折り曲げて貼り付けておけば、楽に剥がして再利用できます。

この用紙はA4ラミネートフィルムで代用したシールドでも利用可能です。
ラミネーターを通した空のラミネートフィルムも、透明シールドの代用として使われてきています。
この場合上下左右3mm大きくなりますが、目分量で左右均等にはみ出すように固定して、打ち抜きます。
たいていのフレームでは穴の間隔さえ合っていれば、6mmぐらいは問題ありません。

A4ラミネートフィルムはできるだけそのままの形で使う方がいいでしょう。A4に切り詰めたり、出来た角を丸めたりすると余計な工程が増えるだけです。角の丸め忘れの点検もしないといけません。

## 注意事項

パンチの裏ぶたを開けて裏から確認しながら穿孔するという危険な裏技があります。
正確な穴はできますが、この方法だと透明シートの固い切り抜きが飛び出て、目を傷つけてしまう可能性があります。
決して行わないでください。
透明なふたのあるものでなければ、裏から確認する方法は大変危険です。


## 主なフェイスシールド

いろいろありますが、今回対応しているものを列挙しておきます。

### DOYOモデル

サイト：https://github.com/doyodoyo/facesheild

神奈川大学の道用大介准教授が公開しているフェイスシールドです。短時間で印刷できるのが特徴です。
消毒や渡し方の手順などの情報もあって参考になります。

いくつかのモデルがあり、特に推奨されているのがfast-typeVです。
しかしこれは穴の加工が独特で1穴パンチによる加工が必要になります。
穴の位置指定の台紙も用意されているのですが、黒丸だけなので、この用紙を作ってみました。


### Prusa Face Shield

サイト：https://www.prusaprinters.org/prints/25857

チェコの3DプリンタメーカーPrusa ResearchのコミュニティサイトPRUSAPRINTERSで公開しているフェイスシールドです。
ここに紹介したものの中では一番時間がかかりますが、他に比べてしっかりとしたものができあがります。
ヨーロッパ向けの4穴のものと、アメリカ向けの3穴のものがあります。
それぞれに4段のスタックバージョンもあります。

日本で作る場合は、メートル法で設計されたヨーロッパ向けのシールドが作りやすいでしょう。
透明シートの指示書には横長の穴が描かれ、間隔79mmと書いてありますが、簡易的に作るならば8cmm、6cm、8cmの間隔にして2穴パンチの丸い穴で作れます。

### 3DVerkstan

サイト：https://3dverkstan.se/protective-visor/

スウェーデンの団体 3DVerkstan のプロジェクト。
短時間で3D印刷できる軽量フレームです。
特徴は、いろいろな間隔の穴のシールド向けに数種類のフレームが用意されていることです。
日本で作成する場合は、スウェーデン以外のヨーロッパ向けバージョンがいいでしょう。
具体的には、Europe ISO838か、Europe 888、3DVerkstan Prusa Compatible です。

### N3DPS Protective Face Shield

サイト：https://national3dprintingsociety.co.uk/medical-am-covid-19/

イギリスの National 3D Printing Society という団体が行っているプロジェクトです。
以前はログインしなくてもSTLをダウンロードできたので、そのとき試してみました。

短時間で3D印刷できる軽量タイプのフレームです。
4穴で、間隔が888なので、日本の2穴パンチでも作りやすいタイプでした。
ただし、A4シートの端を押さえ込む構造なので、少し幅のあるラミネートフィルムでそのまま作るとちょっとだけ無理をします。

## ガイドファイル

下のPDFファイルから必要なものをダウンロードして印刷して使ってください。

### hole_guide_fast_typeV

・[hole_guide_fast_typeV.pdf](https://github.com/rosmarinus/hole_template/blob/master/hole_guide_fast_typeV.pdf)

対象：DOYOモデル fast-typeV

穴が一直線に並ぶ簡易版の穴開け用です。A4は横でも縦でも使えます。
1穴パンチが基本ですが、どうしても2穴パンチしか使えないときのために、2穴パンチの中点の印も付けています。
2穴の片側だけ使いますが、両方使ってしまって、シールドに余計な穴を作らないように注意してください。

A4縦を利用するときは、半分に曲げた後、さらに端になる線を片側折り曲げて、その角に内側から合わせます。固定したら、折り曲げた部分を戻します。端の線はラミネートフィルム向けの線も引いてあります。

### hole_guide_fast_typeV_curve

・[hole_guide_fast_typeV_curve.pdf](https://github.com/rosmarinus/hole_template/blob/master/hole_guide_fast_typeV_curve.pdf)

対象：DOYOモデル fast-typeV

穴の位置が傾けてあるFabNurseプロジェクトモデル用です。
A4は横だけでなく縦でも利用できます。

A4縦を利用するときは、半分に曲げた後、さらに端になる線を片側折り曲げて、その角に内側から合わせます。固定したら、折り曲げた部分を戻します。端の線はラミネートフィルム向けの線も引いてあります。

1穴パンチで加工するのが基本ですが、どうしても2穴パンチしか使えないときは、2枚印刷して、実線の中間線で折り曲げたものと、点線で折り曲げたものを作り、それぞれで穴を開けます。実線で折ったものでシートを奥まで挟み込み固定し、余計な穴を作らないように穿孔します。そのあと最初の紙はそのままで、点線で折ったものを裏から実線を重ねるようにして固定して穿孔します。

### hole_guide_fast_typeV_square

・[hole_guide_fast_typeV_square.pdf](https://github.com/rosmarinus/hole_template/blob/master/hole_guide_fast_typeV_square.pdf)

対象：DOYOモデル fast-typeV

穴の位置を端から奥にずらして、頭も防げるシールドを作るためものです。
パンチで穴を開けることを諦めて、四角い穴をデザインナイフやカッターナイフを使って開けるようにしています。
これは紙を半分には折りません。紙の上に透明シートをのせて、端を線に合わせます。固定した後、四角い穴をナイフで切り抜きます。

刃物使うので怪我をしないように気をつけてください。
またシールドに余計な隙間を作らないように気をつけてください。

### hole_guide_848

・[hole_guide_848.pdf](https://github.com/rosmarinus/hole_template/blob/master/hole_guide_848.pdf)

対象：DOYO モデル hybrid、DOYO モデル easy

穴の間隔が8cm、4cm、8cmになっている4穴用。fastモデルのようにツルが短いのがhybridモデル、ツルが長いのがeasyモデルです。DOYOモデルの中では、とても単純な工程でシールドを作成できます。

### hole_guide_fast

・[hole_guide_fast.pdf](https://github.com/rosmarinus/hole_template/blob/master/hole_guide_fast.pdf)

対象：DOYOモデル fast

ツルが短いモデルの一つ。透明シートはA4横のみ。1穴パンチの方が加工しやすい。

### hole_guide_3-hole

・[hole_guide_3-hole.pdf](https://github.com/rosmarinus/hole_template/blob/master/hole_guide_3-hole.pdf)

対象：DOYOモデル 初期

透明シートの穴が3つになっています。シールド部はA4横のみ。1穴パンチの方が加工しやすい。

### hole_guide_prusa_4_hole

・[hole_guide_prusa_4_hole.pdf](https://github.com/rosmarinus/hole_template/blob/master/hole_guide_prusa_4_hole.pdf)

対象：Prusa Face Shield (標準のヨーロッパバージョン)、3DVerkstan Prusa Compatible

2mmずらした穴をあけて長円を作ります。二つの穴の中間が上記の868の穴の位置になっています。

### hole_guide_prusa_3_hole

・[hole_guide_prusa_3_hole.pdf](https://github.com/rosmarinus/hole_template/blob/master/hole_guide_prusa_3_hole.pdf)

対象：Prusa Face Shield (USAバージョン)

USA用の108mm間隔の3穴です。2mmずらした穴をあけて長円を作ります。

### hole_guide_prusa_reinforcement

hole_guide_prusa_reinforcement.pdf
・[hole_guide_prusa_reinforcement.pdf](https://github.com/rosmarinus/hole_template/blob/master/hole_guide_prusa_reinforcement.pdf)

PRUSA用のシールドの下部に付ける補強用のパーツ用

### hole_guide_868

・[hole_guide_868.pdf](https://github.com/rosmarinus/hole_template/blob/master/hole_guide_868.pdf)

穴の間隔が8cm、6cm、8cmになっている4穴用。Prusa以外。

### hole_guide_888

・[hole_guide_888.pdf](https://github.com/rosmarinus/hole_template/blob/master/hole_guide_888.pdf)

対象：3DVerkstan EUROPE 888、N3DPS Protective Face Shield

穴の間隔が8cm、8cm、8cmになっている4穴用。ガイド付きの2穴パンチで888、A4_4holeなどの位置。

### hole_guide_iso838

・[hole_guide_iso838.pdf](https://github.com/rosmarinus/hole_template/blob/master/hole_guide_iso838.pdf)

対象：3DVerkstan ISO838

穴の間隔が8cm、6.85cm、8cmになっている4穴用。ガイド付きの2穴パンチでA5縦の位置。

## ソースファイル

それぞれのPDFには Adobe Illustrator CS6 で作成した同名の [ai ソースファイル](https://github.com/rosmarinus/hole_template/tree/master/source)があります。

## ライセンス

このプロジェクトでの配布ファイルはCC0です。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)
