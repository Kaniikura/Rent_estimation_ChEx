## 機械学習によって物件情報から家賃を推定します
* SUUMO様の賃貸情報サイト上で動作するChrome拡張です
* 物件の特徴量(e.g. 面積,階数,地名,アクセス)から線形モデルを用いて予測しています。
* 学習データは都内10万件の物件情報をスクレイピングして集めました。
* ↓ 使用イメージ
![image](https://user-images.githubusercontent.com/32826608/59975488-172e1b80-95f3-11e9-8996-eac02c80e907.png)

## 使い方
1. githubの"Clone or Download"をクリックしダウンロードします．  <br>
2. ダウンロードしたフォルダを拡張機能として読み込みます．  
   chromeの設定   
   -> 拡張機能   
   -> パッケージ化されていない拡張機能を読み込む   
   -> ダウンロードしたmasterのサブディレクトリ(chrome-extension)を選択  <br>  
3. SUUMO様のサイトで賃貸物件を検索し([例．渋谷駅の検索結果](https://suumo.jp/chintai/tokyo/ek_17640/))，  
   物件の詳細をクリック．  
   すると実際の家賃の下に推定値が表示されます(Congrats!).
