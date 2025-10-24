## Game > GameStarter > Console User Guide > Launcher

As discussed in [Get Started](./console-01-getting-started), you must complete the installer and game setup before using the launcher.
First, complete the installer, game setup, and binary preparation.

## Launcher

It describes how to set up and deploy the launcher.

### Launcher Setting List

![launcher_list](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_list_250717.png)

You can view the launcher setting registered in the **Launcher Setting** list. Additionally, you can register or delete a new launcher, and copy the existing launcher setting.
A launcher is also registered by OS the same as with a game.

The launcher list query results contain the following fields:

#### ➊ Launcher Setting Name
It displays the name entered when registering the launcher setting.

#### ➋ OS
It displays the executable OS.

#### ➌ Registration Date
The date the launcher setting were registered or last modified is displayed.

#### ➍ Registrant
The masked email address of the user who first registered or last modified the launcher setting is displayed.

#### ➎ Memo
The memo is displayed that was entered by the user when registering the launcher setting to distinguish them.

#### ➏ Delete
You can delete the registered launcher setting.
Deleting a launcher setting will not delete any previously deployed launcher setting.


### Register Launcher Setting
You can register a new launcher setting by clicking + Windows or + macOS, depending on your OS, at the top left of the launcher setting list.

#### Basic Info
![launcher_register_01](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_register1_250717.png)

##### ➊ Launcher Setting Name
Enter a name for the launcher setting to distinguish them from other launcher setting.
Therefore, the launcher setting name cannot be duplicated.
You can also enter 2 to 20 characters, including Korean, English uppercase and lowercase letters, numbers, and spaces.


##### ➋ Memo
Memo is the information entered for reference in launcher setting.

Once all setting are complete, click Next to proceed to the next page.


#### Configure a Launcher Layout

Set the mode in which the launcher runs.
![launcher_register_01](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_config2_250717.png)


##### ➊ Execution Mode
Sets the launcher's execution mode.
* **Silent Mode**: You can start a game immediately without launching the launcher UI.
* **Autorun**: The game will launch immediately without the user having to take any additional action, such as selecting a game.
> Autorun is only available when there is only one game registered in the launcher UI. 
> In the previous example, the game is unavailable for selection since three games were selected.
> The autorun feature is available when only one game is selected.

* **Auto Update**: Auto update allows you to update a game immediately when the launcher is launched.


##### ➋ Launcher Top
You can select whether to display an icon at the top of the launcher.


##### ➌ Brand Icon
You can also set a brand icon for other games. Upload the image file you want to use.

Only JPG, JPEG, or PNG formats can be used for brand icon image files.
The recommended brand icon image file’s size is 256x256.

#### ➍ Select a Launcher Game

You can launch multiple games from a single launcher and configure the list of games to display on the launcher.

The game registration pop-up will display a list of registered games.
You can see the games appear in the launcher in the order you select them.
The example below illustrates adding **game1**, **game2**, and **game3** in the order.


#### Preview
You can preview the configured launcher information using the Preview button at the bottom.

![launcher_config_preview](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_config_preview_250717.png)

You can register the game by completing all setting and clicking **Register**.


### View Launcher Setting Details
![launcher_config_list](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_config_list_250717.png)

Click on the red area in the image above to move to the page of the launcher setting details.

![launcher_modify_01](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_config_modify_250717.png)

You can modify or copy launcher setting from the View Details page.
To modify or copy launcher setting, click **Modify** or **Copy** in the upper left corner.

#### Modify Launcher Setting

![launcher_modify_02](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_config_modify2_250717.png)

Click **Modify** to move to the page of the **Modify Launcher Setting**.
After modifying the launcher setting, click **Save** in the final step to apply the changes.


##### Copy Launcher Setting
![launcher_copy](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_config_copy_250717.png)

Click **Copy** to display the **Copy Launcher Setting** Information pop-up window.
Copy the setting, excluding the launcher setting name and memo.

* **Launcher Setting Name**
  Enter the launcher setting name you want to copy.
  As with registering launcher setting, duplicate names are not allowed.

* **Memo**
  In the Memo, enter information that will help you identify the launcher setting you want to copy.


### Deploy Launcher
![launcher_deploy_list](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_deploy_list_250717.png)
The Launcher Deployment page allows deployments by deployment zone.
The default deployment zones are SERVICE, DEVELOP, and TEST.
You can deploy launcher setting to each deployment zone.

Initially, no launcher setting are registered, so the **Deploy** button in the **Execute Deployment** section is disabled.

The Launcher Execution screen contains the following components:

#### ➊ Launcher Setting Name
It displays the name of the launcher setting currently deployed.

#### ➋ Game List
It displays the game list of the launcher setting currently deployed in order.

#### ➌ Deployment Date
The last deployment date is displayed.

#### ➍ Deployed by
The masked email address of the last deployer to be deployed is displayed.

#### ➎ Launch Template
The launch template provides JavaScript that can be used to launch the launcher or download the installer from a web browser.

#### ➏ Execute Launcher
Once the launcher is deployed to the deployment zone, you can launch it.


The following is an example of deploying the launcher setting registered in the DEVELOP deployment zone.
Click **Deploy** in the DEVELOP deployment zone to display the **Launcher Deployment** pop-up window shown below.

![launcher_deploy](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_deploy_250717.png)

There are two ways to deploy the launcher:
- Scheduled Deployment
- Immediate Deployment

##### ➊ Launcher Setting
Select a launcher setting you want to deploy.
When you select Launcher Setting, the games you've registered will be displayed in order in the green area on the screen below.

##### ➋ Scheduled Deployment
To deploy the launcher setting at a specific time, click **Scheduled Deployment**.

Select the standard time and deployment time, then click **Confirm** to register the scheduled deployment time.
In the final step, Deployment Comparison , review the details and click **Deploy** to register the scheduled deployment.

##### ➌ Immediate Deployment
Deploy a launcher immediately.
Since immediate deployment requires no separate setting, we move on to the final step, the deployment comparison step.

##### Deployment Comparison
Once immediate or scheduled deployment setting are complete, a pop-up window will appear in the final step, comparing the latest deployment information.

![launcher_deploy_confirm](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_deploy_confirm_250717.png)

You can check the basic information, layout configuration, and game information to be displayed.

After confirming all launcher setting to be deployed, click Deploy.

You'll see the deployment status in the deployment zone changed.


![launcher_deploy_complete](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_deploy_comp_250717.png)

After deployment is complete, you can copy the launch template from the list of **recently deployed launcher setting** or run the launcher.


#### ➊ Launch Template
The launch template provides JavaScript that can be used to launch the launcher or download the installer from a web browser. If the launcher is already installed in the deployment zone, it will launch.
If the launcher is not installed, the installer will be downloaded.
Click **Copy** to copy the JavaScript code.

#### ➋ Execute Launcher
Once the launcher is deployed to the deployment zone, you can launch it.

![launcher_execute](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_execute_250717.png)

Click **Execute Launcher** to execute the launcher in the deployment zone.
Select the game you want to launch and click **Confirm**. Depending on whether the launcher is installed on the PC, the following two options will be displayed:


- If you've already installed the launcher
  ![launcher_execute_urlscheme](https://static.toastoven.net/prod_gamestarter/console/gamestarter_launcher_execute_urlscheme_202311.png)

If you've installed the launcher, a pop-up window will appear in the browser to execute the launcher.
Click **Open GameStarter** to launch the launcher.


- If you haven't installed the launcher
  ![launcher_execute_download](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_download_250717.png)

If you haven’t installed the launcher, a pop-up window will appear in the browser to download the launcher.
You can download the installer by clicking `[Confirm]` button.


- The screen that the launcher is running
  After installing the launcher using the launcher installer, the following screen will appear when you run the launcher.

![launcher_final](https://static.toastoven.net/prod_gamestarter/console/gamestarter_launcher_final_202311.png)



### Deployment History
![launcher_history_01](https://static.toastoven.net/prod_gamestarter/console/launcher/gamestarter_launcher_deploy_history_250717.png)

You can view the launcher deployment history in the **Deployment History** tab.

The deployment history view order is as follows:
➊ Select the OS you want to view.
➋ Select a deployment zone.

Filter by setting up the search conditions. There are three search conditions:
➌ **Launcher Setting Name**: You can filter by launcher setting name.
➍ **Launcher Deployment Date**: You can filter by a specific period.
➎ **Deployment Status**: You can filter by deployment status.


The deployment history query results contain the following fields:
- **Launcher Setting Name**: A name of the deployed launcher setting.
- **Deployment Zone**: It indicates the information of the deployment zone.
- **OS**: An OS of the game.
- **Game List**: A game that the deployed launcher is configured.
- **Deployment Status**: A deployment status of the deployed launcher.
  
  > - Deploying
  > - Deployment Completed
  > - Deployment Scheduled
  > - Deployment Schedule Canceled
  > - Deployment Failed

- **Deployed at**: It indicates the date that the launcher is deployed.
- **Deployed by**: A masked email address of users that deploy the launcher.
- **Memo**: It indicates the memo of the deployed launcher.