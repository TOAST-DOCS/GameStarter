## Game > GameStarter > 콘솔 사용 가이드 > 지표

## Statistics

제공하는 지표 항목에 대해 설명 합니다.
제공되는 지표 항목에는 실시간 모니터링 항목과 모니터링 지표 항목이 있습니다.

![statistics_main](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_main_250717.png)

### 1. 실시간 모니터링

실시간 모니터링 은 당일 자정 부터 조회 시점 시간까지의 지표 데이터를 실시간 조회 기능을 제공합니다.
00:00 부터 조회 시점까지의 데이터를 조회하며, 조건 버튼을 통해 필터링된 데이터의 조회가 가능합니다.

#### 1-1. 실시간 모니터링 > 게임

게임 항목에서는 게임 실행과 게임 설치 지표를 제공합니다.
각각 게임 실행과 설치 지표를 데쉬보드와 차트 데이터를 통해 쉽게 지표 데이터를 얻을 수 있습니다.

##### >- 게임 실행

게임 실행과 관련된 지표 정보를 표시합니다.

![statistics_real_game](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_execute_game_none_250717.png)
대시 보드에서 게임 실행 수, 게임 실행 성공 수, 게임 실행 실패 수를 제공하며, 전일대비 증감치를 확인 할 수 있습니다.
차트 데이터를 통해 시간대별 증감 수치와, 게임 실행 실패 이유 정보를 확인 할 수 있습니다.


지표 데이터를 효율적으로 활용 할 수 있도록, 엑셀 저장 버튼을 통해 지표 데이터를 저장 할 수 있습니다.
저장되는 데이터는 저장시점 요청 시점의 데이터를 기준으로 제공됩니다.

게임 실행과 관련된 엑셀 데이터 저장 항목은 아래와 같습니다.
게임 실행 지표 데이터는 Execute(Game) 텝과 Execute (OS) 탭으로 데이터가 제공됩니다.

![realtime_execute_game_excel](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_execute_game_excel_01_250717.png)
Execute(Game) 텝에서는 시간대별로 게임 별 게임 실행 수, 게임 성공 수, 게임 실패 수 집계 데이터를 제공합니다.

![realtime_execute_game_os_excel](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_execute_game_excel_02_250717.png)
Execute(OS) 텝에서는 시간대 별로 OS 별 게임 실행 수, 게임 성공 수, 게임 실패 수 집계 데이터를 제공합니다.


##### >- 게임 설치

게임 설치와 관련된 지표 정보를 표시합니다.

![realtime_install_game1](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_execute_game_none_250717.png)<br>
![realtime_install_game2](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_install_game2_none_250717.png)

대시보드 에서 게임 설치수, 게임 설치 성공 수, 게임 설치 실패 수, 게임 다운로드 평균 속도, 파일 다운로드 용량, 파일 다운로드 수 에 대한 정보를 확인 할 수 있습니다.
대시보드의 FULL, UPDATE 의 설명은 아래와 같습니다.
>- FULL : 전체 설치
>- UPDATE : 업데이트 설치

차트 데이터를 통해 시간대별 게임 설치수, 게임 설치 실패 이유, 시간대별 게임 전체 업데이트 설치 수, 시간대 별 게임 전체 업데이트 설치 평균시간
시간대별 다운도르 속도 및 용량, 시간대별 게임 다운로드 파일 수 의 정보를 확인 할 수 있습니다.




// TODO : 엑셀 지표 데이터 설명


지표 데이터는 필터데이터를 적용하여 조회 가능합니다.
##### 게임 필터 정보

![realtime_game_filter](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/statistics/gamestarter_statistics_filter_250717.png)
1) 조회 대상<br>
조회 대상은 User ID 기준 과 전체 실행 기준 항목이 있습니다.
> 조회 대상 종류 
>
> - `UserID`: 사용자가 여러번 동일한 동작을 진행하여 발생되는 중복된 데이터를 포함하지 않습니다.
> - `전체 실행`: 사용자의 모든 동작을 기준으로 조회하여, 동일한 동작을 하는 중복된 데이터를 포함한 데이터를 조회합니다.

2) OS<br>
사용자가 사용한 OS 정보

3) 게임 이름<br>
게임 이름 (게임 버전)

//TODO: 이미지 설명 추가.

 






#### 1-2. 실시간 모니터링 > 런처

런처 항목에서는 런처의 실행과 설치 정보를 표시 합니다.

##### 런처 실행

![realtime_execute_launcher]()
대시보드 에서 런처 실행 수, 런처 실행 성공 수, 런처 실행 실패수를 제공하며, 전일대비 증감치를 확인 할 수 있습니다.
차트 데이터를 통해 시간대별 런처 실행수 와 런처 실행 실패이유, OS 점유율, 런처 버전 점유율을 확인 할 수 있습니다.

![realtime_execute_launcher_excel]()
// TODO : 엑셀 지표 데이터 설명


![realtime_install_launcher]()

대시보드 에서 런처 설치 수, 런처 설치 성공 수, 런처 설치 실패 수 를 제공하며, 전일대비 증감치를 확인 할 수 있습니다.
차트 데이터를 통해 시간대별 런처 설치수 와 런처 설치 실패이유를 확인 할 수 있습니다.

![realtime_install_launcher_excel]()
// TODO : 엑셀 지표 데이터 설명



### 2. 모니터링 지표

![monitoring_filter]()
모니터링 지표는 일간, 주간, 월간 별로 정산된 지표를 제공 합니다.
설정한 기간의 정산 지표데이터를 조회하며, 조건 버튼을 통해 필터링된 데이터의 조회가 가능합니다.

#### 게임 실행
![monitoring_execute_game]()
조회된 기간의 게임 실행 수 와 게임 실행 실패 이유의 차트데이터를 제공 합니다.


#### 게임 설치
![monitoring_install_game]()
조회된 기간의 게임 설치 수 와 게임 설치 실패 이유의 차트데이터를 제공 합니다.

#### 런처 실행
![monitoring_execute_launcher]()
조회된 기간의 런처 실행 수 와 런처 실행 실패 이유의 차트데이터를 제공 합니다.

#### 게임 이탈
![monitoring_game_bounce]()
조회된 기간의 게임의 설치나 업데이트 중 사용자가 직접 취소하고 게임에서 이탈한 수의 데이터를 제공 합니다. 

#### 모니터링 지표
![monitoring_grid]()
조회된 기간의 전체 모니터링 지표를 표 형식으로 제공합니다.
기간(일자) 별 데이터를 제공하며 아래의 데이터 항목들을 확인 할 수 있습니다.

>- 게임 실행 /실행 성공 /실행 실패
>- 게임 설치/ 설치 성공/ 설치 실패 / 설치 이탈
>- 게임 업데이트 설치/ 설치 성공/ 설치 실패 /설치 이탈
>- 런처 실행 / 실행 성공/ 실행 실패

#### 엑셀 저장
모니터링 지표 데이터를 엑셀로 저장 할 수 있습니다.

![monitoring_excel]()
// TODO : 엑셀 지표 데이터 설명
