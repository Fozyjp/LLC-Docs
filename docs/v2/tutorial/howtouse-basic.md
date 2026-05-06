---
sidebar_position: 2
description: Light Limit Changer v2.0.0の基本的な使い方、初回生成から設定の変更方法について解説しています。
---

# 導入方法と基本的な使い方

インストールから使い方についての簡単な説明です。

----

## Light Limit Changerのインストール～導入まで

### Modular Avatarの導入

LightLimitChangerの使用には、前提としてModular Avatarの導入が必要です。
もし未導入の際には必ず先に導入してください。
導入されている場合、このセクションは飛ばしてください。

以下のリンクから入手することができます。
Modular Avatar：
https://modular-avatar.nadena.dev/ja

### VCCへの登録

VCC（VRChat Creator Companion）からインストールを行います。

LLC V2のVCCへの登録は、Boothのダウンロードページからダウンロードしたリンクを使用して行ってください。
登録方法につきましても、ダウンロードファイルに同梱されている説明をお読みください。

:::caution

BoothからダウンロードできるVCCリポジトリのWebリンクは購入者にのみ提供しているものです。
未購入者へ教える行為・譲渡・Webへの掲載等、第三者へ公開する行為は規約違反となりますので、絶対におやめください。
特に、VCC/ALCOMのログの写真、映像、配信に映り込む・ログに記載される場合が多いため、もしこれらをご共有される際には誤って公開してしまわないよう細心の注意をお願いいたします。

:::

VCCに登録後、導入したいプロジェクトの **Manage Packages** を開き、**Light Limit Changer** の ＋ボタンをクリックしてインストールしてください。

![Vcc](/img/docs/intro/vcc_1.png)

----

### アバターへのLight Limit Changerの導入

導入したいアバターを右クリック → Light Limit Changer → Setup を押します。  
アバター内部にLight Limit Changerオブジェクトが生成されるので、導入完了です。  

![install](/img/docs/v2/howtouse/install.png)

<!-- もしセキュリティ的に不要なら以下は消す -->

### 初回導入時のみ購入者認証があります。

ダウンロードしたファイルに記載されている方法に従って、インスペクターのメニューから初回認証を行ってください。

認証に失敗する場合は、パスワードの入力を間違えていることや、Unityの通信が許可されていない場合があります。
特に、Windowsの再インストールや、新しいパソコンに移行したときには、Unityの通信が許可されていないことが多くあります。
Unityの通信が許可されてない場合は、以下のようなサイトを参考に、Unityのファイアーウォールの通信を許可してください
https://docs.unity3d.com/ja/Packages/com.unity.live-capture@4.0/manual/setup-network.html

また、時間をおいて再度試していただくことで解決することもあります。


### プリセットを導入する場合

導入したいアバターを右クリック → Light Limit Changer → preset から追加したプリセット名を押します。  
アバター内部にLight Limit Changerオブジェクトが生成されるので、導入完了です。  

![install-preset](/img/docs/v2/howtouse/install-preset.png)

----

## 設定の変更方法  
アバターの中に生成されたLight Limit Changer プレハブのインスペクターから設定を変更します。

![window](/img/docs/v2/howtouse/settings.png)
*基本画面 2.0.0-beta.5 時点のもの

<br/>

:::info
各パラメーターの設定は**解説モード**を御覧ください。
:::
![descriptionmode](/img/docs/v2/howtouse/description_mode.png)