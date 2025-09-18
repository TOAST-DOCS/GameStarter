## Game > GameStarter > 콘솔 사용 가이드 > 런처 인스톨러

## Launcher Installer

GameStarter 런처를 실행하려면 가장 먼저 런처가 사용자 PC에 설치되어 있어야 합니다.
런처 인스톨러는 런처를 사용자 PC에 설치해주는 프로그램입니다.

여기에서는 런처 인스톨러 생성 시 필요한 설정들에 대해 설명합니다.

### 초기 설정


![installer_basic](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_basic_250717.png)

런처 인스톨러의 초기 설정은 프로젝트를 처음 세팅할 때 한 번만 설정 가능합니다.
초기 설정을 완료한 뒤에는 일부 항목들에 대해서만 수정할 수 있습니다.
설정 수정에 대해서는 아래의 **설정 수정**의 내용을 참고하세요.

### URL scheme 설정
![installer_urlscheme](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_url_scheme_250717.png)

초기 설정 시 URL scheme 설정을 가장 먼저 등록해야 합니다.

#### ➊ URL scheme

URL scheme은 사용자가 정의한 프로토콜로 앱과 통신할 수 있도록 합니다.
GameStarter는 사용자가 등록한 URL Scheme으로 런처를 실행할 수 있도록 합니다.

> <font color="red">[주의]</font><br/>
>
> URL scheme은 한 번 설정한 뒤에는 변경하기 어렵습니다.
> 다른 프로그램에서 사용하는 URL scheme으로 설정하면 GameStarter가 정상적으로 실행되지 않을 수 있습니다.


> [참고] URL Scheme 이름 규칙
>
> 첫 글자는 영문 소문자로 시작해야 합니다.
> 영문 소문자 및 숫자만 가능하며, 최대 20자까지 가능합니다.


> [참고] 배포존
> URL scheme은 한 번만 입력 받지만 배포존은 여러 개가 존재합니다.
> GameStarter에서는 이를 구분하기 위해서 SERVICE 배포존을 제외한 존에서는 `-<zone>` 형태로 마지막 부분에 자동으로 추가합니다.
>
> 예) SERVICE
> - URL Scheme: example
>
> 예) DEVELOP
> - URL Scheme: example-develop

### 공통 이름 설정
![installer_names](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_name_250717.png)

#### 공통 이름
공통 이름은 런처 설치 프로그램과 삭제 프로그램 이름으로 사용되며, 설치 폴더와 경로에도 사용됩니다.

> <font color="red">[주의]</font><br/>
>
> 공통 이름은 한 번 등록한 이후에는 변경하기 어렵습니다.

> [참고] 공통 이름 규칙
>
> 공통 이름은 20자 이내의 영문 대소문자, 숫자만 입력 가능합니다.

> [참고] 배포존
> 공통 이름은 한 번만 입력받지만 배포존은 여러 개가 존재합니다.
> GameStarter에서는 이를 구분하기 위해서 SERVICE 배포존을 제외한 존에서는 `_<ZONE>` 형태로 마지막 부분에 자동으로 추가합니다.
>
> 예) SERVICE
> - 런처 Installler 이름: `<공통이름>Insatller`
> - 런처 Uninstaller 이름: `<공통이름>Uninstaller`
> - 런처 설치 폴더 이름: `<공통이름>`
> - 런처 설치 경로: `C:\Users\<UserName>\AppData\Roaming\<공통이름>`
>
> 예) DEVELOP
> - 런처 Installler 이름: `<공통이름>Insatller_DEVELOP`
> - 런처 Uninstaller 이름: `<공통이름>Uninstaller_DEVELOP`
> - 런처 설치 폴더 이름: `<공통이름>_DEVELOP`
> - 런처 설치 경로: `C:\Users\<UserName>\AppData\Roaming\<공통이름>_DEVELOP

여기까지 초기 설정을 완료했습니다.
초기 설정이 완료되면 아래와 같이 인스톨러 설정을 등록할 준비가 되었습니다.
**등록**을 클릭해 인스톨러 설정을 진행합니다.


다음은 DEVELOP 존의 설정을 등록하는 예시입니다.

![installer_comp1](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_comp_250717.png)

초기 설정이 완료된 이후 등록이 필요한 설정 정보는 아래와 같습니다.

#### 런처 바로가기 아이콘
![installer_icons](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_250717.png)

GameStarter 런처를 설치한 뒤 바탕 화면에 자동으로 런처 바로 가기를 생성할 수 있으며, 바로 가기를 생성하는 데 필요한 설정을 등록합니다.

#### ➊ 바로가기 아이콘 이미지
바로가기 아이콘 이미지를 등록합니다.

#### ➋ 바로가기 아이콘 이름
바로가기 아이콘 이름을 입력합니다.
입력한 내용이 올바른지 확인한 뒤 **등록**을 클릭합니다.

#### 등록 설정 확인
등록된 설정은 인스톨러 설정 리스트를 클릭하면 확인할 수 있습니다.

![installer_confirm_list](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_after_list_click_250717.png)

### 런처 인스톨러 설정 배포
인스톨러에 필요한 설정을 모두 마치면 인스톨러 설정을 배포해야 합니다.
이 작업은 몇 분에서 수십 분이 소요될 수 있습니다.

![installer_deploy](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_250717.png)

**➊ 배포**를 클릭해 즉시 배포와 예약 배포를 진행할 수 있습니다.


![installer_deploy_modal](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_modal_250717.png)

**➊ 예약 배포**는 등록 시간 기준보다 10분 이후의 시간부터 설정 가능합니다.
**➋ 즉시 배포**는 바로 배포를 시작합니다.

배포 상태에 따라 상태를 확인할 수 있습니다.
![installer_deploy_status](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_reservation_confirm_2_250717.png)

> 런처 인스톨러 배포 상태 종류는 아래와 같습니다
> - 빌드 대기
> - 빌드 중
> - 배포 중
> - 적용 대기중
> - 배포 실패
> - 배포 완료
> - 배포 예약
> - 배포 취소

> [참고]
>
> 배포 상태가 **배포 실패**로 표시될 경우 고객 센터로 문의하세요.

#### 배포 이력 조회
**배포 이력** 탭에서 배포된 인스톨러의 정보와 배포 이력을 조회할 수 있습니다.
![installer_deploy_list](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_list_250717.png)

### 설정 수정
런처 인스톨러의 설정 상제 정보를 조회하고 수정할 수 있습니다.
위의 안내에 따라 인스톨러 설정의 등록과 배포 이후에 인스톨러 설정 화면입니다.

#### 등록된 설정 확인

하단 이미지에 빨간색으로 표시한 영역을 클릭해 인스톨러 상세 정보를 조회/수정할 수 있는 페이지로 이동할 수 있습니다.

![installer_config_list](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_list_250717.png)

➊ **OS별 조회 버튼**: Windows 또는 macOS별로 등록된 설정을 나타냅니다
➋ 배포존: 배포존 정보를 나타냅니다.
➌ **인스톨러 설정 버전**: 인스톨러의 설정 버전 정보를 나타냅니다.
➍ **등록 일시**: 인스톨러의 설정을 등록한 날짜를 나타냅니다.
➎ **등록자**: 런처 인스톨러 설정을 등록한 사용자의 마스킹된 이메일 주소를 나타냅니다.
➏ **메모**: 런처 인스톨러 설정 등록 시 입력한 메모를 나타냅니다.

#### 등록된 설정 상세 정보 확인

인스톨러의 기본 정보를 확인할 수 있으며, 하단의 **다음**을 클릭해 런처 바로가기 아이콘 등록 정보를 확인할 수 있습니다.
**수정**을 클릭해 기본 정보 설정을 수정할 수 있습니다.

![installer_config_enter](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_enter_250717.png)
➊ **수정 버튼**: 인스톨러 설정을 수정 할 수 있습니다.
➋ **URL Scheme**: 등록된 URL Scheme 정보를 나타냅니다.
➌ **공통 이름**: 등록된 런처의 Installer 이름, Uninstaller 이름, 설치 폴더 이름 및 설치 경로에 사용되는 공통 이름 정보를 나타냅니다.
➍ **인스톨러 버전**: 인스톨러 버전 정보를 나타냅니다.
➎ **메모**: 런처 인스톨러 설정 등록시 입력한 메모를 나타냅니다.

#### 기본 정보 수정
기본 정보를 수정하려면 **수정**을 클릭하거나, **인스톨러 설정 상세 정보** 화면에서 다음을 클릭해 아래 **인스톨러 설정 수정** 페이지로 진입하세요

![installer_config_modify_default](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_modify_default_250717.png)
➊ **인스톨러 버전**: 인스톨러 버전을 수정할 수 있습니다.
➋ **메모**: 인스톨러 설정 메모의 내용을 수정할 수 있습니다.
하단의 ➌ **다음**을 클릭해 다음 수정 페이지로 이동합

#### 런처 바로 가기 아이콘 수정

런처 바로가기 아이콘을 수정하려면 **수정**을 클릭하거나, **기본 정보 수정 화면**에서 **다음**을 클릭해 아래 페이지로 진입하세요.

기존에 등록된 런처 바로가기 아이콘 정보를 확인하고 바로가기 아이콘 이름을 수정할 수 있습니다.
![installer_config_modify_shotcut](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_modify_shotcut_250717.png)

**미리보기**를 클릭해 수정한 내용을 미리 확인할 수 있습니다

![installer_config_modify_preview](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_modify_preview1_250717.png)
미리보기 화면에서는 아래 정보를 확인 할 수 있습니다.
- 배포 존 정보
- 변경할 기본 정보
- 반경할 런처 바로가기 아이콘 정보

수정을 완료한 뒤 **저장**을 클릭해 수정된 설정 내용을 반영할 수 있습니다.
