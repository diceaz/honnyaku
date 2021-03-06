Test Automation Problems Survey results
====

テスト自動化の問題点の調査結果
====

In February/March 2014, I put out a survey on Test Automation Problems (using surveymonkey.com). The main reason was to find out whether or not the problems we thought were common in automation actually were.

2014年2月から3月にかけて、テスト自動化における問題について調査を行いました（surveymonkey.comを使って）。調査の主な理由は、私たちがテスト自動化において実際に共通であると思っている問題が本当にそうなのかどうかを知りたかったからです。

The questions we asked are related to the “diagnostic questions” that we now have on the Test Automation Patterns wiki, which I am working on with Seretta Gamba. (See testautomationpatterns.org for a preview of an earlier version of the wiki and how to be invited).

私達が行った質問は、Seretta Gamba女史と一緒に作ったテスト自動化パターンWikiの「診断の質問」に関係しています。（testautomationpatterns.orgの早期のバージョンのWikiと招待方法を参照してください）

I publicised the survey on Twitter, LinkedIn, Test Automation Patterns wiki members, and by email to my random newsletter contacts list. A total of 183 responses are included in this report. Anyone who asked (and also left an email address there were half a dozen who didn’t!) has already received the results of the survey.

私はTwitterやLinkedIn、テスト自動化パターンWikiのメンバー、ニュースレターのコンタクトリストに調査結果を公表しました。全部で183ものレスポンスがこのレポートに含まれています。回答してくれた人たちには既にこの調査結果をお送りしています。（メールアドレスを残した人ですが、半ダースほどは残していませんでした）

I asked where people worked: 32% of respondents were from North America, 13% from the UK, 10% from Benelux countries. There were also responses from Scandinavia, other European countries, Japan, Malaysia, Australia/NZ, India, Israel, Poland and Romania.

回答してくれた人達が働いている国は、32%が北米で、13%が英国、10%がベルギーオランダルクセンブルクでした。その他にはスカンジナビアや他のヨーロッパ諸国、日本、マレーシア、オーストラリア、ニュージーランド、インド、イスラエル、ポーランド、ルーマニアでした。

Note that in the questions below, percentages may add to more than 100% because people could choose more than one option! I have picked out a few comments for each question, but have edited the text in some cases (for brevity & clarity).

以下、各質問を挙げていきますが一つ断っておきます。パーセンテージが100%を超えるのは、みなさんがひとつの意見だけではなく複数の意見を選択できるからです。私は各質問に対していくつかのコメントをピックアップしましたが、文章を少々編集しました。（簡潔さと明快さのためです）

The survey shows that there is a wide range of varied problems in test automation; no single one stood out as vastly more common. Many of the problems are related to expectations, management and “people” issues, but there are also significant technical problems. One surprise (for me) was that “unreliable execution” was the top problem in the category of unsatisfactory quality of automation.

調査結果はテスト自動化に幅広い様々な問題があることを示しています。はるかに一般的な問題として目立つものはありませんでした。多くの問題は、テスト自動化への期待やマネジメント、そして「人間系」に関連し、重要なテクニカルな問題もありました。（私にとって）一つのサプライズだったのは、「実行に信頼をおけないこと」が、不十分な自動化のクオリティのカテゴリで、トップの問題だったことです。

## Q1: Where are you in your current (system-level) test automation?
## Q1: テスト自動化のシステムレベルはどのくらい？

There are a lot of people in the “starting automation” stage: 12% first-timers, 10% restarting after failing earlier, and 23% starting to automate a new area (GUI, web
mobile etc.), for a total of 45% (which may include some overlap).

多くの人が「自動化のスタートライン」に立っていました。12%が初めての自動化で、10%が過去に自動化に失敗して再スタートを切ったところ、そして23%が新たなエリア（GUIやweb、モバイル等）で自動化を始めたところで、全体の45%でした。

However, 27% of people had significant (7%) or many problems (20%), and the winner in this category are those with automation that works pretty well but has minor problems (45%). The 10% of people who are completely satisfied with their automation does include some automation experts known to us!

27%の人は問題（重大な問題7%、多くの問題20%）を抱えていますが、このカテゴリで成功している人は自動化をうまく実施しているものの、些細な問題（45%）を抱えています。10%の人が完璧に彼らの自動化に満足していて、私達も知っている自動化のエキスパート達もこの中に入っています。

Here are some of the comments (showing some frustration):
いくつかのコメントを記載します。（少しフラストレーションがあるようです）：

>“Current automation runs satisfactorily but running on automation software which
has now become obsolete and unsupported. Awaiting purchase approval for a
different product, to start again from scratch. (but LONG wait! Over a year!!)” !

>"「現在の自動化はうまく運用できているが、自動化のソフトウェアが今では時代遅れでサポートされなくなっている。違う製品の導入の承認を待っているが、また一から始めないといけない。（長く待たされていて、1年にもなります！）」"

>“Tester’s creativity and ideas have been put down by upper management.” !

>"「テスターの創造性とアイデアは、上司に抑えられました。」"

>“We did start it up - but it went 'out of interest'. The reason was largely that the boss
didn't want to listen to the advice from several testers and developers about what
automatic regression testing can and can't do. Finally we ran out of money and had to
limit ourselves to manual regression testing and defect verification.”

>"「我々は着手しましたが、徐々に興味が薄れていきました。理由の大半はボスがテスターや開発者のリグレッションテストでできること、できないことのアドバイスを聞こうとしなかったからです。最終的に予算がなくなり、手動でリグレッションテストと欠陥評価を行わざるを得なくなりました。」"

##Q2: What problems do you currently have?
##Q2: 今どんな問題をかかえていますか？

We were a bit surprised to see that the responses cover the range of automation problems fairly equally, although there was a clear “winner” in lack of resources (57%), with lack of specific knowledge 2nd at 41%. The others were all roughly 30% with other at 22%.

41%で仕様の知識不足の問題を持つ答えが、リソース不足(57%)に明瞭な「勝者」の次にいましたが、自動化の問題の範囲をかなり等しくカバーすることを理解して、私たちは少し驚きました。他の人たちはおよそ30%で、抱えている他の問題が22%でした。

Comments included one poor soul who said,“We have gone too far down a certain path to be able to change.”I would challenge that change might be difficult, but without changing, yourautomation is probably doomed (maybe that’s what the respondent meant.)

小心な人のコメントでは、「変わることができる確かなパスのかなり下のほうを行ってしまった。」変わることは難しいだろうがチャレンジしないといけません。変わること無しでは自動化はおそらく運が尽きます（たぶん回答者が言いたいことです）。

Other comments:

その他のコメント：

“There are a lot of people who think they know what to do, because they read something on the internet. Therefore it is sometimes hard to make a plan, convince the boss and stay on track. Typically the bosses don't want to hear about the cost of maintaining a test suite, since the tool vendors typically promise something that other people have to deliver ...”

>"「何をすべきか知っている人はかなりいます。彼らはなにかをインターネットから情報を得ているからです。それゆえ時に計画を立てるのが難しいのですが、ボスを確信させて軌道に乗せてください。概してボスは、テストスイートのツールベンダーが他の人々に必要だと約束したことへのメンテナンスコストを聞きたくはないのです。"

>“Lack of discipline. The BAs and developers know they should do it, and (mostly) have the skills, there is the direction from the top (at least from the top of the development org chart) but they lack the discipline and/or culture to do it consistently.”

>"「修練不足。ビジネスアナリストと開発者は修練をすべきことを知っているし、大抵の場合スキルも持っているが、トップ（少なくとも開発組織上の）の指揮はあるものの、修練不足かもしくは首尾一貫して修練する文化がないかである。」"

We then asked more specific questions about each of these major problem areas, in Questions 3 to 7.

我々は質問3から7でこれらのメジャーな問題エリアへの明確な質問をしています。

##Q3: Lack of support:
##Q3: サポート不足：

The “winner” in this category was managers expecting a “silver bullet” (54%), but developers not helping the automation team came out at 39%. The Other category included specialists not helping the automation team and no-one helping new people.

このカテゴリの勝者は解決策を予期しているマネージャ（54%）だが、自動化チームのサポートをしない開発者が39%につけています。その他には自動化チームをサポートしないかつ、新人もサポートしないスペシャリストが入っています。

Comments:

>“There is management support at the engineering level, however higher up the chain we are getting resistance (from product owners, stakeholders) who fail to understand the importance of test regression, and therefore feel that money spent upfront in building a regression suite is waste.”

>"「エンジニアリングのレベルでマネジメントのサポートはあるものの、
我々は（プロダクトオーナーやステークホルダーから）抵抗にあいます。彼らはリグレッションテストの重要性を理解できず、またそれゆえにリグレッションスイートは無駄で前払いでお金を使うことと感じているのです。」"

>“As for management, ROI seems to be [in the] driver's seat all throughout the
program. Team looses focus to create quality test suites with good test technique.”

>"「マネジメントにとっては、ROIがプログラムを通じて支配的地位を占めます。チームは素晴らしいテストテクニックでテストスイートの品質を作りこむことへの意識を失っています。」"

>“I think everyone sees the benefit of automation but if you use vendors, particularly
offshore then how are they incentivized to do process improvement (including
automation)? It's easy to demonstrate the advantages of automation but it requires
other people to be onboard to ensure that manual test cases are good quality, and the
test environments (particularly complex ones) are in a state that you can develop
automated script successfully against them.”

>"「自動化の利益は知っていると思いますが、もしベンダーをつかったら、とりわけオフショアを使う場合には、どのようにして彼らにプロセス改善を動機づけられますか？
自動化の利点をデモンストレーションすることは簡単ですが、自動化は逆説的に、手動テストは良い品質で、かつテスト環境（特に複雑系）は彼らに対して自動化スクリプトを上手に作れることを示せるということを保証してしまうのです。」"

>“Very often it is an 'either-or' when you try to sell automation to the project
management; you may have Automatic Unit Testing together with Continuous
Integration or you may have Automatic Regression Testing on the UI or you may
pursue exploratory testing. In general; the test project will rarely be allotted sufficient
resources to implement a successful automatic testing. Therefore successful
automators are hard to find.”

>"「自動化をプロジェクト・マネジメントに売ろうとするとき、大抵二者択一です。自動ユニットテストとCIか、UIの自動リグレッションテストとか探索的テストの追求です。普通は、テストプロジェクトは自動テストを成功裏にインプリメントするのに十分なリソース分配できることは稀です。よってオートメータを見つけるのは大変なのです。」

##Q4: Lack of resources
##Q4: リソース不足

The major factor here is no time or insufficient time being planned for automation
work 63%. The next two, training for automation not planned, and expenses not
budgeted were at 37% and 35% respectively. The rest were approximately 20%.
Some interesting comments in this section:

この質問で多勢を占めるのは自動化を計画できる時間が全くないか、とても限られることで63%です。次に続く2つが、自動化のトレーニングが計画されないことと、経費が予算化されていないことで、それぞれ37%と35%です。残りはほぼ20%です。

以下興味深いコメントをいくつか：

>“If the entire IT group worked on automation for 6 months, we’d be in parity with
development.”

>"「もし全ITグループが6ヶ月間自動化に取り組めば、開発と同等になります。」"

>“Automation doesn’t work well in a project-driven organisation - project managers
don’t see beyond their project.”

>"「プロジェクトを回している組織では、自動化はうまく動きません。- プロジェクトマネージャは彼らのプロジェクトを超えて見ませんから。」"

>“While you’re busy delivery [good automation], you forget to watch your back and
run into a political ambush - being considered an ‘expensive error’ by the next ‘rising
star’.”

>"「いそいそと良い自動化をデリバーしている間は、後ろを振り返ることを忘れて政治的待ちぶせに足を踏みいれてしまいます - 次世代タレントに’高価なエラー’であると考えられる。」"

##Q5: Lack of direction
##Q5: 方向性の欠如

For this question, respondents needed to choose the one option that best applied,
rather than being able to tick as many as applied (so the percentage values are lower).
The most common problem here was automation being done without a strategy or
architecture (27%), followed by testers doing automation don’t know how to do it
well (19%). Only 8% voted for no-one being in charge of automation, everyone does
what they want.

この質問は、（パーセンテージがより低いように）多くのものをチェックすることができるというよりかは、最もあてはまる1つを選ぶ必要がありました。ここでの最も多くの問題は戦略あるいはアーキテクチャ無しでの自動化が行われているということでした（27%）。続くのが、テスターはどうやってうまいこと自動化するかを知らずにやっていることです（19%）。8%だけ誰も自動化を担当しておらず、皆好きなことをしていると回答しています。


Comments:

>“Testers/management think they have to automate the manual test cases as is, and
hire an automator to do that job - any issues resulting from this setup are blamed on
‘bad automation’"

>"「テスターあるいはマネジメントは手動テストケースをそのまま自動化するべきと考えていて、その通りにこなしてくれるオートメータを採用します - この状況こそが、’悪い自動化’の原因である。」"

>“Perhaps it is not 'lack' of direction but more 'wrong' direction as it relates to an
earlier statement: "Managers expect a silver bullet" and therefore insist on
automating basically everything (which is obviously not possible, nor efficient let
alone useful..) “

>"「おそらくは方向性の’欠如’ではなくて、早い段階での声明が起因するより’悪い’方向性なのではないか：”マネージャは解決策を望む”それゆえ自動化が基本的にすべてであると（役に立つことは言うまでもなく、明らかに可能でもないし、効率的でもありません）。」

>“Each application group is doing their own thing, multiple tools and frameworks with
no overall architecture for cross-platform, cross-application automation. “
>"「各アプリケーションチームは彼ら独自のことをしていて、クロスプラットフォームやクロスアプリケーションをカバーする自動化のツールやフレームワークを考えていません。」"


##Q6: Lack of specific knowledge
##Q6: ナレッジ不足

The two highest responses here are The people that are to use the tool don’t know
how to use it (38%) and Testers are supposed to write automation scripts but don’t
know how (34%). For 30%, the automators don’t know the application [whose tests]
they are automating. The least popular response was 9% where the only one who
knew about automation has left the company. The remaining responses were all
between 21% and 25%.

どのようにしてツールを使うか知らない（38%）と、テスターはどのようにしてスクリプトを書くか知らない（34%）という2つの回答が目立ちました。そして30%がオートメータは自動化しようとしているテスト対象のアプリケーションを知らないという回答でした。最も少なかったのが9%で、唯一自動化を知っている人が会社を去ったことでした。残りは21%と25%の間でした。

Comments:

>“People requesting automated tests have unrealistic expectations of what can be
automated or how long it will take. “

>"「テスト自動化は、何が自動化できるのかどのくらいかかるのか、非現実的な期待を寄せられます。」"

>“The tool is selected by the umpire: 'Look - we HAVE this tool. Make do with that -
somebody told me that it can get the job done, so I don't wanna hear that YOU can't
do it...'”

>"「ツールは審判に決められます：’ほら、このツールがあるじゃないか。これでできるって誰かが言ってたし、できないなんて聞きたくないんだ。’」"

>“The testers are generally well-informed but lack management and governance. It is
also a large test team moving towards DevOps and Continuous testing but are
constantly beset by co-ordination problems, a lack of direction and real management
and DB set up problems. (Each test environment is over 100GB because they are
dealing with large media files) “

>"「テスターは大抵精通しているが、マネジメントや管理が残念だ。大きなテストチームはDevOpsや継続的テストに向かっているが絶えず同じ問題に付きまとわれている。方向性やマネジメントの欠如、DBのセットアップの問題など（テスト環境は大きなメディアファイルを扱うので100GBを超える）。」"

>“New application being built and automated at the same time. Issues with build
constantly changing, application knowledge, disconnect between vendor builders,
scripter and automators. We are still working out how this process will work best. “

>"「新しいアプリはビルドされると同時に自動化される。ビルドは常に変化し、アプリ知識も変わり、ベンダービルダー、スクリプタ、オートメータにすれ違いがおきる。我々は未だにこのプロセスをベストに回すやり方を編み出していないのだ。」"

>“How to measure effeciency of automated tests? “ (a very good question!)

>"「自動化されたテストの効果的な測り方は？」"

##Q7: Unsatisfactory quality of automation
##Q7: 自動化のいただけない品質

The most common problem here was a bit of a surprise (to me) it is Automated
scripts don’t execute reliably (50%). The runner-up in this category is Maintenance of
automation is too expensive (44%). The 3rd is Expected Return on Investment (ROI)
has not been achieved (34%). Two factors were voted in by 28% of respondents:
Execution of automated scripts is too slow and Important tests have not been
automated, only easy ones. The rest were all approximately 20%.

ここでの一番の問題点は少し驚きで、自動化スクリプトの実行に信頼をおけない（50%）。
次点が自動化の保守費がとても高いことでした（44%）。3番目が期待したROIに届かなかったこと（34%）。28%の回答が、自動化の実行がとても遅いことと、重要度の高いテストは自動化されずに簡単なテストのみ自動化されるという2つのファクターがありました。残りはほぼ20%でした。

Comments:

>“The biggest problem by far is inadequate requirements management.”
>"「最大の問題は、不十分な要求管理だ。」"

>“Most test environments require too much simulation behavior (mocks) which means
that coverage is rather low or people do not trust the results.”

>"「多くのテスト環境は、カバレッジが低く結果が信じがたいシミュレーションの振る舞いのようだ。」"

>“The above all depends on vendor and quality of the resource. Typically where I have
used a UK test company the quality is generally good, but where the work is
predominantly done offshore then they struggle with key basic concepts. Offshore
SHOULD only be used for factory level development of basic scripts, not for any
automated scripts which require some clever development or for any innovation.
What I have experienced is the common sense element is just not there, but where it
has worked is where the framework is developed onsite and then basic stuff is rolled
out offshore where the manager goes offshore as well to manage the work.”

>"「結局はベンダーとリソースの品質次第なのだ。UKのテスト会社の品質は概ね良かったのだが、ほとんどオフショアを使っていて、彼らはベーシックコンセプトに取り組んでいた。オフショアは基本スクリプトを開発するなど工場レベルの仕事に使うべきで、自動スクリプトを含むような賢明な開発やイノベーションを期待し任せてはならない。私が経験したのは常識的なことで、フレームワークはオンサイトで開発され、基本スタッフはマネージャがうまく管理できるオフショアに任すということだった。」"

###Automation books

I listed six books on test automation, and asked if people had heard of them, read
them, and/or recommended them. I was pleased to see that my own two books seemed
to be the best known, most read, and most recommended! But then, I did send this
survey to a lot of people who I already knew! Each book was recommended by at
least 3 people (and mine by over 20 - :&)

テスト自動化の本をリストアップしておきました。読んでみるといいよ。

Thanks to one respondent for this:

>“Experiences of Test Automation: Case Studies is probably the only other book to do
a decent job balancing the technical side and the management side.”

>"「テスト自動化の経験：ケーススタディーこそテクニカルとマネジメントの両面でバランスをとって適切な仕事を成し遂げるもう一つの本である。」"

There were also a number of suggestions for other books on automation, as well as
mentions of blogs, etc.
他にもブログとかで挙げられる自動化のサジェッションに富んだ他の本もあるよ。

- The “A” Word, Alan Page (download from leanpub new to me, interesting
short blog posts about automation, including why not to do [much] GUI
automation well worth a read)
- Automated Testing Handbook, Linda Hayes (re-published in 2004 but looks to
be the same content as the 1995 version I have. A good summary of
automation principles good for high level managers?)
- Lessons Learned in Software Testing, Kaner, Bach & Pettichord (very good
book on testing with useful automation wisdom too)
- How Google Tests Software, Whittaker, Arbon & Carollo
- Testautomatsierung, Seidl, Baumgartner & Bucsics

The following books are more technical; I am not familiar with them.

これらは技術的な本です。あまり詳しくないけど。

- .NET Test Automation Recipes, James McCaffrey (mainly good reviews)
- Next Generation Java Testing: TestNG and Advanced Concepts, Cedric Beust
& Hani Suleiman. (written by the author of TestNG, mixed reviews.)
- QTP Unplugged, Tarun Lalwani
- Java Power Tools
- Django 1.1 Testing and Debugging
- The Cucumber Book: Behaviour-Driven Development for Testers and
Developers, Wynne & Hellesoy
- ATDD by Example, Gartner
- Continuous Delivery, Humble & Farley

Thanks to all those who took the time to fill in the survey!
答えてくれた皆さんに感謝します！

Dorothy Graham, 27th March 2014
