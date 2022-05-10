### v0.2.1 SNAPSHOT

- [내부] 버전 코드가 조금 더 자동화되었습니다.<br>리소스 버전은 여전히 날짜로 제공되며, 코드 버전과 내부 버전을 직관적으로 변경하였습니다.
  * 코드 버전은 `메인 버전 코드``-``수정일`
  * 내부 버전(설정에 표시됨)은 `메인 버전 코드``-SNAPSHOT` (릴리스는 `-SNAPSHOT`이 삭제되어 제공)
- [내부] 듀얼-버전 리소스를 준비하기 위해 내부적으로 작업을 실시하였습니다.

## Release 0.2.0

* 포지 모드가 업데이트되었습니다. 모든 번역 변경사항이 적용되었습니다.
* FancyMenu 설정이 또 갱신되었습니다.
* 리소스팩이 업데이트되었습니다. 추가로 리소스팩의 적용이 강제됩니다.<br>이에 따라 최소 RAM 용량을 2GB 이상으로 설정하시는 것을 권장합니다.
  - 팩 버전은 8로 되돌렸습니다.
* 인스톨러는 이제 관리자 권한을 요청합니다. 여전히 코드 오류로 인해 2번 실행해야 할 수 있습니다.
* 기본 실행 경로가 분리되었습니다.

## Prerelease 0.1.3 alpha 2

- Icon 투명화 다시 진행: 이제 좀 제대로 보일 겁니다.
- 1.16.5와 1.18.1의 Optifine 모드 캐시 파일을 삭제하였습니다.
- [설정]에 표시되는 버전 정보를 한글화하였습니다.
- FancyMenu 설정을 갱신하였습니다.
- 1.18.2로의 업데이트:
  * Forge 버전을 1.18.1-39.1.2에서 1.18.2-40.1.0으로 업데이트하였습니다.
  * 1.18.2에서 작동하는 모드를 모두 1.18.2로 업데이트하였습니다.
  * 리소스팩 경고가 뜨지 않도록, 리소스팩을 1.18.2 팩 버전 (9)에 맞게 업데이트하였습니다.
  * FancyMenu 설정 갱신은 포함되지 않았습니다.

## Prerelease 0.1.3 alpha 1

* Icon 투명화 진행: 이제 아이콘 파일이 투명하게 보입니다. 살짝 깨져 보일 수는 있습니다.<br>뭐 임시 로고니까 괜찮겠죠?
* 인스톨러가 삭제하는 폴더를 모드 폴더, 모드 설정 폴더, 리소스팩 폴더로 제한하였습니다.
* 시스템 설정에 변화가 생겼습니다. 512MB 단위로 조정 가능한 것을 256MB 단위로 조정할 수 있게 변경하였습니다.
* 시스템 설정에 1GB = 1024MB 힌트를 추가하였습니다.
* 권장 RAM (4GB)과 Shader 관련 힌트를 추가하였습니다.
* Microsoft 계정 로그인 창을 개편하였습니다.
  - 배경에 보이는 문구를 수정하였습니다. "Microsoft 계정으로 로그인 중 / 잠시만 기다려주세요"
  - 창 제목을 "XboxLoginWindow"에서 "Microsoft 계정으로 로그인"으로 변경하였습니다.
* Pam's HarvestCraft 2 - Food Core / Food Extended 모드를 추가하였습니다.
* 런처 빌드 소프트웨어를 VS Community 2022로 업데이트하였습니다.<br>기존 VS Community 2019는 라이브러리 등을 위하여 남겨뒀으나 곧 이전한 후 삭제 예정입니다.

## Prerelease 0.1.2

- Optifine 교체: `HD Ultra H4` -> `HD Ultra H6`
- Icon 파일 교체
- 이제 인스톨러는 기존 설치(game 폴더만)를 삭제합니다
- Options 파일이 변경되었습니다. 이제 기본 GUI 스케일은 2로 고정됩니다.

## Prerelease 0.1.1

* 현재 사용되고 있는 리소스팩
* [소스코드] LFS 끄고 달립시다(?)

## Initial 0.1.0

### Resolve delta
- Source: non-public
- Upstream: Fetched

### This includes...
- Mods & Few Configs
- Beta Resource Packs that is once used
- Automatic Server Enter
- FancyMenu Configurations for Devs
- The desc here is in Engligh
