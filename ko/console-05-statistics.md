## Game > GameStarter > 콘솔 사용 가이드 > 지표

GameStarter는 게임의 효율적인 지표 파악을 위해 관련 데이터를 제공합니다.
게임의 설치, 실행, 런처 설치 및 실행 데이터를 제공하며, 게임 이탈률 등 게임 실행과 진입에 관한 주요 지표를 쉽게 확인할 수 있습니다.

## 지표

지표 데이터를 조회하기 위한 메뉴 구성은 아래와 같습니다.

![statistics_title1](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_title_1_250717.png)

➊ **실시간 모니터링**: 당일 자정부터 조회 시점까지의 지표 데이터를 제공합니다.
➋ **모니터링 지표**: 설정한 기간(일간, 주간, 월간)의 집계 데이터를 제공합니다.
➌ 데이터의 조회 기준 시간을 확인할 수 있습니다.
➍ **새로고침**: 데이터를 요청 시점 데이터로 갱신할 수 있습니다.
실시간 지표는 서버 부하를 방지하기 위해 자동으로 갱신되지 않습니다. 데이터를 갱신하려면 **새로고침**을 클릭하세요.
➎ **조건**: 필터를 적용하여 데이터를 조회할 수 있습니다. 제공되는 필터는 각 항목의 필터 정보의 내용을 확인하세요.
**조회**를 클릭해 데이터를 조회할 수 있습니다.
➏ **Excel 저장**: 지표 데이터를 엑셀 파일로 저장할 수 있습니다. 제공되는 엑셀 데이터에 대한 설명은 각 항목의 **엑셀 저장**의 내용을 확인하세요.


### 실시간 모니터링

실시간 모니터링은 당일 자정부터 조회 시점까지의 지표 데이터를 조회할 수 있는 기능입니다.
자정(00:00)부터 조회 시점까지의 데이터를 조회하며, **조건**을 클릭해 데이터를 필터링하여 조회할 수도 있습니다.

![statistics_main](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_main_250717.png)


#### 실시간 모니터링 - 게임

게임 실행 및 설치에 대한 지표 데이터를 대시보드와 차트 데이터로 확인할 수 있습니다.
각각 게임 실행과 설치 지표를 데쉬보드와 차트 데이터를 통해 쉽게 지표 데이터를 얻을 수 있습니다.

##### 게임 필터 정보

지표 데이터는 필터를 적용하여 조회하고 엑셀 파일로 저장할 수 있습니다.

![realtime_game_filter](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_filter_250717.png)

> ➊ 조회 대상
>  조회 대상은 User ID 기준과 전체 실행 기준 항목이 있습니다.
>  조회 대상 종류
> - **User ID 기준**: 사용자가 여러 번 동일한 동작을 진행하여 발생되는 중복된 데이터를 포함하지 않습니다.
> - **전체 실행 기준**: 사용자의 모든 동작을 기준으로 조회하여, 동일한 동작을 하는 중복된 데이터를 포함한 데이터를 조회합니다.
>
> ➋ OS
>  사용자가 사용한 OS 정보 리스트를 필터링해 조회할 수 있습니다.
>
> ➌ 게임 이름
>  게임 이름(게임 버전) 정보 리스트를 필터링해 조회할 수 있습니다.
>
> 원하는 필터 데이터를 선택한 뒤 **적용**을 클릭해 조회 결과를 필터링할 수 있습니다.


##### 게임 실행

게임 실행과 관련된 지표 정보를 표시합니다.

![statistics_real_game](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_execute_game_none_250717.png)
대시보드에서 **게임 실행 수**, **게임 실행 성공 수**, **게임 실행 실패 수**를 제공하며, 전일 대비 증감치를 확인할 수 있습니다.
또한 차트를 통해 **시간대별 증감 수치**와 **게임 실행 실패 이유** 정보를 확인할 수 있습니다.


지표 데이터를 보다 효율적으로 활용할 수 있도록 **엑셀 저장**을 클릭해 지표 데이터를 저장할 수도 있습니다.
엑셀 저장 데이터는 저장 요청 시점의 데이터를 기준으로 제공됩니다.

##### 게임 실행 엑셀 저장
게임 실행과 관련된 엑셀 데이터 저장 항목은 아래와 같습니다.
파일명은 `RealTime_GameExecution_날자_시간.xlsx` 형식으로 제공됩니다.

게임 실행 지표 데이터는 시간대별로 Execute (Game) 탭과 Execute (OS) 탭에서 확인할 수 있습니다.

1. Execute(Game) 탭에서는 시간대에 따른 게임별 게임 실행 수, 게임 성공 수, 게임 실패 수 집계 데이터를 제공합니다.
2. Execute(OS) 탭에서는 시간대에 따른 OS별 게임 실행 수, 게임 성공 수, 게임 실패 수 집계 데이터를 제공합니다.

##### 게임 설치

게임 설치와 관련된 지표 정보를 표시합니다.

![realtime_install_game1](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_install_game_none_250717.png)

대시보드에서 **게임 설치 수**, **게임 설치 성공 수**, **게임 설치 실패 수**, **게임 다운로드 평균 속도**, **파일 다운로드 용량**, **파일 다운로드 수**에 대한 정보를 확인할 수 있습니다.
대시보드의 FULL과 UPDATE의 의미는 각각 다음과 같습니다.
- **FULL**: 전체 설치
- **UPDATE**: 업데이트 설치


![realtime_install_game2](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_install_game2_none_250717.png)

차트 데이터에서 시간대별 **게임 설치 수**, **게임 설치 실패 이유**, **시간대별 게임 전체 업데이트 설치 수**, **시간대별 게임 전체 업데이트 설치 평균 시간**, **시간대별 다운로드 속도 및 용량**, **시간대별 게임 다운로드 파일 수**의 정보를 확인할 수 있습니다.

##### 게임 설치 엑셀 저장
게임 설치와 관련된 엑셀 데이터 저장 항목은 아래와 같습니다.
파일명은 `RealTime_GameDownload_날자_시간.xlsx` 형식으로 제공됩니다.

게임 실행 지표 데이터는 Download, Download (Game), Download (OS), Update, Update (Game), Update (OS) 탭으로 데이터가 제공됩니다.

**Download** 탭에서는 시간대별 전체 설치 항목들의 정보를 보여주며, 조회 가능한 항목은 다음과 같습니다.
   - **Download**: 전체 설치 수
   - **Download Success** : 전체 설치 성공 수
   - **Download Fail** :  전체 설치 실패 수
   - **Download Average Time (sec)** : 다운로드 평균 시간 (sec)
   - **Download File Size (MB)** : 다운로드 파일 사이즈 (MB)
   - **Download Files** :  다운로드 파일 카운트

**Download (Game)** 탭에서는 시간대에 따른 게임별 지표 정보를 제공 합니다.
   각 Game 명 하위에 아래와 항목 지표를 확인 할 수 있습니다.
   - **Total** : 전체 설치 수
   - **Success** : 전체 설치 성공 수
   - **Failure** : 전체 설치 실패 수

**Download (OS)** 탭에서는 시간대에 따른 OS 별 지표 정보를 제공 합니다.
   각 OS별 하위에 아래와 같은 항목 지표를 확인할 수 있습니다.
   - **Total** : 전체 설치 수
   - **Success** : 전체 설치 성공 수
   - **Failure** : 전체 설치 실패 수

**Update** 탭에서는 시간대에 따른 업데이트 설치의 지표 정보를 제공 합니다.
   - **Update** : 업데이트 설치 수
   - **Update Success** : 업데이트 설치 성공 수
   - **Update Fail** : 업데이트 실패 수
   - **Update Average Time (sec)** : 업데이트 평균 시간 (sec)
   - **Update File Size (MB)**:  업데이트 파일 사이즈 (MB)
   - **Update Files**: 업데이트 파일 수

**Update (Game)** 탭에서는 시간대에 따른 업데이트 설치의 게임별 지표 정보를 제공합니다.
   각 OS별 하위에 아래의 항목 지표를 확인할 수 있습니다.
   - **Total**: 전체 설치 수
   - **Success**: 전체 설치 성공 수
   - **Failure**: 전체 설치 실패 수

**Update (OS)** 탭에서는 시간대에 따른 업데이트 설치의 OS별 지표 정보를 제공합니다.
   각 OS 별 하위에 아래와 항목 지표를 확인할 수 있습니다.
   - **Total**: 전체 설치 수
   - **Success**: 전체 설치 성공 수
   - **Failure**: 전체 설치 실패 수


#### 실시간 모니터링 - 런처

런처 항목에서는 런처의 실행과 설치 정보를 표시합니다.

##### 2-1) 런처 필터정보

![realtime_execute_launcher_filter](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_filter_launcher_250717.png)

> ➊ 조회 대상
>  조회 대상은 **User ID 기준**과 **전체 실행 기준** 항목이 있습니다.
>  조회 대상 종류
>    - **UserID 기준**: 사용자가 여러 번 동일한 동작을 진행하여 발생되는 중복된 데이터를 포함하지 않습니다.
>    - **전체 실행 기준**: 사용자의 모든 동작을 기준으로 조회하여, 동일한 동작을 하는 중복된 데이터를 포함한 데이터를 조회합니다.
>
> ➋ OS
> 사용자가 사용한 OS 정보 리스트를 필터링해 조회할 수 있습니다.
>
> ➌ 런처 버전
> 런처 버전 정보 리스트를 필터링해 조회할 수 있습니다.
>
> 원하는 필터를 선택한 뒤 적용을 클릭해 조회 결과를 필터링할 수 있습니다.


##### 런처 실행

![realtime_execute_launcher](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_execute_launcher_none_250717.png)

대시보드에서 런처 실행 수, 성공 수, 실패 수를 제공하며, 전일 대비 증감치를 통해 실행 트렌드를 확인할 수 있습니다.
차트에서 시간대별 런처 실행 수, 런처 실행 실패 이유, OS 점유율, 런처 버전 점유율을 확인할 수 있습니다.

##### 런처 실행 엑셀 저장

런처 실행과 관련된 엑셀 데이터 저장 항목은 아래와 같습니다.
파일명은 `Realtime_Launcher_날자_시간.xlsx` 형식으로 제공됩니다.

런처 실행 지표는 **Dashboard**, **Execution (OS)**, **Execution (Launcher Version)** 탭으로 데이터가 제공됩니다.

**Dashboard** 탭에서는 시간대별 런처 실행 지표 정보를 제공합니다.
   - **Launcher Execution**: 런처 실행 수
   - **Launcher Execution Success**: 런처 실행 성공 수
   - **Launcher Execution Fail**: 런처 실행 실패 수

**Execution (OS)** 탭에서는 시간대에 따른 OS별 지표 정보를 제공합니다.
   각 OS 명 하위에 아래와 항목 지표를 확인 할 수 있습니다.
   - **Total**: 전체 설치 수
   - **Success** : 전체 설치 성공 수
   - **Failure**: 전체 설치 실패 수

**Execution (Launcher Version)** 탭에서는 시간대에 따른 런처 버전별 지표 정보를 제공합니다.
각 런처 버전별 하위에 아래의 항목 지표를 확인할 수 있습니다.
   - **Total**: 전체 설치 수
   - **Success** : 전체 설치 성공 수
   - **Failure**: 전체 설치 실패 수


##### 런처 설치
![realtime_install_launcher](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_install_launcher_none_250717.png)

대시보드에서 **런처 설치 수**, **런처 설치 성공 수**, **런처 설치 실패 수**를 제공하며, 전일 대비 증감치를 확인할 수 있습니다.
차트에서 시간대별 런처 설치 수와 **런처 설치 실패 이유**를 확인할 수 있습니다


##### 런처 설치 엑셀 저장
런처 설치와 관련된 엑셀 데이터 저장 항목은 아래와 같습니다.
파일명은 `Realtime_LauncherInstall_날자_시간.xlsx` 형식으로 제공됩니다.

런처 설치 지표는 **Dashboard**, **Install (OS)**, **Install (Launcher Version)** 탭으로 데이터가 제공됩니다.
**Dashboard** 탭에서는 시간대별 런처 실행 지표 정보를 제공합니다.
   - **Launcher Install**: 런처 설치 수
   - **Launcher Install Success** : 런처 설치 성공 수
   - **Launcher Install Fail** : 런처 설치 실패 수

**Install (OS)** 탭에서는 시간대에 따른 OS별 지표 정보를 제공합니다.
   각 OS 이름 하위에 아래의 항목 지표를 확인할 수 있습니다.
   - **Total**: 전체 설치 수
   - **Success** : 전체 설치 성공 수
   - **Failure**: 전체 설치 실패 수

**Install (Launcher Version)** 탭에서는 시간대에 따른 런처 버전별 지표 정보를 제공합니다.
   각 런처 버전별 하위에 아래의 항목 지표를 확인할 수 있습니다.
   - **Total**: 전체 설치 수
   - **Success** : 전체 설치 성공 수
   - **Failure**: 전체 설치 실패 수


### 모니터링 지표


모니터링 지표는 일간, 주간, 월간으로 정산된 지표를 제공합니다.
설정한 기간의 정산 지표 데이터를 조회하며, **조건**을 클릭해 필터링된 데이터를 조회할 수 있습니다.

#### 모니터링 지표 필터 정보

![monitoring_filter](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_filter_none_250717.png)

> 1. 조회 대상
>  조회 대상은 **User ID 기준**과 **전체 실행 기준** 항목이 있습니다.
>  조회 대상 종류
>    - **User ID 기준**: 사용자가 여러 번 동일한 동작을 진행하여 발생되는 중복된 데이터를 포함하지 않습니다.
>    - **전체 실행 기준**: 사용자의 모든 동작을 기준으로 조회하여, 동일한 동작을 하는 중복된 데이터를 포함한 데이터를 조회합니다.
>
> 2. OS
>  사용자가 사용한 OS 정보 리스트를 필터링해 조회할 수 있습니다.
>
> 3. 런처 버전
>
>  런처 버전 정보 리스트를 필터링해 조회할 수 있습니다.
>
> 4. 게임 이름
>  게임 이름(게임 버전) 정보 리스트를 필터링해 조회할 수 있습니다.
>  원하는 필터를 선택한 뒤 **적용**을 클릭해 조회 결과를 필터링할 수 있습니다.


#### 게임 실행

![monitoring_execute_game](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_execute_game_none_250717.png)

조회한 기간의 게임 실행 수와 게임 실행 실패 이유의 차트 데이터를 제공합니다.

#### 게임 설치

![monitoring_install_game](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_install_game_none_250717.png)

조회한 기간의 게임 설치 수와 게임 설치 실패 이유의 차트 데이터를 제공합니다.

#### 런처 실행

![monitoring_execute_launcher](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_execute_launcher_none_250717.png)

조회한 기간의 런처 실행 수와 런처 실행 실패 이유의 차트 데이터를 제공합니다.

#### 모니터링 지표

![monitoring_grid1](https://static.toastoven.net/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_grid_1_none_250717.png)

조회한 기간의 전체 모니터링 지표를 표 형식으로 제공합니다.
기간(일자)별 데이터를 제공하며 아래의 데이터 항목들을 확인할 수 있습니다.

>- 게임 실행/실행 성공/실행 실패
>- 게임 설치/설치 성공/설치 실패/설치 이탈
>- 게임 업데이트 설치/설치 성공/설치 실패/설치 이탈
>- 런처 실행/실행 성공/실행 실패


#### 모니터링 엑셀 저장

모니터링 지표 데이터를 엑셀로 저장할 수 있습니다.

모니터링 지표의 엑셀 데이터 저장 항목은 아래와 같습니다.
파일명은 `Monitoring_날자_시간.xlsx` 형식으로 제공됩니다.

런처 설치 지표는 **GameExecution (Game)**, **GameExecution (OS)**, **GameDownload (Game)**, **GameDownload (OS)**,
**GameUpdate (Game)**, **GameUpdate (OS)**, **LauncherExecution (OS)**, **LauncherExecution (Version)**, **Bounce** 탭으로 데이터가 제공됩니다.

**GameExecution** 관련 탭에서는 조회 기간의 게임 실행 정보를 제공합니다.
   - **GameExecution (Game)**: 게임별 게임 실행 지표(총 숫자, 성공 수, 실패 수)
   - **GameExecution (OS)**: OS별 게임 실행 지표(총 숫자, 성공 수, 실패 수)

**GameDownload** 관련 탭에서는 조회 기간의 게임 다운로드 정보를 제공합니다.
   - **GameDownload (Game)**: 게임별 게임 다운로드 지표(총 숫자, 성공 수, 실패 수)
   - **GameDownload (OS)**: OS별 게임 다운로드 지표(총 숫자, 성공 수, 실패 수)

**GameUpdate** 관련 탭에서는 조회 기간의 게임 업데이트 정보를 제공합니다.
   - **GameUpdate (Game)**: 게임별 게임 업데이트 지표(총 숫자, 성공 수, 실패 수)
   - **GameUpdate (OS)**: OS별 게임 업데이트 지표(총 숫자, 성공 수, 실패 수)

**LauncherExecution** 관련 탭에서는 조회 기간의 런처 실행 정보를 제공합니다.
   - **LauncherExecution (Game)**: 게임별 런처 실행 지표(총 숫자, 성공 수, 실패 수)
   - **LauncherExecution (OS)**: OS별 런처 실행 지표(총 숫자, 성공 수, 실패 수)

**Bounce** 탭에서는 조회 기간의 게임별 이탈률 지표 정보를 제공합니다.
   각 게임별로 설치 및 업데이트 과정에서 발생한 이탈률을 확인할 수 있습니다.

   이탈한 수는 게임의 설치 중단 및 업데이트 중 이탈한 수를 나타냅니다.
   데이터를 확인한 후, 런처 실행 실패 데이터를 통해 문제를 더 상세히 분석할 수 있습니다.
   - **Game Install**: 게임 설치가 시도된 수
   - **Game Install Bounce**: 게임 설치 중 이탈한 수
   - **Game Update**: 게임 업데이트 시도한 수
   - **Game Update Bounce**: 게임 업데이트 중 이탈한 수
   - **Game Execution**: 게임 업데이트나 설치를 시도한 유저 중 실행까지 시도한 수
