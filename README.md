# Jirettai-Senju-Project-事業計画書

<p align="right">
2017年 4月 5日<br>
代表者 溝垣 雅人<br>
所属名 株式会社じれったい
</p>

![QA](resouceFile/2.png)

<p align="center"> -記- </p>

## 事業化構想の名称 「ソフトウェア品質テスト自動化ツール SENJU」
![hyousi](resouceFile/1.png)
<br>

## 代表者及び共同製作者

|  氏名 | 所属 |
| --- | --- |
| 溝垣 雅人 | 合同会社じれったい  CEO & Programmer |
| 大堀 祐一 | 合同会社じれったい  Product Designer |
| 柴田 幸輝 | 合同会社じれったい Chief Technology Officer |  
| 神谷 小太郎| 合同会社じれったい Chierf Information Officer |

#### 溝垣 雅人 プロフィール
フリーランスのプログラマーとして様々な現場で開発を経験して2017年に起業する<br>
高い志と情熱を持ち，ソフトウェアの労働環境及び品質を改善するために現在も邁進している<br>
今後もソフトウェアによって多様な品質改善のビジネスを提案していく<br>  

#### 大堀 祐一 プロフィール
今回のプロダクトに情熱と魂を込めてアサイン<br>
代表の溝垣とはリクルートキャリアにてアプリ開発チームでのチームメイト<br>
現在もプロダクトデザイナーとして様々な案件に関わる。 

#### 柴田 幸輝 プロフィール
早稲田大学卒、エンジニアになるために生まれてきた男、謹厳実直、外柔内剛<br>
テックレジデンス（エンジニア専門のシェアハウス）で共に技術知見や情報を交換と同時に<br>
ルームメイト、ハッカソンでの優勝経験もあり、技術力はピカイチ、CTOとしてアサインする<br>

#### 神谷 小太郎 プロフィール
京都大学卒、天才数学者、スーパーハッカー、進取果敢、真実一路<br>
テックレジデンス（エンジニア専門のシェアハウス）で共に技術知見や情報を交換と同時に<br>
ルームメイト、ハッカソンでの優勝経験もあり、圧倒的な情報量でCIOとしてアサインする<br>
<br><br>

![hinshitu](resouceFile/4.png)<br>
<br>

## 事業の動機，開発背景
QAエンジニアをなくしたいと考えている<br>
それはソフトウェア開発においてQA業務が多くの開発機関と経営資源を奪うからである<br>
QAが自動化されれば開発期間が短くなり、ユーザへのソフトウェアの提供が飛躍的に短くなる<br>
また開発エンジニアもソフトウェアの開発に専念でき、結果的にソフトウェア開発の品質向上に繋がると考えている<br>

## 品質保証テストとは
ソフトウェアの品せ質保証テストは、コンピュータのプログラムから仕様にない振る舞い<br>
または欠陥（バグ）を見つけ出す作業のことです。<br>
エンジニアの作業時間の多くはこのテストの作業に当てられています。<br>
SENJU ではこのテストを効率化し円滑なソフトウェア開発を後押しします<br>

開発スケジュールの多くを占め、バグの少ない高品質な開発には不可欠<br>
大手企業ではエンジニアの1/3をテスト要員として割く<br>
QAテスト専門の会社も存在<br>
![hinshitu](resouceFile/3.png)<br>

## マーケットサイズ

ソフトウェア開発市場規模（13兆円）<br>
　→QAテストの市場規模を算出（人員ベースでは約4人に1人がテスト要員）<br>
　→この市場を切り開く<br>


## targetについて！
![target](resouceFile/target.png)<br>


## 小規模事業会社のエンジニアの方にアンケートを実施（n=23）
うち、フロントエンドが10人以上の回答だった3件は除外

### テストの実施状況
- 単体テスト　実施13　未実施7
- 結合テスト　実施19　未実施1

### 結合テストの方法について（複数回答可）
- コードを書いたプログラマーが確認する 13名
- 別のプログラマーが確認する　6名
- ディレクター　5名
- テスト会社に依頼 0名　　
- プロジェクトマネージャー 3名　　
- jenkins 1名　　
- QA、テスト専用メンバー　4名


#### *コードを書いたプログラマー自身でテストする状況は不健全*　<br> *専門の人員はおらず、テストの質が人に大きく依存してしまう*


## QAテストの流れ

①ソフトウェア開発<br>
↓↑<br>
②単体テスト<br>
↓<br>
③テスト設計<br>
↓<br>
④結合テスト<br>
↓<br>
⑤バグ報告<br>
↓<br>
⑥タスク化　→①<br>

＝＝＝

## SENJUの提供する解決策

QAテストの流れの中の③、④をほぼ自動化し、⑤⑥バグ（仕様との差）報告をスムーズにする

## HOW

特許出願中の差分抽出機能<br>
新旧バージョンの画面をサーバー上に保存し、その差分を自動で抽出<br>
確認をToDOリスト化することで高速でのバグ報告が可能<br>
例：　5人日→1人日　80％削減！(要検証)<br>

GoogleAnalyticsのようにいれる<br>

## デモ

![task](resouceFile/03_task.png)<br>
### 新旧の画面差分をハイライト。問題のある差分はgithubへタスク登録<br>

![story](resouceFile/02_story.png)<br>
### ストーリーの中に複数のシナリオ<br>

![dashboard](resouceFile/01_dashboard.png)<br>
### チーム内でのテスト状況を確認

## 競合サービス

### Magic Pods

|  | |
| --- | --- |
| 仕組み | seleniumIDEとAppuimをベースにしたテスト実行ツール|
| 対応プラットフォーム | Andoroid iOS |
| 導入コスト　 | ipaファイルを書き出し、テストする全ての画面のスクリーンキャプチャーを作り<br>それらをMagic PodsにインポートMagic Podsにタップする外面を選択して自然言語で実行させる。|  


### Appuim

|  | |
| --- | --- |
| 仕組み | seleniumIDEをベースにしたテスト実行ツール|
| 対応プラットフォーム | Andoroid iOS |
| 導入コスト　 | AppumuをインストールしてエンジニアがRubyやnode.jsなどのプログラミング言語で実行させる|  


## 我々のサービス

### SENJU
|  | |
| --- | --- |
| 仕組み | Xcode UITESTをベースにしたテスト自動化ツール|
| 対応プラットフォーム | iOS |
| 導入コスト　 | XcodeProjectにSDKをインポートしてXcode UITestを起動 シュミレーターを起動させて録画開始<br>テストしたい順に触る録画停止を押し行くとSwiftで実行コードが生成される Runして実行|  



## 隠れたマーケット
・クラウドソーシングのような小規模開発の現場<br>
・スピード重視で進むスタートアップ<br>
　→テストをしたくてもできていいなかった市場も存在<br>
・クラウドソーシングの市場規模<br>




### 料金
導入無料<br>
同プロジェクトにユーザー2名以上登録する際に課金。<br>
5000円/人月のサブスクリプション<br>

例：5名で1年間継続利用した場合<br>
（5-1）×5000×12=240,000円<br>

## 今後のスケジュール
|   |  |
| --- | --- |
| 初年度| α版リリース　無料開放でブラッシュアップ<br> β版リリース　有料版スタート<br> 有料ユーザー獲得目標　100人（登録者数は500人見込み）|
| 2年目| 多機能化、高速化を進める<br> 英語版リリース<br> 有料ユーザー獲得目標　1000人（登録者数は5000人見込み)<br>法人向けに営業加速<br>|
| 3年目| バグの自動抽出機能リリース<br> 有料ユーザー獲得目標　10000人（登録者数は50000人見込み）　<br> 課金者10000人獲得の際の年間売上：6億円<br>|
| 4年目| 有料ユーザー獲得目標　50000人（登録者数は250000人見込み）<br>課金者30000人獲得の際の年間売上：30億円<br>|
| 5年目| 有料ユーザー獲得目標　100,000人（登録者数は500,000人見込み）<br>課金者100,000人獲得の際の年間売上：60億円<br>|



以        上
