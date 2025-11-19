## Game > GameStarter > Console User Guide > Launcher Installer

## Launcher Installer

To run GameStarter launcher, first of all, the launcher must be installed on your PC.
The launcher installer is a program that installs the launcher on your PC.

This document describes the settings required when creating a launcher installer.

### Initial Settings


![installer\_basic](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_basic_250717.png)

The initial setting of the lancer installer can only be set once when setting up the project for the first time.
You can only modify some items after the initial setting is complete.
For modifying settings, see **Modify Settings** below.

### URL Scheme Settings
![installer\_urlscheme](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_url_scheme_250717.png)

The URL scheme setting must be registered first for initial setting.

#### ➊ URL scheme

URL scheme allows the user to communicate with the app using the custom protocols.
GameStarter allows the user to run a launcher with the registered URL Scheme.

> <font color="red">\[Caution]</font><br/>
>
> The URL scheme cannot be changed once set.
If you set it to the URL scheme used by other programs, GameStarter might not run properly.


> [Note] URL Scheme Name Rule
>
> The first letter must start with an English lowercase letter.
> Only lowercase English letters and numbers are allowed, up to 20 characters.


> [Note] Deployment Zone
> URL scheme is entered only once, but multiple deployment zones exist.
> In GameStarter, to distinguish this, it is automatically added to the last part in the form `-<zone>` in the zones excluding the SERVICE deployment zone.
>
> e.g.) SERVICE
> - URL Scheme: example
>
> e.g.) DEVELOP
> - URL Scheme: example-develop

### Common Name Settings
![installer\_names](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_name_250717.png)

#### Common Name
The common name is used as the name of the launcher installation program and deletion program, and is also used in the installation folder and path.

> <font color="red">\[Caution]</font><br/>
>
> The common name cannot be changed once registered.

> [Note] Common Name Rule
>
> For common names, only English uppercase and lowercase letters and numbers are allowed, up to 20 characters.

> [Note] Deployment Zone
> The common name is entered only once, but multiple deployment zones exist.
> In GameStarter, to distinguish this, it is automatically added to the last part in the form `-<ZONE>` in the zones excluding the SERVICE deployment zone.
>
> e.g.) SERVICE
> - Launcher Installler Name: `<Common Name>Insatller`
> - Launcher Uninstaller Name: `<Common Name>Uninstaller`
> - Launcher Installation Folder Name: `<Common Name>`
> - Launcher Installation Path: `C:\Users\<UserName>\AppData\Roaming\<Common Name>`
>
> e.g.) DEVELOP
> - Launcher Installler Name: `<Common Name>Insatller_DEVELOP`
> - Launcher Uninstaller Name: `<Common Name>Uninstaller_DEVELOP`
> - Launcher Installation Folder Name: `<Common Name>_DEVELOP`
> - Launcher Installation Path: \`C:\\Users\\<UserName>\\AppData\\Roaming\\<Common Name>\_DEVELOP

The initial setting has been completed so far.
Once the initial setting is complete, you will be ready to register the installer settings as shown below.
Click **Register** to set the installer.


The following is an example of registering the DEVELOP zone settings:

![installer\_comp1](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_comp_250717.png)

The following is the setting information that requires registration after the initial setting is complete:

#### Go to Launcher Icon
![installer\_icons](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_250717.png)

After installing the GameStarter launcher, you can automatically create a Go to Launcher on the desktop and register the settings required to create a launcher.

#### ➊ Go to Icon Image
Register the Go to icon image.

#### ➋ Go to Icon Name
Enter the Go to icon name.
Check that you have entered correctly and click **Register**.

#### Confirm Registration Settings
You can check the registered settings by clicking the installer settings list.

![installer\_confirm\_list](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_after_list_click_250717.png)

### Deploy Launcher Installer Settings
Once you complete all the settings required for the installer, you must deploy the installer settings.
This task can take a few to tens of minutes.

![installer\_deploy](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_250717.png)

Click **➊ Deploy** to proceed with the deployment and scheduled deployment immediately.


![installer\_deploy\_modal](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_modal_250717.png)

**➊ Scheduled Deployment** can be set from 10 minutes after the registration time.
**➋ Immediate Deployment** is started, the deployment is immediately started.

You can check the status depending on the deployment status.
![installer\_deploy\_status](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_reservation_confirm_2_250717.png)

> Launcher installer deployment status types are as follows:
> - Pending
> - Building
> - Deploying
> - Pending
> - Deployment Failed
> - Deployment Completed
> - Deployment Scheduled
> - Deployment Canceled

> [Note]
>
> If the deployment status appears as **Deployment Failed**, contact the Customer Center.

#### View Deployment History
You can view the information and deployment history of the deployed installer in the **deploy history** tab.
![installer\_deploy\_list](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_list_250717.png)

### Modify Settings
You can view and modify the setting information of the launcher installer.
The installer setting screen after registering and deploying the installer settings according to the instructions above.

#### Check Registered Settings

You can go to a page where you can view/modify the installer details by clicking the areas displayed in red in the lower image.

![installer\_config\_list](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_list_250717.png)

➊ **View per OS button**: Indicate the settings registered for Windows or macOS.
➋ Deployment Zone: Display the deployment zone information.
➌ **installer Setting Version**: Display the installer's configuration version information.
➍ **Registered on**: Indicate the date of registering the installer settings.
➎ **Registered by**: Indicates the masked email address of the user registering the launcher installer settings.
➏ **Memo**: Indicate the memo you entered when registering the launcher installer settings.

#### Confirm the Details of the Registered Settings

You can check the basic information of the installer, and you can check the registration information for the Go to Launcher icon by clicking **Next** at the bottom.
You can modify the basic information settings by clicking **Modify**.

![installer\_config\_enter](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_enter_250717.png)
➊ **Modify button**: You can modify the installer settings.
➋ **URL Scheme**: Indicate the registered URL Scheme information.
➌ **Common Name**: Indicate Installer name, Uninstaller name, installation folder name, and common name information used for the installation path of the registered launcher.
➍ **Installer Version**: Display the installer version information.
➎ **Memo**: Indicate the memo entered when registering the launcher installer settings.

#### Modify Basic Info
To modify the basic information, click **Modify** or click **Next** on the **Installer Settings Details** screen to access the **Modify Installer Settings** page below.

![installer\_config\_modify\_default](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_modify_default_250717.png)
➊ **Installer Version**: You can modify the installer version.
➋ **Memo**: You can modify the contents of the installer setting memo.
Click ➌ **Next** to go to the Next Modify page.

#### Modify GO to Launcher Icon

To modify the Go to Launcher icon, click **Modify**, or click **Next** on the **Modify Basic Info screen** to go to the page below.

You can check the information of the previously registered Go to Launcher icon and modify the Go to icon name.
![installer\_config\_modify\_shotcut](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_modify_shotcut_250717.png)

You can pre-check what has been modified by clicking **Preview**

![installer\_config\_modify\_preview](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_modify_preview1_250717.png)
You can check the information below on the preview screen:
- Deployment zone information
- Basic information to change
- icon information for the Go to Launcher to change

After modifying, you can click **Save** to reflect the modified settings.
