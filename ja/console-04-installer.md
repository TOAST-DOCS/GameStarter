## Game > GameStarter > コンソール使用ガイド > ランチャーインストーラー

## Launcher Installer

GameStarterランチャーを実行するには、まずランチャーがユーザーのPCにインストールされている必要があります。
ランチャーインストーラーは、ランチャーをユーザーのPCにインストールするためのプログラムです。

ここでは、ランチャーインストーラーの作成時に必要な設定について説明します。

### 初期設定


![installer_basic](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_basic_250717.png)

ランチャーインストーラーの初期設定は、プロジェクトを最初にセットアップする際に一度だけ設定可能です。
初期設定を完了した後は、一部の項目についてのみ修正できます。
設定の修正については、以下の**設定の修正**の内容をご参照ください。

### URLスキーム設定
![installer_urlscheme](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_url_scheme_250717.png)

初期設定の際、URLスキーム設定を最初に登録する必要があります。

#### ➊ URL scheme

URLスキームは、ユーザーが定義したプロトコルでアプリと通信できるようにします。
GameStarterは、ユーザーが登録したURLスキームでランチャーを実行できるようにします。

> <font color="red">[注意]</font><br/>
>
> URLスキームは、一度設定すると変更が困難です。
> 他のプログラムで使用されているURLスキームに設定すると、GameStarterが正常に実行されない可能性があります。


> [参考] URLスキームの命名規則
>
> 最初の文字は英小文字で始める必要があります。
> 英小文字及び数字のみ使用可能で、最大20文字までです。


> [参考] 配布ゾーン
> URLスキームは一度しか入力しませんが、配布ゾーンは複数存在します。
> GameStarterでは、これを区別するため、SERVICE配布ゾーンを除いたゾーンでは、末尾に`-<zone>`という形式で自動的に追加します。
>
> 例) SERVICE
> - URL Scheme: example
>
> 例) DEVELOP
> - URL Scheme: example-develop

### 共通名の設定
![installer_names](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_name_250717.png)

#### 共通名
共通名は、ランチャーのインストーラーとアンインストーラーの名前として使用され、インストール先のフォルダ名やパスにも使用されます。

> <font color="red">[注意]</font><br/>
>
> 共通名は、一度登録すると変更が困難です。

> [参考] 共通名の命名規則
>
> 共通名は、20文字以内の英大文字・小文字、数字のみ入力可能です。

> [参考] 配布ゾーン
> 共通名は一度しか入力しませんが、配布ゾーンは複数存在します。
> GameStarterでは、これを区別するため、SERVICE配布ゾーンを除いたゾーンでは、末尾に`_<ZONE>`という形式で自動的に追加します。
>
> 例) SERVICE
> - ランチャーインストーラー名：`<共通名>Insatller`
> - ランチャーアンインストーラー名：`<共通名>Uninstaller`
> - ランチャーインストールフォルダ名：`<共通名>`
> - ランチャーインストールパス：`C:\Users\<UserName>\AppData\Roaming\<共通名>`
>
> 例) DEVELOP
> - ランチャーインストーラー名：`<共通名>Insatller_DEVELOP`
> - ランチャーアンインストーラー名：`<共通名>Uninstaller_DEVELOP`
> - ランチャーインストールフォルダ名：`<共通名>_DEVELOP`
> - ランチャーインストールパス：`C:\Users\<UserName>\AppData\Roaming\<共通名>_DEVELOP

ここまでで初期設定は完了です。
初期設定が完了すると、以下のようにインストーラー設定を登録する準備が整います。
**登録**をクリックし、インストーラー設定を進めます。


以下は、DEVELOPゾーンの設定を登録する例です。

![installer_comp1](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_comp_250717.png)

初期設定完了後、登録が必要な設定情報は次のとおりです。

#### ランチャーのショートカットアイコン
![installer_icons](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_250717.png)

GameStarterランチャーのインストール後、デスクトップに自動でランチャーのショートカットを作成でき、その作成に必要な設定を登録します。

#### ➊ ショートカットアイコンの画像
ショートカットアイコンの画像を登録します。

#### ➋ ショートカットアイコン名
ショートカットアイコン名を入力します。
入力内容が正しいことを確認した後、**登録**をクリックします。

#### 登録設定の確認
登録された設定は、インストーラー設定リストをクリックすると確認できます。

![installer_confirm_list](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_after_list_click_250717.png)

### ランチャーインストーラー設定の配布
インストーラーに必要な設定を全て終えたら、インストーラー設定を配布する必要があります。
この作業には、数分から数十分かかることがあります。

![installer_deploy](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_250717.png)

**➊ 配布**をクリックし、即時配布と予約配布を行うことができます。


![installer_deploy_modal](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_modal_250717.png)

**➊ 予約配布**は、登録時間を基準に10分後から設定可能です。
**➋ 即時配布**は、すぐに配布を開始します。

配布状況に応じて、ステータスを確認できます。
![installer_deploy_status](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_reservation_confirm_2_250717.png)

> ランチャーインストーラーの配布状況の種類は以下の通りです
> - ビルド待機
> - ビルド中
> - 配布中
> - 適用待機中
> - 配布失敗
> - 配布完了
> - 配布予約
> - 配布キャンセル

> [参考]
>
> 配布状況が**配布失敗**と表示された場合は、カスタマーセンターへお問い合わせください。

#### 配布履歴の照会
**配布履歴**タブで、配布されたインストーラーの情報と配布履歴を照会できます。
![installer_deploy_list](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_list_250717.png)

### 設定の修正
ランチャーインストーラーの設定詳細情報を照会・修正できます。
上記案内に従いインストーラー設定の登録と配布を行った後の、インストーラー設定画面です。

#### 登録済み設定の確認

下部画像の赤色で示した領域をクリックすると、インストーラー詳細情報を照会・修正できるページへ移動できます。

![installer_config_list](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_list_250717.png)

➊ **OS別照会ボタン**：WindowsまたはmacOS別に登録された設定を表します。
➋ 配布ゾーン：配布ゾーン情報を表します。
➌ **インストーラー設定バージョン**：インストーラーの設定バージョン情報を表します。
➍ **登録日時**：インストーラーの設定を登録した日時を表します。
➎ **登録者**：ランチャーインストーラー設定を登録したユーザーの、マスキングされたメールアドレスを表します。
➏ **メモ**：ランチャーインストーラー設定の登録時に入力したメモを表します。

#### 登録済み設定の詳細情報確認

インストーラーの基本情報を確認でき、下部の**次へ**をクリックしてランチャーのショートカットアイコン登録情報を確認できます。
**修正**をクリックして、基本情報の設定を修正できます。

![installer_config_enter](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_enter_250717.png)
➊ **修正ボタン**：インストーラー設定を修正できます。
➋ **URL Scheme**：登録されたURLスキーム情報を表します。
➌ **共通名**：登録されたランチャーのインストーラー名、アンインストーラー名、インストールフォルダ名及びインストールパスに使用される共通名情報を表します。
➍ **インストーラーバージョン**：インストーラーのバージョン情報を表します。
➎ **メモ**：ランチャーインストーラー設定の登録時に入力したメモを表します。

#### 基本情報の修正
基本情報を修正するには、**修正**をクリックするか、**インストーラー設定詳細情報**画面で**次へ**をクリックし、以下の**インストーラー設定修正**ページへ進んでください。

![installer_config_modify_default](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_modify_default_250717.png)
➊ **インストーラーバージョン**：インストーラーのバージョンを修正できます。
➋ **メモ**：インストーラー設定のメモ内容を修正できます。
下部の➌**次へ**をクリックし、次の修正ページへ移動します。

#### ランチャーのショートカットアイコン修正

ランチャーのショートカットアイコンを修正するには、**修正**をクリックするか、**基本情報修正画面**で**次へ**をクリックし、以下のページへ進んでください。

既存の登録済みランチャーショートカットアイコン情報を確認し、ショートカットアイコン名を修正できます。
![installer_config_modify_shotcut](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_modify_shotcut_250717.png)

**プレビュー**をクリックすると、修正内容を事前に確認できます。

![installer_config_modify_preview](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_modify_preview1_250717.png)
プレビュー画面では、以下の情報を確認できます。
- 配布ゾーン情報
- 変更する基本情報
- 変更するランチャーショートカットアイコン情報

修正を完了した後、**保存**をクリックして修正した設定内容を反映できます。
