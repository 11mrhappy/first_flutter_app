# first_flutter_app

widgetを重ねてアプリのUIを作る

Column Widgetは縦に並ぶ
Row Widgetは横に並ぶ。>>ブロック要素とインライン要素みたいなもの？

option と enter でcenterとかcolumn、row widgetを簡単に入れられる

Container Widgetはただの箱
height: double.infinity は全体の高さにするってことかな？

RaisedButtonというボタンのWidget。他にもFlatButton、OutlineButtonなど様々なボタンがある
onPressedでボタンを押せるようになる。この中に画面遷移のコードなどを書く

新しいファイル(dart)を作ってクラス名を指定した時、赤い波アンダーバーをクリック、「Create 1 missing override」を押すと自動で雛形?みたいなのを作ってくれる
importにはcupertinoかmaterialが入っていればOK

onPressedの中に書く画面遷移のコードは公式からコピペするとかでOK
この中に Navigator.pop(context); を入れることで前のページに戻るボタンが作れる;

画面遷移にはルーティングを最初に決めてやる方法もある。が、エラーがどうしても解決できなかったので割愛
