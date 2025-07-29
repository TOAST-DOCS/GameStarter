## Game > GameStarter > 콘솔 사용 가이드 > 지표

GameStarter 에서는 게임의 효율적인 지표 파악을 위해 관련 데이터를 제공하고 있습니다.
게임의 설치, 실행, 런처 설치 및 실행 데이터를 제공하며, 게임 이탈률 등 게임 실행과 진입에 관한 주요 지표를 쉽게 확인할 수 있습니다.

## 지표

지표 데이터를 조회 하기 위한 메뉴 구성은 아래와 같습니다.

![statistics_title1](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_title_1_250717.png)

1. `실시간 모니터링`은 당일 자정부터 조회 시점까지의 지표 데이터를 제공합니다.
2. `모니터링 지표`는 설정한 기간(일간, 주간, 월간)의 집계 데이터를 제공합니다.
3. 데이터의 `조회 기준 시간`을 확인 할 수 있습니다.
4. `새로고침` 버튼을 통해서 데이터를 요청시점 데이터로 갱신 할 수 있습니다.
   실시간 지표는 서버 부하를 방지하기 위해 자동으로 갱신되지 않습니다. `데이터를 갱신`하려면 `새로고침` 버튼을 사용할 수 있습니다.
5. 제공되는 지표 데이터는 `조건` 버튼을 통하여 데이터의 필터를 적용 하여 조회 할 수 있습니다. 제공되는 필터 는 각 항목의 `필터 정보` 내용을 확인 해 주세요.
   `조회` 버튼을 통하여 데이터를 조회 할 수 있습니다.
6. 지표 데이터는 엑셀 파일로 저장 할 수 있습니다. 제공되는 엑셀데이터 설명은 각 항목의 `엑셀저장` 내용을 확인 해 주세요.


### 실시간 모니터링

실시간 모니터링 은 당일 자정 부터 조회 시점 시간까지의 지표 데이터의 조회 기능을 제공합니다.
00:00 부터 조회 시점까지의 데이터를 조회하며, 조건 버튼을 통해 필터링된 데이터의 조회가 가능합니다.

![statistics_main](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_main_250717.png)


#### 1. 실시간 모니터링 > 게임

게임 항목에서는 게임 실행과 게임 설치 지표를 제공합니다.
각각 게임 실행과 설치 지표를 데쉬보드와 차트 데이터를 통해 쉽게 지표 데이터를 얻을 수 있습니다.

##### 1-1) 게임 필터 정보

지표 데이터는 필터데이터를 적용하여 조회와 엑셀 파일로 저장 할 수 있습니다.

![realtime_game_filter](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_filter_250717.png)

> 1) 조회 대상
> 조회 대상은 User ID 기준 과 전체 실행 기준 항목이 있습니다.
> 조회 대상 종류
>
>> - `UserID`: 사용자가 여러번 동일한 동작을 진행하여 발생되는 중복된 데이터를 포함하지 않습니다.
>> - `전체 실행`: 사용자의 모든 동작을 기준으로 조회하여, 동일한 동작을 하는 중복된 데이터를 포함한 데이터를 조회합니다.
>
> 2) OS
> 사용자가 사용한 OS 정보 리스트를 필터링 하여 조회 할 수 있습니다.
>
> 3) 게임 이름
> 게임 이름 (게임 버전) 정보 리스트를 필터링 하여 조회 할 수 있습니다.
> 
> `원하는 필터 데이터를 선택한 후, 적용 버튼을 눌러 조회 결과를 필터링할 수 있습니다.`


##### 1-2) 게임 실행

게임 실행과 관련된 지표 정보를 표시합니다.

![statistics_real_game](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_execute_game_none_250717.png)
대시 보드에서 `게임 실행 수`, `게임 실행 성공 수`, `게임 실행 실패 수`를 제공하며, `전일대비 증감치`를 확인 할 수 있습니다.
차트 데이터를 통해 `시간대별 증감 수치`와, `게임 실행 실패 이유 정보`를 확인 할 수 있습니다.


지표 데이터를 효율적으로 활용 할 수 있도록, 엑셀 저장 버튼을 통해 지표 데이터를 저장 할 수 있습니다.
`저장되는 데이터는 저장요청 시점의 데이터를 기준`으로 제공됩니다.

##### 1-3) 게임 실행 엑셀 저장
게임 실행과 관련된 엑셀 데이터 저장 항목은 아래와 같습니다.
파일명은 `RealTime_GameExecution_날자_시간.xlsx` 형식으로 제공 됩니다.

게임 실행 지표 데이터는 시간대별로 Execute (Game) 탭과 Execute (OS) 탭에서 확인할 수 있습니다.

1) Execute(Game) 탭에서는 시간대별 게임 별 게임 실행 수, 게임 성공 수, 게임 실패 수 집계 데이터를 제공합니다.
2) Execute(OS) 탭에서는 시간대 별 OS 별 게임 실행 수, 게임 성공 수, 게임 실패 수 집계 데이터를 제공합니다.

##### 1-4) 게임 설치

게임 설치와 관련된 지표 정보를 표시합니다.

![realtime_install_game1](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_install_game_none_250717.png)

대시보드 에서 `게임 설치수`, `게임 설치 성공 수`, `게임 설치 실패 수`, `게임 다운로드 평균 속도`, `파일 다운로드 용량`, `파일 다운로드 수` 에 대한 정보를 확인 할 수 있습니다.
대시보드의 FULL, UPDATE 의 설명은 아래와 같습니다.
>- `FULL` : 전체 설치
>- `UPDATE` : 업데이트 설치


![realtime_install_game2](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_install_game2_none_250717.png)

차트 데이터를 통해 시간대별 `게임 설치수`, `게임 설치 실패 이유`, `시간대별 게임 전체 업데이트 설치 수`, `시간대 별 게임 전체 업데이트 설치 평균시간`,
`시간대별 다운도르 속도 및 용량`, `시간대별 게임 다운로드 파일 수` 의 정보를 확인 할 수 있습니다.

##### 1-5) 게임 설치 엑셀 저장
게임 설치와 관련된 엑셀 데이터 저장 항목은 아래와 같습니다.
파일명은 `RealTime_GameDownload_날자_시간.xlsx` 형식으로 제공 됩니다.

게임 실행 지표 데이터는 Download, Download (Game), Download (OS), Update, Update (Game), Update (OS) 탭으로 데이터가 제공됩니다.
1) Download 탭에서는 시간대별 전체 설치 항목들의 정보를 보여주며 조회 가능한 항목은 아래와 같습니다.
    1-1) `Download` : 전체 설치 수
    1-2) `Download Success` : 전체 설치 성공 수
    1-3) `Download Fail` :  전체 설치 실패 수
    1-4) `Download Average Time (sec)` : 다운로드 평균 시간 (sec)
    1-5) `Download File Size (MB)` : 다운로드 파일 사이즈 (MB)
    1-6) `Download Files` :  다운로드 파일 카운트

2) Download (Game)  탭에서는 시간대에 따른 게임별 지표 정보를 제공 합니다.
각 Game 명 하위에 아래와 항목 지표를 확인 할 수 있습니다.
    2-1) `Total` : 전체 설치 수
    2-2) `Success` : 전체 설치 성공 수
    2-3) `Failure` : 전체 설치 실패 수

3) Download (OS) 탭에서는 시간대에 따른 OS 별 지표 정보를 제공 합니다.
각 OS 별 하위에 아래와 항목 지표를 확인 할 수 있습니다.
    3-1) `Total` : 전체 설치 수
    3-2) `Success` : 전체 설치 성공 수
    3-3) `Failure` : 전체 설치 실패 수

4) Update 탭에서는 시간대에 따른 업데이트 설치의 지표 정보를 제공 합니다.
    4-1) `Update` : 업데이트 설치 수
    4-2) `Update Success` : 업데이트 설치 성공 수
    4-3) `Update Fail` : 업데이트 실패 수
    4-4) `Update Average Time (sec)` : 업데이트 평균 시간 (sec)
    4-5) `Update File Size (MB)` :  업데이트 파일 사이즈 (MB)
    4-6) `Update Files` : 업데이트 파일 수

5) Update (Game) 탭에서는 시간대에 따른 업데이트 설치의 게임별 지표 정보를 제공 합니다.
각 Game 명 하위에 아래와 항목 지표를 확인 할 수 있습니다.
    5-1) `Total` : 전체 설치 수
    5-2) `Success` : 전체 설치 성공 수
    5-3) `Failure` : 전체 설치 실패 수

6) Update (OS) 탭에서는 시간대에 따른 업데이트 설치의 OS별 지표 정보를 제공 합니다.
각 OS 별 하위에 아래와 항목 지표를 확인 할 수 있습니다.
    6-1) `Total` : 전체 설치 수
    6-2) `Success` : 전체 설치 성공 수
    6-3) `Failure` : 전체 설치 실패 수


#### 2. 실시간 모니터링 > 런처

런처 항목에서는 런처의 실행과 설치 정보를 표시 합니다.

##### 2-1) 런처 필터 정보

![realtime_execute_launcher_filter](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_filter_launcher_250717.png)

> 1) 조회 대상
> 조회 대상은 User ID 기준 과 전체 실행 기준 항목이 있습니다.
> 조회 대상 종류
>
>> - `UserID`: 사용자가 여러번 동일한 동작을 진행하여 발생되는 중복된 데이터를 포함하지 않습니다.
>> - `전체 실행`: 사용자의 모든 동작을 기준으로 조회하여, 동일한 동작을 하는 중복된 데이터를 포함한 데이터를 조회합니다.
>
> 2) OS
> 사용자가 사용한 OS 정보 리스트를 필터링 하여 조회 할 수 있습니다.
>
> 3) 런처 버전
> 런처 버전 정보 리스트를 필터링 하여 조회 할 수 있습니다.
> 
> `원하는 필터 데이터를 선택한 후, 적용 버튼을 눌러 조회 결과를 필터링할 수 있습니다.`


##### 2-2) 런처 실행

![realtime_execute_launcher](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_execute_launcher_none_250717.png)

대시보드에서 런처 실행 수, 성공 수, 실패 수를 제공하며, 전일 대비 증감치를 통해 실행 트렌드를 확인 할 수 있습니다.
차트 데이터를 통해 시간대별 런처 실행수 와 런처 실행 실패이유, OS 점유율, 런처 버전 점유율을 확인 할 수 있습니다.

##### 2-3) 런처 엑셀 저장
런처 실행과 관련된 엑셀 데이터 저장 항목은 아래와 같습니다.
파일명은 `Realtime_Launcher_날자_시간.xlsx` 형식으로 제공 됩니다.

런처 실행 지표 데이터는 Dashboard, Execution (OS), Execution (Launcher Version)  탭으로 데이터가 제공됩니다.
1) Dashboard 탭에서는 시간대별 런처 실행 지표 정보를 제공 합니다.
    1-1) `Launcher Execution` : 런처 실행 수
    1-2) `Launcher Execution Success` : 런처 실행 성공 수
    1-3) `Launcher Execution Fail` : 런처 실행 실패 수

2) Execution (OS)  탭에서는 시간대에 따른 OS별 지표 정보를 제공 합니다.
각 OS 명 하위에 아래와 항목 지표를 확인 할 수 있습니다.
    2-1) `Total` : 전체 설치 수
    2-2) `Success` : 전체 설치 성공 수
    2-3) `Failure` : 전체 설치 실패 수

3) Execution (Launcher Version)  탭에서는 시간대에 따른 런처 버전별 지표 정보를 제공 합니다.
각 런처 버전별 하위에 아래와 항목 지표를 확인 할 수 있습니다.
    3-1) `Total` : 전체 설치 수
    3-2) `Success` : 전체 설치 성공 수
    3-3) `Failure` : 전체 설치 실패 수


##### 2-4) 런처 설치
![realtime_install_launcher](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_install_launcher_none_250717.png)

대시보드 에서 `런처 설치 수`, `런처 설치 성공 수`, `런처 설치 실패 수` 를 제공하며, `전일대비 증감치`를 확인 할 수 있습니다.
차트 데이터를 통해 `시간대별 런처 설치수` 와 `런처 설치 실패이유`를 확인 할 수 있습니다.


##### 2-5) 런처 설치 엑셀 저장
런처 설치와 관련된 엑셀 데이터 저장 항목은 아래와 같습니다.
파일명은 `Realtime_LauncherInstall_날자_시간.xlsx` 형식으로 제공 됩니다.

런처 설치 지표 데이터는 Dashboard, Install (OS), Install (Launcher Version)  탭으로 데이터가 제공됩니다.
1) Dashboard 탭에서는 시간대별 런처 실행 지표 정보를 제공 합니다.
    1-1) `Launcher Install` : 런처 설치 수
    1-2) `Launcher Install Success` : 런처 설치 성공 수
    1-3) `Launcher Install Fail` : 런처 설치 실패 수

2) Install (OS)  탭에서는 시간대에 따른 OS별 지표 정보를 제공 합니다.
각 OS 명 하위에 아래와 항목 지표를 확인 할 수 있습니다.
    2-1) `Total` : 전체 설치 수
    2-2) `Success` : 전체 설치 성공 수
    2-3) `Failure` : 전체 설치 실패 수

3) Install (Launcher Version)  탭에서는 시간대에 따른 런처 버전별 지표 정보를 제공 합니다.
각 런처 버전별 하위에 아래와 항목 지표를 확인 할 수 있습니다.
    3-1) `Total` : 전체 설치 수
    3-2) `Success` : 전체 설치 성공 수
    3-3) `Failure` : 전체 설치 실패 수x


### 모니터링 지표


모니터링 지표는 일간, 주간, 월간 별로 정산된 지표를 제공 합니다.
설정한 기간의 정산 지표데이터를 조회하며, 조건 버튼을 통해 필터링된 데이터의 조회가 가능합니다.

#### 1. 모니터링 지표 필터 정보

![monitoring_filter](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_filter_none_250717.png)

> 1) 조회 대상
> 조회 대상은 User ID 기준 과 전체 실행 기준 항목이 있습니다.
> 조회 대상 종류
>
>> - `UserID`: 사용자가 여러번 동일한 동작을 진행하여 발생되는 중복된 데이터를 포함하지 않습니다.
>> - `전체 실행`: 사용자의 모든 동작을 기준으로 조회하여, 동일한 동작을 하는 중복된 데이터를 포함한 데이터를 조회합니다.
>
> 2) OS
> 사용자가 사용한 OS 정보 리스트를 필터링 하여 조회 할 수 있습니다.
>
> 3) 런처 버전
> 런처 버전 정보 리스트를 필터링 하여 조회 할 수 있습니다.
> 
> 4) 게임 이름
> 게임 이름 (게임 버전) 정보 리스트를 필터링 하여 조회 할 수 있습니다.
> `원하는 필터 데이터를 선택한 후, 적용 버튼을 눌러 조회 결과를 필터링할 수 있습니다.`


#### 2. 게임 실행
![monitoring_execute_game](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_execute_game_none_250717.png)
조회된 기간의 게임 실행 수 와 게임 실행 실패 이유의 차트데이터를 제공 합니다.

#### 3. 게임 설치
![monitoring_install_game](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_install_game_none_250717.png)
조회된 기간의 게임 설치 수 와 게임 설치 실패 이유의 차트데이터를 제공 합니다.

#### 4. 런처 실행
![monitoring_execute_launcher](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_execute_launcher_none_250717.png)
조회된 기간의 런처 실행 수와 런처 실행 실패 이유의 차트 데이터를 제공합니다.

#### 5. 모니터링 지표
![monitoring_grid1](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_monitoring_grid_1_none_250717.png)
조회된 기간의 전체 모니터링 지표를 표 형식으로 제공합니다.
기간(일자) 별 데이터를 제공하며 아래의 데이터 항목들을 확인 할 수 있습니다.

>- 게임 실행 /실행 성공 /실행 실패
>- 게임 설치/ 설치 성공/ 설치 실패 / 설치 이탈
>- 게임 업데이트 설치/ 설치 성공/ 설치 실패 /설치 이탈
>- 런처 실행 / 실행 성공/ 실행 실패

#### 6. 모니터링 엑셀 저장
모니터링 지표 데이터를 엑셀로 저장 할 수 있습니다.

모니터링 지표의 엑셀 데이터 저장 항목은 아래와 같습니다.
파일명은 `Monitoring_날자_시간.xlsx` 형식으로 제공 됩니다.

런처 설치 지표 데이터는 GameExecution (Game), GameExecution (OS), GameDownload (Game), GameDownload (OS), GameUpdate (Game), GameUpdate (OS), LauncherExecution (OS), LauncherExecution (Version), Bounce 탭으로 데이터가 제공됩니다.
1) GameExecution 관련 탭에서는 조회 기간의 게임 실행 정보를 제공 합니다.
    1-1) `GameExecution (Game)` : 게임별 게임 실행 지표 (총 숫자, 성공수, 실패수)
    1-2) `GameExecution (OS)` : OS별 게임 실행 지표 (총 숫자, 성공수, 실패수)

2) GameDownload 관련 탭에서는 조회 기간의 게임 다운로드 정보를 제공 합니다.
    2-1) `GameDownload (Game)` : 게임별 게임 다운로드 지표 (총 숫자, 성공수, 실패수)
    2-2) `GameDownload (OS)` : OS별 게임 다운로드 지표 (총 숫자, 성공수, 실패수)

3) GameUpdate 관련탭에서는 조회 기간의 게임 업데이트 정보를 제공 합니다.
    3-1) `GameUpdate (Game)` : 게임별 게임 업데이트 지표 (총 숫자, 성공수, 실패수)
    3-2) `GameUpdate (OS)` : OS별 게임 업데이트 지표 (총 숫자, 성공수, 실패수)

4) LauncherExecution 관련탭에서는 조회 기간의 런처 실행 정보를 제공 합니다.
    4-1) `LauncherExecution (Game)` : 게임별 런처 실행 지표 (총 숫자, 성공수, 실패수)
    4-2) `LauncherExecution (OS)` : OS별 런처 실행 지표 (총 숫자, 성공수, 실패수)

5) Bounce 탭에서는 조회 기간의 게임별 이탈률 지표 정보를 제공 합니다.
   각 게임별로 설치 및 업데이트 과정에서 발생한 이탈률을 확인할 수 있습니다.
   Bounce 텝에서 제공되는 데이터는 설치 중단 및 업데이트 중 이탈한 수를 나타냅니다.
   데이터를 확인한 후, 런처 실행 실패 데이터를 통해 문제를 더 상세히 분석할 수 있습니다.
    5-1) `Game Install` : 게임 설치가 시도된 수
    5-2) `Game Install Bounce` : 게임 설치 중 이탈한 수
    5-3) `Game Update` : 게임 업데이트 시도한 수
    5-4) `Game Update Bounce` : 게임 업데이트 중 이탈한 수
    5-5) `Game Execution` : 게임 업데이트나 설치를 시도한 유저중 실행까지 시도한 수