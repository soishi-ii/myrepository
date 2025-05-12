# 導入
- Power Automate の機能を確認する
- さまざまな Power Automate アプリを確認する
- クラウド フローのコンポーネントを確認する
- Power Automate のシナリオ例を確認する
- プロセス マイニングを確認する
- 基本的な Power Automate クラウド フローを構築する
- Copilot を使用してクラウド フローを構築する方法を確認する
- 基本的な Power Automate デスクトップ フローを構築する
- Power Automate によって実現するビジネス バリューを確認する
# Power Automate の機能について説明する
Power Automate は、反復的な業務プロセスを自動化するツールで、作業の効率化やエラーの削減を支援します。
- **反復タスクの自動化**：異なるシステム間でのデータ移動などを自動化します。
- **ユーザーのプロセス誘導**：営業プロセスなどで、ユーザーが各段階を順に進めるようガイドします。
- **ロボティック プロセス オートメーション (RPA)**：デスクトップや Web 上の作業を自動化します。

## フローの種類

### 1. ビジネス プロセス フロー

- **目的**：モデル駆動型アプリで使用され、ユーザーが定義されたプロセスに従って作業を進めるのを支援します。
- **例**：営業プロセス、サポート案件の解決、イベント計画、住宅販売など
![img](https://learn.microsoft.com/ja-jp/training/modules/introduction-power-automate/media/04-describe-automation-power-automate-01.png)
### 2. クラウド フロー

- **目的**：クラウドベースのサービス間での自動化を実現します。最も使われてる。
- **種類**：
    - **自動化フロー**：特定のイベント（例：メール受信）をトリガーに自動的に実行。
    - **インスタント フロー**：ユーザーの操作（例：ボタンのクリック）で即時に実行。
    - **スケジュール済みフロー**：定期的なスケジュールに基づいて実行。
- **例**：承認プロセスの自動化、アプリケーション統合、生産性向上のためのタスク自動化など。
![img](https://learn.microsoft.com/ja-jp/training/modules/introduction-power-automate/media/04-describe-automation-power-automate-02.png)

### 3. デスクトップ フロー

- **目的**：ユーザーの操作を記録し、再生することでデスクトップや Web 上の作業を自動化します。RPA。
- **例**：従業員の生産性向上、レガシ システムとの連携、Web サイトとのやり取りの自動化、キーボードやマウス操作の自動化など。

# クラウド フローのコンポーネントについて
## トリガー
- データに変更があった時
- スケジュールトリガ
- ボタンを押したとき
- メールを受信したとき
- SharePointフォルダ監視
- Teamsのメッセージ
## アクション
- SharePoint の承認プロセスを管理する
- SharePoint のファイルやリストを操作する
- Microsoft Outlookでメール送信
- Microsoft Forms は、アンケートや投票を作成
- 
## データ操作
- Microsoft Dataverse
- Salesforce
- Dynamics 365
- Google ドライブ
- Office 365
- Oracle

![](https://learn.microsoft.com/ja-jp/training/modules/introduction-power-automate/media/04-describe-automation-power-automate-15.png)

## Copilot でクラウド フローを構築する
 Copilot を使用すると、フローで実行する内容を記述するだけで、Copilot によってフローが作成されます。 提案を使用して、フローの詳細を調整することができます。
 - プロンプトに基づいてフローを作成する。
- プロンプトに基づいて必要なパラメーターをフロー内で適用する。
- フローおよび製品に関する質問に答える。
![](https://learn.microsoft.com/ja-jp/training/modules/introduction-power-automate/media/04-describe-automation-power-automate-17.png)

![](https://learn.microsoft.com/ja-jp/training/modules/introduction-power-automate/media/04-describe-automation-power-automate-18b.png)
