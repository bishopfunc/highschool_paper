# highschool_paper

## これは何？
  本レポジトリは高校の卒業論文に使われた実験コードをまとめたものである。執筆期間は2020年4月~2020年10月であるが、最近やっと少し整理してGitHubにアップロードすることを決意した。
  筆者は個人的にかなり頑張ったつもりだが、実験の厳密さはやや欠けており、実験コードも書籍やサイトから参考したものである。
  いつか余裕があればコードをより効率化良く実装し、また発展研究にも取り組んでいきたいと思う。


## 論文の概要(Abstract)
  [『粘菌を活用した新たな経路探索アルゴリズムに関する研究 ～ダイクストラ法・粘菌アルゴリズム・強化学習の比較検証～](https://github.com/bishopfunc/highschool_paper/blob/main/highshool_paper.pdf)
  > 本研究では、粘菌アルゴリズムと強化学習の生物らしさという共通点に着目した新たなアルゴリズムの開発を目指した。本論文で紹介する内容は、その第一歩としての位置づけである。粘菌アルゴリズムと強化学習、及びダイクストラ法をpythonで実装し迷路を解かせた場合の比較実験を行った。対象とする迷路は、粘菌が迷路を解くことを発見した中垣氏の実験から参考にした。その結果、ダイクストラ法、粘菌アルゴリズム、強化学習の順番で処理時間が短いことが分かった。また、強化学習は安定して解を求めることができる一方で、粘菌アルゴリズムは安定しなかった。一方で、アルゴリズム開発に向けて、扱うデータの形式の違い、粘菌アルゴリズムの不安定性、大規模実験の必要性などの課題が明らかとなった。

## 発表経験
   - [首都圏オープン2021（TSEF2021）](http://www.f.waseda.jp/yasushin/posts/post16.html) 優等賞
   - [ジュニア農芸化学会2021](https://www.jsbba.or.jp/2021/program_junior.html)P13-B 参加賞 
   
## 各ファイルの紹介
  - dire.csv　各マスにおける移動可能な方向を1,0で表現する
  - block_maze_random.ipynb　迷路をランダムで解く
  - block_maze_q_learning.ipynb　迷路をQ-learningで解く
  - block_maze_sarsa.ipynb　迷路をSARSAで解く
   
  - dijkstra.ipynb　迷路をダイクストラ法で解く
      
  - physarum_solver.ipynb　迷路を粘菌アルゴリズムで解く
   
  - highshool_paper.pdf　論文のPDF 
  
 ## コードの参考書籍・サイト
  - [Numpy だけで書いたガウスの消去法で連立 1 次方程式を解いて みた WATLAB](https://watlab-blog.com/2020/05/01/gaussian-elimination/)
  - [Python で粘菌ネットワーク Qiita](https://qiita.com/STInverSpinel/items/8ced06ea7881613a3e2c)
  - [増井敏克  Python ではじめるアルゴリズム入門 伝統的なアルゴリズムで学ぶ定石と計算量」翔泳社](https://www.amazon.co.jp/Python%E3%81%A7%E3%81%AF%E3%81%98%E3%82%81%E3%82%8B%E3%82%A2%E3%83%AB%E3%82%B4%E3%83%AA%E3%82%BA%E3%83%A0%E5%85%A5%E9%96%80-%E4%BC%9D%E7%B5%B1%E7%9A%84%E3%81%AA%E3%82%A2%E3%83%AB%E3%82%B4%E3%83%AA%E3%82%BA%E3%83%A0%E3%81%A7%E5%AD%A6%E3%81%B6%E5%AE%9A%E7%9F%B3%E3%81%A8%E8%A8%88%E7%AE%97%E9%87%8F-%E5%A2%97%E4%BA%95-%E6%95%8F%E5%85%8B/dp/4798163236)
  - [株式会社電通国際情報サービス 小川雄太郎 「つくりながら学ぶ！ 深層強化学習 PyTorchによる実践プログラミング」 マイナビ出版](https://www.amazon.co.jp/%E3%81%A4%E3%81%8F%E3%82%8A%E3%81%AA%E3%81%8C%E3%82%89%E5%AD%A6%E3%81%B6%EF%BC%81%E6%B7%B1%E5%B1%A4%E5%BC%B7%E5%8C%96%E5%AD%A6%E7%BF%92-PyTorch%E3%81%AB%E3%82%88%E3%82%8B%E5%AE%9F%E8%B7%B5%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0-%E6%A0%AA%E5%BC%8F%E4%BC%9A%E7%A4%BE%E9%9B%BB%E9%80%9A%E5%9B%BD%E9%9A%9B%E6%83%85%E5%A0%B1%E3%82%B5%E3%83%BC%E3%83%93%E3%82%B9-%E5%B0%8F%E5%B7%9D%E9%9B%84%E5%A4%AA%E9%83%8E-ebook/dp/B07DZVRXFK)

  

  
  
     
 
  
