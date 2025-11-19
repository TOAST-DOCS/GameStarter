## Game > GameStarter > Console User Guide > Metrics

GameStarter provides relevant data for efficient metric detection of the game.
It provides installation, execution, launcher installation, and launch data for the game, and makes it easy to see the main metrics for running and entering the game, such as churn rate.

## Metrics

The menus to view metric data is as follows:

![statistics\_title1](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_title_1_250717.png)

➊ **Real-time Monitoring**: Provide metric data from midnight of the day to the view time.
➋ **Monitoring Metrics**: Provide aggregate data for the set period (day, week, and month).
➌ You can check the query reference time of the data.
➍ **Refresh**: Data can be updated to the data at the time of request.
Real-time metrics are not automatically updated to avoid server load. Click **Modify** to update the data.
➎ **Conditions**: You can apply filters to view data. For the provided filters, check the contents of the filter information for each item.
You can view data by clicking **View**.
➏ **Save in Excel**: You can save the metric data as an Excel file. For a description of the provided Excel data, see the contents of the item in **Save in Excel**.


### Real-time Monitoring

Real-time monitoring is a feature that allows you to view indicator data from midnight of the same day to the time of inquiry.
It allows you to retrieve data from midnight (00:00) to the view time, and you can also filter and view data by clicking **conditions**.

![statistics\_main](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_main_250717.png)


#### Real-time Monitoring - Game

You can see the metric data for running and installing the game with the dashboard and chart data.
You can easily get metric data for each game execution and installation metrics through dashboard and chart data.

##### Game Filter Info

Metric data can be viewed and stored as an Excel file by applying filters.

![realtime\_game\_filter](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_filter_250717.png)

> ➊ View Target
>View target includes items based on User ID and overall execution criteria.
>View Target Type
>- **Based on User ID**: it does not include duplicate data that occurs when a user performs the same action multiple times.
>- **Based on Total Execution**: it searches all user actions and data that includes duplicate data for the same action.
>
> ➋ OS
>   You can view by filtering the list of OS information used by an OS user.
>
> ➌ Game Name
>   You can view game names by filtering the list of game names (game version) information.
>
> Select the filter data you want and click **Apply** to filter out your results.


##### Run Game

Display metrics related to running the game.

![statistics\_real\_game](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_execute_game_none_250717.png)
**game executions**, **game execution successfully**, and **game execution failed** are provided in the dashboard, and you can check the increase compared to the previous day.
Charts also allow you to see **the number of increases** by time zone and the information about the **reason for launch failure**.


You can also save metric data by clicking **Save** to make more efficient use of metric data.
The data saved in Excel is based on the data when the save request is made.

##### Save Game Execution in Excel
The following are the excel data storage items related to launching the game.
The file name is provided in the `RealTime_GameExecution_dates_times.xlsx` format.

Game execution metric data can be found in Execute (Game) and Execute (OS) tabs per time.

1. The Execute (Game) tab provides aggregate data for the number of games launched by game, number of games successful, and number of games failed by time zone.
2. The Execute (OS) tab provides aggregate data for the number of games launched by OS, number of games successful, and number of games failed by time zone.

##### Install Game

Display metrics related to the game installation.

![realtime\_install\_game1](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_install_game_none_250717.png)

You can check the **number of games installed**, **number of games installed successfully**, **number of games installed failed**, **average game download speed**, **file download capacity**, and **file download capacity** in the dashboard.
The meanings of FULL and UPDATE for dashboard are as follows:
- **FULL**: full Installation
- **UPDATE**: update installation


![realtime\_install\_game2](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_install_game2_none_250717.png)

Chart data lets you see **the number of games installed** by time, **reason for game installation failed**, **total number of games installed by update**, **average of entire game updates installed by time**, **download speed and capacity per time**, and **the number of games download files by time**.

##### Save Game Installation in Excel
The following are the excel data storage items related to game installation.
The file name is provided in the `RealTime_GameDownload_dates_times.xlsx` format.

Game execution metric data is provided with data in the Download, Download (Game), Download (OS), Update, Update (Game), and Update (OS) tabs.

The **Download** tab displays the information of all installation items by time. The following items that can be viewed.
- **Download**: Total number of installations
- **Download Succecced**: Total number of successful installations
- **Download Failed**: Total number of installations failed
- **Download Average Time (sec)**: Average download time (sec)
- **Download File Size (MB)**: Download file size (MB)
- **Download Files**: Download File Count

The **Download (Game)** tab provides metrics for each game by time zone.
You can see the metrics below under each game name.
- **Total**: Total number of installations
- **Success**: Total number of successful installations
- **Failure**: Total number of installation failed

The **Download (OS)** tab provides metrics for each OS by time zone.
You can see the metrics below for each OS.
- **Total**: Total number of installations
- **Success**: Total number of successful installations
- **Failure**: Total number of installation failed

The **Update** tab provides metrical information for the update installation by time zone.
- **Update**: Number of update installations
- **Update Success**: Number of successful update installations
- **Update Fail**: Number of update failures
- **Update Average Time (sec)**: Average update time (sec)
- **Update File Size (MB)**: Update file size (MB)
- **Update Files**: Number of update files

The **Update (Game)** tab provides metrics for each game for the update installation by time zone.
You can see the metrics below in the subsection of each OS.
- **Total**: Total number of installations
- **Success**: Total number of successful installations
- **Failure**: Total number of installation failed

The **Update (OS)** tab provides metric information for the update installation by OS by time zone.
You can check the metrics below for each OS separately.
- **Total**: Total number of installations
- **Success**: Total number of successful installations
- **Failure**: Total number of installation failed


#### Real-time Monitoring - Launcher

The launcher item displays the launcher execution and installation information.

##### launcher Filter Information

![realtime\_execute\_launcher\_filter](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_filter_launcher_250717.png)

> ➊ View Target
>The target for the view has items in **Based on User ID** and **Based on Total Execution**.
>View Target Type
>   - **Based on UserID**: it does not include duplicate data that occurs when a user performs the same action multiple times.
>   - **Based on Total Execution**: it searches all user actions and data that includes duplicate data for the same action.
>
> ➋ OS
> You can view by filtering the list of OS information used by an OS user.
>
> ➌ Launcher version
> You can view the launcher version information list by filtering.
>
> Select the filter you want and click Apply to filter out the results.


##### Run launcher

![realtime\_execute\_launcher](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_execute_launcher_none_250717.png)

The dashboard provides the number of launcher executions, the number of successes, and the number of failures, and you can check the execution trend through the previous day's decrease.
You can see the number of launcher executions per time, the cause of launcher failure, OS share, and launcher version share in the chart.

##### Save Launcher Execution in Excel

The following are the Excel data storage items related to running a launcher.
The file name is provided in the `Realtime_Launcher_datum_hour.xlsx` format.

Metrics for running a launcher are provided with data in the **Dashboard**, **Execution (OS)**, and **Execution (Launcher Version)** tabs.

The **Dashboard** tab provides information about the execution metrics for the launcher by time.
- **Launcher Execution**: Number of launcher executions
- **Launcher Execution Success**: Number of successful launcher executions
- **Launcher Execution Fail**: Number of launcher execution failed

The **Execution (OS)** tab provides metrics for each OS by time zone.
You can check the metrics below for each OS name.
- **Total**: Total number of installations
- **Success**: Total number of successful installations
- **Failure**: Total number of installation failed

The **Execution (Launcher Version)** tab provides metrics for each launcher version by time zone.
You can see the metrics below for each launcher version.
- **Total**: Total number of installations
- **Success**: Total number of successful installations
- **Failure**: Total number of installation failed


##### Install Launcher
![realtime\_install\_launcher](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_install_launcher_none_250717.png)

The dashboard provides the **number of launcher installations**, **number of successful launcher installations**, and **number of launcher installations failed**, and you can check the increase compared to the previous day.
You can check the number of launcher installations per hour and **why the launcher installation failed** in charts.


##### Save Launcher Installation in Excel
The following are the excel data storage items related to the installation of the launcher.
The file name is provided in the `Realtime_LauncherInstall_datum_time.xlsx` format.

The metric for installing the launcher is provided with data in the **Dashboard**, **Install (OS)**, and **Install (Launcher Version)** tabs.
The **Dashboard** tab provides information about the execution metrics for the launcher by time.
- **Launcher Install**: Number of launcher installations
- **Launcher Install Success**: Number of successful launcher installations
- **Launcher Install Fail**: Number of launcher executions failed

The **Install (OS)** tab provides metrics for each OS by time zone.
You can check the metrics below under each OS name.
- **Total**: Total number of installations
- **Success**: Total number of successful installations
- **Failure**: Total number of installation failed

The **Install (Launcher Version)** tab provides the metric information for each launcher version by time zone.
You can see the metrics below for each launcher version.
- **Total**: Total number of installations
- **Success**: Total number of successful installations
- **Failure**: Total number of installation failed


### Monitoring Metrics


Monitoring metrics provide metrics calculated by day, week, and month.
You can view the actual metric data for the set period, and click **Condition** to view the filtered data.

#### Monitoring Metrics Filter Info

![monitoring\_filter](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_filter_none_250717.png)

> 1. View Target
     > View Target has items in **Based on User ID** and **Based on Total Execution**.
     > View Target Type
     >   - **User ID**: Do not include duplicate data that occurs because the user performs the same action multiple times.
     >   - **Based on total execution**: it searches all user actions and data that includes duplicate data for the same action.
>
> 2. OS
     >You can view by filtering OS > OS information list used by users.
>
> 3. Launcher Version
>
>  You can view the launcher version information list by filtering.
>
> 4. Game Name
     > You can view by filtering the list of the game name (game version) information.
     > Select the filter you want and click **Apply** to filter the view results.


#### Run Game

![monitoring\_execute\_game](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_execute_game_none_250717.png)

Provide chart data for the number of games executed for the view period and why the game failed.

#### Install Game

![monitoring\_install\_game](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_install_game_none_250717.png)

Provide chart data for the number of game installations for the view period and why the game installation failed.

#### Run launcher

![monitoring\_execute\_launcher](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_execute_launcher_none_250717.png)

Provide chart data of the number of launcher executions and the reason for the launcher execution failure for the view period.

#### Monitoring Metrics

![monitoring\_grid1](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_grid_1_none_250717.png)

Provide a full monitoring metric for the view period in table format.
Data is provided by period (date), and you can see the data items below.

>- Game execution/execution succeeded/launch failed
>- Game installation/installation succeeded/installation failed/installation abandonment
>- Game update installation/installation succeeded/installation failed/installation abandonment
>- Launcher execution/execution succeeded/execution failed


#### Save Monitoring in Excel

You can store the monitoring metric data as an excel.

The Excel data storage item of the monitoring metric is as follows.
The file name is provided in the `Monitoring_datum_hour.xlsx` format.

The metric for game installation is provided with **GameExecution (Game)**, **GameExecution (OS)**, **GameDownload (Game)**, **GameDownload (OS)**,
**GameUpdate (Game)**, **GameUpdate (OS)**, **LauncherExecution (OS)**, **LauncherExecution (Version)**, and **Bounce** tabs.

The **GameExecution** related tab provides the game execution information for the search period.
- **GameExecution (Game)**: Metrics of game execution by game (total, number of successes, and failures)
- **GameExecution (OS)**: Metrics of game execution by OS (total number, number of successes, number of failures)

The **GameDownload** related tab provides the game download information for the search period.
- **GameDownload (Game)**: Metrics for game-by-game download (total number, number of successes, and number of failures)
- **GameDownload (OS)**: Metrics for game download by OS (total number, number of successes, and number of failures)

The **GameUpdate** related tab provides game update information for the search period.
- **GameUpdate (Game)**: Metrics for game-by-game update (total numbers, number of successes, and number of failures)
- **GameUpdate (OS)**: Metrics for game update by OS (total number, number of successes, number of failures)

The **LauncherExecution** related tab provides the execution information for the search period.
- **LauncherExecution (Game)**: Metrics of launcher execution by game (total number, number of successes, and number of failures)
- **LauncherExecution (OS)**: Metrics for running the launcher per OS (total, number of successes, number of failures)

The **Bounce** tab provides information about the abandonment rate for each game for the search period.
You can check the abandonment rate that occurs during the installation and update process for each game.

The number of abandonments shows the number of abandonments during the game's installation and updates.
After reviewing the data, you can further analyze the issue using the launcher launch failure data.
- **Game Install**: Number of game installation attempts
- **Game Install Bounce**: Number of abandonments during game installation
- **Game Update**: Number of game update attempts
- **Game Update Bounce**: Number of abandonments during game updates
- **Game Execution**: Number of users trying to update or install the game until they execute
