了解しました。  
ここでは **「OSCPを12月31日に購入 → 2026年取得を目指す」ための準備期間（2025年5月〜12月）** に対応した「**週単位のToDoリスト（全7か月）**」を作成します。

---

# 【OSCP準備：週単位ToDoリスト】

## ◆ フェーズ1：基礎体力作り（5月〜6月｜8週間）

### Week 1〜2（5月下旬）

- Linuxの基礎構造を学ぶ（ファイル階層、ユーザーと権限）
- `ls`, `cat`, `chmod`, `find`, `grep`, `scp`などコマンド練習
- TryHackMe「Linux Fundamentals 1」開始
- Kali Linuxのインストール＆基本操作確認

### Week 3〜4

- Windowsの基礎構造（レジストリ、ユーザー、サービス）学習
- TryHackMe「Windows Fundamentals 1〜2」
- コマンド練習（`net user`, `tasklist`, `sc`, `reg`）
- TryHackMeでPre-Securityパス完了

### Week 5〜6

- 簡単なファイル転送方法（`python -m http.server`, `smb`, `nc`）の習得
- VM間でファイルを送るテスト（Kali ⇄ Windows）
- `nmap`, `gobuster`などツールの基本操作を覚える

### Week 7〜8（6月下旬）

- TryHackMe「Intro to Offensive Security」パスへ移行
- 自分で小さなラボ環境を構築（Kali + Metasploitable2 or Vulnhub）

---

## ◆ フェーズ2：攻撃手法の習得（7月〜9月｜12週間）

### Week 9〜10（7月上旬）

- 情報収集〜侵入の流れを実践：`nmap → gobuster → shell取得`
- TryHackMe「Offensive Pentesting」パス開始
- Burp Suiteの基本操作を習得（TryHackMeで練習）

### Week 11〜14

- Web脆弱性演習：SQLi, XSS, File Inclusion, Command Injection
- PortSwigger Web Security Academy（最低「Practitioner」まで）
- TryHackMe「Pickle Rick」「Simple CTF」などのCTFで実践

### Week 15〜16（8月下旬）

- Linux/Windows権限昇格演習：`sudo`, SUID, LinPEAS, winPEAS
- TryHackMe「Linux PrivEsc」「Windows PrivEsc」完了

### Week 17〜20（9月）

- ファイル転送／シェル取得方法の復習・暗記（20種以上）
- パスワードクラック練習（`john`, `hydra`, `hashcat`）

---

## ◆ フェーズ3：OSCP対応準備（10月〜12月）

### Week 21〜24（10月）

- Hack The Box: Starting Pointの全問題をクリア
- Buffer Overflow基礎学習（TryHackMe「BOF」や[このBOFガイド](https://zero-to-oscp.herokuapp.com/)）
- `gdb`, `pattern_create`, `shellcode`の基本を実践

### Week 25〜28（11月）

- VulnhubやHTBの難しめマシンで1日1台ペース演習
- 実践中に「記録→スクショ→手順整理→レポート化」を練習
- できれば、模擬レポートを1本書いてみる

### Week 29〜31（12月）

- OSCP模試形式で「5時間攻略＋5時間レポート」を試す
- 不足スキルの洗い出し・復習（Web脆弱性 / 権限昇格など）
- 12/31：OSCPを購入！

---

## ◆ 補足

- TryHackMeは基本「英語」ですが、繰り返すことで慣れます。最初はDeepLで訳しながらOK。
- 毎日少しでも「手を動かす」ことが重要です。最低30分でも演習が効果的です。
- わからないマシンはWriteupを参考にしてもよいですが、「一部だけ見る→手を動かす」がおすすめ。

---

必要であれば、**「毎週やることのチェックリストPDF」**も作れます。作成しましょうか？