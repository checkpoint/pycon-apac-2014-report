=======================================
 「PyCon APAC 2014」 レポート ～二日目
=======================================

台湾で開催された `PyCon APAC 2014 <https://tw.pycon.org/2014apac/ja/>`_ の参加レポート第2弾になります。本稿ではイベント二日目の様子をお届けします。


二日目
======

Keynote speech: Jessica McKellar
--------------------------------------

宵です。Jessica McKellar氏はPython Software Foundation(PSF)のディレクターをつとめていて、またボストンのPythonユーザグループを運営しています。さらにソフトウェアエンジニア、起業家としても活躍しています。このキーノートでは、様々な場所で使われているPythonについての紹介を行ってました。低いとこでは海底、高いとこでは宇宙ステーションでの利用例を紹介していました。また様々なプラットフォーム（Linux、Windows、モバイル）や科学技術の分野での利用例も紹介していました。

.. figure:: /_static/second/jessica_1.jpg
   :height: 400

   Jessica McKellar氏（１）


.. figure:: /_static/second/jessica_2.jpg
   :height: 400

   Jessica McKellar氏（２）

.. figure:: /_static/second/jessica_3.jpg
    :height: 400

    Jessica McKellar氏（３）

Keynote speech: Andreas Klöckner
--------------------------------------

関根です。次の基調講演はAndreas Klöckner氏が登壇しました。ハードウェアを利用したPythonによる並列コンピューティングに関する内容でした。まずは並列コンピューティングに関するプログラミングモデルの概要を説明し、OpenCLなどの並列コンピューティングのフレームワークの紹介をしていました。その後でPythonから利用できる `PyOpenCL <http://mathema.tician.de/software/pyopencl/>`_ や、`PyCUDA <http://mathema.tician.de/software/pycuda/>`_ の説明を行い、実際のデモに移りました。デモでは実際に画面上からPythonコードを入力し、結果を表示していました。インタラクティブなセッションだったのでとてもイメージが掴みやすかったです。

.. figure:: /_static/second/andreas.jpg
   :height: 400

   Andreas Klöckner氏

Keynote speech: Rapid Web Development with Mezzanine
--------------------------------------------------------

最後の基調講演はStephen McDonald氏が登壇しました。Djangoの上に構築された `Mezzanine <http://mezzanine.jupo.org/>`_ というCMSの紹介でした。なぜ他のCMSではなくMezzanineが良いのか、またDjango上に構築されている利点などについて説明がありました。Batteries Includedというキーワードの通り、あらかじめ必要な機能は一通りそろっている印象でした。管理画面なども洗練されていて使いやすようなUIでした。なによりDjangoアプリケーションなので開発者としては一度触ってみたくなるプロダクトでした。

.. figure:: /_static/second/stephen_1.jpg
   :height: 400

   Stephen McDonald氏（１）

.. figure:: /_static/second/stephen_2.jpg
   :height: 400

   Stephen McDonald氏（２）

- 資料: https://speakerdeck.com/stephenmcd/rapid-web-development-with-mezzanine

PyConAPACパネル
-----------------------------

寺田です。2日目の午前中に、APAC community panelと題しアジア各国のPyCon代表者が集まって議論を行いました。
このパネルディスカッションは、昨年日本で行われたPyCon APAC 2013 in Japanにおいて、シンガポールと台湾から座長経験者が参加いただいたことから急遽行ったものを、本格的に準備をし、今年のPyCon APAC in Taipeiでも行うことになりました。

パネリストはは以下のとおりです。

司会: Iqbal Abdullah (日本 & マレーシア)

パネリスト:

- Liew Beng Keat (シンガポール)
- Yung-Yu Chen (台湾)
- 寺田　学 (日本)
- Mark Steve Samson (フィリピン)
- Kwon-Han Bae (韓国)
- Zaki Akhmad (インドネシア)
- Jessica McKellar (PSFメンバー・アメリカ)

.. figure:: /_static/second/APAC_Panel.jpg
   :height: 400

   APAC community panelのパネリスト 【左から(国記号で)、US/TW/KR/PH/MY/SG/ID/JP】


今回は、多くの国・地域のPyConを中心的に支えているメンバーが集まり、各PyConの状況や困っていることを持ち寄り、今後のAPAC地域(アジア太平洋地域)で開催されるPyConやPyCon APACの将来について話し合いが行われました。当初は1時間枠でパネルディスカッションを行う予定でしたが、30分以上延長し、さらにランチを食べながら議論を継続していました。

パネルディスカッションの最初は、パネリストが順番に自己紹介と各国の開催状況の説明を行いました。2010年から開催しているシンガポールや2012年から開催の台湾、そして2011年から開催している日本が、今までのAPACコミュニティの中心でした。既に2回開催しているフィリピンや今年春にmini PyConを開催したマレーシア、これから国内で開催を予定している韓国やインドネシアといった各国で置かれている状況の違いや運営スタイルの違いなどがわかってきました。

その後、来年のPyCon APACの開催地について、今回と同じく台北で行うか、又はフィリピン・マニラで行う方向で調整を進めることになりました。議論の中では、シンガポールや東京といった滞在コストの高い場所ばかりでやるより、多少でもコストが抑えられることは、地域全体のPythonユーザに取って有益なことだということになりました。私自身さほど感じていなかった視点でしたが、言われてみると、台湾でのPyCon APACにはアジア各国からの参加者が多く感じました。反対に、日本でのPyCon APACには北米やヨーロッパからの来場者が多いと改めて感じた次第です。

各国のPyConが抱えている問題について、議論がありました。一つにはスポンサーの獲得について、地域の企業だけでなくグローバル企業をスポンサーとして獲得したいという事もあり、PSF(Python Software Foundation)からの支援や紹介をしてもらえないかという話が出ていました。

さらに、APAC共通の資金を持ってはどうかといった視点や、教育関係・学生への支援、アジアからPSFのボードに誰もいないことについても議論がありました。
今回のAPACパネルディスカッションは、確実に参加国を増やすことができましたが、まだオーストラリアやタイ、インドなどの国を取り込めていないことが課題として残っていると感じています。

私自身、英語でのパネルディスカッションということで非常に緊張しましたし、うまく伝えきれないところが有りましたが、日本で一緒にPyConスタッフをしている司会のIqbal氏に助けられ、なんとかなったかと思います。今後のためにも英語の勉強をしていかなければと思い知らされる半日でした。


What Is Async, How Does It Work, and When Should I Use It?
----------------------------------------------------------

宵です。このセッションではPythonの非同期処理(Async)について語っていました。
まず例として、客がピザを注文してから焼きあがるのを待つのと、板前におまかせと言って勝手に出てくる寿司を受け取る場合を挙げて、同期/非同期の違いについて説明を行っていました。またC10K問題( クライアントが1万台のオーダーになったとき処理が捌ききれなく問題 )にも触れ、最後にPythonでの非同期通信の方法としてtwisted, tornedo、そしてPython3.4から標準搭載となったasyncioについての説明を行っていました。

.. figure:: /_static/second/jesse_1.jpg
   :height: 400

   A.Jesse Jiryu Davis氏（１）

.. figure:: /_static/second/jesse_2.jpg
   :height: 400

   A.Jesse Jiryu Davis氏（２）

- スピーカー: A. Jesse Jiryu Davis
- リンク: https://tw.pycon.org/2014apac/ja/program/53

Social Network Analysis with Python
-----------------------------------

FacebookのOAuth経由APIを使って、イイネ！ボタン押したユーザ数とか友達ユーザクラスタの検出などを行ってました。実際にその場で実行しており、見ていてとてもわかり易い発表でした。また発表中、中国語(マンダリン)の単語分割器JIEBA(日本でいうとこのMeCabの単語分割部分のみってところ)の紹介があり、それを使ったツールも紹介されていました。日本人の私がそのツールを使ってもJIEBAによって漢字部分だけ抽出されていました。


.. figure:: /_static/second/social_analysis.jpg
   :height: 400

   David Chiu氏

- スピーカー: David Chiu
- リンク: https://tw.pycon.org/2014apac/ja/program/46

Designing a Python-integrated query language for distributed computing
----------------------------------------------------------------------

集計、JOINに特化した分散環境言語、Socialiteの紹介をしていました。Pythonから呼ぶことができ、文法はErlangのようでした。比較対象としてHadoop上で動くJiraphも挙げている部分が面白いと感じました。ただこの辺ってSparkもそうですがSQLに似た言語の方が好まれる感じもするのですが如何なんでしょうか。Hadoop(MapReduce)の場合Hive, Sparkの場合Shark, SparkSQLといったのがSQLライクな言語としてあります。

- リンク: https://tw.pycon.org/2014apac/ja/program/37
- スピーカー: Jiwon Seo
- github: http://socialite-lang.github.io/


Python Performance Profiling: The Guts And The Glory
----------------------------------------------------------------------

関根です。MongoDBに勤務するA. Jesse Jiryu Davis氏によるパフォーマンスのプロファイリングのお話でした。PyMongoの事例を元に、`Yappi <http://https://code.google.com/p/yappi/>`_ を利用してどうやってプロファイリングするか、また少ない努力でどうやって最大限の効果を引き出せば良いかの説明をしていました。Yappiについては初めて知ったのでとても参考になりました。

- リンク: https://tw.pycon.org/2014apac/ja/program/54
- スピーカー: A. Jesse Jiryu Davis


Narrowing the Gender Gap at Hackathons
----------------------------------------------------------------------

MongoDBに勤務するAmalia Hawkins氏による、ハッカソンにおいてのGender Gapをどうやって少なくしているかの説明でした。ハッカソンを女性のために改善していくことは、すべての人に対して改善していくのと同じだと述べてました。ハッカソンは協力であり競争ではないという事、また今後の新しいハッカソンの形などを紹介していて、非常に参考になりました。これからハッカソンなどを開催する機会があれば、ぜひ参考にしていきたいです。


.. figure:: /_static/second/amalia_1.jpg
   :height: 400

   Amalia Hawkins氏（１）

.. figure:: /_static/second/amalia_2.jpg
   :height: 400

   Amalia Hawkins氏（２）

- リンク: https://tw.pycon.org/2014apac/ja/program/75
- スピーカー: Amalia Hawkins
- 資料: https://speakerdeck.com/hawka/narrowing-the-gender-gap-at-hackathons


会場の雰囲気
-----------------------------

ここでは簡単に会期中の会場の雰囲気についてご紹介します。
会期中は昼にランチタイム、午後にティーブレイクが設けられていました。
ランチでは2日間ともお弁当を頂きました。とても美味しく、ボリュームもあり満足できる内容でした。
お弁当を食べる場所は複数あったので、それぞれ好きな場所でゆったりと食事をする事ができました。

.. figure:: /_static/second/lunch_1.jpg
   :height: 400

   ランチ会場

.. figure:: /_static/second/lunch_2.jpg
   :height: 400

   お弁当（１日目）

.. figure:: /_static/second/lunch_3.jpg
   :height: 400

   お弁当（２日目）


ティーブレイクでは、小籠包、お菓子、フルーツなどが提供されていました。
またスポンサーによるコーヒーやお茶なども提供されており、とても充実した内容でした。
軽食しながら休んだり、他の方と交流したり、それぞれが楽しみながら、ティーブレイクを過ごしていたようです。

.. figure:: /_static/second/tea_break_1.jpg
   :height: 400

   ティーブレイクのお菓子

.. figure:: /_static/second/tea_break_2.jpg
   :height: 400

   スポンサーによるお茶の提供

クロージング
-----------------------------

2日間にかけて行われたPyCon APAC 2014も終わりの時を迎えました。
まずは、会期中に撮影した写真をスライドショーにして表示しました。
2日間という短い期間でしたが、非常に内容の濃い充実した2日間だったと思いました。

次にChairperson（座長）であるWen-Chang "Tim" Hsu氏が壇上に上がり、スピーチを行いました。
スピーチの内容は中国語だったので、詳しい事はわからなかったのですが、感謝の言葉を述べているようでした。

スピーチの最中に、スタッフからWen-Chang "Tim" Hsu氏へ花束のプレゼントがありました。
丁度この日Wen-Chang "Tim" Hsu氏の誕生日だったようです。会場にいる方々からも大きな拍手がありました。

.. figure:: /_static/second/closing.jpg
   :height: 400

   Wen-Chang "Tim" Hsu氏のスピーチ

こうして2日間にわたるPyCon APAC 2014が終了し、最後に参加メンバーで記念撮影を行いました。


.. figure:: /_static/second/group.jpg
   :height: 400

   全体集合写真

ディナー
-----------------------------

寺田です。台湾でのPyConでは恒例となっている、クロージング後のスタッフディナーに参加してきました。
参加者は、現地のスタッフや講演者及び海外からのゲストたちでした。特に形式張ったディナーではなく、カフェテリアでビュッフェスタイルで行われました。日本からも8名ほど参加しました。

最初に、座長のTim Hsu氏から「スタート」の号令があり、参加者がテーブルから立上り食事を取りに行き各々食事を楽しみました。一部のメンバーのみビールを飲んでいましたが、個別に購入したものとのことでしたので私も思わず台湾ビールを頼みました。
約2時間、自由に食事したり、会話をして流れ解散となりました。

私は、韓国から来ていたPyConメンバーとじっくり話をしたいと考えていたので、今年開催を予定しているPyCon KRについて、状況を聞いたり、具体的な案の相談をしました。先日正式に今年の8月30日にソウルで `PyCon KR <http://www.pycon.kr/>`_ が開催されることになりました。
他には、5年来の付き合いになる台湾のPloneユーザグループのリーダであり、PyCon APACのスタッフでもあるTsungWei Hu氏と近況報告をお互いにしました。

いろいろな友達が作れたり、海外から参加しても楽しく過ごせるようなこの会に参加できたことは非常に良かったと思います。

.. figure:: /_static/second/dinner_1.jpg
   :height: 400

   カフェテリア

.. figure:: /_static/second/dinner_2.jpg
   :height: 400

   ディナーの様子

PyCon APAC 2014の運営者へのインタビュー
----------------------------------------------------------

関根です。スタッフディナーの時にカフェテリアの外でPyCon TaiwanのChairperson（座長）であるWen-Chang "Tim" Hsu氏に時間をとって頂き，私と寺田さんでインタビューを行いました。

.. figure:: /_static/second/interview_1.jpg
   :height: 400

   インタビューに答える Wen-Chang "Tim" Hsu氏

**参加者とその内訳を教えて頂けますか。**

全体で650名ほどの方が参加してくれました。9割が台湾からの参加者で、残りの1割が海外からの参加者でした。マレーシア、シンガポール、インドネシア、フィリピン、日本、韓国、カナダ、アメリカなどの国々から参加して頂けました。

**今回からFLTが始まりましたが、FLTの感触はいかがでしたか。**

FLTについては特にアテンドはせず、こちらでは準備だけを行いました。LTは少し長いと感じており、短い方が良いと考えました。

**SciPyのような科学技術関連のセッションがたくさんありましたが、運営側として働きかけはしましたか。**

科学技術関連には強さ、ポテンシャルがあり、そういう技術者の方に新しいきっかけを与えたいと思いました。科学には強さがあり、産業としてお金を稼ぐ事もできます。科学とコンピューティングが、合流することは、とてもエキサイティングだと思いました。

**今回からチェアマン（座長）になりました。とても大変だと思いますが、なぜチェアマン（座長）になると決心しましたか。**

とてもシンプルです。Pythonはとても素晴らしく、私はコミュニティがより良く成長する事を望んでいます。さらにコミュニティに貢献する事ができるのなら、それは私にとっても良い機会だと思いました。

**最後に日本のPythonistaへメッセージをお願いします。**

Pythonのコミュニティはとてもに素晴らしく、また日々コミュニティも成長しています。台湾のPythonistaはとてもクールですが、日本のPythonistaもまたクールです。

**どうもありがとうございました。**

お忙しい中、貴重なお時間を頂いてインタビューに回答して頂きました。英語でのインタビューという事で、質問をうまく伝える事が出来ずだいぶご迷惑をおかけしましが、本当に丁寧に回答して頂き感謝しています。

.. figure:: /_static/second/interview_2.jpg
   :height: 400

   記念撮影

日本からのスポンサーシップ
-----------------------------

今回は日本から `株式会社HDE <http://www.hde.co.jp/>`_ が、MongoDB, Googleと並ぶゴールドスポンサーとして、CTOの小椋氏以下4名で参加しブースを出展していました。同社は企業向けのクラウド型セキュリティサービス「HDE One」を提供する会社ですが、その大部分はPythonで書かれており、グローバル人材を採用する一環でスポンサーとして手を挙げたそうです。『ブースに来る台湾人Pythonista達が、英語に加えて日本語も堪能なのに大変驚き、良い感触を得た』とのことです。

同社では奇しくもMongoDBもハードユースしているそうで、一同、MongoDBの著名な非同期ライブラリ「motor」の作者A. Jesse Jiryu Davis氏のセッションに大興奮していたほか、セッションの合間合間に出てくる大量のおやつに感激していました。

.. figure:: /_static/second/HDE.jpg
   :height: 400

   HDEの皆さん

PyCon JP 2014のお知らせ
=========================

.. figure:: /_static/second/pycon2014-logo.png

   PyCon JP 2014

最後に宣伝です。執筆者もスタッフとして参加している `PyCon JP 2014 <https://pycon.jp/2014/>`_ が9月中旬に東京で開催されます。開催概要は以下の通りです。

:チュートリアル: 2014年9月12日（金）
:カンファレンス: 2014年9月13日（土），14日（日）
:開発スプリント: 2014年9月15日（月・祝）
:テーマ: Pythonで再発見 / Rediscover with Python
:会場: `東京国際交流館プラザ平成 <http://www.jasso.go.jp/tiec/plazaheisei.html>`_
:参加者数(予定): 500

現在， `演題の募集（Call for Proposals） <https://pycon.jp/2014/speaking/cfp/>`_ をしています。トークセッションの募集締め切りは6月20日です。みなさんからの応募をお待ちしています。

PyCon JP 2014の参加チケットは `connpass <http://pyconjp.connpass.com/event/6300/>`_ にて発売中です！ 参加者・発表者のみなさんが楽しく有意義な時間を過ごす事ができるように、スタッフ全員で準備を進めています。
では，PyCon JP 2014でお会いしましょう!!
