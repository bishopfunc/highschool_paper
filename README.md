# highschool_paper

## これは何？
  本レポジトリは高校の卒業論文に使われた実験コードをまとめたものである。執筆期間は2020年4月~2020年10月であるが、最近やっと少し整理してGitHubにアップロードすることを決意した。
  筆者は個人的にかなり頑張ったつもりだが、実験の厳密さはやや欠けており、実験コードも書籍やサイトから参考したものである。
  いつか余裕があればコードをより効率化良く実装し、また発展研究にも取り組んでいきたいと思う。


## 論文の概要(Abstract)
  [『粘菌を活用した新たな経路探索アルゴリズムに関する研究 ～ダイクストラ法・粘菌アルゴリズム・強化学習の比較検証～](https://github.com/bishopfunc/highschool_paper/blob/main/highshool_paper.pdf)
  > 本研究では、粘菌アルゴリズムと強化学習の生物らしさという共通点に着目した新たなアルゴリズムの開発を目指した。本論文で紹介する内容は、その第一歩としての位置づけである。粘菌アルゴリズムと強化学習、及びダイクストラ法をpythonで実装し迷路を解かせた場合の比較実験を行った。対象とする迷路は、粘菌が迷路を解くことを発見した中垣氏の実験から参考にした。その結果、ダイクストラ法、粘菌アルゴリズム、強化学習の順番で処理時間が短いことが分かった。また、強化学習は安定して解を求めることができる一方で、粘菌アルゴリズムは安定しなかった。一方で、アルゴリズム開発に向けて、扱うデータの形式の違い、粘菌アルゴリズムの不安定性、大規模実験の必要性などの課題が明らかとなった。

## 各ファイルの紹介
  - dire.csv
    - 各マスにおける移動可能な方向を1,0で表現する
  - block_maze_random.ipynb
    - 迷路をランダムで解く
  - block_maze_q_learning.ipynb
    - 迷路をQ-learningで解く
  - block_maze_sarsa.ipynb
    - 迷路をSARSAで解く
   
  - dijkstra.ipynb
    - 迷路をダイクストラ法で解く
      
  - physarum_solver.ipynb
    - 迷路を粘菌アルゴリズムで解く
   
  - highshool_paper.pdf
    - 論文のPDF 

  

  
  
     
 
  
