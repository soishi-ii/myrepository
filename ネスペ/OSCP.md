【RTA in 無職】OSCP合格 any% glitchless 半年
OSCP
最終更新日 2023年03月22日
投稿日 2023年03月18日
TRY HARDERは嘘
always try smarter before harder.

この記事需要あるか？
OSCPに無事合格したのでその過程を説明する記事。
こんな事が重要なんだフーンくらいに斜め読みしてほしい。

TL;DR.
ぶっちゃけどれくらいやるの？と言われると、私は100台近く攻略した、絶対落ちないように念には念を入れて準備をした。
人によっては10台攻略しただけでコツ掴んで合格したという報告もあるので時の運もあると思う。

正直OSCP LABの価値は複数ネットワーク環境であって、proxychainsを通した反応を見れることにあると思う、それとAD環境が２つあること。

この記事に限らず合格体験記を読み漁ろう。
THM Linux/Windows　Privescを完璧にする。
ぶっちゃけテキストはざっと１週目を通して２週目にしっかり読むのがよさそう。私は最終的に３週した。

３か月で受かるの正直キツイので先にProving Grounds Playの問題をVulnhubからDLしたり、Practiceを契約しよう、ぶっちゃけPracticeのHard Machinesがスラスラ解けるならOSCPなんて余裕。

情報はOnenoteに纏める

6月
何の準備も無しにOSCPを購入、正直今になって思うと大馬鹿も大馬鹿な決断だったと思う。

３日掛かって解けません！みたいな状況でLearning Path Machinesの攻略もおぼつかない。Forumsを濫用して踏み倒していくスタイルだった、正直学習法としては非常に効率が悪かったと思う。

7月
１日１台レベルには解けるようになっていた記憶、それでもフォーラム便りで正直無理だよねこれじゃって感じだった
多分20台くらいが攻略数

8月
EXAMが近づいていたのでone noteの整理と既に解いたマシンの復習に時間を掛けることに、正直この判断は間違っていなかったが単純に実力が足りておらず・・・
ここまで多分25台くらい

EXAM
不合格おめでとう
多分50点くらいは取れてたんじゃないだろうか？という感じ
この辺から、この資格難しくね？と本気で集中しだすようになる。
正直OSCPを舐めていた。

9月
TryHackMeで時間を潰す
Windows/Linux PrivEscのroomを行い、Offensive Pentestingを完全制覇。
だがAD部分は完全にOSCPを越えているのでやらなくてよいと感じた。

10月
HTB、VulnhubやProving Groundsで時間を潰す

Proving Groundsのplayはvulnhubから拾ってきて無料で解くことができる。
proving groundsの一月契約がなんやかんやでいいかもしれない、OSCPをはるかに超える難易度の物もあるが、いわゆるCTF nonsenseな問題がない。

11月
１月契約でOSCPラボを55マシン攻略
踏み台無しのマシンはスラスラ解ける、踏み台ありのマシンは正直コマンドに時間かかりすぎてウンザリぎみで解いていた。

EXAM
5時間で合格、満点。OneNoteを徹底して「これ見たことあるわ！スラスラ」とできたのと、Enumeration Checklistに限らずとにかく全てを疑って１行１行細かく見るようになったのが大きな違いだったと思う。

総括
hacktricks、GTFObinsは常に見る。
ippsecは神、見ておく。

これから受ける人にお勧めする方法は

1.まずはProving grounds playにあるマシンをvulnhubから拾って攻略する。
2.tryhackmeのWindows/Linux Privescルームは必ずやる。
3.Proving Grounds Practiceを契約する、mediumあたりは大体解けますよくらいまでは練習したい。
4.OSCPを契約する、この時点である程度慣れていて、踏み台無しで転がっているマシンはなぎ倒せるくらいの実力がついているとヨシ。