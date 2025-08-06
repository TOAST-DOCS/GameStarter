## Game > GameStarter > 콘솔 사용 가이드 > 런처 인스톨러

## Launcher Installer

GameStarter 런처를 실행하려면 가장 먼저 런처가 사용자 PC에 설치되어 있어야 합니다.
런처 인스톨러는 런처를 사용자 PC에 설치해주는 프로그램입니다.

런처 인스톨러를 생성할때 필요한 설정들에 대해서 설명합니다.

### 1. 초기 설정

런처 인스톨러의 `[초기 설정]`에 대해 먼저 설정하겠습니다.

![installer_basic](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_basic_250717.png)

런처 인스톨러의 초기 설정은 처음 프로젝트를 셋팅할때 한번만 설정 가능합니다.
초기 설정 이후에는 일부 항목들에 대한 수정만이 가능 합니다.
수정과 관련된 내용은 아래의 `[설정 수정]` 내용을 참고 해주세요.

### 1-1. URL scheme 설정
![installer_urlscheme](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_url_scheme_250717.png)

초기 설정시 처음 등록할 내용은 URL scheme  설정 입니다.

#### 1) URL scheme

URL Scheme은 사용자가 정의한 프로토콜로 앱과 통신을 할 수 있도록 해줍니다.
GameStarter는 사용자가 등록한 URL Scheme으로 런처를 실행할 수 있도록 해줍니다.

> <font color="red">[주의]</font><br/>
>
> URL Scheme는 한 번 설정한 이후에는 변경하기 어렵습니다.
> 다른 프로그램에서 사용하는 URL Scheme로 설정하면 GameStarter가 정상적으로 실행되지 않을 수 있습니다.


> [참고] URL Scheme 이름 규칙
>
> 첫 글자는 영문 소문자로 시작해야 합니다.
> 영문 소문자 및 숫자만 가능하며, 최대 20자까지 가능합니다.


> [참고] 배포존
> URL Scheme는 한 번만 입력받지만 배포존은 여러 개가 존재합니다.
> GameStarter에서는 이를 구분하기 위해서 SERVICE 배포존을 제외한 존에서는 `-<zone>` 형태로 마지막 부분에 자동으로 추가합니다.
>
> 예) SERVICE
> - URL Scheme: example
>
> 예) DEVELOP
> - URL Scheme: example-develop

### 1-2. 공통 이름 설정
![installer_names](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_name_250717.png)

#### 1) 공통 이름
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

여기까지 `초기 설정` 이 완료 되었습니다.
초기 설정이 완료되면 아래와 같이 인스톨러 설정을 등록 할 준비가 되었습니다.
`[+등록]` 버튼을 클릭하여 인스톨러 설정을 진행하도록 하겠습니다.
예시에서는 DEVELOP 존의 설정을 등록하도록 하겠습니다.

![installer_comp1](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_comp_250717.png)

초기 설정이 완료된 이후 등록이 필요한 설정 정보는 아래와 같습니다.

#### 2) 런처 바로가기 아이콘
![installer_icons](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_250717.png)

GameStarter 런처가 설치되고 난 이후 바탕화면에 자동으로 런처 바로 가기를 생성할 수 있으며,
바로 가기를 생성하는 데 필요한 설정을 등록 합니다.

#### 1) 바로 가기 아이콘
바로가기 아이콘 이미지를 등록합니다.

#### 2) 바로 가기 아이콘 이름
입력한 내용이 올바른지 확인이 끝나면 `[등록]` 버튼을 클릭합니다.

#### 3) 등록 설정 확인
등록된 설정은 인스톨러 설정 리스트를 클릭하면 확인 할 수 있습니다.
![installer_confirm_list](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_after_list_click_250717.png)

### 1-3. 런처 인스톨러 설정 배포
인스톨러에 필요한 설정을 모두 마치면 인스톨러 설정을 배포 하여야 합니다.
이 작업은 몇 분에서 수십 분이 소요될 수 있습니다.

![installer_deploy](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_250717.png)

#### 1) 배포 버튼을 통하여 즉시 배포와 예약 배포를 진행 할 수 있습니다.


![installer_deploy_modal](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_modal_250717.png)

#### 1) 예약 배포는 등록시간기준 보다 10분 이후의 시간부터 설정 가능 합니다.
#### 2) 즉시 배포는 바로 배포를 시작합니다.

배포 상태에 따라 상태를 확인 할 수 있습니다.
![installer_deploy_status](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_reservation_confirm_2_250717.png)

> #### 런처 인스톨러 배포 상태는 아래와 같습니다.
> 1. 빌드 대기
> 2. 빌드 중
> 3. 배포 중
> 4. 적용 대기중
> 5. 배포 실패
> 6. 배포 완료
> 7. 배포 예약
> 8. 배포 취소

> [참고]
>
> 빌드 상태가 `배포 실패`면 고객센터로 문의 하시기 바랍니다.

#### 4) 배포 이력 조회
배포 이력 텝에서 배포된 인스톨러의 정보와 배포 이력을 조회 할 수 있습니다.
![installer_deploy_list](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_list_250717.png)

### 2. 설정 수정
런처 인스톨러의 설정 상제 정보를 조회 하고 수정 할 수 있습니다.
위의 안내에 따라 인스톨러 설정의 등록과 배포 이후에 인스톨러 설정 화면입니다.

#### 2-1. 등록된 설정 확인

설정 수정을 위해서는 설정리스트의 빨간박스 영역을 클릭하여 등록한 인스톨러 상세정보를 조회/수정 할 수 있는 페이지로 이동해야 합니다.

![installer_config_list](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_list_250717.png)

1. **OS 별 조회 버튼**: OS 별로 등록된 설정을 나타냅니다.
2. **배포존**: 배포존 정보를 나타냅니다.
3. **인스톨러 설정 버전**: 인스톨러의 설정 버전 정보를 나타냅니다.
4. **등록 일시**: 인스톨러의 설정을 등록한 날자를 나타냅니다.
5. **등록자**: 런처 인스톨러 설정을 등록한 사용자의 마스킹 된 이메일 주소를 나타냅니다.
6. **메모**: 런처 인스톨러 설정 등록시 입력한 메모를 나타냅니다.

#### 2-2. 등록된 설정 상세 정보 확인

인스톨러의 기본 정보를 확인 할 수 있으며, 하단의 다음 버튼을 클릭하여 런처 바로가기 아이콘 등록정보를 확인 할 수 있습니다.
설정 수정을 위해서는 `[수정]` 버튼을 통하여 기본정보를 수정 할 수 있습니다.

![installer_config_enter](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_enter_250717.png)
1. **수정 버튼**: OS 별로 등록된 설정을 나타냅니다.
2. **배포존**: 배포존 정보를 나타냅니다.
3. **인스톨러 설정 버전**: 인스톨러의 설정 버전 정보를 나타냅니다.
4. **등록 일시**: 인스톨러의 설정을 등록한 날자를 나타냅니다.
5. **등록자**: 런처 인스톨러 설정을 등록한 사용자의 마스킹 된 이메일 주소를 나타냅니다.
6. **메모**: 런처 인스톨러 설정 등록시 입력한 메모를 나타냅니다.

#### 2-3. 기본 정보 수정
설정 수정을 위해서는 수정 버튼을 누르거나, 2-2 항목(인스톨러 설정 상제 정보)에서 다음 버튼을 통하여 아래의 페이지로 진입 하여 수정 할 수 있습니다.

![installer_config_modify_default](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_modify_default_250717.png)
1. **인스톨러 버전**: 인스톨러 버전 항목을 수정 할 수 있습니다.
2. **메모**: 인스톨러 설정 메모 내용을 수정 할 수 있습니다.
3. 하단의 **[다음]** 버튼을 클릭하여 다음 수정 페이지로 이동 합니다.

#### 2-4. 런처 바로 가기 아이콘 수정

설정 수정을 위해서는 수정 버튼을 누르거나, 2-3 항목(기본정보 수정)에서 다음 버튼을 통하여 아래의 페이지로 진입 하여 수정 할 수 있습니다.

기존에 등록된 런처 바로가기 아이콘 정보를 확인하고 바로가기 아이콘 이름을 수정 할 수 있습니다.
![installer_config_modify_shotcut](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_modify_shotcut_250717.png)

[미리보기] 버튼을 눌러 수정 한 내용을 미리 확인 할 수 있습니다.
![installer_config_modify_preview](https://static.toastoven.net/prod_gamestarter/console/installer/gamestarter_installer_config_modify_preview1_250717.png)
미리보기 화면에서는 아래 정보를 확인 할 수 있습니다.
1. 배포 존 정보
2. 변경할 기본 정보
3. 반경할 런처 바로가기 아이콘 정보

수정이 완료된 이후에는 **[저장]** 버튼을 클릭하여 수정된 설정내용을 반영 할 수 있습니다.