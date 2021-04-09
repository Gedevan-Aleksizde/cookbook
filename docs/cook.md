---
title: "ザ・クックブック"
author: 'ill-identified^[twitter ID: \@ill-identified]'
date: "最終更新時刻 2021-04-10 02:57:06, 初公開: 2021/4/1"
site: bookdown::bookdown_site
description: ""
documentclass: ltjsreport
classoption: a4paper
link-citations: true
linkcolor: blue
citecolor: blue
urlcolor: magenta
bibliography: Cooking.bib
pagestyle: fancy
github-repo: "Gedevan-Aleksizde/cookbook"
url: 'https://github.com/Gedevan-Aleksizde/cookbook'
---




\listoffigures

# 初めに {-#preface}

\begin{rmdcaution}
本書は R 言語並びに \textbf{rmarkdown}, \textbf{bookdown},
\textbf{rmdja}パッケージなどを使って書かれています.
\end{rmdcaution}

2020年は外出できなかったのでいろいろ作った.

プロの料理人でも料理道の家元でもないので, もちろんここで紹介しているものが唯一正統な作り方というわけではない. うまい料理を見つけ出すのに最後に必要なのはあなたの努力だろう. しかし, 本書があなたの今後の食事を豊かにすることになんらかの形で寄与できることを願っている.


# 本書の読み方 {-}

各レシピは次のようなセクションに分かれている.

* 「難度」は文字通り料理の難度を5段階で評価したものである. 評価は完全に個人的な経験に基づくものなので, 読者すべてに当てはまるとは言えない. 必要な材料の入手難度と, 料理手順の技術的難度について記載している.
* 「材料」は文字通り必要な材料とその分量である. 「適量」と書かれているのは常識の範囲でわかりそうな場合か, 作者が正確な分量を量ってなかったり覚えてなかったりするもの.
* 「道具」は特筆すべき調理器具が必要な場合に記載する. フライパンや鍋や包丁などありふれたものは省略するが, 例えば大きいフライパンや鍋が要求されるばあいは記載する.
* 「作り方」も文字通り使い方で, 基本的には時系列に沿って手順を記載している. 簡単な注意事項なども補足することがある.
* 「補足」はレシピ全般に関する参考情報や, 他のセクションに書くには長すぎる注意事項などを書いている.
* 「参考資料」は文字通り

## 凡例 {-}

### 国名の略記 {-}

基本的に1字だが重複があるもの, 紛らわしいものは2字で表記

* 亜塞 - アゼルバイジャン
* 米 - アメリカ合衆国
* 英 - イギリス (現時点ではスコットランド等を区別しない)
* 印 - インド
* 宇 - ウクライナ
* 月 - ウズベキスタン
* 韓 - 韓国
* 草 - ジョージア
* 捷 - チェコ
* 中 - 中国
* 日 - 日本
* 白露 - ベラルーシ
* 波 - ポーランド
* 露 - ロシア




<!--chapter:end:index.Rmd-->

# 手抜き料理編 {#tenuki}

難易度の低そうな料理, 比較的簡単に, 一度に大量に作りやすい料理をジャンル等無節操に紹介する.

## ペペロンチーノ (伊: Spaghetti Aglio, Olio e Peperoncino)\index{うどん!ペペロンチーノ} {#peperoncino}

アンチョビすら使わない本場の手抜きレシピを紹介する


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* スパゲッティ 1人前
* 塩 大さじ1杯
* 水 2-3 l
* オリーブオイル
* ニンニク 1かけ
* 唐辛子 1本
  * できれば生が良い
* (オプション) イタリアンパセリの葉

### 道具

* 茹でるための鍋
* トング
* フライパン
  * 小さいものが使いやすい

### 作り方

1. 水に大さじ1杯の塩を加え沸騰させる
    * 下味を付けるため, これくらい多くても良い
1. スパゲッティを入れて説明書にある時間くらい茹でる
1. フライパンを弱火にかけ, オリーブオイルをひき, 刻んだニンニクと唐辛子を炒める
    * 生の唐辛子は入手しづらい. 乾燥鷹の爪を使う場合, 焦がさないように少し後で入れる
    * 見た目の理由で唐辛子の種は取ったほうが良い. 辛いのが苦手ならなおさら.
1. 中火-強火にしてスパゲッティの茹で汁を少しづつ, 大さじ2-3杯くらい
1. 水分が飛んで油と半々の粘り気のある状態になったら火を止める
1. スパゲッティに絡める
1. オプションで刻んだパセリをふりかける

#### 補足

パセリで彩りを加えると幸福追求権が多少満たされた感じがする. 昆布出汁で茹でると味にちょっと深みが出る. しかし和風の味付けが嫌ならやらなくてもよい.

## 娼婦風スパゲッティ (伊: Spaghetti Alla Puttanesca)\index{うどん!娼婦風スパゲッティ} {#puttanesca}

ジョジョ四部のあれ. ペペロンチーノよりも手間を加えて美味しくしたいときに.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/puttanesca/finished} 

}

\caption{娼婦風スパゲッティ}(\#fig:finished-puttanesca)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* スパゲッティ 1人前

* 塩
* オリーブオイル
* ニンニク 1かけ
* 唐辛子 1個
  * 注意点はペペロンチーノと同じ.
* アンチョビ 3切れ程度
  * トマトソースに塩分がない前提
* オリーブの実 (種抜き) 4-5個
* トマトソース 大さじ3杯程度
* (オプション) トッピング
  * パセリの葉
  * ケーパーの塩漬け
  * 粉チーズ

### 道具

ペペロンチーノと同じ

### 作り方

1. スパゲッティを茹でるところまではペペロンチーノと同じ.

1. フライパンにオリーブオイルをしき, 弱火でニンニクと唐辛子を入れる.

1. 香りが立ってきたら刻んだアンチョビも加える.

1. さらに少ししたらトマトソースと輪切りにしたオリーブの実を入れ, よく混ぜながら加熱する.

1. ソースが煮立ってきたら火を止める.

1. スパゲッティとソースを混ぜる.

1. 皿に盛り付けてオプションのトッピングをする.

### 補足

アンチョビの量は, トマトソースに味付けがないという前提である. もし塩で味付け済みの市販のトマトソースを使うなら, これより少なくても良い.

#### アンチョビの調達方法 {-}

スーパーでよく売っている小さい缶詰は容量あたりの単価が高い. よく使うならスカーリア製の3000円程度の瓶詰めが価格と品質のバランスが良い. ゴムパッキン付きの瓶なので保存容器として再利用できる. それより安いものは身が崩れていたりするが, 味はそこまで変わらないので, 最初からペーストとして使うならそういうものでも問題ないだろう.

## 海軍風パスタ (露: макароны по-флотски) {#makaroni-po-flotski}

ソ連時代に流行した大衆料理. 名前の通りソ連海軍のメニューが発祥と言われている.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/makaroni-po-flotski/finished} 

}

\caption{海軍風パスタ}(\#fig:finished-makaroni-po-flotski)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* パスタ
  * ロシア語ではマカロニ=パスタ類全般なのでなんでもいい
  * ペンネを使う例が多い?
* ノザキコンビーフ缶 1個 (100gくらいのやつ)
  * または牛ひき肉
* バター
* 玉ねぎ
* 塩胡椒
* (オプション) 刻んだパセリや万能ネギ等

### 道具

ペペロンチーノと同じ

### 作り方 (1-2食分)

1. パスタを茹でる.
1. 玉ねぎをみじん切りにする
1. フライパンを弱火にかけ, バターを溶かす
1. 玉ねぎを炒める
    * 焦らず, 焦がさず, 時間をかけて茶色くなるまで炒めるとうまいが, 適当に切り上げても良い
1. コンビーフを混ぜる
1. 塩胡椒で味付けする
1. パスタと絡める
1. 皿に盛り付けてオプションをトッピングする

### 補足

ロシアで一般的なコンビーフ (тушенка) は脂身やブイヨンが一緒になった大きな缶詰なので, 大量のパスタに温めたコンビーフを混ぜるだけで作ることができたらしい.

### 参考資料

* 『ロシアの味』日本在住ロシア人による動画 (日本語) https://www.youtube.com/watch?v=HXz8deILEe8
* 『ロシア・ビヨンド』での言及 https://jp.rbth.com/multimedia/video/2015/03/03/52185

## 醤油炒飯 (中) {#chahan}

イマドキは冷凍食品を炒めるだけでもできてしまうので王剛式炒飯を参考にしたレシピを紹介する. 最もシンプルな炒飯で, ほとんど具も入ってない.


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 米飯 1人前
  * 一度炊いてから完全に冷えて固くなったもの
* 卵 1個
* サラダ油
* ニンニク
* ショウガ
* 万能ねぎ
* うま味のあるもの
  * 干瓢とか干し椎茸とか
* 醤油
* (オプション) 明油
* (オプション) 片栗粉か小麦粉

### 道具

* ザル
* 中華鍋
  * あったほうが楽しい

### 作り方

1. 米をザルに入れて短時間冷水ですすぎながらほぐし, 水気を良く切る
    * 水を使わない方法: 片栗粉か小麦粉を軽くまぶして吸収させる

2. 卵を卵白と卵黄に分ける
    * [ちょっと悪趣味な器具](https://www.google.com/search?sxsrf=ALeKk00q-gEeJLwrMinjdKzuK0vEwdEO9w:1613567209399&q=%E3%82%A8%E3%83%83%E3%82%B0%E3%82%BB%E3%83%91%E3%83%AC%E3%83%BC%E3%82%BF%E3%83%BC+%E3%81%B2%E3%82%88%E3%81%93&sa=X&ved=2ahUKEwiL-Nii_vDuAhWRyosBHRVKDc4Q1QIoA3oECAwQBA&biw=1920&bih=947)を使ってもいいし, 手でやってもいい.

3. 卵白をよくかき混ぜる

4. ニンニク, ショウガ, その他を細かく切り刻む
    * 米と同じくらいの大きさだと混ぜやすい

5. フライパンまたは中華鍋を温め, 油をひいてなじませる
    * テフロンなら焦げ付きは我慢しよう

6. 弱火で卵白を注ぎ, 焦がさないって程度にゆっくり加熱して固める
    * 中華鍋ならある程度固まってきたら鍋の上を回すだけで焦げ付かせずに加熱できる
  * 途中でいちどひっくり返す

7. 一旦卵白を取り出し, 油を多めに追加する

8. 卵黄を入れ, すぐかき混ぜる

9. 卵黄が固まってきたら, 卵白とネギ以外の固形物も入れ, お玉やしゃもじで叩いてよくほぐす

10. 中華鍋なら適度に鍋を振り, そうでないなら固まったり焦げ付いたりしないようにかき混ぜ続ける

11. 全体に火が通ってパラパラになってきたら, 少し火を強くして醤油と油をふりかける
    * ネギ油など香りの良いものを使うと良い

12. 再び水気が飛ぶまで固まらないように, 焦げないように混ぜ続ける

13. 最後にネギを加える

14. パラパラになってきたら盛り付ける

#### 補足

中華鍋で作ったほうがやりやすい. 卵黄と卵白を分けるのは面倒なように見えるが, このほうが卵が塊にならず均等に混ざりやすい.

王剛の方法では片栗粉などで米をほぐしているが, ザルさえあれば Foodie の記事で紹介されているように水ですすいでしまうほうが簡単である. ただし, 平たいフライパンではくっつきやすくなり, より多くの油が必要になる.

### 参考資料

* 美食作家王剛の醤油炒飯の作り方 (中国語, 英語字幕あり) https://www.youtube.com/watch?v=1Q-5eIBfBDQ 
* Foodie の記事 https://mi-journey.jp/foodie/59108/

## 西紅柿炒鶏蛋 (中) + 面 {#friedtomatoegg}

炒鶏蛋とも. 卵と西紅柿 (トマト) を炒めただけ. なおトマトは番茄ともいう (主に台湾で使われる表現?). 王剛のレシピのうち最も簡単な「怠け者のレシピ」に基づいたレシピを紹介する. 麺に乗せて食べても良い(図\@ref(fig:finished-friedtomatoegg)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/friedtomatoegg/finished} 

}

\caption{西紅柿炒鶏蛋麺}(\#fig:finished-friedtomatoegg)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (1人前)

* トマト 中サイズ 1個
* 卵 2個
* 長ネギ 1/4 - 1/3 程度
* 塩胡椒 少々

### 作り方

1. 卵を良く混ぜる
2. トマトを小さく角切りに, ネギをみじん切りにする
3. これらをまぜ, 塩胡椒を少々加える
4. フライパンまたは中華鍋に油をひき, よく熱する
5. 材料を入れる
6. ある程度固まるまではかき混ぜすぎず, 軽く揺する程度にする
    * 早くにかき混ぜると油と混ざり塊にならないが, 好みならそれでも良い (図\@ref(fig:cooking-friedtomatoegg))
7. 好みの固さになるまで加熱する

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/friedtomatoegg/cooking} 

}

\caption{スクランブルエッグに近い状態}(\#fig:cooking-friedtomatoegg)
\end{figure}

### 補足

王剛のレシピでは卵4個を使っているが, 一度に大量に作るのは難しく, また1食としては多すぎるので卵2個, 中サイズのトマト1個とした. 王剛は卵とトマトの量は 4:3 が良いと言っているので, これを念頭において大きさを選ぶと良い. トマトが多すぎると水っぽくなる. 酢や刻んだニンニクを入れるのも良い.

麺にかけてもよい. インスタント麺でも良いが, つけ麺や油そば用の太い麺とも合うだろう.

### 参考資料

* 美食作家王剛による6動画
  * 通りの作り方の動画, 冒頭から2分までが「怠け者のレシピ」https://www.youtube.com/watch?v=3gF44PXZXNc
  * 中華鍋で丁寧に作る場合の解説 (日本語) https://www.youtube.com/watch?v=-7vw-sHGtDY
  * 水を足してスープにしている「西红柿鸡蛋面」 https://www.youtube.com/watch?v=PtAhBml14Uw

## シャクシュカ (中近東) {#shakushka}

中近東および北アフリカで見られる料理. 西紅柿炒鶏蛋同様トマトと卵の料理だが, 唐辛子ソースのハリッサやオリーブオイルを加えるのでもう少し豪華になる (図\@ref(fig:shakushuka-finished)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/shakushka/finished} 

}

\caption{シャクシュカの例}(\#fig:shakushuka-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (2食分)

* 卵 4個
* ホールトマト缶 1個 (400g)
* ニンニク
* 玉ねぎ
* オリーブオイル
* ハリッサ 大さじ1-2杯
  * なければ以下を少しづつ加える
  * 唐辛子
  * コリアンダーシード
  * クミンシード
  * パプリカパウダー
* 塩・胡椒
* オリーブの実 (種抜き) 数個
* コリアンダーの葉
  * イタリアンパセリでも良い

### 作り方

1. 玉ねぎとニンニクをみじん切りにする
1. フライパンにオリーブオイルをひき, 玉ねぎとニンニクを火が通るまで炒める
1. トマトとハリッサを入れ, よくかき混ぜる
1. トマトに火が通って余計な水分が減り, 柔らかくなるま煮込む
1. 卵を投入する
    * トマトペーストにくぼみを作ると均等に配置しやすい
1. 目玉焼きの容量で, 蓋をして卵全体を蒸す
1. 卵に十分に火が通ったら皿に盛り付ける
1. 刻んだオリーブの実とコリアンダーの葉を散らす

### 補足

KALDI で売っているハリッサを使うと楽だが, ちょっと割高なので材料を直接入れても良い.

### 参考資料

* アラブ式シャクシュカ (アラビア語, 英語字幕) https://www.youtube.com/watch?v=aSTBwIeYBYk
* (英語) https://www.youtube.com/watch?v=Iy3mUtlvw84
* モロッコ式シャクシュカ (英語)  https://www.youtube.com/watch?v=9z9UU10kM5c

## シュクメルリ\index{シュクメルリ} (草: შქმერული\index{შქმერული|see{シュクメルリ}}) {#shkmerli}

最近松屋の限定メニューになったので知名度が上がったが, 松屋ではなく本場ジョージアに近い (と思う) レシピを紹介する (図\@ref(fig:shkmerli-finished)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/shkmerli/finished} 

}

\caption{シュクメルリ}(\#fig:shkmerli-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (1人前)

* 鶏モモ肉 1枚
  * 本来は丸ごと使うが, 手抜きレシピなので骨抜きのモモ肉でよい
  * 丸ごと使うなら 4-5人前くらいになる
* バター 30 g
* ニンニク 2-3かけ
  * もう少し多くてもよい?
* 牛乳 100-200cc
* (オプション) トッピング
  * コリアンダーの葉
  * パプリカパウダー
  * 粉チーズ

### 作り方

1. 丸ごとや骨抜きのモモ肉以外の場合, なるべく平たくなるよう切り開く.
2. 塩を軽く振って下味をつける
3. フライパンを熱してバターを溶かし, 鶏肉をのせる.
4. 上から重しをする
    * アルミホイルの上から水を入れた炊飯釜や鍋などを載せるとよい (図\@ref(fig:shkmerli-press))
5. 中火で10-15分程度焼く
6. 裏返して同様に重しをして焼く. 焼き目がついていたら成功 (図\@ref(fig:shkmerli-fried))
7. 一旦鶏肉を取り出し, 熱に気をつけて食べやすい大きさに切る (図\@ref(fig:shkmerli-chopped))
8. 弱火にして, フライパンに刻んだニンニクを入れ, バターと溶けた鶏の脂に絡める
9. ニンニクの香りが出てきたら再度鶏肉を入れ, 牛乳を注ぐ
10. ふつふつと煮立ってくるまで加熱する
11. 皿にソースと一緒に盛り付けてオプションのトッピングをする.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/shkmerli/press} 

}

\caption{重しをする}(\#fig:shkmerli-press)
\end{figure}

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/shkmerli/fried} 

}

\caption{片面を焼いた直後 (胸は切除している)}(\#fig:shkmerli-fried)
\end{figure}

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/shkmerli/chopped} 

}

\caption{適当に切り分ける}(\#fig:shkmerli-chopped)
\end{figure}

### 補足

ハチャプリ (作り方は参考資料参照) かパン, そしてワインないしチャチャ (ჭაჭა) と一緒に食べると良い. もともとはタパカというローストチキンのレシピをアレンジしたものらしい.

### 参考資料

* シュクメリ村での伝統的な作り方, 牛乳の代わりに水を使う (ジョージア語) https://www.youtube.com/watch?v=qBpRB3QAjoQ
* 『シュクメルリ異聞』上記の動画に言及した日本語の解説記事 http://georgia1001.com/2020/02/12/anotherstoryofshkmeruli/
* 『シュクメルリには「茶シュク」と「白シュク」の2つがある。本当のシュクメルリは茶色い料理です。』 http://jp.ndish.com/diary/20200901_3847/
* ジョージア大使によるハチャプリの作り方実演動画 https://www.youtube.com/watch?v=v1fL2_qm4xE

## パエリヤ (西: Paella)\index{パエリヤ}\index{paella|see{パエリヤ}}

パエリヤというとムール貝やエビをふんだんに使ったものを連想しがちだが, ここでは鶏肉がメインの比較的簡単な paella valenciana 風のレシピを紹介する.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/paella/finished} 

}

\caption{鶏肉のパエリア}(\#fig:paella-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (3-4食分)

* 米 1合
    * できればジャバニカ米がいいが, なければ日本の米でいい.
* 鶏肉 またはウサギ肉
* オリーブオイル
* インゲン豆
    * さやごと使う.
* 日本とスペインで一般的なインゲン豆は品種が違うような気がする
* ニンニク 1個
* 玉ねぎ 1玉
* トマトピューレ 50g
* パプリカパウダー 大さじ1杯
* ローズマリー 数本

* サフラン ひとつまみ

  – 香りが肝だが高価なのでなければないで可

* (オプション) コンソメスープ だいたい米の2倍

  – コンソメスープの素などなんでも

### 道具

* アルミホイル

* 専用フライパンではなく普通のフライパンでもなんとかなる.

### 作り方

1. サフランをアルミホイルに包み, 熱したフライパンに10秒だけ載せて煎る.

2. 肉を食べやすい大きさに切る

3. 玉ねぎとニンニクをみじん切りにする

4. フライパンに火をかけオリーブオイルをひく

5. 鶏肉を焼き目が付くまでよく炒める

6. インゲン豆も炒める

7. 玉ねぎとニンニクも加えて炒める

8. よく火が通ったら, パプリカパウダーとトマトピューレを加える

9. コンソメスープか, なければお湯を注ぐ

10. 米を入れる. たぶん研がなくても良い. 米が山になってたらならす

11. ローズマリーを添える

12. 一切かき混ぜずに加熱を続ける. 加熱時間は米の量や品種次第なので状況判断する

13. 水かさが減ってきて米が露出してきたら, 蓋をかぶせて弱火にする

    * 残った水分で蒸すことになる

#### 補足

欲張って一度に大量に作ろうとすると米の上層に火が通ってないのに底が焦げ付くということが起こりがちである.

参考動画ではアルティチョークを使用しているが, なかなか手に入らないので私は使ったことがない.

### 参考資料

* https://www.youtube.com/watch?v=L_dDUw_QuDU

## スペイン風オムレツ  (西: Tortilla de Patatas)\index{スペイン風オムレツ}\index{tortilla de patatas|see{スペイン風オムレツ}}

日本のオムレツ (フランス風) と違いしっかり焼き目をつけ, 固くする(図\@ref(fig:finished-tornilla)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/tortilla/finished} 

}

\caption{スペイン風オムレツ}(\#fig:finished-tornilla)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (3-4食分)

* 卵 4-5個
* ジャガイモ 1-2個
* 玉ねぎ 1個
* ベーコンまたはハム 50-100g?
* 塩胡椒
* オリーブオイル

### 道具

* 大きめのフライパン
  + 直径 28cmとかそれくらいの
  + 蓋も必要
* 大きめの皿

### 作り方

1. ジャガイモ, 玉ねぎ, ベーコンを小さく切る
    * ジャガイモはスライス, それ以外はみじん切りがよい
1. フライパンにオリーブオイルを広げ, 上記を炒める
    * ジャガイモが焦げ付かないように油は多め, 火は弱く
1. 塩胡椒で味付けする
    * ケチャップ等をかけない前提なのでしっかり味付けする
1. 火を止めて少し冷ます
1. ボウルに卵を全て割り, 溶き卵にする
1. 卵に炒めた具材を混ぜる
1. 蓋をして10分寝かせる
1. フライパンに注いで再び数分加熱する
    * 混ぜる必要はないが軽く揺すってくっつかないようにする
1. 底が十分焼き固まったようなら, 皿をかぶせ, 裏返して皿に載せる
    * 油が垂れてやけどしないようにすばやくやる
1. フライパンに戻して反対側も焼き固める
1. ピザのように切り分けて食べる

### 補足

ベーコンはさほど重要ではない. 必須なのはジャガイモ.

### 参考資料

* https://www.youtube.com/watch?v=JceGMNG7rpU

## チェスネチカ - (捷: česnečka)\index{チェスネチカ}\index{česnečka|see{チェスネチカ}} {#cesnecka}

名前はそのまま「ニンニク (のスープ)」と言う意味 (図\@ref(fig:cesnecka-finished)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/cesnecka/finished} 

}

\caption{チェスネチカ}(\#fig:cesnecka-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* バター 20 g
* ニンニク 5-6 個
* 玉ねぎ 1個
* ジャガイモ 1個
* 水またはブイヨン 適量
* 塩胡椒 適量
* キャラウェイシード 少々
* マジョラム 少々
* (オプション) クルトン, あるいは古くなった食パン
* (オプション) 溶き卵

### 作り方

1. 鍋にバターをひく
2. 玉ねぎをみじん切りにし, 弱火で炒める
3. 鍋で湯を沸かす
    * ブイヨンの素などを溶かすと良い
4. ジャガイモの皮を向き, 小さめに切る
5. 鍋にジャガイモを入れて茹でる
6. みじん切りにしたニンニクを入れる
7. キャラウェイシードやマジョラムを入れる
8. 塩胡椒で味を調える
8. 盛り付け, お好みでクルトンや溶き卵を入れる

#### 補足

中世の頃から似たような料理が同地に存在するらしい. 現代のチェコ人は二日酔いや風邪気味で調子が悪かったら朝食をこれにするらしい. ニンニクは最初に入れたり, 2回に分けて入れたりしても良い. もうすこし食べごたえのあるものにしたければ, ベーコンを入れても良い

#### 参考資料

* czechcookbook の動画 (英語音声) https://www.youtube.com/watch?v=vYeoxYUMzME
* Random Innkeeper の動画 (英語音声, 日本語字幕) https://www.youtube.com/watch?v=F_59dZw5G44
* @faktor2007Traditional p. 18

## 鶏・野菜・味噌 (日)\index{鶏・野菜・味噌}

料理名なのか怪しいが, こういう名前で通っている. 最低限鶏肉と白菜と味噌があれば作れる. 冬に作ると良い.

TODO: 画像


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

材料

* 味噌
  – 「まつや」の専用味噌は高いので使わない
  – 「日本海味噌^[https://www.youtube.com/watch?v=JG_eS7HcuD8]」あたりが味と価格のバランスが良い
  – 煮干しや昆布の出汁も合わせるとより良い
* 白菜
* 鶏肉
  – できればモモ肉
* その他鍋料理に使う食材
  – 椎茸, えのき, 人参, ネギなど
* (オプション) 七味唐辛子

### 作り方

1. 昆布や煮干しの出汁か, 熱湯に味噌を溶く.
2. 適当に切った食材を煮る
    * 人参, 肉, 白菜その他の野菜, の順が良いと思う.
3. 野菜に火が通り柔らかくなってきたら食べる
4. 七味唐辛子で味付けして食べる
1. 残った出汁でうどんを煮たり雑炊にしても良い.

#### 補足

たぶん石川県民しか知らない. 本来は特製の味噌を使う. https://www.toriyasaimiso.jp/recipe

<!--chapter:end:01-easy.Rmd-->

# 激辛料理編 {#spicy}

主に四川料理とインド料理. 冗談抜きで辛いレシピばかりなので辛いのが苦手だと自負する人にはお薦めしない. 四川料理はだいたい「美食作家王剛」の動画を模倣したもの.

## 辣子鶏 (中, 四川)\index{辣子鶏}\index{辣子鸡|see{辣子鶏}}

唐辛子まみれの鶏の唐揚 (図\@ref(fig:laziji-finished)). 『中華一番!』にもあるように, 唐辛子は食べなくてもいい.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/laziji/finished} 

}

\caption{辣子鶏}(\#fig:laziji-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (2食分)

唐揚げの下処理に必要な材料

* 鶏肉 300 g
  + 若い雄鶏が良いらしい
* 塩 小さじ 1 杯
* 醤油 小さじ 1 杯
  * 元のレシピでは生抽
* 胡椒 少々
* 片栗粉 小さじ2杯
* 卵黄 1個分
* 料理酒 小さじ 1/2杯

唐揚げと炒める材料

* 唐辛子 90 g
    * 元のレシピでは 干七星, 小弾頭, 燈籠の三種を使うとあるが鷹の爪を使う前提にする
* 青花椒 10 g
    * 王剛のレシピはかなり多いと感じる. 多少すくなくても良い
* ニンニク
* 生姜
* ネギ 20 g
    * 元のレシピでは香葱だが, 日本では入手が難しいのでネギ類なら何でも可
* ピーナッツ 20 g
* 白ごま 適量
* 胡麻
* 揚げ物用のサラダ油 大量に
* ごま油 20 ml
* 花椒油 20 ml
    * これも苦手ならもっと少なくても良い
* 香醋 20 ml
    * 独特の香りと色が日本で一般的な穀物酢にはないので, 代用できるか怪しい
* 砂糖 少々
* うま味調味料 少々
    * シャンタンとか

### 道具

* 中華鍋
  * フライパンでもさほど難しくないと思われる
* 中華お玉
* ジャーレン
* ボウルといくつかの小皿

### 作り方

1. 鶏肉を通常の唐揚げよりかなり小さく, 一口サイズにぶつ切りにする
    * だいたい 1-2cm 四方くらい
    * 小さく切らないと高温かつ短時間で揚げることができない
2. (1) に塩, 胡椒, 料理酒 醤油, 卵黄を混ぜてよく揉む
3. 片栗粉を加え良く混ぜる
4. 10 ml の植物油を加えよく混ぜる
5. ニンニク, 生姜, ネギをみじん切りにする 
6. 唐辛子を適当な大きさに切る (図\@ref(fig:laziji-ingredients))
    * 辛いのが苦手ならこのとき種を全て捨てる, 種の有無で辛さはかなり変わる
    * ジャーレンをふるいの代わりにすると簡単に種と実を選り分けられる
7. 揚げ物用の油を 210度C まで加熱する (図\@ref(fig:laziji-fried))
    * 家庭用のコンロでは高温の維持が難しいので気休め
8. 鶏肉を1分程度揚げる
    * 家庭用のコンロではすぐ温度が下がるので実際は3-5分程度
    * 肉どうしがくっつかないようにほぐす
9. 一旦鶏肉を取り出し, 揚げカスを取り除く
10. 240度Cまで上げて, 再度1分程度揚げる
    * この温度も実際には維持が難しい
    * 表面をカリカリにするという意図
11. 鶏肉を取り出し, 油もよける
12. 油を 20ml 引き, 加熱する
13. ニンニク, 生姜, ネギ, 唐辛子, 花椒を入れて炒める
    * 唐辛子はかさばるので溢れたり, 焦げ付かせたりしないように注意 (図\@ref(fig:laziji-fry-wtih-chille))
14. 香りが立ってきたら鶏肉を入れ, 2分ほど炒める
    * じっくりと炒め, 辛味を鶏肉に移す
15. うま味調味料と砂糖を少々, ピーナッツと胡麻, そして残りの香り付け用の油と酢をふりかける
16. これもよくかき混ぜる

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/laziji/ingredients} 

}

\caption{揚げる直前の材料}(\#fig:laziji-ingredients)
\end{figure}

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/laziji/fried} 

}

\caption{揚げる量に対して十分な大きさの中華鍋を用意すること}(\#fig:laziji-fried)
\end{figure}

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/laziji/fry-with-chille} 

}

\caption{焦げ付かないよう絶えず鍋を振る}(\#fig:laziji-fry-wtih-chille)
\end{figure}

### 補足

鶏肉を小さく切る, ピーナッツを入れるといったやり方は宮保鶏丁のレシピを部分的に取り入れた王剛のアレンジだと思われる. ピーナッツや胡麻, 揚げ物用以外の油は主に香りを付けるためにある. エッセンシャルなのは下味を付けた一口サイズの唐揚げ, ネギ, 唐辛子, そして花椒である. なお食べ終わった後に大量に残る唐辛子は残念ながら捨てなければならない.

### 参考資料

* 美食作家王剛の動画 https://www.youtube.com/watch?v=NqHI1CJU-Rg
* 同, 火鍋の素を入れるなどアレンジしたバージョン https://www.youtube.com/watch?v=ZjnOTA65DPo
* 『メシ通』の記事, フライパンを使用 https://www.hotpepper.jp/mesitsu/entry/noriki-washiya/19-00032

## 魚香肉絲\index{魚香肉絲}/青椒肉絲\index{青椒肉絲} (中, 四川) {#rosu}

レシピが似ているので2つまとめて紹介する. 四川料理の中ではさほど辛くない. 魚香肉絲の「魚香」は「魚料理風の味付け」という程度の意味なので魚は使わない.


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (2食)

肉と下処理に必要な材料

* 豚肉 200-300g
* 塩・胡椒 少々
* 酒 小さじ1
* 醤油 小さじ 1/2
* 卵白 1個分
* 中華風スープ 少量
  * 湯に溶いたシャンタンでも何でも良い
* 片栗粉 小さじ1

魚香に必要な材料

* キクラゲ 40 g
* タケノコ 50 g
  * 本場では蜀漢笋を使うがなくてもよい
* 白ネギ 30 g
* 泡辣椒 30 g
* ニンニク 20g
* 生姜 20g
* 合わせ調味料
  * 塩 少々
  * うま味調味料 少々
  * 砂糖 大さじ1
  * 料理酒 小さじ2
  * 醤油 小さじ1
  * 醋 小さじ2
    * なければ酢で良い

青椒に必要な材料

* ピーマンやししとう, 青唐辛子など 適量
  * 日本の青唐辛子は辛いので少しだけにしておく
* 醤油 小さじ1
* 塩 少量
* うま味調味料 少量
* 油 適量


### 道具

* 例によってできれば中華鍋があるとよい

### 作り方

1. 豚肉の下処理
  1. 肉を細く切る
  2. 片栗粉を除く上記の調味料を加え, 2分間かき混ぜ続ける
  3. 片栗粉をさらに加え,よく混ぜる
1. 野菜の下処理
  1. キクラゲを細く切る (巻いてから輪切りにするとやりやすい)
  1. タケノコも細く切る
  1. ネギも細く切る
  1. 青椒の場合はピーマン等を細く切る
  1. ニンニク・生姜・泡辣椒をみじん切りにする
1. 合わせ調味料の作成
  1. 上記の材料を予め混ぜておく
1. 調理
    1. 熱湯に塩を少々入れ, タケノコとキクラゲを数分だけ下茹でする
    1. 鍋に油を多く入れ, 120度Cまで加熱してから火を止め, 余熱で肉を加熱する (油通し)
        * 表面が白くなる程度まで加熱すれば十分
    1. 鍋をきれいにし, ニンニク・生姜・泡辣椒を加えて弱火で炒める
    1. 香りが立ってきたら肉を入れて強火で炒める
    1. キクラゲとタケノコを加えて馴染むまで炒める
    1. 合わせ調味料も加えて炒める
    1. 最後にネギと少量の油を加えて炒める
        * ネギを焦がさない程度でやめる

青椒肉絲の場合は, 肉の油通しの後, 代わりに野菜を先に炒め, 火が通ってきたら肉と調味料を投入して炒める.

### 補足

ちょうどいい火加減はよくわからないので, フライパンを置いて料理する場合は注意.

王剛は切った肉を水でゆすぐと肉が柔らかくなるとしているが, 私は違いを感じられなかったので省略している.

### 参考資料

* 美食作家王剛の料理動画 (中国語) https://www.youtube.com/watch?v=TpR9-9CNxAY
* 同, 古いバージョン https://www.youtube.com/watch?v=68v5mGdE978
* 同, 青椒肉絲の料理動画 (中国語)  https://www.youtube.com/watch?v=wn0_7SMpw6o

## 水煮肉片 (中, 四川)\index{水煮肉片}

水煮という名に反して赤黒い液体で煮込まれた四川料理 (図\@ref(fig:finished-mizuni)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/mizuni/finished} 

}

\caption{水煮肉片}(\#fig:finished-mizuni)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (2食分)


下処理に必要な材料

* 豚ロース 300g 
  * バラやヒレでも可
* 塩 小さじ 1/2
* 胡椒 少々
* 片栗粉 小さじ1
* 醤油 小さじ1
* 料理酒 小さじ1
* 卵白 1個分
* 片栗粉 小さじ2
* 植物油 大さじ1

炒める材料

* もやし 100g
* レタス 数枚
* ニンニク 2-3個
* トッピング用ニンニク 2-3個
* 生姜 1かけ
* 泡辣椒 20 g
* 刀口辣椒 適量
* 乾燥唐辛子 10 g
* 青花椒 5 g
* 豆板醤 10 g
* 葉ニンニク   
  + なければニンニクの芽やネギ

### 作り方

1. 豚肉を薄切りにする
2. 塩小さじ1杯, 胡椒少々, 醤油小さじ1杯, 調理酒小さじ1杯を入れる
3. 2分間かき混ぜよくなじませる
4. 卵白に片栗粉を小さじ2杯加えてよく混ぜる
5. (4) を肉とよく混ぜる
4. レタス, 葉ニンニクを適当な大きさに切る
5. ニンニク, 生姜, 泡辣椒をみじん切りにする
6. 中華鍋に油をひき, 170度まで熱する
7. 乾燥唐辛子と青花椒を入れ爆する
    * 刀口辣椒と同様, 短時間だけ加熱し焦がさないようにする
8. 野菜を投入する
9. 塩を少々入れて味付けする
10. そのまま20秒程度爆する
    * 軽く火が通ってしんなりする程度で良い
11. 皿によそう
12. ニンニク, 生姜, 泡辣椒を鍋に入れる
13. 軽く炒めたら豆板醤もいれ, よく溶かす
14. 水を入れ, 強火にする
15. スープが煮え立ってきたら塩, 砂糖, うま味調味料を少々入れる
16. 水溶き片栗粉も入れてとろみをつける
17. 中火にし, とろみが取れないよう静かに肉を入れて煮る
18. 肉に火が通ったら皿に肉を盛り付け, スープも適量注ぐ
19. 最後に刀口辣椒とみじん切りにしたニンニクとネギをふりかける
    * ニンニクは刀口辣椒の後にかける
20. 210度に熱した油を上からかける

### 補足

正確にはレタスではなく油麦菜 (チシャ) を使う. また, 王剛のやり方では芹菜も使うが日本では入手しづらいので省略した.

### 参考資料

* 美食作家王剛の料理動画 https://www.youtube.com/watch?v=hyiGCNwCMxU

## 麻婆豆腐 (中, 四川)\index{麻婆豆腐}

国内メーカーのインスタント食品と比べると味の濃さも油っこさも段違いである.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/mabo/finished} 

}

\caption{麻婆豆腐}(\#fig:finished-mabo)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (2食分)

* 豆腐 1丁 (約 400 g)
  * 味がとても濃いのでバランスを取るため木綿が良い
* 牛挽き肉 50-100g
  * 脂身の多い部位が望ましい
  * 安い部位を買ってきて包丁で粗挽き肉にするのも一興
* ニンニク 4-5 欠片
* 生姜 20 g
* 豆板醤 大さじ1杯
* 泡辣椒 5-6本
* 豆豉 大さじ1杯
* 刀口辣椒 大さじ1杯 + 1食ごとに1杯
  + 刀口辣椒の作り方は別項参照
* 中華風スープまたは熱湯 300 ml
  * 私は口水鶏の茹で汁を良く使う
  * 怠け者向け: 豆腐の茹で汁を使う
* (オプション) 老抽
  * たまり醤油に近いもの
* 砂糖 大さじ1杯
* 片栗粉 大さじ2杯
* ラードまたはバター 30g
* ニンニクの芽
  * なければネギ
  * 元のレシピでは葉ニンニクを使う
* ネギ油 50 ml

### 道具

* 鍋
* 中華鍋
  * おそらくフライパンでも代用可
* 中華お玉
  * 200 ml くらいのものが使いやすい
* ジャーレン

### 作り方

1. ニンニク, 生姜, 泡辣椒はみじん切りにする
2. 鍋に油をはり, 大さじ1杯の塩を入れて軽く豆腐を茹でる
3. 中華鍋に油をひき, さらにラードまたはバターを溶かす
4. 肉を入れて強火でよく混ぜる
5. 肉に火が通ってきたらニンニクと生姜と泡辣椒, そして豆板醤を入れる
6. 全体が赤くなるまでかき混ぜつつ炒める
7. 豆豉と刀口辣椒を入れ, 少し炒めたらすぐに中華スープまたは熱湯を入れる
    * 水で味が薄まるので熱湯の場合はシャンタンやウェイパーなど中華風うま味調味料で味を補強すると良い
8. 中火にして砂糖と老抽を入れる
9. さいの目切りにした豆腐を入れる
10. 3-4分ふつふつと沸き立つ程度に加熱する
11. 弱火にし, 水に溶いた片栗粉を3回に分けて入れる
    * 50 ml の水に対して, 小さじ半, 小さじ1, 小さじ1.5 の順で分けて入れる
    * 豆腐の容器を捨てずにここで使うと楽
12. 最後にネギ油をふりかける
13. 盛り付ける際には刻んだニンニクの芽と刀口辣椒をトッピングする

### 補足

王剛のレシピでは肉は50gとしているが, 何品も作るの労力を考え一品で腹持ちを良くするため多めにしている. 

老抽はたまり醤油に近い製法の, 中国の醤油である.  比較的マイルドな味であり, ここではおもに色を濃くするのが目的のため, 省いても味は大きく変化しない. 

体感での辛さは主に豆板醤と (青花椒を含んだ) 刀口辣椒の量に依存する. 例えば市販のインスタント食品『陳麻婆豆腐』などは花椒が多いため辛く感じるが, このレシピならばむしろ味の濃さが印象付けられ相対的に辛さを感じにくいだろう.

あまり鍋を振る必要がないので, フライパンでもさほど支障がないと思われる. 


### 参考資料

* 美食作家王剛による料理動画 https://www.youtube.com/watch?v=USoC8AqirVA
* 『美味四川』の記事「[永久保存版！本場の四川で食べる麻婆豆腐の作り方](https://sisen-recipe.com/sichuan/2016/03/1.html)」
* 『メシ通』の記事「[「麻婆豆腐の作り方」を四川料理のスゴイ人に教わったら、目からウロコが3回落ちた](https://www.hotpepper.jp/mesitsu/entry/noriki-washiya/18-00431)」

## 回鍋肉 (中, 四川) \index{回鍋肉}

これも本場式の辛いレシピを紹介する.

TODO: 画像


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* ニンニク 3欠片
* 生姜
* 長ネギ 1本
  * 葉ニンニクがあればつかう. ニンニクの芽でもよい
* 豆豉 大さじ1
  * 永川豆豉がよいらしい
* 豆板醤 大さじ1
  * 郫県豆板醤がよいらしい
* 甜麺醤 小さじ1
* 醤油 小さじ1
* 泡辣椒 適量
* 砂糖 適量
* うま味調味料 適量
* 酢 適量
* 豚バラ肉 300 g
  * 塊のものを用意する
* 下処理に必要な薬味
  * 生姜 1欠片
  * ネギ 適量
  * 料理酒 30cc

### 道具

中華鍋でやったほうがそれっぽい

### 作り方

1. 鍋に水を張り, 薬味を加えて豚肉を20分下茹でする
1. 肉を取り出し, 冷水で冷やす
1. 肉を薄切りにする
    * 肉の繊維にそって切るとやりやすい
1. ネギを半分または4分割してぶつ切りにする
    * ニンニクの芽ならたたいて繊維をほぐし, ぶつ切りにする
    * 葉ニンニクなら単にぶつ切りするだけで良い
1. 生姜と泡辣椒を刻む
1. 甜麺醤と醤油を混ぜておく (合わせ調味料)
1. 鍋に油を引き, 最大火力で肉を炒める
    * これは余分な脂を落とす意図がある
1. 肉が焼けて丸まってきたら, 火からおろし豆板醤と豆豉を入れる
1. 肉に全体的に色が移るまでよく混ぜながら弱火で炒める
1. 刻んだ生姜, 泡辣椒を加え再度強火で炒める
1. 酢, 合わせ調味料, 砂糖やうま味調味料で味を調整する
1. ニンニクの芽を入れて最大火力で炒める

### 補足

最初の下茹でで十分に火が通っており, また薄切りにしているため, 2度目に加熱する際は焦がさないよう火加減に注意して行うとよい. 特に最後の工程は太いネギやニンニクの芽を使うと火が通る前に肉が焦げてしまうため, 切り方にも注意する.

王剛の動画では皮付きの豚肉を扱っているが, 日本ではあまり売ってないのでその処理は省略した.

### 参考資料

* 王剛の料理動画
  * その1 https://www.youtube.com/watch?v=v72yoabCHXA
  * その2 https://www.youtube.com/watch?v=DIMwUp9UqB4

## 酸湯肥牛 (中, 四川) \index{酸湯肥牛}

花椒の麻味と漬け物から染み出した酸味が強いので暑い日によいかもしれない

TODO: 画像


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 泡酸菜や泡酸萝卜
  * なければ高菜漬けや野沢菜漬など乳酸発酵による漬け物 (糠臭くないものや麹発酵してない漬け物ならだいたい可).
* 牛切り落とし
  * 薄く脂身の多い牛肉ならなんでも可. 安いものでいい.
* えのき
* 泡辣椒
* ニンニク
* 生姜
  * できれば泡子姜がいいが, 日本で売ってるのを見たことがない.
* 料理酒
* 酢
* 青唐辛子
* 花椒


### 作り方

1. ニンニクと生姜と青唐辛子をみじん切りにする
1. えのきの石づきを切り取り, 適当にほぐす
1. 湯を沸かし, 水と油を少々入れてえのきを湯通しする
1. 同じ湯で肉も湯通しする
1. フライパンにラードをひき, ニンニク, 生姜, 漬け物を炒める
1. 先ほどの湯を適量加える
    * 味が薄いと感じたらうま味調味料を足す
1. 漬け物を取り除く
1. 肉を入れて煮る
1. 料理酒と酢を少々入れる
1. 泡酸菜を煮込んでだしをとる
1. 泡酸菜を除き, えのきをいれて茹でる
1. 肉を茹でる
1. 皿に盛り付け, 上から青唐辛子や花椒をふりかける
1. 少々の油を強く熱して青唐辛子にかける

### 補足

この料理では漬け物をだしを取るためだけに使う. もったいないと思ったら食べても構わない.

私はこの料理を都内の料理店「[天府舫](http://www.tenfufan.com/)」で知った. ここ提供されるものは花椒の実がまるごと浮かんでおり, 非常に辛かった.

### 参考資料

* 『美味四川』の記事「[暑い日に食べたい酸っぱ辛い四川料理「酸湯肥牛」の作り方](https://sisen-recipe.com/sichuan/2018/07/2358.html)」
* 『美食台』の動画 (中国語) https://www.youtube.com/watch?v=8SlM9nacW0g

## 口水鶏 (中, 四川)\index{口水鶏}\index{口水雞|see{口水鶏}}\index{口水鸡|see{口水鶏}}

いわゆる「よだれ鶏」\index{よだれ鶏|see{口水鶏}}日本で出回っているものはちょっと辛い棒々鶏 (棒々鶏も本場のものは辛い) みたいなのが多いが, 本場では赤黒いソースをかけた見るからに辛そうな料理である (図\@ref(fig:yodare-finished)). 

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/yodare/finished} 

}

\caption{モモ肉の口水鶏}(\#fig:yodare-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (2人前)

鶏の下処理に必要な材料

* 鶏もも肉 2枚
  * 骨付きのほうが見た目がかっこいいが食べやすさを考えると骨抜きが楽
* 生姜 1かけ
* 料理酒 50 cc
* ネギ 1/2本

ソースに必要な材料

* ニンニク 20 g
* 生姜 10 g
* 唐辛子 10 g
* 刀口辣椒 大さじ1杯
* 香辣紅油 50 cc
* 醤油 少々
* 塩 少々
* ネギまたはコリアンダーの葉

### 道具

鶏を1羽丸ごと茹でる場合は, 十分に大きな寸胴鍋を用意しないと均等に加熱できない(図\@ref(fig:yodare-smaller-pot))

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/yodare/smaller} 

}

\caption{鍋が小さいと完全に入り切らない}(\#fig:yodare-smaller-pot)
\end{figure}

### 作り方

鶏の下処理

1. 鍋で湯を沸かす
2. 臭い取りのため生姜, ネギ, 料理酒を入れる
3. 鶏肉を入れ, 茹でる
    * 沸騰してから10分くらい?
4. 肉を取り出し, 粗熱をとる
    * 冷水で冷ましても良い

ソースを作る

1. ニンニク, 生姜, 唐辛子をみじん切りにする, もしくはすりおろす
2. 熱した香辣紅油をかける
3. 茹で汁の一部, 醤油を加え, 塩で味を調える
  * オイスターソースを隠し味にするのも良い
  
盛り付け

1. 鶏肉を適当な大きさに切り分ける
2. 皿に盛り付け, 上からソースをかける
3. お好みでネギやコリアンダーの葉をふりかける

### 補足

生の唐辛子の入手が難しいなら, 泡辣椒でもよい.

ソースは別の作り方もある. これは以下の『简单 家常 美味！』の動画で紹介されたものに基づいている. 必要な調味料の種類が多いが, 調理自体はほぼ混ぜるだけなのでこっちのほうが簡単である. この場合は以下を混ぜて作る.

* サラダ油 60 ml
* ニンニク 20 g
* 唐辛子または青唐辛子, ししとう 10 g
* 万能ネギ 少々
* ピーナッツ 10 g
* 醤油 大さじ 3
* 辣油 大さじ 3
* ごま油 大さじ 1
* 花椒油 小さじ 1
* 蚝油 (オイスターソース) 小さじ 1

1. ニンニク, ネギ, 唐辛子, ピーナッツを細かく刻む
2. 油を130度くらいまで加熱する
3. (1) に油を注ぐ
    * これでニンニクが加熱される
    * 熱すぎると唐辛子が焦げるので注意
4. 残りの材料をよく混ぜる


### 参考資料

* 鶏を〆る方法含んだ王剛の料理動画 (中国語, 英語字幕あり) https://www.youtube.com/watch?v=99nspRiav-A

* 王剛の香辣红油の作成動画 (中国語, 英語字幕あり) https://www.youtube.com/watch?v=6wlDqKt2ADo

* 『简单 家常 美味！』の動画 https://www.youtube.com/watch?v=laB1e6fWbmA

## (TODO) インドカレー (印)

TODO


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

<!--chapter:end:02-spicy.Rmd-->

# 炭水化物編 {#ch-carbon}

ジャガイモや小麦粉を大量に使う料理.

## ブランボラーク (捷: Bramboráky)\index{ブランボラーク}\index{bramboráky|see{ブランボラーク}}

チェコの伝統的なファストフード. ジャガイモのかき揚げ.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/bramborak/finished} 

}

\caption{ブランボラーク}(\#fig:bramborak-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (5-6枚)

* ジャガイモ
* 小麦粉
* 卵
* ニンニク
* (オプション) マジョラムまたはパセリ
* (オプション) キャラウェイシード
* 塩胡椒
* ラード 100g 程度
  * なければバターやサラダ油

### 道具

* ジャガイモをすりおろすスライサー
* ボウル
* お玉
* 大きめのフライパン
* 揚げ終わった後で油を取る手段
  * 新聞紙でもいい
* フライ返しと菜箸, あるいはフォークなどがあるとよい

### 作り方

1. ジャガイモの皮をむいて細かくすりおろす
    * 粒度は好み次第. 細切れにするとかき揚げのようになる
    * 軽く手で抑えて水気を切ると良い
2. 小麦粉, 卵, みじん切りにしたニンニク, スパイス類を加えてよく混ぜる(図\@ref(fig:bramborak-dough))
3. フライパンを中火にかけ, ラードまたは油を多めにひく
    * 生地が半分浸かるくらいは必要
    * 天ぷらのように丸ごと浸かる必要はない
4. お好み焼きの容量で生地をお玉ですくって垂らし, 軽く押して平たくする
5. 片面が固まって焼き目が付いたら油ハネに注意してひっくり返す
    * フライ返しと菜箸をそれぞれ両手に持ってやると丁寧に返せる
6. 反対側も同じように焼けたら取り出し, 油を切る
7. やけどしないように食べる

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/bramborak/dough} 

}

\caption{揚げる直前}(\#fig:bramborak-dough)
\end{figure}

### 補足

チェコ語でジャガイモのことをブランボル (brambor) というので, ブランボラークという名前はストレートにジャガイモ料理であることを示唆している. サワークリームを添えて食べることもある. ラトケ (latke) やウクライナのデルニー (деруни), ベラルーシのドラニキ (драники) など類似料理がいくつかある. デルニーは生地にもサワークリームやすり下ろした玉ねぎを混ぜる.


### 参考資料

* 動画 (英語音声) https://www.youtube.com/watch?v=pTInrevl54Q
* Václav Frič による料理動画 (チェコ語音声) https://www.youtube.com/watch?v=lUGyggN9ygY

## クネドリーク (捷: Knedlíky) \index{クネドリーク}\index{knedlíky|see{クネドリーク}}

ドイツのゼンメルクネーデル\index{ゼンメルクネーデル|see{クネドリーク}}\index{semmelknödel|see{ゼンメルクネーデル}}と関連があるが, チェコのクネドリークはジャガイモがメインだったりパンくずを整形したり作り方がいろいろある. ここでは最も簡単と思われる, 発酵もさせず, 主にジャガイモを使うクネドリークを紹介する.


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* ジャガイモ (男爵いもが良い) 3-4 個
* 小麦粉 50 cc
* 卵 1個
* 塩 少々


### 道具

ラップだけだとほどけることがあるのでラップの上から形状維持しやすいアルミホイルで包むと良い.

* ラップ
* アルミホイル

### 作り方

* じゃがいもの皮をむき, 下茹でする
  * 弱火で40分程度かかるだろう
* ポテトピューレのように念入りに潰す
* 粗熱が取れるまで待つ
* 小麦粉と卵と塩を加え, よく混ぜてこねる
* 整形して, ラップで包み, さらにアルミホイルで包む
    * よくあるパターンは, (1) 細長く (2) 丸く (3) ボート型
* 10分ほど茹でる
    * 適切な時間は当然ながら大きさに依存する

### 補足

オーストリアや南ドイツ, あるいはチェコ国内のカルロヴィ・ヴァリではパンを細かくちぎったものを混ぜることもあるらしい.

グラーシュ (セクション\@ref(gulas)) の付け合せに, あるいは vepřo knedlo zelo を作ってビールと一緒に食べるとよい.

### 参考資料

* http://www.czechfriend.jp/event/040826.htm
* "Kuchyně Lidlu" による標準的なクネドリークの料理動画 (チェコ語)  https://www.youtube.com/watch?v=rgouyUynrlA
* "Kuchyně Lidlu" による「パンくずのクネドリーク」の料理動画 (チェコ語) https://www.youtube.com/watch?v=4_KnXyIiZds
* "Recepty.cz" による「カルロヴィ・ヴァリ風」クネドリーク (チェコ語)  https://www.recepty.cz/recept/karlovarsky-knedlik-140268
*  "Kuchyně Lidlu" のカルロヴィ・ヴァリ風の作成動画 (チェコ語)  https://www.youtube.com/watch?v=SIee8PWWSbI

## ピエロギ (波: Pierogi)\index{ピエロギ}\index{pierogi|see{ピエロギ}}

餃子と似ているがひき肉を入れることはあまりない. 最もポピュラーな Pierogi Ruskie と  Pierogi kapustą i grzybami (ザワークラウトとキノコのピエロギ) の例を紹介する.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/pierogi/finished} 

}

\caption{ピエロギ}(\#fig:finished-pierogi)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (20個程度?)

* 小麦粉 600cc
* 塩 小さじ1/2
* 水 150cc
* 室温に戻した卵 1 個


詰め物 (Ruskie の場合)

* ジャガイモ 2-3 個
* チーズ  100g
  * リコッタかカッテージチーズが良い
* 玉ねぎ 1/2 個
* 塩 小さじ1/2
* 胡椒

詰め物 (キノコとキャベツの場合)

* ザワークラウト 適量
* キノコ 適量
* 玉ねぎ 1/2 個

* (オプション) トッピング・付け合せ
  * 玉ねぎ
  * バター
  * サワークリーム

### 道具

* 大きめのボウル
* 延し台

### 作り方

1. 生地の材料をよく混ぜてこねる
    * こねすぎてもいけない. 50回程度が良いらしい
1. 布かラップを被せ10分寝かせる
1. 直径7cm程度の薄い円形に延ばす
1. 大さじ1杯程度の詰め物を乗せて包む
    * だいたい餃子と同じ要領で良い
    * 縁にフォークを押し付けても良い
1. 3分煮る
    * 煮たピエロギを並べるとき, トレーに油を塗っておくと良い
1. さらにこの後, バターで軽く焼き目を付けても良い
1. サワークリームや時間を掛けて炒めた玉ねぎを添えて食べる

Ruskie の場合の詰め物は, マッシュポテトにリコッタチーズ・みじん切りにして炒めた玉ねぎ・塩小さじ半を混ぜる
キャベツとキノコの場合は, 材料を (ザワークラウトを特に念入りに) みじん切りにした上で炒め, 塩胡椒で味を調える.

### 補足

果物やジャムを入れることもある. スモモジャム (ポヴィドル) がポピュラー. 17世紀のポーランドの料理本 "Compendium Ferculorum" には現存する最も古いピエロギのレシピが記載されており, 当時から甘い物や肉など様々な具材を入れていたことが分かっている. ロシアやウクライナにもピローク (пирог) というパイ料理があり, 名称は似ているが作り方は異なる.

### 参考資料

* The Polish Chef による Ruskie の作り方 https://www.youtube.com/watch?v=GQ0GiTKzu38
* 日本語のレシピ https://jpya.or.jp/ja/2018/12/pierogi/
* @czerniecki1682Compendium pp.86-87 (ほとんど読めない)

## (予定) ペリメニ (露: Пельмени)\index{ペリメニ}\index{пельмени|see{ペリメニ}}

ゲニスとワイリは「怠け者のための料理」と呼んでいるが, 皮を作るのが少し面倒なので手抜きリストには入れなかった.

TODO: 画像


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 小麦粉
* 水
* 卵
* 塩
* 牛または豚の挽き肉

### 作り方

バター

1. 茹でたらバターを入れたボウルに投入し, 余熱でバターを溶かす
1. ボウルをよく振ってバターを絡める
1. 例によってパセリやディルやサワークリームなどを添えて食べる.


### 補足

餃子より一回り小さい. 市販の餃子の皮は大きすぎるので向かない

* 茹でる直前の状態で, くっつかないように小分けして冷凍しておけば好きな時に食べられる
* ロシアでは家庭でペリメニを一気に大量に作るため, ハニカム構造の型が流通している
  + 型抜きで生地を分けるなら, ウォッカ用のショットグラスがちょうどいい大きさになる.
  + 参考: https://www.youtube.com/watch?v=_o9934oSYqQ

### 参考資料

* Коллекция Рецептов の料理動画 https://www.youtube.com/watch?v=N9aS8jBaTS8 
* @OginoNumano2017 p. 54
* @boumei Ch. 27, および付録のサラファン式レシピ

## ヒンカリ (草: ხინკალი)\index{ヒンカリ}\index{ხინკალი|see{ヒンカリ}}

小籠包に似たジョージア料理. 餃子や小籠包より一回り大きく, 皮が厚い.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/khinkali/finished} 

}

\caption{ヒンカリ}(\#fig:khinkali-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

生地

皮が薄い市販の餃子の皮は向かない.

* 小麦粉
* 水
* (オプション) 卵
  + 使っても使わなくてもいい
  + 使う場合は水を少し減らす
* 塩

以下は詰め物

* ひき肉 300 g
  + 牛, 鶏, 羊, 豚などなんでもいい
  + 合い挽きでも可
* 玉ねぎ 1個
* ニンニク 3-4個
* 唐辛子 1本
* コリアンダーの葉
  + 種でも可
* ブイヨン または水
* 塩胡椒

### 道具

* ボウル
* のし台
* 鍋


### 作り方

1. ニンニク, 玉ねぎ, 唐辛子, コリアンダーの葉を刻む
2. 挽き肉と混ぜる
    * 伝統的なやり方にならって野菜と肉の塊と一緒に斧や重い剣で叩いてもよい (図\@ref(fig:khinkali-minced))
3. 塩胡椒を加えてよく混ぜる
4. 水を加えてよく混ぜる
5. 生地を延ばして切り分ける
    * 包み方のため, きれいに円形にならなくともなんとかなる
6. 大さじ1-1.5杯程度を包む (図\@ref(fig:khinkali-pre-boil), \@ref(fig:khinkali-wrapping))
    * 包み方は動画等参照
7. 鍋に湯を沸かし, 塩を大さじ1杯入れる
8. ヒンカリを入れ茹でる
    * 張り付かないようにかき混ぜて水流を作ると良い
    * 沸騰しすぎると良くない, 少し泡立つ程度で良い
9. 数分で浮かんでくるので取りだす (図\@ref(fig:khinkali-boiling))

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/khinkali/minced} 

}

\caption{野菜とともにミンチにする}(\#fig:khinkali-minced)
\end{figure}

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/khinkali/pre-boil} 

}

\caption{茹でる直前}(\#fig:khinkali-pre-boil)
\end{figure}

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/khinkali/wrapping} 

}

\caption{包んでいる途中}(\#fig:khinkali-wrapping)
\end{figure}

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/khinkali/boiling} 

}

\caption{ローレルは必須ではない}(\#fig:khinkali-boiling)
\end{figure}

### 補足

ヘタ部分をつまんで食べる. ヘタ部分は食べない. これもタレはないので詰め物にしっかり味付けする. 胡椒などを軽く振ることはある.

現地人の動画では延ばしてから型抜きで切り分けているが, 台所がせまい場合は餃子のように生地を細長くしてちぎってから延ばすやり方でも良い.

### 参考資料

* 伝統的な道具を使った料理法 (ジョージア語音声) https://www.youtube.com/watch?v=YRNOKkblZzc
* 日本在住のロシア人による料理動画 (日本語音声) https://www.youtube.com/watch?v=-v2sk3QxVDc
* ジョージア在住の日本人による解説動画, 肉ではなくジャガイモ入り (日本語, ロシア語音声) https://www.youtube.com/watch?v=Z7HJ1f-Qp0


## (予定) ポンチキ



\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

## ラグマン (ウイグル: `{`{=latex}ﻟﻪﯕﻤﻪﻦ`}`{=latex})\index{うどん!ラグマン}

ウイグル族をはじめ中央アジア各所で見られる料理. 中国語の「拉麺」の由来と考えられる. 日本のラーメンと違い, 本来の語義通り手延べ麺であることが特徴. スープに漬けるものもあれば, 「混ぜそば」「焼きそば」風のものもあるが, 今回は簡単な混ぜそば風のものにする.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/laghman/finished} 

}

\caption{ラグマン}(\#fig:laghman-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★★★ }\\
\bottomrule
\end{tabular}

### 材料

麺に必要なもの

卵, 水, 小麦粉 400g

小麦粉と水は 1:4 くらい?

20分寝かせる

1.5 - 2mm に伸ばす
麺は切る派と伸ばしに伸ばして1本の長い麺にする派がいる

* 小麦粉 400 g
* 水 小麦粉に対して 1/4 程度
  * 卵で補っても良い?
* 塩 ひとつまみ
* 植物油

具に必要なもの

* 羊肉または鶏肉
  * 牛肉でも良い
* 玉ねぎ
* 人参
* トマト
* パプリカ
* ニンニク
* 生姜
* 羊脂または植物油
* 塩胡椒
* クミンシード

茄子やネギやいんげんを入れても良い

### 道具

* のし台
* 大きめの皿, またはフライパン

### 作り方

手延べ麺の作成

1. 小麦粉と水, 塩を混ぜてよくこねる
1. ふきんをかぶせて1時間ほど寝かせる
1. 棒状に延ばす
    * 延ばす際は打ち粉ではなく油を塗ってくっつかないようにすること
    * この時点では太くても良い
    * いくつかに分割してやると場所を取らない
1. 表面に油を塗る
1. もうすこし細長く延ばし, 渦巻き状にして皿に置く (図\@ref(fig:laghman-spiral))
1. 乾かないように表面に油を塗り, 1時間ほど寝かせる
1. 先端から引っ張ってさらに少しづつ細く延ばす
1. うどんみたいに両手に巻き付けて振って延ばす
1. コップに水をいれておく
1. 熱湯で茹でる, 激しく茹だったらコップ半分だけ室温に戻した水を入れる
1. もう一度茹だったら麺を取り出し, 冷水で締める
  * もう一度水を入れて, 三度目の沸騰で取りだすやり方もあるらしい

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/laghman/spiral} 

}

\caption{作成中の麺}(\#fig:laghman-spiral)
\end{figure}

具の作成 (麺を寝かせている間に作るとよいだろう)

1. 肉と野菜を小さく切る
1. フライパンに油をひき, 炒める
1. 塩胡椒とクミンシードで味付けする

最後に麺の上に具を盛り付ける

### 補足

ロシアではヴォク (中国語の鑊が由来か) と言う名前で野菜と鶏肉と太い麺を炒め, アメリカのドラマでよく見かける箱に入れたファストフードが頻繁に見られた. ラグマンと関係があるのかは不明

### 参考資料

* 小泉武夫『食マガジン』での紹介 https://koizumipress.com/archives/6314
* 中央アジア雑貨輸入販売業者『シルクロードキャラバン』によるレシピ『ウズベク料理 ラグメンのレシピ』 http://sr-caravan.com/?mode=f10
* "UYGHUR HAND-PULLED NOODLES | LAGHMAN" (英語) https://www.youtube.com/watch?v=XhrxYD4Zahg
* "How to make Lagman Noodles Homemade Hand-pulled Noodle Uyghur Laghman" (英語) https://www.youtube.com/watch?v=AiMGPbMcAw0
* ロシア国内で知られているラグマンは手延ではないことが多く, またジャガイモやディルを使うなどロシア的ローカライズがなされている
    * 「ウズベキスタン風」ラグマン (ロシア語) https://www.youtube.com/watch?v=4QdaJoJpt5s
    * Всегда Вкусно! による「ウズベキスタン風」ラグマン  (ロシア語)  https://www.youtube.com/watch?v=pF0MiqYUxLw


## プロフ/パラフ (露: Плов/月: Palov) \index{плов|see{プロフ}} \index{palo|see{プロフ}}

オシュ (Osh) とも. おそらくピラフと起源を同じにする, ウズベキスタン周辺の中央アジア起源の料理だが, ソ連時代にロシアに普及した. 真面目に作ろうとすると, 材料と器具の調達の点で炒飯やピラフより大変である. ウズベキスタン国内でもタシケント式, サマルカンド式, フェルガナ式, ブハラ式など地域によって差異がある. 東北地方の芋煮会めいてコミュニティで共同して作る習慣があるので一度に大量に作る前提のレシピになっている. (現地にはプロフを作るための専用施設もある) ロシアではスタローバヤの定番料理のため, 大衆向けの安価な食事というイメージらしい.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/palov/finished} 

}

\caption{プロフとアチク=チュチュク}(\#fig:finished-palov)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 羊肉 200g
  + イスラム教徒が大半なので豚は使わない
* 人参 1本
  * 現地では黄色い人参がよく使われる. 沖縄の島にんじん的な?
* 玉ねぎ 1個
* ニンニク
  + 皮も含めて丸ごと
* クミンシード 小さじ1
* 塩胡椒 適量
* 米 2合
  * ジャポニカ米は使われないようだが気にしない
* 水 通常の炊飯と同じ量

以上は多くの地域で共通するもの. その他, 地域によって添えるものが変わってくるオプション

* 干しぶどう
* ひよこ豆
* 鶏やウズラのゆで卵
* 鶏肉や羊肉, 馬肉ソーセージなど複数種類の肉を入れることもある

### 道具

* カザン (大型で丸底の鉄鍋)
  – なければ中華鍋や底の深い平底鍋でもできなくはない
* 蓋になる大きめのボウル
  – 現地の人がやってるように皿を載せるだけで密閉できなくともわりとなんとかなる

### 作り方


1. 鍋に洋脂を溶かす
    * 肉から脂身を切り取って使う
    * なければ植物油
2. 千切りにした玉ねぎと人参を入れ, 弱火でじっくり炒める
3. 玉ねぎと人参はよく火が通り, 水分が抜けるまで炒める
    * 焦げないように130度程度を保つと良い
4. 手頃な大きさに切った肉を入れる
5. ある程度火が通ったら, 米と水を入れる
    * 米は事前に研がなくてもよい
6. 米は水平になるように均し, 水位が米と同じくらいの高さになるまで待つ
8. 唐辛子, ニンニク, 荒く挽いたクミンシード, そして塩を入れる
    * クミンシードは手のひらこすり合わせるようにしてすりつぶすことができる
    * 肌が弱い人はやらないほうがいいが, 慣れると意外と簡単に手で挽くことができる
9. ボウルで蓋をする場合, 米を覆えるように鍋の中央に盛り上げる
    * 底のほうにある野菜や肉は混ぜ返さないようにする
10. 水分が抜けやすいように長い菜箸かフォークで数カ所に穴を開ける
11. 蓋をして20分程度待つ
12. 火を止めて10分程度蒸らす
13. 鍋底をさらうようによくかき混ぜてから盛り付ける
14. オプションでゆで卵や干しブドウを添える

### 補足

米が丸底鍋の底に触れていると焦げやすいため, 下敷きになるように野菜は十分に入れる必要がある.


余裕があれば輪切りにした玉ねぎとトマトにコリアンダーと塩胡椒を振ったサラダ (アチク=チュチュク) を作って一緒に食べる

材料を入れる順番はかなり差異がある.

### 参考資料

* @OginoNumano2017 p. 83
* ウズベク風プロフ (ロシア語) https://www.youtube.com/watch?v=J-D3eZgos3I
* フェルガナ式プロフ (ロシア語) https://www.youtube.com/watch?v=LDSO3W88QvU
* サマルカンド式 (ロシア語) https://www.youtube.com/watch?v=6gnzLZdpxQs
* タシュケント式 (ロシア語) https://www.youtube.com/watch?v=oYqqHNdoGMk
* 炊飯器で作る方法 (日本語) https://www.youtube.com/watch?v=ZVTa4OQ0atk
* アゼルバイジャン人による料理動画 https://www.youtube.com/watch?v=oAOYV9Y6MVc
* 現地の「プロフセンター」の風景
* e-food.jp の簡略化したレシピ (日本語) https://e-food.jp/recipe/asia/samalkandplov/


## メドゥ・ワダ (印, タミル/セイロン)

南インドの豆のドーナツ. 映画『バーフバリ』で一瞬ドーナツみたいな料理が皿に山盛りになってるシーンがあったので気になって調べたら見つけた.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/medu-vada/finished} 

}

\caption{メドゥ・ワダ}(\#fig:medu-vada-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
\bottomrule
\end{tabular}

### 材料

* ウラド・ダル (ケツルアズキ)
* カレーリーフ
* 唐辛子
* 油
* 塩

### 道具

ミキサーがあったほうがよい

### 作り方

1. ウラド・ダルを水に浸けて柔らかくする
1. 水気を切って細かく潰す
    * ミキサーを使ったほうがいい
1. 冷蔵庫で2時間寝かせる
1. 塩, カレーリーフ, 少量の唐辛子を混ぜる
1. 小さく丸め, 指で穴を空けてドーナツ状にする
1. 油で揚げる

### 補足

ミキサーがないと困難. 粘りが出ずにすぐ崩れる. 小麦粉等をつなぎにするしかない.

### 参考資料

* https://www.youtube.com/watch?v=Zjm9fQBBHiM

<!--chapter:end:03-carbon.Rmd-->

# 肉編 {#meet}

## (TODO) ミティティとキョフテ


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 牛豚合い挽き肉
  * もちろん, キョフテには豚肉を使わない
* ベーキングパウダー
* 玉ねぎ
* 塩胡椒
* クミンシード
* パプリカ

### 道具

* オーブントースターまたは魚焼きグリル

## プルドポーク (北米: pulled pork) \index{プルドポーク}\index{pulled pork|see{プルドポーク}}

北米のバーベキュー料理の一種. じっくり火を通してほぐした豚の肩肉.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/pulled-pork/finished} 

}

\caption{プルドポークバーガー}(\#fig:pulled-pork-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 豚ショルダー
  + 赤身肉が適している
  + 脂身の多いバラ肉などは適していない
* 砂糖
  * できればブラウンシュガー
* 塩
* ガーリックパウダー
* 唐辛子の粉末
* パプリカパウダー
* マスタード
* バーベキューソース

### 道具

* オーブン (オーブントースター可)
* 燻製器

### 作り方

1. 塩, 砂糖, ガーリックパウダー, 唐辛子の粉末, パプリカパウダーを良く混ぜる
1. 肉の表面の水分を良く拭き取る
1. 肉によく塗る
1. 6時間温燻または熱燻する
    * 表面が黒く固くなるまで
    * 器具がなければ残りの材料を塗って鍋で柔らかくなるまで煮込む
1. バーベキューソースとマスタードをたっぷり塗り, アルミホイルで包む
1. さらに20分ほど加熱する
1. フォークでよくほぐす
1. ハンバーガーなどにして食べる

### 補足

燻製にする場合, 生のニンニクなど水分のあるものは肉に塗るべきではない. 燻製にしないなら気にしなくても良い.

### 参考資料

## ヴェプショ=クネドロ=ゼロ (捷: Vepřo-Knedlo-Zelo)\index{ヴェプショ=クネドロ=ゼロ}\index{vepřo-knedlo-zelo|see{ヴェプショ=クネドロ=ゼロ}}

「豚肉・クネドリーク・キャベツ」という意味になる. ローストポーク, クネドリーク, 甘酸っぱく炒めたザワークラウトを並べたチェコの居酒屋の定番メニュー.

TODO: 画像


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (2-3食)

* 豚肉 300g
  * ショルダー, モモなど
* キャラウェイシード 適量
* タイム 適量
* 玉ねぎ 1個
* 塩・胡椒
* 砂糖
* ニンニク
* ザワークラウト
* クネドリーク \@ref(#knedliky) 参照 数切れ
* ラード 適量
  * なければバターや植物油
* (オプション) 白ワインまたはワインビネガーまたは 酢 適量

### 道具

* できればロースト用のオーブン
  * なければ圧力鍋等で

### 作り方

1. ローストポークを作る
    1. 豚肉に塩胡椒を振り, 塩胡椒とすりおろしたニンニクで下味を付ける
    2. みじん切りにした玉ねぎ1/2・水・タイム・キャラウェイシード・ラードを加えてオーブンでローストする
        * 代替案: 圧力鍋で加熱する
        * 単に豚肉のステーキにする
1. ザワークラウトのペーストを作る
    1. ザワークラウトを細かく切る
    1. 鍋にラードを引き, 玉ねぎ1/2を弱火で炒める
    1. 色がついたらザワークラウトと汁・キャラウェイシード・ベイリーフを入れて炒める
    1. しんなりしてきたら水を加え, 蓋をして20分煮込む
    1. 砂糖, あるいは好みでワインビネガーや酢も使って甘酸っぱく調える
1. ローストポークの肉汁に水と小麦粉を適量補いとろみをつけてソースにする
1. ローストポークを切り分け, クネドリークとザワークラウトとソースと一緒に盛り付ける

### 参考資料

* @faktor2007Traditional p.65
* "Recepty bez brepty" の動画 https://www.youtube.com/watch?v=rXudmMKbInQ
* "Czechcookbook" の動画 https://www.youtube.com/watch?v=tkCtjcHuJ-s

## 「スペイン風」ミートボール/ルーラーデン (捷: španělský ptáček/独: Rouladen)\index{スペイン風ミートボール}\index{španělský ptáček|see{スペイン風ミートボール}}\index{ルーラーデン|see{スペイン風ミートボール}}\index{rouladen|see{ルーラーデン}}

内部にゆで卵やソーセージ, ピクルスを詰め込んだ大きめのミートボール.「スペイン風」とあるが, チェコの料理である.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/spanelsky-ptacek/finished} 

}

\caption{「スペイン風」ミートボール, クネドリークと米を添えて}(\#fig:spanelsky-ptacek-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
\bottomrule
\end{tabular}

### 材料

* 牛スネ肉
  * もしくは他の柔らかい部位
  * なるべく大きい塊肉がよい
* ソーセージ
* ピクルス
* ゆで卵
* ベーコン
* マスタード
* 玉ねぎ
* ラードまたはバター
* 小麦粉

### 道具

* 料理用のタコ糸
  * または爪楊枝や竹串

### 作り方

1. 牛肉を薄く切り, 叩いて延ばす
1. 牛肉に少量の塩胡椒とマスタードを塗って下味をつける
1. 玉ねぎ, ゆで卵, ソーセージ, ピクルスを小さく切る
1. 肉で上記を包み, タコ糸等で固定する
1. 外側に再度少量のマスタードを塗る
1. 鍋を熱してラードを溶かし, みじん切りにした50gのベーコンと玉ねぎ1/2を中火で炒める
1. 火が通って色が変わってきたら, ミートボールを入れ表面を焼く
1. 鍋に温めたブイヨンを入れる. 肉が浸かる位の量が必要
1. 鍋に蓋をして2時間ほど煮る (圧力鍋を使って短縮しても良い)
1. 肉を取り出し, 茹で汁は固形物を濾し取ってから小麦粉でとろみを付け, ソースにする
1. 皿にミートボールとソースを盛り付ける
1. クネドリークまたは米と合わせて食べる

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/spanelsky-ptacek/tied} 

}

\caption{タコ糸, マスタードを塗る}(\#fig:spanelsky-ptacek-tied)
\end{figure}

### 補足

ヨーロッパのマスタードは全般的に日本の練からしよりだいぶ辛味がマイルドなので, どちらを使うかで使用量に注意する.

柔らかい部位の肉を使う場合, 茹で時間は少ないほうが良いかもしれない.

ルーラーデンは類似のドイツ料理である. こちらも薄く延ばした肉で具材を巻いて焼くという点が同じだが, 使われる材料は異なる.「小鳥」と訳したらチェコ人に間違えを指摘された. ptáček は辞書には小鳥とあるが, ミートボールというニュアンスもあるので, ここは素直に「ミートボール」と訳す.

この料理の起源は神聖ローマ皇帝ルドルフ2世時代にあると言われている. 皇母マリアはスペイン出身であり, その影響でスペイン人のシェフがおり, その影響でスペイン風の料理として考案された. 一応スペインにも肉を巻いて焼く料理があるらしい. チェコ料理ではあまり米が使われることがないが, このミートボールにはしばしば米が添えられる. 地中海を想起される食材なのかもしれない.

### 参考資料

* @faktor2007Traditional p.54
* "video-recepty.com" の動画 https://www.youtube.com/watch?v=T2hfkBYQjkc
* Wikipedia の記事 https://cs.wikipedia.org/w/index.php?title=%C5%A0pan%C4%9Blsk%C3%BD_pt%C3%A1%C4%8Dek&oldid=19363197

## ゴウォンプキ (波: Gołąbki) \index{ゴウォンプキ}\index{gołąbki|see{ゴウォンプキ}}

ポーランドのロールキャベツ. 日本のと似ているが, 米を多く混ぜる, トマトソースと一緒に煮込む, という特徴がある. ロシアの `\aruby{голубцы}{ガルプツィ}`{=latex} \index{голубцы|see{ゴウォンプキ}} もほぼ同じ.
\index{ガルプツィ|see{ゴウォンプキ}}

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/golabki/finished} 

}

\caption{ゴウォンプキ}(\#fig:finished-golabki)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
\bottomrule
\end{tabular}


### 材料 (2-3食分)

* キャベツ1玉
* ひき肉 600g
* 玉ねぎ半分-1個
* 米 お椀1杯~大盛り程度
  + できればインディカ米
* パン
* 牛乳
* 塩
* 卵
* パプリカパウダー
* トマトピューレ

### 作り方

1. 米を炊く
2. キャベツの芯をくり抜き, 葉が柔らかくなるまで丸ごと茹でる
    * 別に手でちぎってもよい
3. 玉ねぎを炒める
4. 玉ねぎ, 米, ひき肉, 卵, 牛乳ひたしたパンをまぜる
5. 塩胡椒, パプリカパウダー, パセリ粉末, トマトピューレを混ぜる
    * 塩胡椒の代わりにコンソメ粉末とかでもいい
6. ロールキャベツと同様に肉を巻く.
7. 鍋に詰め込んで熱湯を注ぎ, コンソメ粉末, オールスパイスとローレルの葉を加えて蒸す
8. 十分に蒸したら水を切る
9. 茹で汁は捨てずに小麦粉とトマトピューレ, そして刻んだディルを加えて加熱し, ソースを作る
10. ゴウォンプキの入った鍋にソースをかける

### 参考資料

* ポーランド在住日本人による解説付きの動画 (日本語) https://www.youtube.com/watch?v=GYV1bVHyglQ
* Dorotki による料理動画 (ポーランド語, 英語字幕あり) https://www.youtube.com/watch?v=LFc-PO0fu7A
* @OginoNumano2017 pp. 40-41

## キムチチム (韓: 김치찜)

キムチチムの調理自体は簡単だが, よく発酵したキムチの入手または作成が大変である. キムチの自作方法は別項参照.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/kimchichim/finished} 

}

\caption{キムチチム}(\#fig:kimchichim-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★★ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (4-5食分)

* 豚バラ肉ブロック 1 kg
  * 肉の選び方は補足の部分参照
* 白菜キムチ 1.3 kg (白菜1/4株相当)
  * 発酵が進み酸味が強くなったものが良い
* ニンニク 3-4かけら
* 生姜
* 玉ねぎ
* 長ねぎ
* 唐辛子の粉 大さじ 2-3杯
  * キムチ用のさほど辛くないものを使う
  * カイエンヌペッパーのような特別に辛い種類のものは適さない
  * 辛いのが苦手ならば一部をパプリカパウダーに置き換えてもよい
* (オプション) 生の唐辛子
* (オプション) 隠し味
  * テンジャン (甜麺醤などでも良いかもしれない?)
  * 砂糖
  * 酢
  * 醤油またはエクチョッなどキムチに使う調味料

### 作り方

1. 豚肉を取り分けやすい大きさに切る
1. 野菜を適当な大きさに切る
2. 鍋底にキムチをしく
3. その上に肉とネギ, 玉ねぎ, ニンニク, 生姜, 生の唐辛子をふりかける
4. 肉が隠れる程度まで水を入れる (図\@ref(fig:kimchichim-pot))
4. 唐辛子の粉をかける
    * これは水で色や味が薄まることに対する補強である
5. 軽く沸き立つまで加熱する
6. ある程度煮立ったらオプションの調味料で味を調整する
    * 酸味が足りなかったら酢を入れる
    * 味が薄かったら醤油とかを入れる
    * 発酵しすぎて匂いが強ければ砂糖を入れる
7. 肉が十分に柔らかくなるまで煮込み続ける
    * 1時間半程度
	* 圧力鍋を使って短縮しても良い
    * だいたい角煮と同じ要領で良い

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/kimchichim/pot} 

}

\caption{煮込む直前}(\#fig:kimchichim-pot)
\end{figure}

### 補足

激辛料理の章に掲載しようか迷ったが, 唐辛子をよほど入れない限りそこまで辛くはならないと思われる. 多くのレシピでは豚バラ肉を指定し, 実際豚バラ肉は柔らかくするのが簡単で, キムチチムは基本的には発酵したキムチの酸味と豚肉の脂身の組み合わせを楽しむ料理だが, ものによっては脂身が多すぎることもある. ペク・ジョンウォンがすすめるようにショルダーを使ったり, 脂身の少ない肉にラードを継ぎ足すのも良いかもしれない. 国内で流通しているキムチの多くは長期熟成を想定していないようなので, 衛生面の問題は自己責任で.

### 参考資料

* ペク・ジョンウォンの料理動画 https://www.youtube.com/watch?v=RVfSeUZ8XkY

## キエフ風カツレツ (露: котлета по-киевски/котлета де-валяй) \index{キエフ風カツレツ}\index{котлета по-киевски|see{キエフ風カツレツ}}\index{котлета де-валяй|see{キエフ風カツレツ}}

古典的な котлета де-валяй はいわゆるメンチカツ的なレシピだったらしいが, ここで紹介するのはソ連時代の一般的な
作り方で, 以前ブログで言及したものと同じ

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/kotlet-kiev/finished} 

}

\caption{キエフ風カツレツとポテトピューレ}(\#fig:finished-kotlet-kiev)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★★★ }\\
\bottomrule
\end{tabular}

材料 (4人前)

* 鶏丸ごと 1羽
  * ローストチキン用に頭や内臓を除いたものが良い
  * 使うのは胸・ささみ・手羽元にあたる部分のみ
* バター 100 g
* イタリアンパセリ
* ディルの葉
* レモンの絞り汁 少量
* 塩胡椒
* 小麦粉 100 ml
* 卵 2個
* 牛乳 50 ml
* パン粉 100 g
  * できれば細かいもの
* 揚げ物用の油
* (オプション) ニンニク
* (オプション) ポテトピューレまたはフライドポテト

### 道具

* 肉を叩く棒
  * トゲのあるものは良くない, ワインボトルとかでもいい
* 揚げ物ができる鍋

### 作り方

1. バターを室温で柔らかくする
1. 刻んだパセリとディル, レモンの絞り汁と小さじ半分程度の塩を混ぜる
1. 袋かラップに包み, 棒状に形成して冷蔵庫に入れて冷やし固める.
1. 肉を切り出す (詳細は後述)
1. 胸肉を半分にする. なるべく均等な厚さになるように
1. 胸肉とささみをそれぞれ, ラップを被せて叩いて薄く延ばす
    * まっすぐ打ち下ろすのではなく, やや中央から外側に力を掛けて均等に丸く広がるように
    * ささみは多少破れても問題ない
1. ささみを半分に切る
1. バターを取り出し, 適当な大きさに切る
1. バターをささみで包む
1. さらに胸肉で包み, ボート型になるよう押さえる
1. 小麦粉, 卵, パン粉で衣を付ける
1. 卵とパン粉は二度付ける
1. 油で揚げる
1. 好みでついでにフライドポテトも作る
1. さらに表面をサクサクにしたい場合, オーブンで5-10分加熱する
1. ポテトピューレかフライドポテトと一緒に皿に盛り付ける


1. 鶏の腹に包丁を入れ皮を切る
1. 手でひっぱって皮をはぎ, さらに腹の正面を走っている軟骨 (竜骨突起) に沿って包丁を入れる
1. 一般的な方法ではここでささみ (小胸筋) を分離するが, 今回は切り離さずそのまま軟骨にそって肉を切り離す
1. 手羽側は肩の関節で繋がっているため, 先に尻側から切って最後に肩を取り外すのがやりやすい
1. モモ肉と胸肉は皮でつながっているだけなので皮を剥がせば下側は難なく外れる
1. 手羽の周りだけで繋がっている状態になったら, 包丁で関節を探り当ててそこから切断する
1. 無理に骨を切断しようとすると鋭利な破片ができて危険であるので, 関節を外すようにする
1. あとは皮で繋がってるだけなので手で外せる
1. 切り離した胸肉に手羽元と, ひだのようなささみが繋がっていれば成功
1. これを両胸で行う

### 補足

中に入っているのがバターなので, 時間が経つと漏れ出してしまう. 揚げたてを食べるのが良い.

余った部分はシュクメルリとか口水鶏とか辣子鶏とかに使うとよいだろう.


### 参考資料

* Коллекция Рецептов によるソ連時代の作り方 (ロシア語, 英語字幕あり) https://www.youtube.com/watch?v=C-nt0yqz-0g
* 上記を参考にしたブログ記事 https://under-identified.hatenablog.com/entry/2020/12/30/233933
* より簡単な作り方の紹介 (日本語) https://www.youtube.com/watch?v=MKhA7T9nzbE
* もっと簡単な作り方の紹介 https://note.com/dogirls_ua/n/n72220579a52b

## ドルマの三姉妹 (亜塞: Üç-Bacı Dolması)

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/dolma/dolma-finished} 

}

\caption{ドルマの三姉妹}(\#fig:dolma-finished)
\end{figure}

アゼルバイジャン料理のユーチューブチャンネルで見つけた. トルコやイランにもあるかもしれない.


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (3食分)

* 挽き肉 400 - 500 g
  * 羊肉または鶏肉, あるいは牛肉
* ピーマン 適量
* トマト 3個
* 茄子 3-4本
* 植物油
* 玉ねぎ 1個
* 塩 小さじ2杯
* 胡椒 少々
* パプリカパウダー 小さじ 1杯
* ターメリック 小さじ 1杯
* ニンニク 2-3欠片
* コリアンダーの葉 1束
* 水 50 cc
* (オプション) マッシュルーム

### 道具

* フライパンと蓋
  * 野菜の大きさによっては底の深い鍋を使うべき

### 作り方

1. 茄子はへたを切り取り, 切れ目を入れて塩を刷り込む
2. ピーマンは上のほうに切り込みを入れて芯と種を取りだす
3. トマトも同様にする. おそらくスプーンを使うと簡単
    * 中身は捨てずに後で使う
4. 茄子を水でゆすいで塩分をとる
5. フライパンに油をひき, 茄子を柔らかくなるまで軽く素揚げする
    * 人によってはピーマンとトマトも同様にすることもある
    * 茹でるケースもある
6. 胡椒, パプリカパウダー, ターメリック, ニンニクを混ぜてよくすりつぶす
    * なければカレー粉とかフメリ・スネリとかでもいいんじゃない
7. フライパンで玉ねぎを炒める
8. 挽き肉と上記のスパイスを混ぜる
    * コリアンダーの葉を混ぜても良い
9. さらにトマトの中身も合わせて炒める
10. 炒めた肉を野菜に詰める
11. フライパンに並べ, 少量の水を加え, 蓋をして野菜が柔らかくなるまで蒸し焼きにする
12. (オプション) 炒めたマッシュルームや刻んだコリアンダーの葉を添える

### 補足

おそらく最も難しいのは羊の挽き肉を入手または作成することだろう. それ以外は原始的な調理器具でも対処できる.  多くの場合, トマトとピーマンを事前に加熱する必要はない. 特にトマトはもろく崩れやすくなるため注意 (図\@ref(fig:dolma-failed)). 荻野のドルマのレシピで紹介されているように, 米を入れたり, 茄子も中をくり抜いたりする動画も見られた.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/dolma/dolma-failed} 

}

\caption{加熱のし過ぎでトマトが崩れる}(\#fig:dolma-failed)
\end{figure}

### 参考文献

* (たぶんアゼリー語, ロシア語, 英語字幕あり) https://www.youtube.com/watch?v=GUfGmjOgCZE
* (たぶんアゼリー語) https://www.youtube.com/watch?v=bohT4pGV7rc
* (たぶんアゼリー語) https://www.youtube.com/watch?v=eNj9yJ0_1NI
* 荻野恭子『ピーマンとなすの肉詰め煮～ドルマ～』キューピー3分クッキング https://www.ntv.co.jp/3min/recipe/20070901/


## 豚足のアスピック (捷: Huspenina) \index{アスピック}\index{huspenina|see{アスピック}}\index{にこごり@煮凝り|see{アスピック}}

要するに煮凝り (図\@ref(fig:huspenina-finished)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/huspenina/finished} 

}

\caption{フスペニナ}(\#fig:huspenina-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (大勢で食べられる)

* 豚足 4本
  * 血抜きや体毛の下処理はしてあるものとする
* 水 2l 程度
* 玉ねぎ
* 人参
* パセリ根
* セロリ
  * あればセルリアックを使う
* ニンニク
* ゆで卵
* 塩・胡椒
* オールスパイス
* ベイリーフ

### 道具

* Huspenina を固める型
  * ババロア用の型など, 耐熱性があり底の深い容器ならなんでもよい
* 大きめの鍋, 2つあると良い

### 作り方

1. 豚足をよく水で洗い汚れを落とす
1. 鍋に豚足を入れ, 完全に浸かるまで十分に水を注ぐ
1. しばらく下茹でしアク取りをする
1. アクが取れたら玉ねぎ, 塩胡椒, オールスパイス, ベイリーフを入れる
1. 弱火で1時間45分茹で続ける
1. 皮を剥いた人参とパセリ根とセロリを入れ, 15分茹でる
    * 小さく切っても良い
1. 豚足と人参とパセリ根を取りだす
1. 粗熱が取れてから, 豚足の骨から皮と肉を外す
    * ひづめ周辺の小さい骨を残さないように注意
1. 皮と肉をミンチにする. 柔らかいので包丁でも可
1. 取り出した根菜を小さく角切りにする
1. 肉と根菜を新しい鍋に入れ, さらに茹で汁を濾したものを注ぐ
1. 軽く湯だつまで加熱する
1. 型に切ったゆで卵と上記を注ぎ, 冷蔵庫で一晩冷やす

### 補足

元のレシピでは豚の頭も使用しているが, 入手が難しかったため使用しなかった. 赤身肉の少なさが気になるなら適当に肉を継ぎ足してもよいだろう.

豚足4本でできる Huspenina はかなり多く, またこの水の量ではだいぶ濃い色になる. もっと水が多くても問題ないだろう.

おそらくは, 豚を解体し, 肉は塩漬けに, 血と腸はソーセージにして残った頭と足も食べるために考案された料理だろう. このような豚の屠殺を zabíjačka といい, 現在でもチェコの田舎では中世の農村さながらの豚の解体祭りをするらしい. 煮凝りにせず, 単に柔らかくなるまで塩水で煮ただけで食べる ovar という料理もある[@faktor2007Traditional].

周辺各国にも類似した料理が存在する. ロシア (Холодец, студень),
ベラルーシ,
ウクライナ (холодець),
ポーランドなどでも類似した料理が存在する. これらは豚の頭や足を使うこと, 卵や野菜を入れる点で共通している.

### 参考資料

* Random Innkeeper の動画 https://www.youtube.com/watch?v=7Eegww-atzU
* @faktor2007Traditional, p. 58


## ハルチョー(+ ゴーミ) (草: ხარჩო, 露: харчо)

ジョージアのスープ. どちらかというと材料調達の難易度が高い (図\@ref(fig:kharcho-finished)). @boumei で紹介されているレシピは豊富な種類の果物やスパイスを使用しているが, ここではもう少し簡単に, かつジョージアでよく見られる鶏肉を使用したレシピを提案する

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/kharcho/finished} 

}

\caption{羊肉のハルチョーとゴーミ}(\#fig:kharcho-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★★ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 鶏肉 600 g
* セロリの茎葉 1本
* 月桂樹の葉 1枚
* クルミ 200g
* ニンニク 3欠片
* コリアンダーの葉
* トマトまたはトマトピューレ
* アンズまたはザクロ, なければ柑橘類など酸味のある果物
* フメリ・スネリ (後述)

フメリ・スネリはロシア雑貨を扱っている店などで買えるが, ジョージアのものとは違うかもしれない. 今回は次のような簡易バージョンを提案する.

* クレイジーソルト
* バジルの葉
* コリアンダーの葉
* サフラン
* マジョラム
* パプリカ
* 胡椒
* 鷹の爪
* カイエンヌパウダー


### 作り方


1. キンザ, ディル, ニンニク, セロリ, ネギ を細かく刻む
1. 肉を茹でる
1. アクをあらかた除いたら, セロリとベイリーフを入れる
    1. ニンジンや玉ねぎを入れても良い
1. そのまま1時間ほど弱火で茹でてブイヨンを作る
1. 固形物を取り除く. 肉は食べやすい大きさに切って残す
1. ソース(アディカ)を作る
    1. クルミを細かく砕く
    1. フメリ・スネリまたは上記のハーブ・スパイスを細かく刻んで入れる
    1. ペースト状になる程度の量に調整してブイヨンの一部を入れる.
1. 鍋にバターを溶かし, 肉と玉ねぎを炒める
1. タマネギをみじん切りにして油で炒める
1. トマトピューレかホールトマトを混ぜてさらに炒める
1. アディカを入れてしばらく煮込む
1. 最後に果汁をふりかける


### 補足

ロシアでも広く知られているが, ジョージア本来のもととは多少異なるようだ. ロシアでは牛肉, ジョージアでは鶏肉を使うことが多い. ロシアではあまりクルミをあまり入れず赤っぽくなるが, ジョージアでは砕いたクルミを大量に入れて茶色っぽくなる. また, ロシアのスープの常として, ディルが入れられることもある. しかしながらジョージア国内でも地域によっても差があるようにみえる.

さらに大きな違いとして, ジョージアでは `\aruby{ღომი}{ゴーミ}`{=latex} というトウモロコシ粉のポリッジにチーズを乗せた料理と一緒に食べることが多い.

図\@ref(fig:kharcho-finished)は粟で同様のものが作れないか試した際のものである. 粟に対して3倍程度の水を加え, 1時間ほど浸してから弱火で加熱しながらかき混ぜる. 途中で小麦粉を足す. 最後にスライスしたチーズを乗せる.

沸騰して跳ねることがあるため暑い日でも服を着て調理すべきである.

### 参考資料

ジョージア語はほとんどわからないので見様見真似である

* Apolines cuisine の動画, くるみのペーストに近い見た目 (ジョージア語音声) https://www.youtube.com/watch?v=DeLvJ7V-30k
* Arkadi Kalantarov の動画 (ジョージア語字幕) https://www.youtube.com/watch?v=kcV9GgPqcoU
* 1TV (ジョージアのテレビ局) の紹介動画, 後半は「ハルチョー風パスタ」? (ジョージア語音声) https://www.youtube.com/watch?v=kcV9GgPqcoU
* Спасибо Шеф の動画 (ロシア語) https://www.youtube.com/watch?v=mRybqZc_gZk
* @boumei 10章
* CNN の記事 https://edition.cnn.com/travel/article/georgia-best-food-tbilisi/index.html
* 「ゴーミ」の料理動画 (英語) https://www.youtube.com/watch?v=76jFKW23X_Y

<!--chapter:end:04-meat.Rmd-->

# 夏の料理編 {#summer}

暑い季節に食べやすいものを紹介する

## 鮎の塩焼き (日) \index{鮎の塩焼き}

鮎といえば6月だがいまは天然物が貴重でスーパーで売ってるのはだいたい養殖物なのであまり関係ない気もする.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/ayu/finished} 

}

\caption{鮎の塩焼き}(\#fig:ayu-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 鮎 1尾
* 塩
* 割り箸 1本
  * 竹串があれば使って良い
* (オプション) すだち

### 道具

魚焼きグリル

### 作り方

1. 尻ビレ付近の肛門の手前を指で押し, 残ったフンを押し出す
2. 鮎を冷水で洗い, 表面のぬめりを取る
3. 表面の水を良く拭き取る
4. 塩を振る
5. ヒレには多めに塩をなすりつける
6. 串を打つ
    * 割り箸の場合はカッターナイフや包丁で削って尖らせる
    * のぼり串/踊り串に挑戦するのも一興
7. グリルで焼く

### 補足

尾ヒレを取り, 全身をかるく箸で押してほぐしてからえらの手前でちぎると背骨が抜けやすい.

## ウハー (露: Уха)\index{ウハー}\index{уха|see{ウハー}} {#ukha}

> 言うまでもなく, ウハーとは儀式である.
>
> ::: {.flushright data-latex=""}
> --- A. ゲニス & P. ワイリ
> :::

川魚を使ったスープ. @boumei によると, 川で釣った魚をその場で食べるためのレシピとのこと. 基本的に彼らの記述に則したレシピ (図\@ref(fig:ykha-finished)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/ukha/finished} 

}

\caption{鮭のウハー}(\#fig:ykha-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 川魚    
  * 鮭, タラ (日本での入手方法は不明), ニジマス, チョウザメなど
  * チョウザメのウハーが最も上等とされる
* 人参
* ジャガイモ
* 塩胡椒
* パセリの葉
* ローレルの葉
* 万能ねぎ
* (オプション) 煮干し
* (オプション) サフラン
* (オプション) ウォッカ
  * 隠し味に
* (オプション) ディルの葉

### 作り方

1. 湯を沸かし, 煮干しで出汁をとる (なければ湯を沸かすだけ)
1. 出汁から煮干しの残りカスを濾し取り, 捨てる
1. 出汁を弱火にかけ, みじん切りにした玉ねぎ, セロリ,  パセリ, ローレル, 塩胡椒を加える
1. 20-30分ほど煮て香りを引き出す
1. 細切れにした人参とジャガイモを入れて5-6分加熱する
1. 魚の切り身を入れ, 数分煮る. あればウォッカを少し入れる
1. 火を止める
1. カップにサフランを1つまみ入れ, 煮えた出汁を1すくいかけ, これを鍋に入れる.
1. 刻んだディルの葉などを添えて食べる
    * 飲むためのウォッカも用意する

### 補足

玉ねぎを入れる人も多いが, @boumei ウハーは透き通ったスープであることが大切なので, スープが濁る玉ねぎは使うなと主張する. また, タラゴンやバジルなど, ハーブは種類が多ければ多いほどよいとも書いている. 私は試したことがないが, ヴィクトリアショップではロシア製のウハー用ミックススパイスを扱っている^[https://victoriashop.jp/collections/%E3%82%B9%E3%83%91%E3%82%A4%E3%82%B9%E9%A1%9E/products/%E3%82%A6%E3%83%8F%E3%83%BC-%E3%83%AD%E3%82%B7%E3%82%A2%E9%A2%A8%E9%AD%9A%E3%81%AE%E3%82%B9%E3%83%BC%E3%83%97-%E3%83%9F%E3%83%83%E3%82%AF%E3%82%B9%E3%82%B9%E3%83%91%E3%82%A4%E3%82%B9].

### 参考資料

* @boumei Ch. 20

## シャルティバルシュチャイ (立: Šaltibarščiai) \index{シャルティバルシュチャイ}\index{Šaltibarščiai|see{シャルティバルシュチャイ}}

ボルシチに似ているが肉を使わない, 冷たい料理.「液体のサラダ」とでもいうべき料理(図\@ref(fig:saltibarsciai-finished))

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/saltibarsciai/finished} 

}

\caption{ふかし芋入りのシャルティバルシュチャイ}(\#fig:saltibarsciai-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (3-4食)

* ビーツ 1 個
* ケフィア 400 g
  * ヨーグルトやサワークリームも可
* 卵 1個
* 塩胡椒 少々
* キュウリ 1本
* ディルの葉
* 万能ねぎ
* (オプション) ジャガイモ 1個


### 作り方

1. ビーツをすりおろす
2. キュウリを細かく切る
3. ビーツ, キュウリ, ケフィアを良く混ぜ, 塩で味を調える
4. ゆで卵, ふかし芋, 刻んだディルの葉や万能ねぎを添える

### 補足

リトアニア語で「冷たいボルシチ」という意味だが, ロシアではあまり食べられていないようだ^[ただしロシアにもボトヴィニヤやオクローシカといった多様な冷製スープのレシピが存在するので, そのうちどれかと関係があるかもしれない.]. ポーランドの chłodnik\index{chłodni|see{シャルティバルシュチャイ}}, ベラルーシの халаднік\index{халаднік|see{シャルティバルシュチャイ}}, ウクライナの холодник \index{холодник|see{シャルティバルシュチャイ}}もほぼ同じ料理.

### 参考資料

* @OginoNumano2017 p.14
* (たぶんリトアニア語, 英語字幕) https://www.youtube.com/watch?v=sL8Q05qt56c

## ニジマスのバターグリル (捷, pečený pstruh na másle) \index{pečený pstruh na másle|see{ニジマスのバターグリル}}

図\@ref(fig:trout-finished) のようにレモンの薄切りを乗せることが多い.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/trout/finished} 

}

\caption{ザワークラウトは不要だった}(\#fig:trout-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* ニジマス 2 匹
* レモン
* バター
* キャラウェイシード
* パセリ

### 道具

オーブンがあると良いが, なければフライパンや魚焼きグリルで代用する

### 作り方

1. ニジマスの腹を開き, ワタを取り, 腹の中を水で洗う
1. 水気を拭き取る
1. 酢を軽くふりかける
1. 小さく切ったバターを腹に詰める
1. 軽く塩をして10分寝かせる
1. キャラウェイシードもふりかける
1. 表面に小麦粉をまぶす
1. オーブンで焼く
1. 輪切りにしたレモンやパセリを乗せて盛り付ける

### 補足

茹でたジャガイモとともに食べることが多い.

マヨネーズやディジョンマスタードをかけることも多い

ニンニクの欠片を入れてもよいかもしれない.

### 参考資料

* @faktor2007Traditional p.24
* https://www.youtube.com/watch?v=RNjsLl5w5-E

<!--chapter:end:05-summer.Rmd-->

# 冬の料理編 {#winter}

基本的に熱いうちに食べるとうまいスープや煮込み料理.

## グラーシュ (捷: Guláš) {#gulas}

もとはハンガリー料理のグヤーシュ guyás だが, これが元になったチェコ料理のほうが本家より有名になっている. 現地でも様々な作り方があるため, このレシピが唯一の正統なものではないことに注意する (どのラーメンが正しいか論争するようなもの).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/gulas/finished} 

}

\caption{牛肉のグラーシュ}(\#fig:finished-gulas)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 牛肉 200 g
  * スネ肉など煮込みに適した部位がよい
* ラードまたはバター
* パプリカパウダー 大さじ2
* 玉ねぎ 大1個
* トマトピューレ
* 塩胡椒 適量
* ニンニク 数欠片
* キャラウェイシード 小さじ1
* マジョラム 1つまみ
* 小麦粉

### 作り方

1. 鍋を熱してラードを溶かす
1. 玉ねぎをみじん切りにして焦がさないよう弱火で炒める
1. 色がついてきたらパプリカパウダーを入れてよくかき混ぜる
1. 肉を入れて炒める
1. トマトピューレを入れる
1. 水を加える
1. 塩胡椒で味付けする
1. 小麦粉でとろみをつける
1. みじん切りまたはすりおろしたニンニクとキャラウェイシードを入れる
1. パセリや薄く輪切りにした玉ねぎを添えても良い

### 補足

定番の隠し味として, ビールを入れる, あるいは肉をビールにつけて柔らかくするというものがある. 

広く普及している料理なので作り方のバリエーションが多い.

### 参考資料

* @faktor2007Traditional p.50
* https://www.toprecepty.cz/recept/4007-klasicky-hospodsky-gulas-vidensky/

## ボルシチ (宇/露: Борщ)\index{ボルシチ}\index{Борщ|see{ボルシチ}}

> 「ボルジチ」じゃあない「ボルシチ」だ. 何度も言ってるだろう...
> 
> ::: {.flushright data-latex=""}
> --- アルカージィ&ボリス=ストルガツキィ
> :::

主にウクライナ風のレシピを紹介するが, ロシア風に作るヒントも残しておく. 広く普及してるのでいろいろなバリエーションはあるが, 典型的な特徴は

1. ウクライナでは豚肉を使うことが多い

2. ロシアでは牛肉を使うことが多い

である. 脂っこさと煮込んだ野菜の甘味が重要なのはおそらく両国共通. ここではクロポテンコのレシピに近いものを紹介する (図\@ref(fig:finished-borscht)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/borscht/finished} 

}

\caption{スペアリブのボルシチ}(\#fig:finished-borscht)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料 (5-6食分)

分量は目安. 好みでよい.

* 肉 バラ肉やスペアリブなど脂の多い部位 500 g

* 水 2 l

* ビーツ 大きめの 1個
    
    * 缶詰や真空パックの水煮ではなく, 生のものが最適
* 人参 1 - 2本
* セロリ 1本
    * セロリアックが良いらしいが日本で売ってるのを見たことがないので茎と葉で良い.
* 玉ねぎ 大 1個
* ジャガイモ 1-2個
* 塩胡椒 適量
* トマトピューレ 50g程度
* (オプション) 香り付けのスパイス・ハーブ
    * ローリエの葉
    * オールスパイス
* (オプション) 薬味
* イタリアンパセリ
* ディルの葉
* 万能ねぎ
* サワークリーム

### 道具

* 鍋
* フライパン
* 野菜をすりおろす器具

### 作り方

まず肉と野菜を煮込んでブイヨンを作ってから, 改めて肉と野菜を入れ直して作る.

1. ブイヨン用に玉ねぎ半分, 両端を切った人参を用意する (皮はむかなくてもよい)
    * 玉ねぎは煮崩れしないように爪楊枝で留めておくと楽
2. フライパンで肉に焼き目をつける. フライパンは洗わずにとっておく
    * クロポテンコによるとアク取りをサボるためのテクニックであり, 必須ではない
3. 鍋に火をかけ水を注ぎ, 肉, 半分に切った玉ねぎ, 人参, セロリを1時間ほど煮込む
4. 必要に応じてアク取りをする
5. 玉ねぎ, セロリ, 人参, 肉を取りだす, 肉以外は不要
6. (オプション) 肉を食べやすい大きさに切って鍋に戻す
    * どうせ柔らかくなるので食べやすくない大きさにしても良い
7. ジャガイモ, パプリカ, 人参を食べやすい大きさに切り, 玉ねぎもみじん切りにする
    * 今度は皮をむく
8. ジャガイモを鍋に入れる
    * ジャガイモの大きさによっては茹で時間の間を開ける
9. フライパンに油を引き, 上記を炒める
    * ビーツも一緒に炒めることが多いが, 熱しすぎると色が薄くなるので注意
10. 塩胡椒と砂糖を加える
11. 炒めた野菜とローリエの葉を鍋に移す
12. トマトピューレとみじん切りにしたニンニクを鍋に入れる
13. ビーツも皮をむいてすりおろし, 鍋に入れる
    * ビーツの表面は固く筋っぽいので表皮だけでなく黒ずんだ部分も切り取ると良い
    * すり下ろし器があると楽
14. キャベツを千切りにして鍋に入れる
    * これもクロポテンコの好みによるもので, もっと早く入れても良い
15. 味見しつつ塩胡椒で味を調える
16. スープ皿などに盛り付け, 上から薬味をふりかける

### 補足

黒パンやサーロ, ウォッカ/ホリルカとともに食べるとよい.

ロシア風に作る場合も大筋で同じだが, 肉は牛肉を使うこと. また, キドニービーンズやザワークラウトを入れることもある.  材料はだいたい共通しているが, どれくらい大きく切るかは個人差がかなりあるので正しい方法というものはおそらく存在しない. 

トマトとビーツの色は全く違うので, ボルシチはトマトで色を付けると思ってはならない (トマトを入れない派閥も存在する). さらにビーツの色素は熱分解するため長時間煮込むと色あせてしまうため, 炒めに時間をかけすぎないように注意. 缶詰や真空パックのビーツも加熱処理済みであるためどうしても色彩に劣ってしまう. なるべく生のビーツを入手したい.

### 参考資料

* クロポテンコの料理動画 (ウクライナ語, 日本語字幕あり) https://www.youtube.com/watch?v=LgjumwEC7zo
* クロポテンコの「ヘトマン風ボルシチ」レシピ (ウクライナ語, ロシア語) https://klopotenko.com/getmanskij-borshh/

* “Всегда Вкусно!” の料理動画 (ロシア語) https://www.youtube.com/watch?v=_-9nH4zFThs
* 『ナスチャンネル』のロシア式の料理動画 (日本語音声) https://www.youtube.com/watch?v=5mXOepWrzGc
* @OginoNumano2017 pp. 36-37

## シチー (露: Щи)

ボルシチより古い歴史があると言われるロシア料理. 以前公開したスライドと同じ.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/schi/finished} 

}

\caption{シチーその他}(\#fig:schi-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 牛肉
  * 煮込み料理に適した部位が良い
* 玉ねぎ
* 人参
* セロリ
* 塩漬けキノコ
* ザワークラウト
* ジャガイモ
* ニンニク
* 塩胡椒
* (オプション) 付け合せ
  * キノコの塩漬け
  * サワークリーム
  * ディルの葉
  * パセリ
  * 青ネギ

### 道具

* 鍋
* できれば土鍋も欲しい

### 作り方

1. ボルシチと同様にブイヨンを作る
    1. 牛肉を下茹でし, アクを取る
    1. アクをあらかた取ったら, 玉ねぎとニンジンとセロリを入れる
    1. 牛骨があれば使ってもよい
1. 軽く絞ったザワークラウトと, それが浸かるくらいの水を入れる
1. バターを小さじ2杯入れ, 弱火で10分ほど蒸す
1. 上記とみじん切りにした玉ねぎとニンジン, そしてジャガイモを鍋に入れてよく煮る
1. 塩胡椒で味を調える
    * ザワークラウトの塩気があるためおそらくあまり必要ない
1. 火を止める直前にみじん切りにしたニンニクを入れる
1. サワークリーム, ディルの葉, パセリ, 青ネギ, キノコの塩漬けなどを添えて食べる

### 補足

ゲニス&ワイリによれば, 「シチーはスプーンが立つほど具だくさんにするのが良い」とのこと.

### 参考資料

* @OginoNumano2017 p. 25
* @boumei Ch. 3

## ソリャンカ/ゾルヤンカ (宇/露: Солянка/独: Soljanka) \index{ソリャンカ}\index{ゾルヤンカ|see{ソリャンカ}}\index{soljanka|see{ソリャンカ}}\index{Солянка|see{ソリャンカ}}

ロシア (ウクライナ) 発祥のスープ (図\@ref(fig:solyanka-finished)) と東ドイツローカライズされたもの.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/solyanka/finished} 

}

\caption{ロシア風ソリャンカ}(\#fig:solyanka-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★★ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 牛肉
* 牛タン
* サラミ
* ボローニャソーセージ
* 玉ねぎ
* ニンジン
* トマトピューレ
* ザワークラウト
* 塩漬けキュウリ
* バター
* オリーブの実
* ケーパーの塩漬け
* 万能ねぎ
* レモン
* ディルの葉
* イタリアンパセリ
* ベイリーフ
* サワークリーム

### 作り方

以下を参考に

https://speakerdeck.com/ktgrstsh/how-to-make-solyanka

### 補足

ゾルヤンカも概ね同じであるが, パプリカを入れることが多い. さらにキュウリの塩漬けはピクルスに置き換わっている. ロシアのスープ料理によく見られる香草も振りかけないことが多い.

### 参考資料

* @boumei Ch. 6
* https://young-germany.jp/2019/04/ddr4/
* https://www.youtube.com/watch?v=8KxbfDXqwyU

## (予定) ビーフストロガノフ (露: Бефстроганов/Говядина По-строгановски) \index{ビーフストロガノフ}

名前がロシアっぽくないのは当時のロシアの貴族階級がフランスかぶれだったためか. 

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/bef-stroganov/finished} 

}

\caption{ビーフストロガノフとライ麦パン}(\#fig:finished-bef-stroganov)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 牛肉
* 玉ねぎ
* トマト
* サワークリーム

### 作り方

TODO

### 補足

@OginoNumano2017 によればキノコのカーシャ, または炊き込みご飯とも相性が良い.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/bef-stroganov/rice} 

}

\caption{キノコのカーシャとの盛り合わせ}(\#fig:bef-stroganov-rice)
\end{figure}

### 参考資料

* @OginoNumano2017 pp. 42-43

## 真のうどん豆腐 (江戸?)

18世紀の『豆腐百珍』で100品目に紹介されている料理.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/udon-tofu/finished} 

}

\caption{実際のレシピよりかなり手抜きしている}(\#fig:udon-tofu)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
\bottomrule
\end{tabular}

### 材料

* 絹豆腐 1 丁
* つけ汁
  * 醤油 1 升
  * 酒 3 合
  * だし汁 5 合
* 薬味
  * 大根おろし
  * とうがらし粉
  * ねぎの白根
  * みかんの皮
  * 浅草海苔

### 道具

* 豆腐を崩さずに熱湯からすくうための大きめの器具

### 作り方

1. 豆腐をうどんのように細く切る
1. 熱湯でゆでて温める
1. 崩さないように取りだす
    * 塩を加えて煮締めるとちょうどいい固さになる
1. うどんのようにつけ汁や薬味とともに食べる

### 補足

『豆腐百珍』にはところてんの突き出しを湯の中に浸けて豆腐を細く切れとあるが, 崩れさえしなければ方法はなんでもいいと思われる.

真のうどん豆腐から派生する料理も『豆腐百珍』にいくつか挙げられている. ここでは冬の料理に挙げたが冷やして食べるものは紹介されていないため未知数である.

### 参考資料

* 『豆腐百珍』http://www.toyama-smenet.or.jp/~tohfu/tofuhyakutin.html
* 『豆腐百珍』正本 https://dl.ndl.go.jp/info:ndljp/pid/2536494

<!--chapter:end:06-winter.Rmd-->

# 古代・中世編 {#ancient-medieval}

材料調達と作業のどちらかが極端に難しいものが多いが, 極端に簡単なものもある.

セクション\@ref(cesnecka)の「チェスネチカ」の原型とされる料理は14世紀の料理書にも見られる.

## レンズ豆のスープ (捷, 中世)

> ひもじい思いをしたことがある? 数ヶ月間も豆のスープだけで暮らしたことがあるの?
>
> ::: {.flushright data-latex=""}
> --- ファイナルファンタジータクティクス
> :::

……実際には大量の豆を使った濃厚な料理なのでさほどひもじさは感じない.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/lentil-soup/finished} 

}

\caption{レンズ豆のスープ}(\#fig:finished-lentil-soup)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* レンズ豆
* ベーコン
* 玉ねぎ
* ニンニク
* ラード
* 塩胡椒
* 水またはブイヨン, または豆の茹で汁

### 作り方

1. レンズ豆を2時間, 水に浸して柔らかくする
1. 塩を加えてそのまま煮る
1. 柔らかくなったら水を切る, ただし茹で汁を半分ほど残す
1. ベーコンを細かく切る
1. 玉ねぎとニンニクもみじん切りにする
1. 鍋を熱してラードを溶かし, ベーコンを炒める
1. 焼き目がつくまでベーコンを炒める
1. 玉ねぎを加え, きつね色になるまで炒める
1. 豆の半分と水を加える
1. 残り半分の豆をよく潰す
    * ミキサーを使っても良い
1. これも鍋に入れてよく混ぜる
1. 塩胡椒で味を調える

### 補足

ひもじさを演出したい場合は豆やベーコンを少なくする.

現代的には Čočka na kyselo となり, 目玉焼きを乗せたりする.

### 参考資料

* Random Innkeeper の動画 (日本語字幕あり) https://www.youtube.com/watch?v=5FbGKARjuBU
* Čočka na kyselo の料理動画 (英語) https://www.youtube.com/watch?v=0uVRiei7yxk 


## すりつぶしたレンズ豆 (捷, 15世紀)

スープよりも固形物が多いので満腹感がある. アレンジ版も同時に紹介する.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/mashed-lentil/finished} 

}

\caption{すりつぶしたレンズ豆}(\#fig:unnamed-chunk-51)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* レンズ豆 500 g
* タマネギ 1個
* 塩 小さじ2杯
* 胡椒
* ラード 大さじ1
* 水 300 ml
* (オプション) ニンニク 2欠片
* (オプション) 砂糖 大さじ2
* (オプション) 酢, リンゴ酢がよい 大さじ6
* (オプション) ベーコン 120 g
* (オプション) 小麦粉 大さじ1

オプションは「豪華バージョン」を作るのに必要

### 道具

* 野菜すりおろし器
* ポテトマッシャー

### 作り方

1. レンズ豆を水に浸けて柔らかくする
1. そのまま火にかけて茹でる
1. ほとんど茹で上がったら, 最後に塩を加える
1. 鍋を加熱しラードを溶かす
1. すりおろした or みじん切りにしたニンジンと玉ねぎを加えて炒める
    * 豪華版ではオプションの材料をここで投入し調理する
1. 胡椒と豆の茹で汁を加え, さらに数分火にかける
1. 豆を加え, よく潰す

### 参考資料

* Random Innkeeper の動画 https://www.youtube.com/watch?v=tkkB7AhjGFM

## パンケーキ (捷: palačinky) \index{palačinky|see{パンケーキ}}

単体ではただの薄いパンなのでジャムやベリーやチョコレートやヨーグルトを乗せて巻いて食べる


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* バター
* 小麦粉 100g
* 牛乳 200 cc
* 卵 1個
* パンケーキにつける甘い物 (参考資料参照)

### 道具

小さめのフライパン

### 作り方

1. 小麦粉と水と溶き卵をゆっくり混ぜる
    * 塊ができないよう, 少しづつ混ぜ合わせるとよい
1. フライパンを弱火にかけ, バターを引く
1. お玉一杯分の生地をゆっくり注ぐ
1. 片面が焼けたら手首のスナップをきかせて裏返す
    * 自信がなかったらヘラを使う
1. 両面を焼いたら取りだす

### 補足

いわゆるホットケーキのような膨らましたものではなく, British pancake と呼ばれるタイプと同じでクレープみたいな薄いものである. どうやら古代ローマの時代からあるらしい. 製法もいたってシンプルなので, チェコに限らず古代から中世にかけてのヨーロッパ世界では至るところで見られたのではないかと想像する.

### 参考資料

* Random Innkeeper のレシピ, チェコ風のスプレッドのレシピつき https://www.youtube.com/watch?v=okHyqdnKPfY
* Helltaker のクリア特典には作者 (ポーランド人) の祖母のレシピが含まれている https://store.steampowered.com/app/1289310/Helltaker

## (予定) 中世のドーナツ (捷, 16世紀)

現代のポンチキと似ているが, 甘いものは使わない塩気の多い料理である.

TODO


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
\bottomrule
\end{tabular}

## ロールパン (捷, 15世紀)

かなり脂っこいパン

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/roll-bread/finished} 

}

\caption{中世のロールパン}(\#fig:unnamed-chunk-55)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 小麦粉 500 g
* 卵 1個
* ドライイースト 5g
* ラード 150g
* キャラウェイシード 適量
* クラックリング (油かす) 300g
* 室温に戻したミルク 120 ml
* 白ワイン 200 ml
* 蜂蜜 小さじ1
* 塩 適量

### 道具

* ボウル
* オーブン, またはオーブントースター

### 作り方

1. ボウルに小麦粉とラードを入れるが, かき混ぜてはならない
1. 小麦粉にくぼみを作ってイーストを入れる
1. 牛乳と蜂蜜をイーストにかける
1. 予備発酵を待つ
    * 15分程度かかる
1. 塩とキャラウェイシードを好みの量だけ加える
1. 卵と白ワインを注ぎ混ぜ, 生地をこねる
1. 細かく砕いたクラックリングを混ぜる
1. 布を被せて3時間ほど寝かせる
1. オーブントレーに油をぬる
1. 適当な大きさにちぎって並べる
    1. トレーにくっつかないよう下に打ち粉すると良い
    1. このとき塩やキャラウェイシードを追加でふりかけても良い
1. 上をナイフでひっかき切れ目を入れる
1. 牛乳をはけで塗る(図\@ref(fig:bread-roll-before-bake))
1. 10分間寝かせる
1. オーブンを190度にして10-20分焼く
    * オーブンがないなら体感で努力する

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/roll-bread/bred_roll_dough} 

}

\caption{焼く直前}(\#fig:bread-roll-before-bake)
\end{figure}

### 補足

元はハンガリーの料理であるらしい.

油かすは背脂からラードを精製する際に発生する. もちろん余った脂身を炙って作ってもいい.

### 参考資料

* Random Innkeeper の動画 https://www.youtube.com/watch?v=Lm-FoNIFJE0

## (予定) イラクサのシチュー (捷, 中世)

COVID-19 に対する効果は明らかになっていない.

## 肉なしソーセージ (捷, 15世紀) \index{肉なしソーセージ}

中世の料理書に「ソーセージ」という名前で掲載されているレシピ. しかし肉を一切使わない.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/sausage/finished} 

}

\caption{「ソーセージ」}(\#fig:unnamed-chunk-57)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 卵 6個
* 小麦粉 大さじ6
* レーズン 50g
* パセリ 適量
* セージ 適量
* バター 適量

### 作り方

1. 卵でスクランブルエッグを作る
    * あとで成形しづらくなるので加熱しすぎてはならない
1. 小麦粉, レーズン, パセリ, バターを加えてよくこねる
1. ソーセージのように細長く成形する
1. フライパンにバターを溶かす
1. 「ソーセージ」を焼く
1. 接している面が焼けたら少しづつ転がし他の面も焼く

### 参考資料

* Random Innkeeper の動画 (英語音声, 日本語字幕あり) https://www.youtube.com/watch?v=dKNu_qnQZkM

## パン粉のドーナツと林檎のポリッジ (捷, 15世紀)

この料理は šišky と表現されているため, 辞書的には「団子」「ダンプリング」である(図\@ref(fig:breadcrumbs-dumpling-finished)). しかし, バターで焼き上げる工程があるためここでは「ドーナツ」と書いた.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/breadcrumbs-dumplings/finished} 

}

\caption{パン粉のドーナツと林檎のポリッジ}(\#fig:breadcrumbs-dumpling-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

正確に量らずに作ったので適切な比率は不明. 適宜継ぎ足してほしい.

* ドーナツ
  * 卵 2-3個
  * パン粉 適量
  * 砂糖 適量
  * 干しぶどう 適量
  * バター
* ポリッジ
  * りんご
  * シナモンスティック
  * 白ワイン
  * バター

### 作り方

ドーナツ

1. ボウルに卵を割り, よくかき混ぜる
1. 砂糖と干しブドウを入れる
1. パン粉を少しづつ入れながらかき混ぜる
1. 固まってきたらこねて生地にする
1. 団子の大きさにする
    * あまり大きすぎると中まで火が通らない.
1. フライパンを火にかけ, バターを多めに溶かす
1. 表面に焼き目が付く程度に団子を数分焼く
1. フライパンから取り出し, 油を切る

ポリッジ

1. りんごの皮をむき, みじん切りにする
1. 鍋を弱火にかけ, バターを溶かす
1. りんごを入れて焦げ付かないように加熱する
1. シナモンスティックを入れる
1. 必要に応じて水を足し, りんごが柔らかく崩れるまで加熱する
1. 白ワインを注ぎ, さらに数分加熱する

ポリッジの上にドーナツを乗せると良いだろう.

### 補足

日本のパン粉は粗いので袋にいれて叩くなどして粒を細かくしてから使うと良い. しかし当然ながら小麦粉よりは目が粗いので, あまりきめの細かい生地にはならない.

りんごのポリッジは @Ju2018 pp. 78-79 に類似したイングランドのレシピが見られる.

### 参考文献

* Random Innkeeper の動画 https://www.youtube.com/watch?v=J4iEFjWsMqM
* @Ju2018

## プレッツェル (捷, 15世紀: pleclík)

現代のドイツやオーストリアのものとはかなり違う中世のレシピ (図\@ref(fig:pleclik-finished)). イーストも苛性ソーダも使用しない. グラインダーが無いと重労働なのでもう作りたくない.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/preclik/finished} 

}

\caption{中世のプレッツェル}(\#fig:pleclik-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★★★★★★★★ }\\
\bottomrule
\end{tabular}

### 材料 (4個分)

* 小麦粉 200 g
* 蜂蜜 100 ml + 「蜂蜜粉」の3/4 *
* 油または小麦粉 少量
* (オプション) 味付け用のスパイス (胡椒、クローブ、ショウガ、オールスパイス、シナモンなど)

### 道具

* オーブンまたはオーブントースター
* 固いものを細かく粉砕するグラインダー

### 作り方

1. 蜂蜜を温めて溶かす
1. 火傷に注意して小麦粉と混ぜてこねる
    * 粘りのある生地にするのは難しいのでほどほどでやめる
1. オーブントレーに油を塗る, または小麦粉を振る
1. 平たくつぶした生地を乗せ, 170度に熱したオーブンで, 表面が焼きあがるまで焼く
    * 20分程度かかる
1. 焼いた生地を細かく粉砕する
    * グラインダーがないと極めて重労働となる
1. 粉末の 3/4 の量の蜂蜜を温めて溶かし, 混ぜる
    * 多すぎるとベタつくのでやや少なめでも良い
1. オプションでスパイスを粉末にして混ぜる
1. 細長くこねてプレッツェルの形にする
1. 天日干しか, オーブンで焼いて固める

### 参考資料

* Random Innkeeper の動画 (英語, 日本語字幕あり) https://www.youtube.com/watch?v=6JXrlNuYHF8

## エンドウマメの団子 (捷, 15世紀)

すぐ崩れるので難しい上にぶっちゃけうまくない.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/pea-ball/finished} 

}

\caption{最大限うまそうに見せた様子}(\#fig:pea-ball-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
\bottomrule
\end{tabular}

### 材料

* エンドウマメ 500 g
* 砂糖 50 - 100 g
* 干しブドウ 100 g
* 油
* 追加の砂糖

### 作り方

1. エンドウマメを数時間水に浸す
1. 鍋で茹でて柔らかくする
    * この時点では柔らかすぎてはならない
1. 水気を良く切り, 砂糖を加えて潰してかき混ぜる
1. 手で触れられる温度になるまで待つ
1. 適当な量を手に取り, 干しブドウを何粒か包んで団子にする
1. フライパンに油を引き, 絡める色になるまで弱火でこれを焼く
1. 砂糖をまぶす

### 補足

火加減を間違えると固まりにくくなるが, 適切な方法はわからない.

植物性の油を使えばいちおうは断食用になる.

小豆とか甘い豆をつかうとうまくなるかもしれないが, 中世ヨーロッパにはたぶん小豆はない.

### 参考資料

* Random Innkeeper の動画 https://www.youtube.com/watch?v=XSOw8thwkgU

## (予定) 4食のポリッジ

@feyfrlikova2015Kuchyne p. 66 がたぶん元ネタ

### 参考資料

* Random Innkeeper の動画 https://www.youtube.com/watch?v=J4iEFjWsMqM
* @feyfrlikova2015Kuchyne

## 豚肉のビールソース和え (vepřovina divoká, 捷, 16世紀) \index{vepřovina divoká|see{豚肉のビールソース和え}}

おそらく酒場で古くなったビールやパンを再利用するレシピとのこと. 発泡酒ではなくビールを使おう.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/beer-pork/finished} 

}

\caption{豚肉のビールソース和え}(\#fig:beer-pork-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 豚肉 300 g
* ビール 500 ml
* 固くなったパン 食パン2-3枚程度
* 酢, リンゴ酢が良い
* ショウガ
* 胡椒
* 塩
* ニンニク
* 砂糖
* ラード
* (オプション) ブイヨン

### 道具

* ストレイナー/裏ごし器
* 豚を茹でるのと並行してソースを作るため, 鍋が2つあるとよい

### 作り方

1. 多めに塩を加えた水またはブイヨンで豚肉を茹でる
1. 別の鍋にビールと少量の酢を注ぎ, パンを砕いて入れる
1. パンをほぐしながらビールと混ぜる
1. ストレイナーにかけ, 濾し取ったものを再度加熱する
1. 上記の調味料とスパイスで味を調える
    * 砂糖を多めに入れるとよい

### 補足

本来のレシピではソースの材料はビール, 酢, パンしか言及されていなかったが, それだけではとうてい食べられたものではないため上記のスパイスで味付けしている.

### 参考資料

* Random Innkeeper の動画 https://www.youtube.com/watch?v=qWsfd6tn2VY

## 鶏肉とブラックソース kuře v černé jíše (捷, 15世紀)

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/chicken-dark-sauce/finished} 

}

\caption{鶏肉とブラックソース}(\#fig:chicken-dark-sauce-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 鶏胸肉
* リンゴ
* 赤ワイン
* パン粉
* シナモン
* 胡椒
* サフラン
* ショウガ
* 塩
* 砂糖

### 作り方

1. 鍋に湯を沸かし, 多めに塩を加える
1. 軽く沸騰したら鶏肉を入れる
1. 乳鉢でスパイスを全て挽く
1. フライパンを加熱し, パン粉を熱する
1. 焦がさないように茶色くなるまで煎る
1. フライパンに赤ワインとスパイスを注ぐ
1. よく混ぜる
1. 鶏肉が半分ほど煮えたら取り出す
1. 鶏肉をフライパンに入れ, ソースを絡める
1. 赤ワインまたは茹で汁を少し加える
1. 鶏肉全体にソースの色が染み込むまで調理する
1. リンゴをスライスする
1. フライパンにリンゴと少々の赤ワインを入れ, 蓋をして蒸す
1. リンゴに色が移ったら取りだす
1. 好みで砂糖を使いソースの味を調える
1. 全て皿に盛り付ける


### 補足

味の濃い食材がないため, 鶏肉の下茹で時には十分に塩を入れて味付けしておく.

### 参考資料

* Random Innkeeper の料理 https://www.youtube.com/watch?v=XEdpYA_xHLM

## ハンガリー風ローストチキン (kuře po Uhersku, 捷, 15世紀) \index{kuře po Uhersku|see{ハンガリー風ローストチキン}}

例によって「ハンガリー風」という名の中世チェコ料理. 現在の同名の料理はパプリカやトマトを使った赤いソースで鶏肉を煮込んだものだが, 当時のヨーロッパにはトマトはない.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/hungarian-chicken/finished} 

}

\caption{かなり小さい鶏で料理した}(\#fig:hungarian-chicken-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* ローストチキン用の鶏肉 1羽
* 詰め物
  * ベーコン 50 g
  * 粟 150 g
  * 生クリーム 40 ml
  * レーズン 1掴み
  * 卵 2個
* ソースの材料
  * 生クリーム 200 ml
  * サフラン
  * 生姜
  * 砂糖
  * 卵黄 1個

### 道具

* オーブン

### 作り方

1. 卵をかたゆで卵にする
1. 粟を塩水でよく茹でる
1. ベーコンを小さくさいの目切りにする
1. ゆで卵も同様に小さく切る
1. フライパンに油を引き, ベーコンを炒める
1. さらにゆで卵と粟も加えてよく混ぜる
1. レーズンと生クリームも加える
1. 柔らかさを残しつつ, 余分な水分が飛ぶまで加熱する
1. 鶏肉に詰める
1. 頭と尻を縛って漏れないようにする
1. オーブンを160度Cに加熱し1時間焼く
1. その間にソースを作る
    1. 鍋で生クリームを温める
    1. 卵黄を入れ, よくかき混ぜる
    1. サフランと生姜を1つまみ加える
    1. 濃いソースになるまで混ぜ続ける
1. 鶏肉を切り分け, 上からソースをかける

### 補足

オーブンがないのでかなり小さな鶏で試してみたが, ほとんど入らなかった.

### 参考資料

* Random Innkeeper の動画 https://www.youtube.com/watch?v=ZZxF8H4ArbA

## 鶏肉のローフと黒いソース (捷, 15世紀, sekanina slepičí s černou omáčkou) \index{sekanina slepičí|see{鶏肉のローフ}}

肉挽き器が発明されたのは19世紀であり, それ以前のひき肉は包丁で念入りに叩くという重労働の産物であった. しかしこの料理は挽き肉を使い, 見た目にもこだわった贅沢な料理である (図\@ref(fig:sekanina-slepici)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/sekanina/finished} 

}

\caption{鶏肉のローフ (崩れている)}(\#fig:sekanina-slepici)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
\bottomrule
\end{tabular}

### 材料

* 鶏もも肉 (骨付き)
* ベーコン
* 卵
* 塩胡椒
* パセリ
* サフラン
* ジンジャーパウダー
    + なければおろしショウガでもよい
* (オプション) 小麦粉

ソースの材料

* 赤ワイン
* パン粉
* シナモン
* 砂糖

### 道具

* 挽き肉器^[挽き肉器の発明は19世紀になってからなので, 中世気分を味わいたい場合は手作業でミンチにする]
* 複数の鍋

### 作り方

ミートローフの作り方

1. モモ肉を柔らかくなるまで茹でる
1. 骨から肉を外す (骨と茹で汁を捨ててはならない)
1. 肉をミンチにする
1. 卵を固茹でにする
1. ベーコンとゆで卵を細かくみじん切りにする
1. ベーコンをカリカリになるまで炒める
1. ミンチ, ベーコン, ゆで卵, パセリ, 塩胡椒, ジンジャーパウダーを混ぜてこねる
    * 崩れやすかったら小麦粉を混ぜる
1. 骨に生地をつけて骨付き肉のような形にする
1. 茹で汁に静かに入れ, 静かに茹でて固める

ソースの作り方

1. パン粉をフライパンで茶色くなるまで煎る
1. 赤ワインを注ぐ
1. サフラン, シナモン, ジンジャーパウダーなどで香りを付ける
    * 砂糖を加えても良い

### 補足

鶏肉に一度火を通してからひき肉にするため, 十分細かくないと崩れやすい. よって手作業の場合は覚悟すること.


### 参考資料

* Random Innkeeper の動画 https://www.youtube.com/watch?v=vaBtiTrlmVc
* 自作記録 https://under-identified.hatenablog.com/entry/2019/04/13/220424 

## 「ハンガリー風」ローストビーフ #1 (捷, 15世紀, Pečeně hovězí po Uhersku) \index{Pečeně hovězí po Uhersku|see{ハンガリー風ローストビーフ (15世紀)}}

チェコの文献に見られる最も古いレシピの1つ. ハンガリーに同じ料理があったのかは不明 (図\@ref(fig:hungraian-beef15)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/hungarian-beef15/finished} 

}

\caption{ハンガリー風牛肉}(\#fig:hungraian-beef15)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 牛肉 400 g
* 玉ねぎ 小3個
  * 玉ねぎの個数にこだわる必要はない
* 赤ワインビネガー 50 ml
* ブイヨン 300 ml
* キャラウェイシード
* ジュニパーベリー
* 黒胡椒
* ショウガ
* クローブ
* メース
* 塩
* (オプション) 砂糖

### 道具

* 牛肉が入るオーブン
* 裏ごし器

### 作り方

1. 牛肉を水に浸して涼しい場所で2時間寝かせる
1. 水気を切り, 全体に塩をよく振る
1. オーブンを160度Cに熱して20分焼く
    * ここでは完全に火が通っている必要はない
1. 玉ねぎをみじん切りにする
1. キャラウェイシード, 生姜, ジュニパーベリーをすりつぶす
1. 牛肉を鍋に入れ, ビネガー, ブイヨン, 玉ねぎ, 塩ひとつまみ, そして砂糖以外の残りのスパイスを全て入れる
1. 肉が柔らかくなるまで, 1.5時間ほど煮込む
1. 残った汁から固形物を濾し取る
1. さらに加熱して水気を減らし, 好みの濃さにする
    * もし酸味が強すぎるなら砂糖で調整する
1. 牛肉にソースをかける

### 補足

@feyfrlikova2015Kuchyne pp. 80-81 にこのレシピの現代語訳が記載されている. 疫病に関する本に記載されていたレシピの1つであるという.

### 参考資料

* Random Innkeeper の動画 https://www.youtube.com/watch?v=QnSHjogWAMA
* @feyfrlikova2015Kuchyne  

## 「ハンガリー風」ローストビーフ #2 (捷, 16世紀, Hovězie po Uhersku) \index{Hovězie po Uhersku|see{ハンガリー風ローストビーフ (16世紀)}}

これもチェコの料理. 現代的なローストビーフとあまり変わらない味付けであり, 現代人にとってのハードルは低いと思われる (図\@ref(fig:hungarian-beef16)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/hungarian-beef16/finished} 

}

\caption{ハンガリー風ローストビーフ}(\#fig:hungarian-beef16)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 牛肉, ブリスケットが良い
* リンゴ 1個
* 玉ねぎ 1個
* 小麦粉
* 酢, リンゴ酢が良い
* 塩

### 道具

* オーブン
* ストレイナー/裏ごし器

### 作り方

1. 玉ねぎとリンゴを荒く切り, オーブン用の鍋に入れる
1. 小さな肉の切れ端や脂身を切り取って混ぜる
1. 塊肉の全体によく塩を振ってこれらの上に乗せる
1. コップ半分の水を注ぎ, 蓋をする
1. オーブンを160度Cに熱して柔らかくなるまでローストする
    * この温度だと2時間程度かかる
1. 肉を取りだす
1. 鍋に残ったものからソースを作る
    1. フライパンに注ぎ熱して水気を飛ばす
    1. 酢をひとふりする
    1. 小麦粉をふりかけ, とろみをつける
    1. 水を加え, かき混ぜつつ適切な濃さになるまで熱する
    1. ソースを濾し取る
1. ローストビーフを切り分け, ソースをかけ, リンゴを添える

### 補足

日本の家庭にはローストビーフを作れるオーブンがないことが多い. オーブントースターや魚焼きグリルで代用すると, 熱源との距離が近すぎ焦げやすいため注意. 私は魚焼きグリルで少し加熱し後は圧力鍋を使ったが, おそらくオーブンでローストしたほうがうまいだろう.

なぜリンゴを添えるのかはよくわからない.

### 参考資料

* Random Innkeeper の動画 https://www.youtube.com/watch?v=u5A8wbyBI9Y


## ラム肉のセージソース和え (捷, 15世紀)

当時の羊肉は富裕層でなくても食べる機会が多かったそうなので, 庶民の食事の1つだったのかもしれない.

TODO: 画像


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 羊肉 (ラムのショルダーがよい) 600 g
* 塩
* 胡椒
* (オプション) メース
* ソース
    * ブイヨン 200 ml
        * 羊の茹で汁を使いまわしても良い
    * 酢, リンゴ酢がよい 大さじ2
    * 砂糖 大さじ2
    * セージの葉 大さじ2

### 道具

* オーブン

### 作り方

1. 鍋に水をはり, 塩を加える
1. 肉をよく茹でる
1. ソースを作る
    1. 別の小さい鍋を弱火で熱し, ブイヨンを注ぐ
    1. 酢と砂糖を加える
    1. セージを細かく刻んで加える
    1. よく混ぜてなじませる
    1. およそ10分ほど加熱を続ける
        * 気になるなら葉を濾し取る
1. 肉に塩胡椒とメースをふりかける
1. 肉が柔らかくなるまで焼く
1. オーブンを200度に熱し, 肉が柔らかくなるまでローストする
    * おそらく45分程度
1. 肉を切り分け, ソースをかける

### 補足

メースは当時最も高価な部類に入るスパイスであるので, ロールプレイがしたい人は注意. なお @feyfrlikova2015Kuchyne によれば当時の一般的な都市の住居にはすでにオーブンが備わっていたため^[これはビデオゲーム "Kingdom Come: Deliverance" でも視覚的に再現されている], こちらを気にする必要はないと思われる.

### 参考資料

* Random Innkeeper の動画 https://www.youtube.com/watch?v=BsYVAQfuWqc


## 「鹿肉風」牛肉 (捷, 15世紀)

牛肉をワインに浸けて煮込み, 鹿肉のように赤黒くする料理. ジビエを食べられるのは森を所有していた貴族たちだったので, 狩猟権のない富裕層が牛肉を楽しむために作られたレシピなのかもしれない.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/venison-beef/finished} 

}

\caption{鹿肉風牛肉}(\#fig:venison-beef-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 牛肉
* 塩
* 赤ワイン 十分な量
* クローブ
* 胡椒粒
* リンゴ
* サフラン
* バター 大さじ1
* 砂糖  大さじ1

### 作り方

1. 牛肉を軽く叩いて柔らかくする
1. 牛肉を鍋に入れ, 赤ワインに浸し, 涼し場所で最低2時間寝かせる
1. 弱火でゆっくり加熱し, 塩とクローブと胡椒とサフランを加える
1. 1時間ほどかけて肉が柔らかくなるまで煮る
1. 肉が煮えてきたらフライパンを温めバターを溶かす.
1. 砂糖を加えてスライスしたリンゴの量を焼く
1. 焼いたリンゴの半分を細かく切り刻む
1. 皿の中央に刻んだリンゴを乗せる
1. その周りに茹でた牛肉と残りのリンゴを並べる
1. 茹で汁をソースとしてかける
    * ソースが濃くなるように適宜蒸発させる

### 補足

赤ワインは蒸発しやすいので蓋をするなどして対処する.


### 参考資料

* Random Innkeeper の動画 https://www.youtube.com/watch?v=xZe7p8ofCfg

## (予定) ローストダック (捷, 15世紀)

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/roast-duck-cz/finished} 

}

\caption{中世風}(\#fig:roast-duck-cz-finished)
\end{figure}

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/roast-duck-cz/moravsky} 

}

\caption{現代モラヴィア風}(\#fig:roast-duck-cz-moravia)
\end{figure}


### 参考資料

* https://www.youtube.com/watch?v=mtta0W-kBh4

## 野ウサギの煮込み (捷, 15世紀)

現代のチェコでもウサギ料理はそれなりにポピュラーである.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/kralik-medieval//finished} 

}

\caption{穴ウサギでもいい}(\#fig:hare-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★★ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* ウサギのモモ 2本
* 赤ワイン 150 ml
* ブイヨン (無塩がよい) 800 ml
* タマネギ 2個
* リンゴ 2個
* パン粉
* 胡椒
* 生姜
* クローブ
* サフラン

### 作り方

参照動画を参考にせよ

### 参考資料

* Random Innkeeper の動画 (日本語字幕あり) https://www.youtube.com/watch?v=CcjKye3use8

## ハッシュドレバー (捷, 15世紀)

「見た目はひどいが, 味は良い」レバーの臭みが苦手な人におすすめ. 多少見た目を改善したレシピも紹介する

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/liver-hash/finished} 

}

\caption{見た目に難がある}(\#fig:finished-liver-hash)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* レバー (豚か牛) 400 g
* 赤ワイン 200 ml
* 卵 1個
* 塩
* 胡椒
* アニスシード
* シナモン粉末
* メース
* ショウガ
* キャラウェイシード
* (オプション) パン粉

* (オプション) パテの材料
  * レーズン 50 g
  * ラード 100-200 g
  * 付け合せにタイム、チャイブなど緑色のハーブ

### 道具

* パテにしたい場合は肉挽き器が必要


### 作り方

1. レバーを小さく切る
1. 茹でるために湯を沸かす
    * 無塩ブイヨンを使っても良い
    * ブイヨンに使うような野菜やハーブを入れても良い
1. レバーを茹で, アクを随時取り除く
1. レバーに火が通ったら, 包丁で細かく刻む
1. フライパンを加熱し, 赤ワインを注ぐ
1. 胡椒, シナモン, メース, 生姜を加える
1. レバーと塩も加える
1. 好みでパン粉を加え, よく混ぜる
1. キャラウェイシードとアニスシードをすりつぶし, 加える
1. 火を消し, 卵を加えてよく混ぜ, 余熱で調理する

### 補足

上記は本来のレシピだが, 見た目がとても悪い. ため, 改善のためパテにする方法も提案されている. そのためにはレーズンとともに肉挽き器で細かく挽いた後, ラードを加えてよくこねる. パンに塗り, ハーブをふりかけて食べる.

### 参考資料

* Random Innkeeper の動画 https://www.youtube.com/watch?v=w5oWJZVPRK4

## メルルーサのベーコン煮 (捷, 15世紀: Štiku s slaninami)

イギリス由来の料理のため, 海の魚を使用している. メルルーサを使うのが本来のレシピだが, 今回は入手できなかったためスケトウダラでアレンジした (図\@ref(fig:stiku-s-slaninami-finished)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/stiku-s-slaninami/finished} 

}

\caption{タラのベーコン煮}(\#fig:stiku-s-slaninami-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* スケトウダラ
  * 中世ヨーロッパで獲れそうな海魚
* パースニップ
  * なければ人参で代用
  * もしあれば根パセリという手もある
* 胡椒
* 生姜
* ベーコン

### 作り方

1. パースニップを拍子木切りにする
1. ベーコンを小さく角切りにする
1. 胡椒と生姜を細かく挽く
1. 鍋に水を注ぎ, パースニップ, 魚, ベーコンの順に入れ, その上から胡椒と生姜をふりかける
1. 蓋をして10分ほど弱火で蒸す

### 補足

元のレシピでは全ての材料を一度に入れるとしか書いてないらしい. パースニップを下敷きにするのは Random Innkeeper のアイディアである.

なお, 日本国内の市販ベーコンは味が薄く脂身も少ないため, 塩を余分に加えたほうが良いかもしれない.

@Ju2018 p. 23 でも中世イギリスのタラ料理が言及されている.

### 参考資料

* Random Innkeeper https://www.youtube.com/watch?v=pQthdIYfRR0
* @Ju2018

## トゥ・フー (アッカド, バビロン第1王朝時代? `{\fontspec{Akkadian}`{=latex}𒌅𒌔𒌑`}`{=latex})

古代メソポタミア料理. 材料調達の難易度がかなり高い.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/mesopotamia/finished} 

}

\caption{トゥ・フー}(\#fig:mesopotamia-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★★★★★★★ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

材料と作り方は参考資料を参照せよ

### 参考資料

* @Damerow2012SumerianBT
* @GojkoEtAl2019-blog
* @GojkoEtAl2019
* これらを元にした自作記録 https://under-identified.hatenablog.com/entry/2020/08/01/213350

<!--chapter:end:07-ancient-medieval.Rmd-->

# その他の加工食品

単体で付け合せにできるし, 他の料理に使うこともできる.

## トマトソース (伊)


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* ホールトマト缶 400 ml
* ニンニク 1 欠片
* 玉ねぎ 半分
* 月桂樹の葉
* パセリ
* オリーブオイル

### 作り方

1. フライパンにオリーブオイルを引き, 弱火で加熱する
1. ニンニクと玉ねぎを炒める
1. ホールトマト缶を入れ, 煮崩れるまで加熱を続ける
1. 水分が飛び, 濃厚になるまで続ける
1. 火を止める直前に月桂樹の葉やパセリを入れる

## ザワークラウト\index{ザワークラウト} (独: Sauerkraut)\index{sauerkraut|see{ザワークラウト}}

ドイツや東欧で広く食べられる. ボルシチやシチーの材料にもなる. よく「酢漬け」と間違えられがちだが, 酸味は乳酸発酵によるもの. ただし市販品にはビネガーやワインで味付けしたものもある.


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* キャベツ 1玉 (1.2-1.5 kg程度)
  * 身の詰まった重いものがよい
* 塩 大さじ 2杯
  * キャベツ 500 g あたり塩 10g が相場
* (オプション) 人参
* (オプション) ハーブ・スパイス類
  * 胡椒, オールスパイス, ローレル, ディルなど
  * 白ワイン

### 道具

* 漬け物容器
  + 押し付ける機能のあるものが良い

### 作り方

1. キャベツを半分に割る
1. V字の切り込みを入れ, 芯を切り取る
1. 太い葉脈も適宜切り取る
1. キャベツをさらに半分に割ってから千切りにする
1. 塩でもむ
1. しんなりしてきたら漬け物容器に入れる
    * 最初から漬け物容器内でやってもよい
1. 香り付けにハーブ・スパイス類や白ワインを少し混ぜても良い
1. 冷蔵庫に保管する
    * 冬なら常温放置でも可
1. 一晩すると水分が抜けてくる
1. キャベツ全体が水に完全に浸かるように上から押す力を調整する
1. 2週間-1月程度待つ
1. 全体的に白くなり, 発酵臭がしたら食べごろ
    * 刺激臭がしたり黒ずんだり, カビが生えたりしたら捨てる
    * 常温放置すると表面に酵母が発生することがある

  
### 補足

夏場は管理が難しいので秋や冬にやるとよい. ロシアやポーランドでは人参やディルを混ぜることがよくあるらしい. ドイツやチェコではあまり混ぜない.

### 参考資料

* @katz2012Art
* 日本語の解説付きの作成例 https://www.youtube.com/watch?v=uTgx3Gcixcc

## ウトペネツ\index{ウトペネツ} (捷: Utopenci)\index{utopenec|see{ウトペネツ}}\index{utopenci|see{ウトペネツ}}

ソーセージと野菜を乳酸発酵させたチェコの伝統食品 (図\@ref(fig:utopenci-finished)).

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/utopenci/finished} 

}

\caption{瓶に詰めたウトペネツ}(\#fig:utopenci-finished)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* ベーコンやソーセージ
* パプリカ
* 玉ねぎ
* 唐辛子
* ニンニク
* オールスパイス
* 胡椒粒
* キャラウェイシード
* 月桂樹の葉
* 砂糖大さじ1
* 酢 500 cc
* 塩 大さじ1
* 水 750 cc

### 道具

* 密閉できる清潔な瓶

### 作り方

1. 鍋に水, 塩, 砂糖, オールスパイス, 胡椒, 月桂樹の葉を入れ沸騰させる
1. 瓶にスライスしたパプリカと玉ねぎ, そして残りの材料を詰め込む
1. (1) の熱湯の粗熱が取れたら瓶に注ぎ, 蓋をする
1. 冷暗所で乳酸発酵するまで寝かせる
	* 1-2週間程度

### 補足

`\aruby{utpenci}{ウトペンツィ}`{=latex} は複数形で, `\aruby{utpenec}{ウトペネツ}`{=latex} は単数形. 意味は 「溺死体」

現地では špekáček というソーセージを使用することが多い.

図\@ref(fig:utopenci-finished) は玉ねぎやパプリカを多く入れているが「溺死体」という名前が示すように, 本来は肉がメインである.

ピックル液の量は材料の比率を維持しつつ瓶のサイズに合わせて調整する.

### 参考資料

* 古典的なレシピ https://www.toprecepty.cz/recept/39156-utopenci-klasika/

## (TODO) キノコの塩漬け (露)


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

## (TODO) トマトの塩漬け (露)


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

## (TODO) キュウリの塩漬け (露)

ピクルスと混同されるとおそらくロシア人は不満に思うことだろう. ウォッカのつまみにもよい.


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

## ベーコン\index{ベーコン}(bacon\index{bacon|see{ベーコン}}; 独: spek\index{spek|see{ベーコン}})

塩とスパイスをまぶして熟成させる乾式と, ソミュール液に漬ける湿式がある. 湿式のほうが簡単.

\begin{figure}

{\centering \includegraphics[width=1\linewidth,height=1\textheight,keepaspectratio]{img/bacon/finished} 

}

\caption{ベーコン}(\#fig:finished-bacon)
\end{figure}


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★★★ }\\
\bottomrule
\end{tabular}

### 材料

* 豚バラ肉
* 塩
* その他好きなハーブ・スパイス
  * 胡椒, オールスパイス, タイム, ローズマリー, ニンニクなどが合う

### 道具

* 豚バラ肉の入る, 密閉できる袋 (湿式の場合)
* キッチンペーパーまたはピチットシート (乾式の場合)
* スモークウッド
* 大きめのダンボール箱
* 燃えない丈夫な受け皿
* タコ紐

### 作り方

1. 肉に下味をつける
    * バラ肉に十分な塩とスパイスをすりつける
    * または十分な濃度の塩水 (ピックル液/ソミュール液) に漬ける
		* 15-20%程度の濃度の塩水に好みのハーブ・スパイスを入れて一度沸騰させた液
2. 2週間-1ヶ月ほど冷蔵庫で熟成させる
	* 乾式の場合, 表面に染み出してくる水分をまめに取り除く
	* ピチットシートなら説明書に従い, キッチンペーパーならなるべく1日ごとに取り替える
3. 軽く水洗いし, 表面についたスパイスを洗い流す
4. 表面の水分を拭き取る
5. さらに天日干しで表面を乾燥させる
    * または扇風機で1-2時間風を当て続ける
    * 燻製全般に言えることだが, 表面に水分が残っているとホルムアルデヒドが発生し致命的に味が悪くなる
6. 6時間ほど燻製する
    * 40-60度程度を維持すると良い. これは温燻と呼ばれる処理.
7. 1日冷蔵庫で寝かせる

### 補足

比較的安価な方法は, 段ボールで燻製室を作り, 継続的な加熱の必要ない「スモークウッド」で燻製すること. しかし火災のリスクがまったくないわけではないため, 目を離さないように.

### 参考資料

* 乾式チロリアン風ベーコン (英語字幕あり) https://www.youtube.com/watch?v=VZ9MmxevNeQ
* 『Speck ドイツ式ベーコン』 http://jdg-nishinihon.org/upfiles/files/speck.pdf

## サーロ\index{サーロ} (宇/露: Сало\index{сало|see{サーロ})}

衛生面で問題ないのかは不明.


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 背脂
* 塩


### 作り方

1. 塩をまぶして冷蔵庫で寝かせる
    * 胡椒等のスパイスをブレンドしてもよい

### 補足

黒パンと一緒に食べる, ウォッカで流し込む, 温かいスープと一緒に食べる.

### 参考資料

謎


## キムチ (韓: 김치)


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 白菜の塩漬け 1株
* エクチョッ (魚醤)
* セウジョッ (アミエビの塩辛など)
* 唐辛子の粉末 250 g
* 白玉粉 (片栗粉や小麦粉でも可) 50 g
* ニンニク 半株 - 1株 
* ショウガ 50 g
* 大根またはカブ 適量
* ネギ類や青菜 (大根の葉も可) 適量

### 道具

* 白菜漬けの容器
* 大根または株を細切りするためのスライサー
* 大量のキムチソースを入れる大きめの容器 (かなり大きめのボウルが必要)
* 大量のキムチを保管できるタッパー

### 作り方

1. 白菜を塩漬けにしてザワークラウトのように発酵させる
1. 水に白玉粉を溶いてふやかしを作る
1. 唐辛子の粉末を混ぜる
1. すりおろしたニンニクと生姜を混ぜる
1. セウジョッとエクチョッも混ぜる
1. すりおろした野菜もよくまぜる
1. 大根は塩水に浸けて柔らかくすると良い
1. 白菜の葉1枚1枚にヤンニョムを刷り込む
1. 清潔な箱に入れ, 冷蔵庫で保管する

### 補足

ヤンニョムや抜けた水分に完全に浸かる状態でないとカビが発生しやすいので注意


## 香辣紅油 (中)


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
\bottomrule
\end{tabular}

ネギ類とシナモンで香りを付けた辣油. 四川料理と合う

## 刀口辣椒 (中)

麻婆豆腐を始め四川料理に合う


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★☆☆☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 乾燥唐辛子
  * 小弾頭とか朝天じゃないとダメと言う人もいるが気にしなくてもいい
* 青花椒 (藤椒)
  * 花椒より高価だがこちらのほうが香りが強い
* 油

### 作り方

1. 中華鍋に油を引く
1. 弱火で唐辛子と青花椒を炒める
1. 包丁で細かく刻む

### 補足

焦げると味を損なうので加熱時間に注意

## (TODO) 豆豉 (中)

四川料理でうま味を加えるのに使う.

ぶっちゃけ買ったほうが安い


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★★★★ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★★★ }\\
\bottomrule
\end{tabular}

### 参考資料

* @Jing1992

## 泡辣椒・泡姜 (中)

それぞれ唐辛子と生姜を塩水に浸けて乳酸発酵させたもの. 四川料理でよく使う.


\begin{tabular}[t]{rl}
\toprule
 & 難易度\\
\midrule
材料調達 & {\fontspec{Noto Sans CJK JP} ★★☆☆☆ }\\
調理 & {\fontspec{Noto Sans CJK JP} ★★★☆☆ }\\
\bottomrule
\end{tabular}

### 材料

* 泡辣椒
  * 唐辛子
* 泡生姜
  * 生姜
* (共通) ピックル液
  * 水 適量
  * 塩 適量
  * (オプション) 桂皮
  * (オプション) 八角
  * (オプション) 胡椒粒

### 道具

* 清潔な密閉できる瓶

### 作り方

1. 水 500cc あたり塩大さじ1を加える
1. オプションのスパイスを加えて沸騰させる
1. 瓶に唐辛子または生姜を入れ, 上記のピックル液を入れて浸す
1. 冷暗所で**1ヶ月**ほど寝かせる

<!--chapter:end:08-extra.Rmd-->

# その他補足 {-}

* 中世編で生姜がしばしば使用されるが, 当時のヨーロッパには生の生姜はほとんどなく, もっぱら乾燥させた粉末だったと思われる.
* 華北の文化が主だろうが, @zuien の記述にも中華料理のヒントがある




<!--chapter:end:99-addendum.Rmd-->

