# json2czml

sorry for not english

geojsonをczmlに変換するツールです


##サンプル実行

python test.py >test.czml

で使ってみてください

##呼び出し方
test.pyの内容
 from json2czml import json2czml
 jc=json2czml()
 jc.setColor("[0,0,255,128]") #rgbaの値を設定:
 print jc.to_czml('tokyo.json',{'area_en':'Tokubu'})

