## Game > GameStarter > Console User Guide > Game

## Game

It describes how to register a game and deploy the game settings and binaries.

### Game List
![game_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_list_250717.png)

From the game list, you can register new games or view registered games.
Also, You can filter by game name or whether the game is available.

The game list query results contain the following fields:

#### ➊ Game Name
A unique name of the registered game.

#### ➋ Game OS
An OS to make a game run.

#### ➌ Registration Date
A date that the game was registered.

#### ➍ Registrant
A masked email address of users that registered for a game.

#### ➎ Game Enabled
It Indicates whether the game is enabled or disabled.

#### ➏ View Details
You can check the details of the registered game by clicking **Details** button.


### Register a Game

You can register a new game by clicking **+ Windows** or **+ macOS** by OS' at the top left of the game list.

![game_register](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_regist_win_250717.png)

#### Game Name
Game name should be unique that does not duplicate with other games.
Game names can be 2 to 15 characters long, using Korean, English, uppercase and lowercase letters, and numbers.

#### OS
It indicates the OS information that make a game run.

You can register the game by entering the game name and clicking **Register**.

### Game Details

Click **Details** button for a game in the game list to go to the game details page for detailed information.

![game_detail](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_detail_250717.png)

### Modify a Game

You can modify game information by clicking **Modify** at the top of the game details page.

![game_modify](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_modify_250717.png)

#### ➊ Game Enabled
You can **Disable** a game you're using, or **Enable** a game you're not using.


### Enter the Game

![game_enter](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_enter_250717.png)

Once you've completed game registration, you'll see the games listed.
Click on the red area in the image above to access the game.

Once you've entered the game, you can configure it or deploy its binary.

#### Game Settings List

When you enter a game, the game name appears at the top, and the game's menus appear below.

![game_config_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_list_250717.png)

Game settings allow you to register various settings required when installing a game.

The game settings query results page contains the following fields:
**➊ Game Settings Name**: A name of the registered game settings.
**➋ Registration Date**: It indicates the date the registered game settings were last registered.
**➌ Registrant**: It indicates the masked email address of the registrant who last modified the registered game settings.
**➍ Memo**: A memo for the registered game. 
**➎ Deletion**: Delete the registered game.


#### Register Game Settings

You can register new game settings by clicking **+Register** on the left side of the game settings list.


##### Default Setting
![game_config_register_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_register_01_250717.png)

##### ➊ Game Settings Name
Enter a name for the game settings to distinguish them from other game settings.
Duplicate game names cannot be used within the selected game.
Game settings names can be 2 to 15 characters long, using Korean, English, uppercase and lowercase letters, and numbers.


##### ➋ Memo
Memo is the information entered for reference in game settings.


##### ➌ Obtain Administrator Rights
Select whether to obtain Windows administrator rights when installing the game.
Enabling this feature may cause the user access control (UAC) prompt to appear during the game installation process.


##### ➍ Default Installation Path
When installing a game, specify the default installation path.
For Windows, the default path `<SystemDrive>/ProgramData/<GameName>`.
To set a different path, select **Custom Path** and enter the path you want.


##### ➎ Configured default installation path
The default installation path is shown as an example, based on the default installation path.
Windows displays the default installation path as `<SystemDrive>`, while `C drive` is shown as an example.


Once all settings are complete, click **Next** at the bottom to proceed to the next page.



##### Go to Game Icon


When installing a game, you can create a Go to icon on your desktop.
Click the drop-down menu to choose how you want to create the Go to icon.
![game_select_goto](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_select_goto_250717.png)


When creating a Go to icon, you will need a game icon image and name.

Descriptions of each Go to creation method are as follows:

- **Automatically Create Shortcuts** : shortcuts will always be created without user input.
- **User-selectable Creation** : the launcher can choose whether to create shortcut.
- **Do not Create Shortcuts** : no shortcuts will be created.

![game_config_regist_goto](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_regist_goto_250717.png)

###### ➊ How to Create a Shortcut
You can check the Go to setting information selected above
and modify the Go to setting method selected.


###### ➋ Go to Icon Image
Register the Go to Game icon image to be used when installing the desktop.
The recommended icon image size is 256x256.


###### ➌ Go to Icon Name
Enter the name of the Go to Game icon that is about to be installed on the desktop.
Go to Game icon’s name can be 2 to 50 characters long.
Also, `spacing`, `/` are available for the first and the last characters.


Once all settings are complete, click **Next** at the bottom to proceed to the next page.

##### 5-2-3. Game UI
![game_config_game_ui_basic](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_basic_250717.png)

Game UI allows you to configure the game UI displayed for each game in the launcher.
You can add or remove game icons, background images, and footer content like Terms of Use and Customer Center URLs.


###### ➊ Game Icon
![game_config_game_ui_icon](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_icon_250717.png)

You can register or delete new game icons by clicking '[Edit]' icon on the game icon area.
The recommended game icon image size is 256x256.


###### ➋ Background Image
![game_config_game_background](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_background_250717.png)

You can register new background images by clicking '[Edit]' icon on the background image area.
The recommended background image size is 992x584.
> [Caution] If the image does not fit the given ratio, the launcher image may scroll.


###### ➌ Footer
![game_config_game_terms](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_terms_250717.png)

You can add or remove the Terms of Use or Customer Center from the footer area of the game UI.

The example image above shows the Terms of Use URL input screen that appears when you click '[Edit]' icon for the Terms of Use.
You can also rename "Terms of Use" to something else.


##### Preview


###### UI Preview
You can check the game UI as it will appear in the actual launcher through the **UI Preview** button on the right.

![game_config_game_preview](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_preview_250717.png)

Once you have completed all game settings, you can register the game settings by clicking **Register** button at the bottom.


#### View Game Settings Details

![game_config_register_complete](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_complete_250717.png)

You can go to the game settings details page by clicking on the area highlighted in red in the top image in the game settings list.

![game_config_detail](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_modify_250717.png)

The Game Settings Details page is similar to the Register Game Settings page, but does not allow for input.
You can modify or copy game settings by clicking **Modify** and **Copy** in the upper left corner.


##### ➊ Modify Game Settings

You can modify game settings by clicking **Modify** at the top left of the game settings list.

![game_config_modify](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_modify2_250717.png)

The game settings changes can be saved by clicking **Save** on the last page.


##### ➋ Copy Game Settings

You can copy game settings by clicking **Copy** at the top left of the game settings list.

![game_config_copy](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_copy_250717.png)

A pop-up window for **Copy Game Settings Info** appears, and you can copy it after inputting game settings name and memo.


The above covers registering, viewing details, modifying, and copying game settings.
Since the game settings were simply registered, they were not reflected in the actual launcher.
The description of game deployment follows the description of the game binary.


#### Game Binary

![game_binary_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_list_250717.png)

Game binary is a collection of binary files needed for running a game.
To upload game binaries, you first need to integrate with CDN.

##### CDN Integration
To integrate with CDN, click **Integrate** button on the deployment zone to be integrated.
First, select CDN integration for the deployment zone you wish to link.

In this example, we will integrate with the CDN in the TEST deployment zone.

###### Register Customer CDN

![game_binary_cdn_customer](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn1_250717.png)

Integrate with the customer's own CDN address.
This process requires two steps of setup.

1. Register the GameStarter file storage address as the origin server URL of the customer company's own CDN.
2. Input the customer's own CDN address.
3. Press **Confirm** to start the integration.

![game_binary_cdn_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn_list_250717.png)

The CDN integration result can be checked on the game binary details screen.
Click on the red area in the image above to move to the details screen.

![game_binary_cdn_success](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn_success_250717.png)

If the CDN integration works successfully, you can check the contents on the binary details screen.

![game_binary_cdn_failed](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn_failed_2_250717.png)

Integration may take some time due to deployment to the CDN edge server or other reasons.
If integration takes a while or fails, you can check the contents
on the game binary details screen.


#### View Game Binary Details

![game_binary_cdn_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_list_enter_250717.png)

Click on the red area in the image above to move to the details screen of the game binary.

![game_binary_cdn_enter](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn_enter_250717.png)

Game binary details have the following fields:

##### ➊ Game Binary Info
Display the game binary ID and the deployment zone information.

##### ➋ CDN Info
Display the integrated CDN information.

##### ➌ Game Binary Upload Info
Display the information of the uploaded game binary.
Game binary information provides the number and size of binary files, the date for binary upload date, and upload status.


> [Notes] Upload Status
> 
> - **Upload Canceled**: It indicates the status that game binary upload is canceled.
> - **Upload Completed**: It indicates that the game binary upload is completed.
> - **Upload Failed**: It indicates that error occurred during the game binary upload.
> - **Uploading**: It indicates that game binary is uploading.
> - **Building**: It indicates that the file is being built, including generating metafiles needed for the game binary.
> - **Pending Upload**: It indicates that preparation work is in progress, including generating metafiles needed for the game binary.


##### ➍ Game Executable File Name
It indicates the name of the game executable file among the uploaded game binary files.


#### Game Binary Upload

After CDN integration is complete, you can upload game binary files.
Uploading game binary files will not be immediately reflected in the launcher.
You must deploy the game binary through **Game Deployment** to see the updated version.


![game_binary_upload_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload1_250717.png)

Click **Binary Upload** in the TEST deployment zone line to deploy the game binary list to upload the file.

![game_binary_upload_02](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload2_250717.png)

If you use Windows OS, select the game binary folder to be uploaded
 If you use MAC OS, upload the “game.zip” file provided by Apple and verified.

> <font color="red">\[Caution]</font><br/>
> 
> If the MAC OS’ game binary is not a verified file, the game will not be executed.

![game_binary_upload_03](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload3_250717.png)

You can select the file that runs the game from the **Executable File Name** drop-down menu, or you can type the file name directly to search and then select it.


![game_binary_upload_04](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload4_250717.png)

Once the file is uploaded, the number and size of the uploaded files will be displayed.
Press **Confirm** to proceed the file upload.

![game_binary_upload_05](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload6_250717.png)

It takes time for the file upload to be reflected in the actual CDN.
Wait until **Upload Status** in the red area changes to **Upload Completed**.

Once the upload is complete, the status will change to **Upload Completed**.
You can now deploy the game binary through Game Deployment.

We've covered the process up to uploading the game binary.
You must then deploy the binary after uploading it.

The following sections describe game settings and game binary deployment.


#### Game Deployment

![game_deploy_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_deploy1_250717.png)

You can deploy game settings and game binaries by deployment zone in **Game Deployment**.
The red area in the image above represents a deployment zone.
The orange area allows you to deploy new game settings or check deployment information for a deployment zone.
The green area allows you to deploy new game binary or check deployment information for a deployment zone.

**Deploy** button is disabled if no game settings have been registered or no game binaries have been uploaded.

Below, we will deploy the game settings and binaries registered in the deployment zone.

##### Deploy Game Settings
![game_deploy_config_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_deploy1_reserve_250717.png)

Click **Deploy** in the Game Settings section of the TEST deployment zone to display the **Game Settings Deployment** pop-up window.

Game settings deployment can be scheduled or immediate.

###### Select Game Settings

Registered game settings will be displayed.
Select the game settings you wish to deploy.

###### Scheduled Deployment

![game_deploy_config_01-reserve](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_deploy1_reserve2_250717.png)

Set the ➊ standard time and ➋ deployment time, then click **Confirm** to move to the **Deployment Comparison** step.

###### Immediate Deployment

There's no need to configure anything for immediate deployment. We'll move on to the final step, the **Deployment Comparison** step.

###### Deployment Comparison

![game_deploy_config_deploy](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_deploy_250717.png)

A pop-up window will appear comparing your recently deployed game settings.

After checking all the settings for the new game, click **Deploy** to immediately deploy or schedule a scheduled deployment.
You can check the deployment status and information about the most recently deployed game in the corresponding deployment zone.

![game_deploy_config_complete](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_deploy_complete_250717.png)


##### Deploy Game Binary

Game binary deployment is the process of applying a game binary that has been uploaded.

![game_deploy_binary_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_250717.png)

Click **Deploy** in the **Game Binary Deployment** section of the TEST deployment zone to display the **Game Binary Deployment** pop-up window.
Game binary deployment can be scheduled or immediate.

###### Scheduled Deployment

![game_deploy_binary_02-reserve](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_reserve_250717.png)

Set the ➊ standard time and ➋ deployment time, then click **Confirm** to schedule the game binary deployment.


###### Immediate Deployment
Running **Immediate Deployment** will deploy the uploaded game binary immediately.
You can see that the game binary deployment status has changed to the corresponding deployment zone.

![game_deploy_binary_complete](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_comp_250717.png)

Once deployment is complete, the area will turn green and the **Deploy** button will be disabled, as shown in the image above.
You can check deployment information in the blue box area of the **Game Binary** tab.

![game_deploy_binary_failed](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_failed_250717.png)

You can check the deployment status in the **Game Binary Deployment** area.
The deployment zone area changes color depending on the deployment status.

> [Note] Color information based on deployment status
> 
> **GRAY**: Undeployed status This is the default color when no deployment history exists.
> **YELLOW**: Only game settings are deployed. 
> **GREEN**: Game settings and game binaries have been deployed.
> **RED**: Failed to deploy the game binary


#### Deployment History

##### Game Settings Deployment History

![game_history_config_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_config_1_250717.png)

You can view the deployment history of game settings you've deployed in the Game Settings Deployment History.
You can filter the search results using the search conditions on the right.

##### ➊ Game Settings Name
You can filter your deployment history by the name of the deployed game settings.

##### ➋ Deployment Date
You can filter the deployment history deployed during a specified period.

##### ➌ Deployment Status
You can filter the deployment history with specific deployment status.

The deployment history query results contain the following fields:

![game_history_config_02](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_config_3_250717.png)

##### ➊ Game Settings Name
A name of the deployed game settings.

##### ➋ Deployment Zone
It indicates the deployment zone that game settings is deployed.

##### ➌ Deployment Date
It indicates the date that game settings is deployed.

##### ➍ Deployed by
The masked email address of the user who deployed the game settings is displayed.

##### ➎ Deployment Status
It indicates the status that game settings is deployed.

> [Notes] Status
> 
> - **Deploying**: It indicates that game settings are on deployment.
> - **Deployment Completed**: It indicates that game settings are deployed.
> - **Deployment Failed**: It indicates that error occurred during the game settings deployment.
> - **Deployment Scheduled**: It indicates that game settings deployment is scheduled.
> - **Deployment Schedule Canceled**: It indicates that game settings deployment schedule is canceled.

##### ➏ Memo
A memo of the deployed game settings.


##### Game Binary Deployment History

![game_history_binary_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_binary1_250717.png)

You can view the deployment history of game binaries you've deployed in the Game Binary Deployment History.
You can filter the search results using the search conditions on the right.

##### ➊ Deployment Date
You can filter the deployment history deployed during a specified period.

##### ➋ Deployment Status
You can filter the deployment history with specific deployment status.

The deployment history query results contain the following fields:

![game_history_binary_02](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_binary3_250717.png)

##### ➊ Deployment Zone
It indicates the deployment zone that game binary is deployed.

##### ➋ Game Binary
It displays the information of the deployed game binary.
The game binary information consists of numbers and size of files.

##### ➌ Deployment Date
It indicates the date that game binary is deployed.

##### ➍ Deployer
The masked email address of the user who deployed the game binary is displayed.

##### ➎ Deployment Status

![game_history_binary_04](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_config_4_250717.png)

It indicates the status that game binary is deployed.
Hover over the `?` status in the **Deployment Status** to display the status list.

> [Notes] Status
> 
> - **Deploying**: It indicates that game binary is on deployment.
> - **Deployment Completed**: It indicates that game binary is deployed.
> - **Deployment Failed**: It indicates that error occurred during the game binary deployment.
> - **Deployment Scheduled**: It indicates that a game binary deployment is scheduled.
> - **Deployment Schedule Canceled**: It indicates that game binary deployment schedule is canceled.