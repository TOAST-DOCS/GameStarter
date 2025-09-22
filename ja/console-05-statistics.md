## Game > GameStarter > コンソール使用ガイド > 指標

GameStarterは、ゲームの効率的な指標を把握するため、関連データを提供します。
ゲームのインストール、実行、ランチャーのインストール及び実行データを提供し、ゲームの離脱率など、ゲームの実行と接続に関する主要な指標を簡単に確認できます。

## 指標

指標データを照会するためのメニュー構成は、次のとおりです。

![statistics_title1](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_title_1_250717.png)

➊ **リアルタイムモニタリング**：当日午前0時から照会時点までの指標データを提供します。
➋ **モニタリング指標**：設定した期間(日次、週次、月次)の集計データを提供します。
➌ データの照会基準時間を確認できます。
➍ **更新**：データをリクエスト時点のデータに更新できます。
リアルタイム指標は、サーバー負荷を避けるため自動では更新されません。データを更新するには、**更新**をクリックしてください。
➎ **条件**：フィルタを適用してデータを照会できます。提供されるフィルタは、各項目のフィルタ情報の内容をご確認ください。
**照会**をクリックして、データを照会できます。
➏ **Excel保存**：指標データをExcelファイルとして保存できます。提供されるExcelデータに関する説明は、各項目の**Excel保存**の内容をご確認ください。


### リアルタイムモニタリング

リアルタイムモニタリングは、当日午前0時から照会時点までの指標データを照会できる機能です。
午前0時(00:00)から照会時点までのデータを照会し、**条件**をクリックしてデータをフィルタリングして照会することも可能です。

![statistics_main](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_main_250717.png)


#### リアルタイムモニタリング - ゲーム

ゲームの実行及びインストールに関する指標データを、ダッシュボードとチャートデータで確認できます。
それぞれゲームの実行とインストールの指標を、ダッシュボードとチャートデータを通じて簡単に取得できます。

##### ゲームのフィルタ情報

指標データは、フィルタを適用して照会し、Excelファイルとして保存できます。

![realtime_game_filter](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_filter_250717.png)

> ➊ 照会対象
> 照会対象には、ユーザーID基準と全実行基準の項目があります。
> 照会対象の種類
> - **ユーザーID基準**：ユーザーが同じ操作を複数回行った際に発生する、重複データを含みません。
> - **全実行基準**：ユーザーの全ての操作を基準に照会し、同じ操作による重複データを含んだデータを照会します。
>
> ➋ OS
> ユーザーが使用したOSの情報リストをフィルタリングして照会できます。
>
> ➌ ゲーム名
> ゲーム名(ゲームバージョン)の情報リストをフィルタリングして照会できます。
>
> 目的のフィルタデータを選択した後、**適用**をクリックして照会結果をフィルタリングできます。


##### ゲームの実行

ゲームの実行に関連する指標情報を表示します。

![statistics_real_game](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_execute_game_none_250717.png)
ダッシュボードでは**ゲーム実行数**、**ゲーム実行成功数**、**ゲーム実行失敗数**を提供し、前日比での増減値を確認できます。
また、チャートを通じて**時間帯別の増減数値**と**ゲーム実行の失敗理由**情報を確認できます。


指標データをより効率的に活用できるよう、**Excel保存**をクリックして指標データを保存することもできます。
Excel保存データは、保存リクエスト時点のデータを基準に提供されます。

##### ゲーム実行データのExcel保存
ゲームの実行に関連するExcelデータ保存項目は、次のとおりです。
ファイル名は、`RealTime_GameExecution_日付_時間.xlsx`形式で提供されます。

ゲーム実行の指標データは、時間帯別にExecute (Game)タブとExecute (OS)タブで確認できます。

1. Execute(Game)タブでは、時間帯に応じたゲーム別のゲーム実行数、ゲーム成功数、ゲーム失敗数の集計データを提供します。
2. Execute(OS)タブでは、時間帯に応じたOS別のゲーム実行数、ゲーム成功数、ゲーム失敗数の集計データを提供します。

##### ゲームのインストール

ゲームのインストールに関連する指標情報を表示します。

![realtime_install_game1](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_install_game_none_250717.png)

ダッシュボードで、**ゲームインストール数**、**ゲームインストール成功数**、**ゲームインストール失敗数**、**ゲームダウンロードの平均速度**、**ファイルダウンロード容量**、**ファイルダウンロード数**に関する情報を確認できます。
ダッシュボードのFULLとUPDATEの意味は、それぞれ次のとおりです。
- **FULL**：フルインストール
- **UPDATE**：アップデートインストール


![realtime_install_game2](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_install_game2_none_250717.png)

チャートデータで、時間帯別の**ゲームインストール数**、**ゲームインストールの失敗理由**、**時間帯別のゲームのフル・アップデートインストール数**、**時間帯別のゲームのフル・アップデートインストールの平均時間**、**時間帯別のダウンロード速度及び容量**、**時間帯別のゲームダウンロードファイル数**の情報を確認できます。

##### ゲームインストールデータのExcel保存
ゲームのインストールに関連するExcelデータ保存項目は、次のとおりです。
ファイル名は、`RealTime_GameDownload_日付_時間.xlsx`形式で提供されます。

ゲーム実行の指標データは、Download、Download (Game)、Download (OS)、Update、Update (Game)、Update (OS)の各タブで提供されます。

**Download**タブでは、時間帯別のフルインストール項目に関する情報を表示し、照会可能な項目は次のとおりです。
   - **Download**：フルインストール数
   - **Download Success**：フルインストール成功数
   - **Download Fail**： フルインストール失敗数
   - **Download Average Time (sec)**：ダウンロード平均時間(秒)
   - **Download File Size (MB)**：ダウンロードファイルサイズ(MB)
   - **Download Files**： ダウンロードファイル数

**Download (Game)**タブでは、時間帯に応じたゲーム別の指標情報を提供します。
   各ゲーム名の下に、以下の項目指標を確認できます。
   - **Total**：フルインストール数
   - **Success**：フルインストール成功数
   - **Failure**：フルインストール失敗数

**Download (OS)**タブでは、時間帯に応じたOS別の指標情報を提供します。
   各OSの下に、以下のような項目指標を確認できます。
   - **Total**：フルインストール数
   - **Success**：フルインストール成功数
   - **Failure**：フルインストール失敗数

**Update**タブでは、時間帯に応じたアップデートインストールの指標情報を提供します。
   - **Update**：アップデートインストール数
   - **Update Success**：アップデートインストール成功数
   - **Update Fail**：アップデートインストール失敗数
   - **Update Average Time (sec)**：アップデート平均時間(秒)
   - **Update File Size (MB)**： アップデートファイルサイズ(MB)
   - **Update Files**：アップデートファイル数

**Update (Game)**タブでは、時間帯に応じたアップデートインストールの、ゲーム別指標情報を提供します。
   各OSの下に、以下の項目指標を確認できます。
   - **Total**：フルインストール数
   - **Success**：フルインストール成功数
   - **Failure**：フルインストール失敗数

**Update (OS)**タブでは、時間帯に応じたアップデートインストールの、OS別指標情報を提供します。
   各OSの下に、以下の項目指標を確認できます。
   - **Total**：フルインストール数
   - **Success**：フルインストール成功数
   - **Failure**：フルインストール失敗数


#### リアルタイムモニタリング - ランチャー

ランチャーの項目では、ランチャーの実行とインストールの情報を表示します。

##### ランチャーのフィルタ情報

![realtime_execute_launcher_filter](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_filter_launcher_250717.png)

> ➊ 照会対象
> 照会対象には、**ユーザーID基準**と**全実行基準**の項目があります。
> 照会対象の種類
>   - **UserID基準**：ユーザーが同じ操作を複数回行った際に発生する、重複データを含みません。
>   - **全実行基準**：ユーザーの全ての操作を基準に照会し、同じ操作による重複データを含んだデータを照会します。
>
> ➋ OS
> ユーザーが使用したOSの情報リストをフィルタリングして照会できます。
>
> ➌ ランチャーバージョン
> ランチャーバージョンの情報リストをフィルタリングして照会できます。
>
> 目的のフィルタを選択した後、適用をクリックして照会結果をフィルタリングできます。


##### ランチャーの実行

![realtime_execute_launcher](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_execute_launcher_none_250717.png)

ダッシュボードでは、ランチャー実行数、成功数、失敗数を提供し、前日比での増減値を通じて実行のトレンドを確認できます。
チャートでは、時間帯別のランチャー実行数、ランチャー実行の失敗理由、OSシェア、ランチャーバージョンのシェアを確認できます。

##### ランチャー実行データのExcel保存

ランチャーの実行に関連するExcelデータ保存項目は、次のとおりです。
ファイル名は、`Realtime_Launcher_日付_時間.xlsx`形式で提供されます。

ランチャー実行の指標は、**Dashboard**、**Execution (OS)**、**Execution (Launcher Version)**の各タブでデータが提供されます。

**Dashboard**タブでは、時間帯別のランチャー実行指標情報を提供します。
   - **Launcher Execution**：ランチャー実行数
   - **Launcher Execution Success**：ランチャー実行成功数
   - **Launcher Execution Fail**：ランチャー実行失敗数

**Execution (OS)**タブでは、時間帯に応じたOS別の指標情報を提供します。
   各OS名の下に、以下の項目指標を確認できます。
   - **Total**：フルインストール数
   - **Success**：フルインストール成功数
   - **Failure**：フルインストール失敗数

**Execution (Launcher Version)**タブでは、時間帯に応じたランチャーバージョン別の指標情報を提供します。
各ランチャーバージョンの下に、以下の項目指標を確認できます。
   - **Total**：フルインストール数
   - **Success**：フルインストール成功数
   - **Failure**：フルインストール失敗数


##### ランチャーのインストール
![realtime_install_launcher](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_install_launcher_none_250717.png)

ダッシュボードでは、**ランチャーインストール数**、**ランチャーインストール成功数**、**ランチャーインストール失敗数**を提供し、前日比での増減値を確認できます。
チャートでは、時間帯別のランチャーインストール数と、**ランチャーインストールの失敗理由**を確認できます。


##### ランチャーインストールデータのExcel保存
ランチャーのインストールに関連するExcelデータ保存項目は、次のとおりです。
ファイル名は、`Realtime_LauncherInstall_日付_時間.xlsx`形式で提供されます。

ランチャーインストールの指標は、**Dashboard**、**Install (OS)**、**Install (Launcher Version)**の各タブでデータが提供されます。
**Dashboard**タブでは、時間帯別のランチャー実行指標情報を提供します。
   - **Launcher Install**：ランチャーインストール数
   - **Launcher Install Success**：ランチャーインストール成功数
   - **Launcher Install Fail**：ランチャーインストール失敗数

**Install (OS)**タブでは、時間帯に応じたOS別の指標情報を提供します。
   各OS名の下に、以下の項目指標を確認できます。
   - **Total**：フルインストール数
   - **Success**：フルインストール成功数
   - **Failure**：フルインストール失敗数

**Install (Launcher Version)**タブでは、時間帯に応じたランチャーバージョン別の指標情報を提供します。
   各ランチャーバージョンの下に、以下の項目指標を確認できます。
   - **Total**：フルインストール数
   - **Success**：フルインストール成功数
   - **Failure**：フルインストール失敗数


### モニタリング指標


モニタリング指標は、日次、週次、月次で集計された指標を提供します。
設定した期間の集計指標データを照会し、**条件**をクリックしてフィルタリングされたデータを照会できます。

#### モニタリング指標のフィルタ情報

![monitoring_filter](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_filter_none_250717.png)

> 1. 照会対象
> 照会対象には、**ユーザーID基準**と**全実行基準**の項目があります。
> 照会対象の種類
>   - **ユーザーID基準**：ユーザーが同じ操作を複数回行った際に発生する、重複データを含みません。
>   - **全実行基準**：ユーザーの全ての操作を基準に照会し、同じ操作による重複データを含んだデータを照会します。
>
> 2. OS
> ユーザーが使用したOSの情報リストをフィルタリングして照会できます。
>
> 3. ランチャーバージョン
>
> ランチャーバージョンの情報リストをフィルタリングして照会できます。
>
> 4. ゲーム名
> ゲーム名(ゲームバージョン)の情報リストをフィルタリングして照会できます。
> 目的のフィルタを選択した後、**適用**をクリックして照会結果をフィルタリングできます。


#### ゲームの実行

![monitoring_execute_game](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_execute_game_none_250717.png)

照会した期間の、ゲーム実行数とゲーム実行の失敗理由に関するチャートデータを提供します。

#### ゲームのインストール

![monitoring_install_game](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_install_game_none_250717.png)

照会した期間の、ゲームインストール数とゲームインストールの失敗理由に関するチャートデータを提供します。

#### ランチャーの実行

![monitoring_execute_launcher](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_execute_launcher_none_250717.png)

照会した期間の、ランチャー実行数とランチャー実行の失敗理由に関するチャートデータを提供します。

#### モニタリング指標

![monitoring_grid1](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_grid_1_none_250717.png)

照会した期間の全モニタリング指標を、表形式で提供します。
期間(日次)別のデータを提供し、以下のデータ項目を確認できます。

>- ゲーム実行/実行成功/実行失敗
>- ゲームインストール/インストール成功/インストール失敗/インストール離脱
>- ゲームのアップデートインストール/インストール成功/インストール失敗/インストール離脱
>- ランチャー実行/実行成功/実行失敗


#### モニタリングデータのExcel保存

モニタリング指標データをExcelに保存できます。

モニタリング指標のExcelデータ保存項目は、次のとおりです。
ファイル名は、`Monitoring_日付_時間.xlsx`形式で提供されます。

ランチャーインストールの指標は、**GameExecution (Game)**、**GameExecution (OS)**、**GameDownload (Game)**、**GameDownload (OS)**、
**GameUpdate (Game)**、**GameUpdate (OS)**、**LauncherExecution (OS)**、**LauncherExecution (Version)**、**Bounce**の各タブでデータが提供されます。

**GameExecution**関連タブでは、照会期間のゲーム実行情報を提供します。
   - **GameExecution (Game)**：ゲーム別のゲーム実行指標(合計数、成功数、失敗数)
   - **GameExecution (OS)**：OS別のゲーム実行指標(合計数、成功数、失敗数)

**GameDownload**関連タブでは、照会期間のゲームダウンロード情報を提供します。
   - **GameDownload (Game)**：ゲーム別のゲームダウンロード指標(合計数、成功数、失敗数)
   - **GameDownload (OS)**：OS別のゲームダウンロード指標(合計数、成功数、失敗数)

**GameUpdate**関連タブでは、照会期間のゲームアップデート情報を提供します。
   - **GameUpdate (Game)**：ゲーム別のゲームアップデート指標(合計数、成功数、失敗数)
   - **GameUpdate (OS)**：OS別のゲームアップデート指標(合計数、成功数、失敗数)

**LauncherExecution**関連タブでは、照会期間のランチャー実行情報を提供します。
   - **LauncherExecution (Game)**：ゲーム別のランチャー実行指標(合計数、成功数、失敗数)
   - **LauncherExecution (OS)**：OS別のランチャー実行指標(合計数、成功数、失敗数)

**Bounce**タブでは、照会期間のゲーム別離脱率指標情報を提供します。
   各ゲームのインストール及びアップデート過程で発生した離脱率を確認できます。

   離脱数は、ゲームのインストール中断及びアップデート中の離脱数を表します。
   データを確認した後、ランチャー実行の失敗データを通じて、問題をより詳細に分析できます。
   - **Game Install**：ゲームのインストールが試行された数
   - **Game Install Bounce**：ゲームのインストール中に離脱した数
   - **Game Update**：ゲームのアップデートが試行された数
   - **Game Update Bounce**：ゲームのアップデート中に離脱した数
   - **Game Execution**：ゲームのアップデートやインストールを試みたユーザーのうち、実行まで試みた数
