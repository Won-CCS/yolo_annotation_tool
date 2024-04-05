# 使用方法
1. Pythonの仮想環境に入る  
`./modified_labelimg/Scripts/activate`  
これで入れなかったら`/modified_labelimg/Scripts`まで移動して  
`activate`  
を入力し入る
2. ツールを起動  
`labelimg`  
と入力
3. 起動したら、参照する画像フォルダとアノテーション結果を保存するフォルダを選択  
![alt text](<readme_images/スクリーンショット 2024-04-01 134228.png>)  
Open Dirで参照画像フォルダ  
Change Save Dirでアノテーション結果保存先フォルダ  
4. アノテーション  
`Ctrl`を押しながらホイールを回せばズームインアウトができる  
`x`キーを押してサイロを囲う矩形を作成する  
画像上で左クリックし、矩形左上を固定。ドラッグして左クリックを離すことで矩形右下を決定  
![alt text](<readme_images/スクリーンショット 2024-04-01 134915.png>)  
すると、クラスを入力するウィンドウが出てくるので、対応するクラスを入力し`OK`をクリック  
クラスは以下

|0個|1個|2個|3個|  
|----|----|---|---|  
|none|red1|red2|red3  
||blue1|blue2|blue3  
||purple1|purple2|purple3  
|||red1_blue1|red2_blue1
|||red1_purple1|red2_purple1
|||blue1_purple1|blue2_red1
||||blue2_purple1
||||purple2_red1
||||purple2_blue1
||||red1_blue1_purple1

`Ctrl + s`で保存をし、`d`キーを押して次の画像へ  
以上を繰り返す