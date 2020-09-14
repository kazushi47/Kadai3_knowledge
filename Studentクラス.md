# Studentクラス

今回のクラス設計は以下の通りにしてみる。  
![クラス](https://user-images.githubusercontent.com/61966044/93081738-b2188700-f6ca-11ea-8a29-1509f8be060c.png)  
  
## なぜStudentクラス？
結論から言うと、データを管理しやすいから。  
  
``Stream<String>``型ですと、``String``しか入らないので面倒です。  
例えば氏名は``String``で管理できますが、得点は``int``のほうが計算の時に楽です。  
他にも上図のように同時に管理したい項目がたくさんありますね。  
  
Studentクラスを作ると``Stream<Student>``型にすることができます。  
これでいろいろできそうですね！
