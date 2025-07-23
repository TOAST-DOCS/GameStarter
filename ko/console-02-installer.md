## Game > GameStarter > 콘솔 사용 가이드 > 런처 인스톨러

## Launcher Installer
런처 인스톨러를 생성하려면 필요한 설정이 있습니다.
이 설정들에 대해서 설명합니다.

![installer_basic](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/installer/gamestarter_installer_basic_250717.png)

### 1. URL scheme 설정
![installer_urlscheme](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/installer/gamestarter_installer_url_scheme_250717.png)

#### 1) URL scheme

URL Scheme은 사용자가 정의한 프로토콜로 앱과 통신을 할 수 있도록 해줍니다.
GameStarter는 사용자가 등록한 URL Scheme으로 런처를 실행할 수 있도록 해줍니다.

> <font color="red">[주의]</font><br/>
>
> URL Scheme는 한 번 설정한 이후에는 변경하기 어렵습니다.
> 다른 프로그램에서 사용하는 URL Scheme로 설정하면 GameStarter가 정상적으로 실행되지 않을 수 있습니다.


> [참고] URL Scheme 이름 규칙
> 
> - 첫 글자는 영문 소문자로 시작해야 합니다.
> - 영문 소문자 및 숫자만 가능하며, 최대 20자까지 가능합니다.

> [참고] 배포존
> URL Scheme는 한 번만 입력받지만 배포존은 여러 개가 존재합니다.
> GameStarter에서는 이를 구분하기 위해서 SERVICE 배포존을 제외한 존에서는 `-<zone>` 형태로 마지막 부분에 자동으로 추가합니다.
> 
> 예) SERVICE
> - URL Scheme: example
> 
> 예) DEVELOP
> - URL Scheme: example-develop

### 2. 공통 이름 설정
![installer_names](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/installer/gamestarter_installer_name_250717.png)

#### 1) 공통 이름
공통 이름은 런처 설치 프로그램과 삭제 프로그램 이름으로 사용되며, 설치 폴더와 경로에도 사용됩니다.

> <font color="red">[주의]</font><br/>
>
> 공통 이름은 한 번 등록한 이후에는 변경하기 어렵습니다.

> [참고] 공통 이름 규칙
> 
> - 공통 이름은 20자 이내의 영문 대소문자, 숫자만 입력 가능합니다.

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

#### 2) 런처 바로가기 아이콘
![installer_icons](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_250717.png)

GameStarter 런처가 설치되고 난 이후 바탕화면에 자동으로 런처 바로 가기를 생성할 수 있으며,
바로 가기를 생성하는 데 필요한 설정을 등록 합니다.

#### 1) 바로 가기 아이콘
바로가기 아이콘 이미지를 등록합니다.

#### 2) 바로 가기 아이콘 이름

입력한 내용이 올바른지 확인이 끝나면 [등록] 버튼을 클릭합니다.

등록된 설정은 인스톨러 설정 리스트를 클릭하면 확인 할 수 있습니다.
![installer_confirm_list](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_after_list_click_250717.png)


### 3. 런처 인스톨러 설정 배포
![installer_deploy](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_250717.png)

인스톨러에 필요한 설정을 모두 마치면 인스톨러 설정을 배포 하여야 합니다.
이 작업은 몇 분에서 수십 분이 소요될 수 있습니다.

#### 1) 배포 버튼을 통하여 즉시 배포와 예약 배포를 진행 할 수 있습니다.
![installer_deploy_modal](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_modal_250717.png)

#### 1) 예약 배포는 등록시간기준 보다 10분 이후의 시간부터 설정 가능 합니다.
#### 2) 즉시 배포는 바로 배포를 시작합니다.

배포 상태에 따라 상태를 확인 할 수 있습니다.
![installer_deploy_status](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_reservation_confirm_2_250717.png)

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
> 빌드 상태가 `배포 실패`면 고객센터로 문의를 하시기 바랍니다.

#### 4) 배포 이력 조회
배포 이력 텝에서 배포된 인스톨러의 정보와 배포 이력을 조회 할 수 있습니다.
![installer_deploy_list](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_gamestarter/console/installer/gamestarter_installer_reg_shotcut_deploy_list_250717.png)

