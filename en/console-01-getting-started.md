<!-- pre-align:aligned sig=3d4a4a7e798a -->

<a id="game-gamestarter-console-user-guide-get-started"></a>
## Game > GameStarter > Console User Guide > Get Started { #game-gamestarter-console-user-guide-get-started }

<a id="before-starting"></a>
## Before Starting { #before-starting }

This document describes the information for using GameStarter.

<a id="gamestarter-components"></a>
## GameStarter Components { #gamestarter-components }

GameStarter consists of four main components.

- Game
- Launcher
- Launcher Installer
- Metrics

<a id="game"></a>
### Game { #game }

GameStarter launcher can be configured for multiple games. You must register each game you wish to service and then deploy the required settings and binaries for each game.

For more information about the game, refer to [Console User Guide > Game](./console-02-game).

<a id="launcher"></a>
### Launcher { #launcher }

GameStarter launcher helps downloading, updating, running a game. The launcher must have the necessary information and binaries for game installation. If this information and binaries are missing, the game cannot be installed or run through the launcher.

Therefore, before configuring the launcher, ensure that the game setup and binary deployment are complete.

For more information about the launcher, refer to [Console User Guide > Launcher](./console-03-launcher).

<a id="launcher-installer"></a>
### Launcher Installer { #launcher-installer }

To run GameStarter launcher, first of all, the launcher must be installed on your PC. The launcher installer is a program that installs the launcher on your PC. If the launcher installer isn't available, you won't be able to install the launcher.

Before configuring the launcher, you must ensure that the launcher installer has been created.

For more information about the launcher installer, refer to [Console User Guide > Launcher Installer](./console-04-installer).

<a id="metrics"></a>
### Metrics { #metrics }

GameStarter provides metrics.

It consists of real-time monitoring and monitoring metrics.

Real-time monitoring provides real-time metrics for installing, running launcher and game. Monitoring metrics provides daily, weekly, monthly metrics for installation and run.

For more information about the metric, refer to [Console User Guide > Metric](./console-05-statistics).

<a id="gamestarter-operational-process"></a>
## GameStarter Operational Process { #gamestarter-operational-process }

Each component of GameStarter is interdependent, so the order in which it runs may vary depending on the situation. The following are examples of recommended orderings for different situations:

<a id="project-initial-settings"></a>
### Project Initial Settings { #project-initial-settings }

- Once you’ve created a project, you need to configure \*\*[Game], [Launcher], [Launcher Installer]\*\*.
- We recommend that you proceed in the following order:
- [Game] → [Launcher] → [Launcher Installer] → \[Test]

<a id="game-binary-update"></a>
### Game Binary Update { #game-binary-update }

- If the game settings and binaries have already been deployed to the launcher
- After uploading the game binaries you wish to modify, proceed with binary deployment in Game Deployment.
- We recommend that you proceed in the following order:
- \[Game Binary: Upload] → \[Game Deployment: Binary] → \[Test]

<a id="game-settings-update"></a>
### Game Settings Update { #game-settings-update }

- If the game settings and binaries have already been deployed to the launcher
- Update the settings information through Modify Game Settings
- After that, deploy the game settings in the Deploy Game
- We recommend that you proceed in the following order:
- \[Game Settings: Modify] → \[Game Deployment: Settings] → \[Test]

<a id="add-a-new-game"></a>
### Add a New Game { #add-a-new-game }

- If you have already completed game setup and launcher deployment
- To add a new game, you need to add a [Game] and update a [Launcher\[.
- We recommend that you proceed in the following order:
- [Register Game] → \[Game Settings: Register] → \[Game Binary: Upload] → \[Game Deployment: Settings \& Binary] → \[Launcher Settings: Add Game] → [Launcher Deployment] → \[Test]

<a id="excluding-existing-games"></a>
### Excluding Existing Games { #excluding-existing-games }

- If you need to exclude a game from a previously deployed status, a [Launcher] update is required.
- We recommend that you proceed in the following order:
- \[Launcher Settings: Excluding Game] → [Launcher] → [Launcher Installer] → \[Test]

<a id="deployment-zone"></a>
## Deployment Zone { #deployment-zone }

Typically, before launching a service, a separate launcher is needed for development and testing. To address this, GameStarter added the concept of a deployment zone, allowing the use of a standalone launcher.

The following zones are provided by default:

1. **SERVICE**: Deployment zone for real service
2. **DEVELOP**: Deployment zone for development and alpha test
3. **TEST**: Deployment zone for QA or beta test