---
layout: home
title: 数理モデル化と問題解決(MPS)研究会
ref: index
permalink: /index
---
## 情報処理学会 (IPSJ) 数理モデル化と問題解決研究会へようこそ

数理モデル化と問題解決(SIG Mathematical Modeling and Problem Solving: MPS) 研究会は， 問題の数理的把握とモデル化及び その有効な解決手法の開発に関する研究交流の場として，
1995年に誕生しました．以来， コンピュータを用いた問題解決が求められる理工系・人文社会系の諸分野全体を対象とし， これからも活発な学際的研究会として場を提供していく所存です．

特に， 1999年からは情報処理学会論文誌「数理モデル化と応用」を編集発行し，それにより研究会・シンポジウムの発表， 申し込みも一層活性化されました．
今後， 論文誌の更なる充実・発展を期し， 研究会全体のより一層の国際化及び学際化を進め， 産・官・学の良き交流の場を確立してゆきたいと考えております．

## 研究会設立の目的

実世界における種々の複雑な実問題を解決するためには， 先ず，いかにしてそれを適切に定式化した数理モデルとして表現するかが， 重要な第一ステップとなります．
そのモデル上で効率的な問題解決アルゴリズムを考案し，実行・評価を行うことで， そのモデルの妥当性が検討され， 必要に応じてその改良が繰り返されます．

一般に， 問題の適切なモデル化・定式化はきわめて難しく， しばしば「正しくモデル化ができれば，問題の9割は解けたようなもの」とも言われます．
これまでにも， 情報システム学やオペレーションズ・リサーチなどにおいて， さまざまなモデルが提案され， 解決手法が考案されてきました． しかし，

- 現実の問題からどのようにモデルを作るのか，
- 良いモデル・解決手法とは何か，

という最も根本的なことがらについて，幅広く総合的に議論・交流する適切な場がなく， その必要性が強く認識されておりました．

その要請に答えるため， 当「数理モデル化と問題解決研究会(SIG Mathematical Modeling and Problem Solving : MPS)」が，
平成7年度(1995年度)に，中森眞理雄(農工大)主査， 白石洋一(群馬大)， 伊達博(日立)両幹事の体制で発足しました．
以来， 特に「アルゴリズム研究会」， 「システム評価研究グループ」， 及び電子情報通信学会「コンピュテーション研究会」とは密接な連携関係を持ちながら，
研究会，シンポジウムの開催， 論文誌の編集発行を行って発展を続け， 今日に至っております．

## 対象とする研究分野

<ul>
  {% for l1 in site.data.specific_field.toc %}
    <li> {{l1.label}} </li>
    <ul>
        {% for l2 in l1.fields %}
        <li>{{l2.label}}</li>
        {% endfor %}
    </ul>
  {% endfor %}
</ul>

## 旧Webページへのアクセス

旧 Web ページへのアクセスは [こちら](http://daemon.inf.uec.ac.jp/MPSPortal/) へ

---
{{ page.last_modified_at }}
