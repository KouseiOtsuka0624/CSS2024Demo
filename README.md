# VR/AR行動ハックデモ：視聴覚刺激によるコントロール
本デモンストレーションは[コンピュータセキュリティシンポジウム2024](https://www.iwsec.org/css/2024/)にて発表させていただき、
[最優秀デモンストレーション章](https://www.iwsec.org/css/2024/demo.html)を受賞しました。
VR/AR環境下におけるリスクの認識が技術者や研究者に届いていないという課題を解決するために、実際にリスクを体験していただくというものです。
![1729842993185](https://github.com/user-attachments/assets/e839a9c3-e00f-46d1-bc3c-833b1214e47f)

### [デモ動画（Youtube）](https://youtube.com/shorts/airwTGzU2PU?feature=share)

## リポジトリツリー
    DemoDemoDescriptionUI                             #　デモアプリ中の攻撃説明ダイアログ画像フォルダ
    ├── TitleDialog.png                                   # タイトル画面ダイアログ
    ├── VisualInterferenceObjectsDialog.png               # 視覚干渉オブジェクトの不正挿入の説明ダイアログ
    ├── ObjectSpoofingDialog.png                          # 視覚操作によるオブジェクトの偽装の説明ダイアログ
    ├── AuditoryStimuliAttackDialog.png                   # 聴覚刺激による知覚操作の説明ダイアログ
    └── VisionManipulationMovie.mp4                       # 視界誘導のイメージ動画
    VRAR行動ハックデモ：視聴覚刺激によるコントロール.pdf  # デモポスター資料
    README.md                                         # REMDMEファイル

## 目的
VR/AR技術の急速な発展に伴い、セキュリティやプライバシリスクへの対策の重要性が高まっています。
VR/AR環境下では、PCやスマートフォンと同様のリスクに加えて、VR/AR環境特有あるいは深化するリスクが存在しています。
しかし、VR/ARリスクの認識が技術者や研究者に生き届いていないという現状があります。
本デモンストレーションではVR/AR特有のリスクの認識を広げる事を目的とし、実際にリスクを体験していただくというものになります。

## VR/AR特有あるいは深化するリスク
### VR/AR特有のリスク
VR/AR環境はユーザへの感覚やそれに基づく知覚への影響が高く、ユーザの感覚への不正な刺激を通じて知覚を操作し、
行動や思考を操作する知覚操作攻撃（Perceptual Manipulation Attack, PMA）の可能性が指摘されています。

### VR/ARで深化するリスク
VR/AR環境下ではオブジェクトの偽装（Spoofing）が従来環境と比較し深化すると考えられています。
オブジェクトの偽装とは、ユーザが本来見るはずのオブジェクトを別のものに見せたり、透過させたりといった脅威です。
これによって、広告の偽装や、不正な情報の提示などといったリスクの可能性が挙げられます。

## デモ内容
デモンストレーションでは私が作成したVR版テトリスゲームである、[BlockVRise](https://github.com/KouseiOtsuka0624/BlockVRise)をプレイしていただき、その間に3種類の攻撃を体験していただきます。
1. 視覚干渉オブジェクトの不正挿入
    - ゲームUIに類似したダイアログによりゲームからの通知と誤認
2. 視覚操作によるオブジェクトの偽装
    - 正規のブロックを別ブロックに偽装することによる誤操作の誘導
3. 聴覚刺激による知覚操作
    - 聴覚刺激を受けた方向を向くことによるユーザ操作
  
これらの攻撃のあと、ゲームが一時中断し、攻撃の内容やリスクについての説明が記載されたUIが表示されます。UIのスクリーンショットを本リポジトリ内の[DemoDemoDescriptionUIフォルダ](https://github.com/KouseiOtsuka0624/CSS2024Demo/tree/master/DemoDescriptionUI)に用意しております。

## APKファイル公開
デモンストレーションアプリをMeta Questシリーズに直接インストールして動作確認が可能なAPKファイルで提供します。

### 📥APKダウンロード
👉[APKファイルダウンロード(Googleドライブ)](https://drive.google.com/drive/folders/1__wIQU-s2xulIWDXcCV3t1dl0UiLxCiO?usp=drive_link)

### 📌インストール手順
1. PC側でSideQuest をインストール
2. MetaQuestシリーズをPCに接続し、開発者モードを有効化
3. SideQuest で ダウンロードしたAPKフィル を Quest に転送
4. Quest の 「不明なソース」 からアプリを実行

## 謝辞
本研究は、JST CREST JPMJCR22M4の支援を受けたものです。

## Contact
### メール
[大学用] 6524002o@st.toho-u.ac.jp  
[個人用] kouseiotsuka0624@gmail.com  
### ホームページ
[大塚 航世](https://faceted-caboc-521.notion.site/19a382a9ae56801ba863eb2a26cf5902)  
[研究室](https://www.klab.is.sci.toho-u.ac.jp/)  
 
