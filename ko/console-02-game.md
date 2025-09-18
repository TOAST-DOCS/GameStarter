## Game > GameStarter > 콘솔 사용 가이드 > 게임

## Game

게임을 등록하고 게임의 설정과 바이너리를 배포하는 방법에 대해서 설명합니다.

### 게임 목록
![game_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_list_250717.png)

게임 목록에서는 새로운 게임을 등록하거나 등록된 게임들을 조회할 수 있습니다.
또한 게임 이름이나 게임 사용 여부를 통해서 필터링할 수 있습니다.

게임 목록의 조회 결과에는 아래와 같은 필드를 가지고 있습니다.

#### ➊ 게임 이름
등록된 게임의 고유한 이름을 나타냅니다.

#### ➋ 게임 OS
게임을 실행할 수 있는 OS를 나타냅니다.

#### ➌ 등록 일시
게임을 등록한 날짜를 나타냅니다.

#### ➍ 등록자
게임을 등록한 사용자의 마스킹된 이메일 주소를 나타냅니다.

#### ➎ 게임 사용 여부
게임의 사용 여부(사용 또는 사용 안 함)를 나타냅니다.

#### ➏ 상세보기
**상세** 버튼을 클릭해 등록된 게임의 상세한 정보를 확인할 수 있습니다.


### 게임 등록

게임 목록 왼쪽 상단에서 OS에 따라 **+ Windows** 또는 **+ macOS**를 클릭해 새 게임을 등록할 수 있습니다.

![game_register](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_regist_win_250717.png)

#### 게임 이름
게임 이름은 다른 게임과 구분할 수 있도록 중복되지 않는 고유한 명칭을 가져야 합니다.
게임 이름은 한글, 영문 대소문자, 숫자로 2~15자까지 입력할 수 있습니다.

#### OS
게임을 실행할 수 있는 OS 정보를 보여줍니다.

게임 이름을 입력한 뒤 **등록**을 클릭해 게임을 등록할 수 있습니다

### 게임 상세보기

게임 목록에서 **[상세]** 버튼을 눌러서 게임의 상세보기 페이지로 이동하게 됩니다.

![game_detail](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_detail_250717.png)

### 게임 수정

게임 상세 정보 페이지 상단의 **수정**을 클릭해 게임 정보를 수정할 수 있습니다.

![game_modify](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_modify_250717.png)

#### ➊ 게임 사용 여부
사용 중인 게임을 **사용 안 함**으로 변경하거나, 사용하지 않는 게임을 **사용**으로 변경할 수 있습니다.


### 게임 진입

![game_enter](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_enter_250717.png)

게임 등록을 완료하면 게임 목록에 등록한 게임들이 조회됩니다.
상단 이미지의 빨간색으로 표시한 영역을 클릭하면 해당 게임으로 진입할 수 있습니다.

게임에 진입하면 게임을 설정하거나 바이너리를 배포할 수 있습니다

#### 게임 설정 목록

게임에 진입하면 다음과 같이 상단에 게임 이름이 표시되며, 하단에 해당 게임의 메뉴들이 표시됩니다.

![game_config_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_list_250717.png)

게임 설정은 게임을 설치할 때 필요한 여러 설정을 등록할 수 있습니다.

게임 설정 조회 결과 페이지에는 다음과 같은 필드가 있습니다.

**➊ 게임 설정 이름**: 등록된 게임 설정의 이름을 나타냅니다.
**➋ 등록 일시**: 등록된 게임 설정이 마지막으로 등록된 날짜를 나타냅니다.
**➌ 등록자**: 등록된 게임 설정을 마지막 수정한 등록자의 마스킹된 이메일 주소를 나타냅니다.
**➍ 메모**: 등록된 게임의 메모를 나타냅니다.
**➎ 삭제**: 등록된 게임을 삭제합니다.


#### 게임 설정 등록

새로운 게임 설정은 게임 설정 목록 좌측의 **+ 등록**을 클릭해 등록할 수 있습니다.


##### 기본 설정
![game_config_register_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_register_01_250717.png)

##### ➊ 게임 설정 이름
게임 설정의 이름은 다른 게임 설정과 구분하기 위해서 입력합니다.
선택한 게임 안에서 중복된 게임 이름은 사용할 수 없습니다.
게임 설정의 이름은 한글, 영문 대소문자, 숫자로 2~15자까지 입력 가능합니다.


##### ➋ 메모
메모는 게임 설정의 내용을 참고하기 위해서 입력하는 정보입니다.


##### ➌ 관리자 권한 획득
해당 게임을 설치할 때 Windows의 관리자 권한 획득 여부에 대해서 선택합니다.
이 기능을 활성화하면 사용자가 게임을 설치하는 과정에서 UAC(user access control)가 등장할 수도 있습니다.


##### ➍ 기본 설치 경로
게임을 설치할 때 기본으로 설치할 경로를 지정합니다.
기본 경로는 Windows의 경우 `<SystemDrive>/ProgramData/<GameName>`입니다.
다른 경로로 설정하려면 **사용자 지정 경로**를 선택하고 원하는 경로를 입력하세요.


##### ➎ 설정된 기본 설치 경로
기본 설치 경로에 따라서 기본 설치 경로를 예시로 보여줍니다.
Windows는 `<SystemDrive>`를 `C 드라이브`를 예시로 기본 설치 경로를 표시합니다.


모든 설정을 완료하였으면 하단의 **다음**을 클릭해 다음 페이지로 이동합니다.


##### 게임 바로 가기 아이콘


게임을 설치하면서 바탕 화면에 게임 바로가기 아이콘을 생성할 수 있습니다.
드롭다운 메뉴를 클릭해 게임 바로가기 아이콘 생성 방법을 선택할 수 있습니다.
![game_select_shortcut](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_select_shortcut_250717.png)


바로가기 아이콘을 생성할 경우 게임 아이콘 이미지와 이름이 필요합니다.

바로가기 생성 방법의 각 옵션에 대한 설명은 다음과 같습니다.

- **바로가기 자동 생성** : 게임 사용자의 선택 없이 바로가기를 항상 생성합니다.
- **게임 사용자가 생성 여부 선택** : 런처에서 바로가기 생성 여부를 선택할 수 있습니다.
- **바로가기 생성 안함** : 바로가기를 생성하지 않습니다.

![game_config_regist_shortcut](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_regist_shortcut_250717.png)

###### ➊ 바로가기 생성 방법
앞에서 선택한 바로가기 설정 정보를 확인할 수 있으며,
선택한 바로가기 설정 방법을 수정할 수 있습니다.


###### ➋ 바로가기 아이콘 이미지
바탕 화면 설치 시 사용할 게임의 바로가기 아이콘 이미지를 등록합니다.
아이콘 이미지의 권장 크기는 256x256입니다.


###### ➌ 바로가기 아이콘 이름
바탕 화면에 설치할 게임 바로가기 아이콘의 이름을 입력합니다.
게임 바로가기 아이콘의 이름은 2~50자까지 입력 가능합니다.
또한 첫 번째와 마지막 문자에 `공백`, `/`는 입력할 수 없습니다.


모든 설정을 완료하였으면 하단의 **다음**을 클릭해 다음 페이지로 이동합니다.

##### 게임 UI
![game_config_game_ui_basic](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_basic_250717.png)

게임 UI는 런처에서 게임별로 보이는 게임 UI를 구성할 수 있습니다.
게임의 아이콘, 배경 이미지, 하단 부분에 이용 약관이나 고객센터 URL 등을 추가하거나 삭제할 수 있습니다.


###### ➊ 게임 아이콘
![game_config_game_ui_icon](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_icon_250717.png)

게임 아이콘 영역의 편집 아이콘을 클릭해 새로운 게임 아이콘을 등록하거나 삭제할 수 있습니다.
게임 아이콘 이미지의 권장 크기는 256x256입니다.


###### ➋ 배경 이미지
![game_config_game_background](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_background_250717.png)

배경 이미지 영역의 편집 아이콘을 클릭해 새로운 배경 이미지를 등록할 수 있습니다.
배경 이미지의 권장 크기는 992x584입니다.
> [주의]
> 해당 비율에 맞지 않는 이미지인 경우 런처 이미지에 스크롤이 생길 수 있습니다.


###### ➌ Footer
![game_config_game_terms](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_terms_250717.png)

게임 UI의 Footer 영역에 이용약관이나 고객센터를 추가하거나 제거할 수 있습니다.

위의 예시 이미지는 이용약관의 편집 아이콘을 클릭했을 때 표시되는 이용약관 URL 입력 화면입니다.
또한 '이용약관'의 이름을 다른 이름으로 변경할 수도 있습니다.


##### 미리 보기


######  UI 미리 보기
우측의 **UI 미리 보기** 버튼을 통해서 실제 런처에서 보이는 게임 UI를 확인할 수 있습니다.

![game_config_game_preview](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_preview_250717.png)

모든 게임 설정을 완료하였으면 하단의 **등록** 버튼으로 게임 설정을 등록할 수 있습니다.


#### 게임 설정 상세보기

![game_config_register_complete](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_ui_complete_250717.png)

게임 설정 목록에서 상단 이미지의 빨간색으로 표시한 영역을 클릭하면 게임 설정 상세보기 페이지로 이동할 수 있습니다.

![game_config_detail](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_modify_250717.png)

게임 설정 상세보기 페이지는 게임 설정 등록 페이지와 같지만 입력할 수 없다는 차이점이 있습니다.
왼쪽 상단의 **수정** 및 **복사**를 클릭해 게임 설정을 수정하거나 복사할 수 있습니다.


##### ➊ 게임 설정 수정

게임 설정 목록 왼쪽 상단의 **수정**을 클릭해 게임 설정을 수정할 수 있습니다.

![game_config_modify](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_modify2_250717.png)

게임 설정 변경 사항은 마지막 페이지에서 **저장**을 클릭해 저장할 수 있습니다.


##### ➋ 게임 설정 복사

게임 설정 목록 왼쪽 상단의 **복사**를 클릭해 게임 설정을 복사할 수 있습니다.

![game_config_copy](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_copy_250717.png)

**게임 설정 정보 복사** 팝업 창이 표시되며, 게임 설정 이름과 메모를 입력한 뒤 복사할 수 있습니다.


위에서는 게임 설정 등록, 상세 보기, 수정, 복사에 대해 다루었으며, 단순히 게임 설정을 등록만 하였으므로 실제 런처에는 반영되지 않았습니다. 
게임 배포에 대한 설명은 게임 바이너리에 대한 설명 이후에 이어집니다.


#### 게임 바이너리

![game_binary_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_list_250717.png)

게임 바이너리는 게임 실행에 필요한 바이너리 파일들의 집합을 의미합니다.
게임 바이너리 업로드를 하려면 우선 CDN 연동을 진행해야 합니다.

##### CDN 연동
CDN을 연동하려면 연동할 배포존의 **연동** 버튼을 클릭하세요.


예시에서는 TEST 배포존에 CDN 연동을 진행합니다.

###### 고객사 CDN 등록

![game_binary_cdn_customer](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn1_250717.png)

고객사 자체 CDN 주소로 연동합니다.
이 과정에서는 2단계의 설정 작업이 필요합니다.

1. GameStarter 파일 스토리지 주소를 고객사 자체 CDN의 원본 서버 URL로 등록합니다.
2. 고객사 자체 CDN의 주소를 입력합니다.
3. **확인** 버튼을 눌러 연동을 시작합니다.

![game_binary_cdn_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn_list_250717.png)

CDN 연동 결과는 게임 바이너리 상세 정보 화면에서 확인할 수 있습니다.
위 이미지에서 빨간색으로 표시한 영역을 클릭하면 상세 정보 화면으로 이동할 수 있습니다.

![game_binary_cdn_success](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn_success_250717.png)

CDN 연동이 정상적으로 완료된 경우 바이너리 상세 정보 화면에서 CDN 연동 성공 내용을 확인할 수 있습니다.

![game_binary_cdn_failed](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn_failed_2_250717.png)

CDN 에지 서버에 배포 진행 중이거나 또는 다른 사유에 의해 연동에 다소 시간이 소요될 수 있습니다.
연동 시간이 다소 길어지거나 연동에 실패하는 경우 게임 바이너리 상세 정보 화면에서 CDN 연동 실패 내용을 확인할 수 있습니다.



#### 게임 바이너리 상세보기

![game_binary_cdn_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_list_enter_250717.png)

상단 이미지의 빨간색으로 표시한 영역을 클릭하면 게임 바이너리의 상세 보기 화면으로 이동할 수 있습니다.

![game_binary_cdn_enter](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_cdn_enter_250717.png)

게임 바이너리 상세 정보에는 다음과 같은 필드가 있습니다.

##### ➊ 게임 바이너리 정보
게임 바이너리 아이디와 배포존의 정보를 표시 합니다.

##### ➋ CDN 정보
연동된 CDN 정보를 표시합니다.

##### ➌ 게임 바이너리 업로드 정보
업로드한 게임 바이너리의 정보를 표시합니다.
게임 바이너리 정보에는 바이너리 파일의 개수 및 크기, 바이너리 업로드 일시, 업로드 상태가 제공됩니다.


> [참고] 업로드 상태
>
> - **업로드 취소**: 게임 바이너리 업로드를 취소한 상태를 나타냅니다.
> - **업로드 완료**: 게임 바이너리 업로드 절차가 모두 완료하였음을 나타냅니다.
> - **업로드 실패**: 게임 바이너리 업로드 중 오류가 발생하였음을 나타냅니다.
> - **업로드 중**: 게임 바이너리 업로드가 진행 중인 상태임을 나타냅니다.
> - **빌드 중**: 게임 바이너리에 필요한 메타파일을 생성하는 등 파일을 빌드 중임을 나타냅니다.
> - **업로드 대기**: 게임 바이너리에 필요한 메타파일을 생성하는 등의 준비 작업을 진행 중임을 나타냅니다.


##### ➍ 게임 실행파일 이름
업로드한 게임 바이너리 파일 중 게임 실행 파일의 이름을 나타냅니다.


#### 게임 바이너리 업로드

CDN 연동이 완료된 이후에 게임 바이너리 파일들을 업로드할 수 있습니다.
게임 바이너리 파일을 업로드해도 실제 런처로 즉시 반영되지 않으며, **게임 배포**에서 게임 바이너리를 배포를 진행해야 반영됩니다.


![game_binary_upload_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload1_250717.png)

TEST 배포존의 업로드 실행의 **바이너리 업로드** 버튼을 통해서 파일 업로드를 진행합니다.

![game_binary_upload_02](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload2_250717.png)

Windows 운영체제를 사용할 경우 업로드할 게임 바이너리의 폴더를 선택하세요.
macOS를 사용할 경우 Apple에서 인증하여 제공된 '게임.zip' 파일을 업로드하세요.

> <font color="red">[주의]</font><br/>
>
> macOS의 게임 바이너리가 인증되지 않은 파일일 경우 게임이 실행되지 않습니다.


![game_binary_upload_03](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload3_250717.png)

**실행 파일 이름** 드롭다운 메뉴에서 게임을 실행하는 파일을 선택하거나, 파일 이름을 직접 입력해 검색한 후 선택할 수도 있습니다.


![game_binary_upload_04](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload4_250717.png)

파일 업로드가 완료되면 업로드한 파일의 개수와 크기가 표시됩니다.
**확인** 버튼을 누르면 파일 업로드가 진행됩니다.

![game_binary_upload_05](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_upload6_250717.png)

파일 업로드가 완료된 뒤 실제 CDN까지 반영되기까지는 다소 시간이 소요됩니다.
빨간색 영역의 **업로드 상태**가 **업로드 완료**가 될 때까지 대기하세요.

업로드가 완료되면 **업로드 완료**로 상태가 변경됩니다.
이제부터 게임 배포를 통해서 게임 바이너리를 배포할 수 있습니다.

지금까지 게임 바이너리 업로드까지의 과정을 설명했습니다.
바이너리의 업로드 이후에 배포를 진행하여야 합니다.

다음 섹션에서는 게임 설정과 게임 바이너리 배포에 대해 설명합니다.


#### 게임 배포

![game_deploy_list](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_deploy1_250717.png)

**게임 배포**에서 배포존별로 게임 설정 및 게임 바이너리 배포를 할 수 있습니다.
상단 이미지의 빨간색으로 표시한 영역이 하나의 배포존을 의미합니다.
주황색 영역에서는 배포존의 게임 설정을 새롭게 배포하거나, 배포된 정보를 확인할 수 있습니다.
녹색 영역에서는 배포존의 게임 바이너리를 새롭게 배포하거나 배포된 정보를 확인할 수 있습니다.

등록된 게임 설정이 없거나 게임 바이너리가 업로드되지 않은 경우에는 **배포** 버튼이 비활성화됩니다.

아래에서는 배포존에서 등록한 게임 설정과 바이너리를 배포해 보겠습니다.

##### 게임 설정 배포
![game_deploy_config_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_deploy1_reserve_250717.png)

TEST 배포존에서 **게임 설정 배포**의 **배포**를 클릭하면 게임 설정 배포 팝업 창이 표시됩니다.

게임 설정 배포는 예약 배포 또는 즉시 배포로 진행할 수 있습니다.

###### 게임 설정 선택
등록된 게임 설정들이 표시됩니다.
이 중에 배포하고자 하는 게임 설정을 선택합니다.

###### 예약 배포

![game_deploy_config_01-reserve](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_deploy1_reserve2_250717.png)

➊ 기준 시간과 ➋ 배포 시간을 설정한 뒤 **확인**을 클릭하면 **배포 비교** 단계로 이동합니다.

###### 즉시 배포

즉시 배포에는 별도로 설정해야 내용이 없습니다.
바로 마지막 단계인 **배포 비교** 단계로 이동합니다.

###### 배포 비교

![game_deploy_config_deploy](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_deploy_250717.png)

최근 배포한 게임 설정과 비교하는 팝업 창이 표시됩니다.

새롭게 배포할 게임의 설정 정보를 모두 확인한 뒤 **배포**를 클릭해 즉시 배포 또는 예약 배포를 실행할 수 있습니다.
해당 배포존에서 배포 상태 및 최근 배포 완료된 정보를 확인할 수 있습니다.

![game_deploy_config_complete](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_config_deploy_complete_250717.png)


##### 게임 바이너리 배포

게임 바이너리 배포는 게임 바이너리 업로드가 완료된 게임 바이너리를 적용하는 단계입니다.

![game_deploy_binary_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_250717.png)

TEST 배포존에서 **게임 바이너리 배포**의 **배포**를 클릭하면 **게임 바이너리 배포** 팝업 창이 표시됩니다.
게임 바이너리 배포도 예약 배포 또는 즉시 배포로 진행할 수 있습니다.

###### 예약 배포

![game_deploy_binary_02-reserve](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_reserve_250717.png)

➊ 기준 시간과 ➋ 배포 시간을 설정한 뒤 **확인**을 클릭하면 게임 바이너리 배포가 예약됩니다.


###### 즉시 배포
**즉시 배포**를 실행하면 업로드된 게임 바이너리로 즉시 배포가 진행됩니다.
배포를 실행한 뒤 해당 배포존에서 배포 상태 및 최근 배포 완료된 정보를 확인할 수 있습니다

![game_deploy_binary_complete](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_comp_250717.png)

배포가 완료되면 위 이미지와 같이 영역이 녹색으로 변경되며 **배포** 버튼이 비활성화됩니다.
**게임 바이너리** 탭의 파란색 박스 영역에서 배포 정보를 확인할 수 있습니다.

![game_deploy_binary_failed](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_binary_deploy_failed_250717.png)

**게임 바이너리 배포** 영역에서 배포 상태를 확인할 수 있습니다.
배포 상태에 따라 배포존 영역의 색상이 변경됩니다.

> [참고] 배포 상태에 따른 색상 정보
>
> **GRAY**: 미배포 상태. 배포된 이력이 아무 것도 없을 경우 기본으로 표시되는 색상입니다.
> **YELLOW**: 게임 설정만 배포된 상태
> **GREEN**: 게임 설정과 게임 바이너리가 배포 완료된 상태
> **RED**: 게임 바이너리 배포에 실패한 상태


#### 배포 이력

##### 게임 설정 배포 이력

![game_history_config_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_config_1_250717.png)

게임 설정 배포 이력은 배포한 게임 설정들에 대한 이력을 조회할 수 있습니다.
우측의 검색 조건을 통해서 조회 결과를 필터링할 수 있습니다.

##### ➊ 게임 설정 이름
배포된 게임 설정 이름으로 배포 이력을 필터링할 수 있습니다.

##### ➋ 배포 일시
지정한 기간에 배포된 배포 이력을 필터링할 수 있습니다.

##### ➌ 배포 상태
특정 배포 상태로 배포 이력을 필터링할 수 있습니다.

배포 이력 조회 결과에는 다음과 같은 필드가 있습니다.

![game_history_config_02](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_config_3_250717.png)

##### ➊ 게임 설정 이름
배포된 게임 설정의 이름을 나타냅니다.

##### ➋ 배포존
게임 설정이 배포된 배포존을 나타냅니다.

##### ➌ 배포 일시
게임 설정이 배포된 날짜를 나타냅니다.

##### ➍ 배포자
게임 설정을 배포한 사용자의 마스킹된 이메일 주소가 표시됩니다.

##### ➎ 배포 상태
게임 설정이 배포된 상태를 나타냅니다.

> [참고] 배포 상태
>
> - **배포 중**: 게임 설정 배포가 진행 중임을 나타냅니다.
> - **배포 완료**: 게임 설정 배포가 완료되었음을 나타냅니다.
> - **배포 실패**: 게임 설정 배포 중 오류가 발생하였음을 나타냅니다.
> - **배포 예약**: 게임 설정 배포 예약이 등록되었음을 나타냅니다.
> - **배포 예약 취소**: 게임 설정 배포 예약이 취소되었음을 나타냅니다.

##### ➏ 메모
배포된 게임 설정의 메모를 나타냅니다.


##### 게임 바이너리 배포 이력

![game_history_binary_01](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_binary1_250717.png)

게임 바이너리 배포 이력에서 배포한 게임 바이너리의 배포 이력을 조회할 수 있습니다.
우측의 검색 조건을 통해서 조회 결과를 필터링할 수 있습니다.

##### ➊ 배포 일시
지정한 기간에 배포된 배포 이력을 필터링할 수 있습니다.

##### ➋ 배포 상태
특정 배포 상태로 배포 이력을 필터링할 수 있습니다.

배포 이력 조회 결과에는 다음과 같은 필드가 있습니다.

![game_history_binary_02](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_binary3_250717.png)

##### ➊ 배포존
게임 바이너리가 배포된 배포존을 나타냅니다.

##### ➋ 게임 바이너리
배포된 게임 바이너리의 정보가 표시됩니다.
게임 바이너리 정보는 파일의 개수와 파일의 크기로 구성되어 있습니다.

##### ➌ 배포 일시
게임 바이너리가 배포된 날짜를 나타냅니다.

##### ➍ 배포자
게임 바이너리를 배포한 사용자의 마스킹된 이메일 주소가 표시됩니다.

##### ➎ 배포 상태

![game_history_binary_04](https://static.toastoven.net/prod_gamestarter/console/game/gamestarter_game_history_config_4_250717.png)

게임 바이너리가 배포된 상태를 나타냅니다.
**배포 상태**의 `?`에 마우스 포인터를 올리면 상태 목록을 확인할 수 있습니다.

> [참고] 배포 상태
>
> - **배포 중**: 게임 바이너리 배포가 진행 중임을 나타냅니다.
> - **배포 완료**: 게임 바이너리 배포가 완료되었음을 나타냅니다.
> - **배포 실패**: 게임 바이너리 배포 중 오류가 발생하였음을 나타냅니다.
> - **배포 예약**: 게임 바이너리 배포 예약이 등록되었음을 나타냅니다.
> - **배포 예약 취소**: 게임 바이너리 배포 예약이 취소되었음을 나타냅니다.

