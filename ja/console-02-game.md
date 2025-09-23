## Game > GameStarter > コンソール使用ガイド > ゲーム

## Game

ゲームを登録し、ゲームの設定とバイナリを配布する方法について説明します。

### ゲームリスト
![game_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_list_250717.png)

ゲームリストでは、新しいゲームを登録したり、登録済みのゲームを照会したりできます。
また、ゲーム名やゲームの使用有無によってフィルタリングすることも可能です。

ゲームリストの照会結果には、以下のようなフィールドがあります。

#### ➊ゲーム名
登録されたゲームの固有の名前を表します。

#### ➋ゲームOS
ゲームを実行できるOSを表します。

#### ➌登録日時
ゲームを登録した日時を表します。

#### ➍登録者
ゲームを登録したユーザーの、マスキングされたメールアドレスを表します。

#### ➎ ゲームの使用有無
ゲームの使用状態(使用中または未使用)を表します。

#### ➏詳細表示
**詳細**ボタンをクリックすると、登録されたゲームの詳細情報を確認できます。


### ゲーム登録

ゲームリストの左上で、OSに応じて**+ Windows**または**+ macOS**をクリックし、新しいゲームを登録できます。

![game_register](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_regist_win_250717.png)

#### ゲーム名
ゲーム名は、他のゲームと区別できるよう、重複しない固有の名称にする必要があります。
ゲーム名は、日本語、英大文字・小文字、数字で2～15文字まで入力できます。

#### OS
ゲームを実行できるOSの情報を表示します。

ゲーム名を入力した後、**登録**をクリックしてゲームを登録できます。

### ゲーム詳細表示

ゲームリストで詳細情報を確認したいゲームの**詳細**ボタンをクリックし、ゲーム詳細情報ページへ移動します。

![game_detail](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_detail_250717.png)

### ゲームの修正

ゲーム詳細情報ページの上部にある**修正**をクリックすると、ゲーム情報を修正できます。

![game_modify](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_modify_250717.png)

#### ➊ ゲームの使用有無
使用中のゲームを**未使用**に変更したり、使用していないゲームを**使用中**に変更したりできます。


### ゲーム管理画面への移動

![game_enter](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_enter_250717.png)

ゲームの登録を完了すると、ゲームリストに登録したゲームが表示されます。
上部画像の赤色で示した領域をクリックすると、該当のゲーム管理画面へ移動できます。

ゲーム管理画面へ移動すると、ゲームを設定したり、バイナリを配布したりできます。

#### ゲーム設定リスト

ゲーム管理画面へ移動すると、以下のように上部にゲーム名が表示され、下部には該当ゲームのメニューが表示されます。

![game_config_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_list_250717.png)

ゲーム設定では、ゲームのインストール時に必要な様々な設定を登録できます。

ゲーム設定の照会結果ページには、次のようなフィールドがあります。

**➊ ゲーム設定名**: 登録されたゲーム設定の名前を表します。
**➋ 登録日時**: 登録されたゲーム設定が最後に登録された日時を表します。
**➌ 登録者**: 登録されたゲーム設定を最後に修正した登録者の、マスキングされたメールアドレスを表します。
**➍ メモ**: 登録されたゲームのメモを表します。
**➎ 削除**: 登録されたゲームを削除します。


#### ゲーム設定の登録

新しいゲーム設定は、ゲーム設定リストの左側にある**+ 登録**をクリックして登録できます。


##### 基本設定
![game_config_register_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_register_01_250717.png)

##### ➊ ゲーム設定名
ゲーム設定の名前は、他のゲーム設定と区別するために入力します。
選択したゲーム内で、重複したゲーム名は使用できません。
ゲーム設定の名前は、日本語、英大文字・小文字、数字で2～15文字まで入力可能です。


##### ➋メモ
メモは、ゲーム設定の内容を参照するために入力する情報です。


##### ➌ 管理者権限の取得
該当のゲームをインストールする際に、Windowsの管理者権限を取得するかどうかについて選択します。
この機能を有効にすると、ユーザーがゲームをインストールする過程でUAC(User Access Control)が表示されることがあります。


##### ➍ デフォルトのインストールパス
ゲームをインストールする際に、デフォルトでインストールするパスを指定します。
デフォルトのパスは、Windowsの場合`<SystemDrive>/ProgramData/<GameName>`です。
他のパスに設定するには、**カスタムパス**を選択して目的のパスを入力してください。


##### ➎ 設定されたデフォルトのインストールパス
設定したデフォルトのインストールパスに基づき、その一例を表示します。
Windowsでは、`<SystemDrive>`を`Cドライブ`として、デフォルトのインストールパスの例を表示します。


全ての設定が完了したら、下部の**次へ**をクリックして次のページへ移動します。


##### ゲームのショートカットアイコン


ゲームをインストールする際に、デスクトップにゲームのショートカットアイコンを作成できます。
ドロップダウンメニューをクリックし、ゲームのショートカットアイコンの作成方法を選択できます。
![game_select_shortcut](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_select_shortcut_250717.png)


ショートカットアイコンを作成する場合、ゲームのアイコン画像と名前が必要です。

ショートカットの作成方法の各オプションに関する説明は、次のとおりです。

- **ショートカットを自動作成**：ゲームユーザーの選択なしで、常にショートカットを作成します。
- **ゲームユーザーが作成するかを選択**：ランチャーでショートカットを作成するかどうかを選択できます。
- **ショートカットを作成しない**：ショートカットを作成しません。

![game_config_regist_shortcut](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_regist_shortcut_250717.png)

###### ➊ ショートカットの作成方法
先ほど選択したショートカットの設定情報を確認でき、
選択したショートカットの作成方法を修正できます。


###### ➋ ショートカットアイコンの画像
デスクトップへのインストール時に使用する、ゲームのショートカットアイコン画像を登録します。
アイコン画像の推奨サイズは256x256です。


###### ➌ ショートカットアイコン名
デスクトップにインストールするゲームのショートカットアイコン名を入力します。
ゲームのショートカットアイコン名は、2～50文字まで入力可能です。
また、最初と最後の文字に`空白`、`/`は入力できません。


全ての設定が完了したら、下部の**次へ**をクリックして次のページへ移動します。

##### ゲームUI
![game_config_game_ui_basic](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_basic_250717.png)

ゲームUIでは、ランチャーでゲームごとに表示されるUIを構成できます。
ゲームのアイコン、背景画像、フッター部分に利用規約やカスタマーセンターのURLなどを追加・削除できます。


###### ➊ ゲームアイコン
![game_config_game_ui_icon](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_icon_250717.png)

ゲームアイコンエリアの編集アイコンをクリックし、新しいゲームアイコンを登録・削除できます。
ゲームアイコン画像の推奨サイズは256x256です。


###### ➋ 背景画像
![game_config_game_background](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_background_250717.png)

背景画像エリアの編集アイコンをクリックし、新しい背景画像を登録できます。
背景画像の推奨サイズは992x584です。
> [注意]
> この比率に合わない画像の場合、ランチャーの画像にスクロールバーが表示されることがあります。


###### ➌ Footer
![game_config_game_terms](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_terms_250717.png)

ゲームUIのフッターエリアに、利用規約やカスタマーセンターを追加・削除できます。

上の参考画像は、利用規約の編集アイコンをクリックした際に表示される、利用規約URLの入力画面です。
また、「利用規約」の名前を他の名前に変更することも可能です。


##### プレビュー


######  UIプレビュー
右側の**UIプレビュー**ボタンを通じて、実際のランチャーで表示されるゲームUIを確認できます。

![game_config_game_preview](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_preview_250717.png)

全てのゲーム設定が完了したら、下部の**登録**ボタンでゲーム設定を登録できます。


#### ゲーム設定詳細表示

![game_config_register_complete](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_complete_250717.png)

ゲーム設定リストで、上部画像の赤色で示した領域をクリックすると、ゲーム設定詳細ページへ移動できます。

![game_config_detail](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_modify_250717.png)

ゲーム設定詳細ページは、ゲーム設定登録ページと同じですが、入力ができないという違いがあります。
左上の**修正**及び**コピー**をクリックし、ゲーム設定を修正またはコピーできます。


##### ➊ ゲーム設定の修正

ゲーム設定リスト左上の**修正**をクリックし、ゲーム設定を修正できます。

![game_config_modify](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_modify2_250717.png)

ゲーム設定の変更内容は、最後のページで**保存**をクリックして保存できます。


##### ➋ ゲーム設定のコピー

ゲーム設定リスト左上の**コピー**をクリックし、ゲーム設定をコピーできます。

![game_config_copy](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_copy_250717.png)

**ゲーム設定情報コピー**のポップアップウィンドウが表示され、ゲーム設定名とメモを入力した後、コピーできます。


ここまでゲーム設定の登録、詳細表示、修正、コピーについて扱いましたが、単にゲーム設定を登録しただけでは、実際のランチャーには反映されません。
ゲームの配布に関する説明は、ゲームバイナリに関する説明の後に行います。


#### ゲームバイナリ

![game_binary_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_list_250717.png)

ゲームバイナリとは、ゲームの実行に必要なバイナリファイルの集合を意味します。
ゲームバイナリをアップロードするには、まずCDN連携を行う必要があります。

##### CDN連携
CDNを連携するには、連携したい配布ゾーンの**連携**ボタンをクリックしてください。


例では、TEST配布ゾーンでCDN連携を行います。

###### お客様所有のCDNを登録

![game_binary_cdn_customer](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn1_250717.png)

お客様ご自身のCDNアドレスと連携します。
このプロセスでは、2段階の設定作業が必要です。

1. GameStarterのファイルストレージアドレスを、お客様ご自身のCDNのオリジンサーバーURLとして登録します。
2. お客様ご自身のCDNのアドレスを入力します。
3. **確認**ボタンを押して連携を開始します。

![game_binary_cdn_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn_list_250717.png)

CDN連携の結果は、ゲームバイナリの詳細情報画面で確認できます。
上の画像の赤色で示した領域をクリックすると、詳細情報画面へ移動できます。

![game_binary_cdn_success](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn_success_250717.png)

CDN連携が正常に完了した場合、バイナリ詳細情報画面でCDN連携が成功した旨を確認できます。

![game_binary_cdn_failed](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn_failed_2_250717.png)

CDNエッジサーバーへの配布中、またはその他の事由により、連携に多少時間がかかることがあります。
連携時間が長引いたり、連携に失敗したりした場合は、ゲームバイナリ詳細情報画面でCDN連携が失敗した旨を確認できます。



#### ゲームバイナリ詳細表示

![game_binary_cdn_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_list_enter_250717.png)

上部画像の赤色で示した領域をクリックすると、ゲームバイナリの詳細表示画面へ移動できます。

![game_binary_cdn_enter](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn_enter_250717.png)

ゲームバイナリの詳細情報には、以下のようなフィールドがあります。

##### ➊ゲームバイナリ情報
ゲームバイナリIDと配布ゾーンの情報を表示します。

##### ➋ CDN情報
連携されたCDN情報を表示します。

##### ➌ ゲームバイナリのアップロード情報
アップロードしたゲームバイナリの情報を表示します。
ゲームバイナリ情報には、バイナリファイルの数及びサイズ、バイナリのアップロード日時、アップロード状況が含まれます。


> [参考] アップロード状況
>
> - **アップロードキャンセル**: ゲームバイナリのアップロードがキャンセルされた状態を表します。
> - **アップロード完了**: ゲームバイナリのアップロード手順が全て完了したことを表します。
> - **アップロード失敗**: ゲームバイナリのアップロード中にエラーが発生したことを表します。
> - **アップロード中**: ゲームバイナリのアップロードが進行中の状態であることを表します。
> - **ビルド中**: ゲームバイナリに必要なメタファイルの生成など、ファイルをビルド中であることを表します。
> - **アップロード待機**: ゲームバイナリに必要なメタファイルの生成など、準備作業が進行中であることを表します。


##### ➍ ゲーム実行ファイル名
アップロードしたゲームバイナリファイルの中で、ゲーム実行ファイルの名前を表します。


#### ゲームバイナリのアップロード

CDN連携が完了した後、ゲームバイナリファイルをアップロードできます。
ゲームバイナリファイルをアップロードしても、実際のランチャーに即時反映はされず、**ゲームの配布**でゲームバイナリの配布を行うことで反映されます。


![game_binary_upload_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload1_250717.png)

ゲームバイナリリストで、配布したい配布ゾーンの行にある**バイナリアップロード**をクリックし、ファイルのアップロードを行います。

![game_binary_upload_02](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload2_250717.png)

Windows OSを使用する場合、アップロードするゲームバイナリのフォルダを選択してください。
macOSを使用する場合、Appleによって認証・提供された「ゲーム.zip」ファイルをアップロードしてください。

> <font color="red">[注意]</font><br/>
>
> macOSのゲームバイナリが未認証のファイルである場合、ゲームは実行されません。


![game_binary_upload_03](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload3_250717.png)

**実行ファイル名**のドロップダウンメニューから、ゲームを実行するファイルを選択するか、ファイル名を手動で入力して検索した後に選択することもできます。


![game_binary_upload_04](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload4_250717.png)

ファイルのアップロードが完了すると、アップロードしたファイルの数とサイズが表示されます。
**確認**ボタンを押すと、ファイルのアップロードが開始されます。

![game_binary_upload_05](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload6_250717.png)

ファイルのアップロード完了後、実際にCDNに反映されるまでには多少時間がかかります。
赤色領域の**アップロード状況**が**アップロード完了**になるまでお待ちください。

アップロードが完了すると、ステータスが**アップロード完了**に変わります。
これ以降、ゲームの配布を通じてゲームバイナリを配布できます。

ここまで、ゲームバイナリのアップロードまでの過程を説明しました。
バイナリのアップロード後に、配布を行う必要があります。

次のセクションでは、ゲーム設定とゲームバイナリの配布について説明します。


#### ゲームの配布

![game_deploy_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_deploy1_250717.png)

**ゲームの配布**では、配布ゾーンごとにゲーム設定及びゲームバイナリの配布ができます。
上部画像の赤色で示した領域が、1つの配布ゾーンを意味します。
オレンジ色の領域では、配布ゾーンのゲーム設定を新たに配布したり、配布済みの情報を確認したりできます。
緑色の領域では、配布ゾーンのゲームバイナリを新たに配布したり、配布済みの情報を確認したりできます。

登録されたゲーム設定がない、またはゲームバイナリがアップロードされていない場合は、**配布**ボタンが無効化されます。

以下では、配布ゾーンで登録したゲーム設定とバイナリを配布してみます。

##### ゲーム設定の配布
![game_deploy_config_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_deploy1_reserve_250717.png)

TEST配布ゾーンで、**ゲーム設定の配布**の**配布**をクリックすると、ゲーム設定配布のポップアップウィンドウが表示されます。

ゲーム設定の配布は、予約配布または即時配布で行うことができます。

###### ゲーム設定の選択
登録済みのゲーム設定が表示されます。
この中から、配布したいゲーム設定を選択します。

###### 予約配布

![game_deploy_config_01-reserve](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_deploy1_reserve2_250717.png)

➊ 基準時間と ➋ 配布時間を設定した後、**確認**をクリックすると**配布内容の比較**段階へ移動します。

###### 即時配布

即時配布では、別途設定する内容はありません。
すぐに最終段階である**配布内容の比較**段階へ移動します。

###### 配布内容の比較

![game_deploy_config_deploy](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_deploy_250717.png)

直近に配布したゲーム設定と比較するポップアップウィンドウが表示されます。

新たに配布するゲームの設定情報を全て確認した後、**配布**をクリックして即時配布または予約配布を実行できます。
該当の配布ゾーンで、配布状況及び直近に配布が完了した情報を確認できます。

![game_deploy_config_complete](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_deploy_complete_250717.png)


##### ゲームバイナリの配布

ゲームバイナリの配布は、アップロードが完了したゲームバイナリを適用する段階です。

![game_deploy_binary_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_250717.png)

TEST配布ゾーンで**ゲームバイナリの配布**の**配布**をクリックすると、**ゲームバイナリ配布**ポップアップウィンドウが表示されます。
ゲームバイナリの配布も、予約配布または即時配布で行うことができます。

###### 予約配布

![game_deploy_binary_02-reserve](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_reserve_250717.png)

➊ 基準時間と ➋ 配布時間を設定した後、**確認**をクリックすると、ゲームバイナリの配布が予約されます。


###### 即時配布
**即時配布**を実行すると、アップロード済みのゲームバイナリで直ちに配布が行われます。
配布を実行した後、該当の配布ゾーンで配布状況及び直近に配布が完了した情報を確認できます。

![game_deploy_binary_complete](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_comp_250717.png)

配布が完了すると、上の画像のように領域が緑色に変わり、**配布**ボタンが無効化されます。
**ゲームバイナリ**タブの青いボックス領域で、配布情報を確認できます。

![game_deploy_binary_failed](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_failed_250717.png)

**ゲームバイナリ配布**エリアで、配布状況を確認できます。
配布状況に応じて、配布ゾーン領域の色が変わります。

> [参考] 配布状況に応じた色情報
>
> **GRAY**: 未配布状態。配布履歴が何もない場合に、デフォルトで表示される色です。
> **YELLOW**: ゲーム設定のみが配布された状態
> **GREEN**: ゲーム設定とゲームバイナリの配布が完了した状態
> **RED**: ゲームバイナリの配布に失敗した状態


#### 配布履歴

##### ゲーム設定の配布履歴

![game_history_config_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_config_1_250717.png)

ゲーム設定の配布履歴では、配布したゲーム設定に関する履歴を照会できます。
右側の検索条件を通じて、照会結果をフィルタリングできます。

##### ➊ ゲーム設定名
配布されたゲーム設定名で、配布履歴をフィルタリングできます。

##### ➋ 配布日時
指定した期間に配布された配布履歴をフィルタリングできます。

##### ➌ 配布状況
特定の配布状況で、配布履歴をフィルタリングできます。

配布履歴の照会結果には、以下のようなフィールドがあります。

![game_history_config_02](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_config_3_250717.png)

##### ➊ ゲーム設定名
配布されたゲーム設定の名前を表します。

##### ➋ 配布ゾーン
ゲーム設定が配布された配布ゾーンを表します。

##### ➌ 配布日時
ゲーム設定が配布された日時を表します。

##### ➍ 配布者
ゲーム設定を配布したユーザーの、マスキングされたメールアドレスが表示されます。

##### ➎ 配布状況
ゲーム設定が配布された状況を表します。

> [参考] 配布状況
>
> - **配布中**：ゲーム設定の配布が進行中であることを表します。
> - **配布完了**：ゲーム設定の配布が完了したことを表します。
> - **配布失敗**：ゲーム設定の配布中にエラーが発生したことを表します。
> - **配布予約**：ゲーム設定の配布予約が登録されたことを表します。
> - **配布予約キャンセル**：ゲーム設定の配布予約がキャンセルされたことを表します。

##### ➏ メモ
配布されたゲーム設定のメモを表します。


##### ゲームバイナリの配布履歴

![game_history_binary_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_binary1_250717.png)

ゲームバイナリの配布履歴では、配布したゲームバイナリの配布履歴を照会できます。
右側の検索条件を通じて、照会結果をフィルタリングできます。

##### ➊ 配布日時
指定した期間に配布された配布履歴をフィルタリングできます。

##### ➋ 配布状況
特定の配布状況で、配布履歴をフィルタリングできます。

配布履歴の照会結果には、以下のようなフィールドがあります。

![game_history_binary_02](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_binary3_250717.png)

##### ➊ 配布ゾーン
ゲームバイナリが配布された配布ゾーンを表します。

##### ➋ ゲームバイナリ
配布されたゲームバイナリの情報が表示されます。
ゲームバイナリ情報は、ファイルの数とファイルのサイズで構成されています。

##### ➌ 配布日時
ゲームバイナリが配布された日時を表します。

##### ➍ 配布者
ゲームバイナリを配布したユーザーの、マスキングされたメールアドレスが表示されます。

##### ➎ 配布状況

![game_history_binary_04](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_config_4_250717.png)

ゲームバイナリが配布された状況を表します。
**配布状況**の`?`にマウスカーソルを合わせると、状況のリストを確認できます。

> [参考] 配布状況
>
> - **配布中**：ゲームバイナリの配布が進行中であることを表します。
> - **配布完了**：ゲームバイナリの配布が完了したことを表します。
> - **配布失敗**：ゲームバイナリの配布中にエラーが発生したことを表します。
> - **配布予約**：ゲームバイナリの配布予約が登録されたことを表します。
> - **配布予約キャンセル**：ゲームバイナリの配布予約がキャンセルされたことを表します。
