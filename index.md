---
title: Switch CFW Tutorial GitBook (CFW 튜토리얼 깃북)
layout: home
---

![atmosphere.png](assets/images/index/480418a92aaf116ecc55c59f04e763ace5c065b7.png)

### 😊 Nintendo Switch Custom firmware 설치 가이드 튜토리얼에 오신것을 환영합니다.

> 본 `튜토리얼`을 통해 스위치 **Custom firmware(커스텀 펌웨어)**인 [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere) 를 설치하고, 필수 프론트 엔드인 [Hekate](https://github.com/CTCaer/hekate) 를 구성하는 과정으로 진행됩니다.
>
> 하드웨어 취약점을 가진 구형 스위치를 기준으로 **Nintendo Switch(닌텐도 스위치)**에서 `홈브류` 및 `사용자 정의 펌웨어`를 얻는 데 필요한 모든 단계를 안내해 드리겠습니다.

<br>

`한국` 상황에 맞추어 친절하게 소개된 내용이 많지 않아, 순정 `아트모스피어`로의 설치와 구성에 어려움을 겪는 사용자를 위해 제작된 `깃북` 스타일의 `튜토리얼`입니다.

<br>

#### 🌈 스위치 커스텀 펌웨어 설치가 가능한 경우

- [x] &nbsp;스위치 1세대 기기인 `2018년 7월 이전` 생산 제품을 보유

- [x] &nbsp;별도의 `모드칩(SX Core, hwfly)`등이 설치 되어 NVIDIA 칩셋의 취약점인 `RCM 모드`로 진입 가능

<br>

#### 😢 Atmosphère (아트모스피어) 란 무엇인가요?

**원제 Atmosphère**는 현재 **SciresM** , **TuxSH** , **hexkyz** 및 **fincs** 에서 개발 및 유지 관리하고 있는 오픈소스 커스텀 펌웨어입니다.

**커스텀 펌웨어(CFW)** 는 제조사가 만든 시스템 펌웨어를 사용자화하는 소프트웨어를 이야기하며, 과거 스위치 커펌 초기부터 지금까지 **스위치 커스텀 펌웨어(CFW)** 라고 하면 대표적으로 위 아트모스피어를 칭한다고 할 수 있습니다.

현재 `2018년 7월 이전`에 판매된 모든 닌텐도 스위치는 위 `커스텀 펌웨어(CFW)`를 실행할 수 있습니다.

<br>

`Atmosphère`는 스위치 펌웨어의 `백그라운드에서 실행`되는 여러가지 모듈로 분리되어 있으며, `부팅`과 동시에 즉각적으로 `OS를 패치하는 형태`로 구동됩니다.

이를 통해 대부분의 사용자 영역 익스플로잇보다 더 높은 수준의 권한을 `홈브류`에 부여하여 시스템 기능을 확장할 수 있으며, 홈브류 개발자 및 사용자가 `LayeredFS`라는 내부 모듈을 사용한 게임 `모딩`이나 `치트`와 같은 `다양한 목적`으로 활용할 수 있는 `추가 기능`을 제공하는 데 사용된다 할 수 있습니다.

`커스텀 펌웨어(CFW)`는 모든 스위치 펌웨어 버전의 `1세대 콘솔`에서 설치가 가능하지만, `RCM 모드`라는 일종의 `복구모드`로 진입하기 위한 준비물들이 필요합니다.

<br>

#### 👍 이 튜토리얼을 따라 CFW를 설치하면, 무엇을 얻을 수 있을까요?

- 사용자가 만든 `테마`와 `스플래시 화면`으로 홈 메뉴를 사용자화 가능
- 소유한 게임에 `ROM 해킹` 사용
- 많은 게임의 `저장 백업`, `편집` 및 `복원`
- `RetroArch` 또는 기타 `독립 실행형 에뮬레이터`를 사용하여 다양한 레트로 게임기로 사용 가능
- `homebrew`에 대한 액세스 권한을 잃을 염려 없이 최신 시스템 버전으로 안전하게 업데이트

아트모스피어는 `100%` 무료이며 현존하는 모든 `AIO(올인원)` 파일들의 근본이 되는 `CFW`입니다.

따라서 아트모스피어를 다룰 줄 안다면, 다른 어떤 올인원 파일도 다룰 수 있다는 뜻이 됩니다.

<br/>

😒 물론 지금까진 무슨 소리인지 하나도 모르셔도 좋습니다.

지금부터 천천히 따라오시다 보면 앞으로 `혼자`서도 충분히 `설치`가 가능해질겁니다. 👌

<br><br><br><br><br>

## Jekyll with GitBook

Live demo on Github Pages: [Jekyll Gitbook](https://sighingnow.github.io/jekyll-gitbook)

[![Jekyll Themes](https://img.shields.io/badge/featured%20on-JekyllThemes-red.svg)](https://jekyll-themes.com/jekyll-gitbook/)

본 튜토리얼은 위 지킬 깃북 테마를 이용해 작성했습니다.

## License

> 이 튜토리얼은 Creative Commons Attribution-ShareAlike 4.0 International 저작권을 준수합니다. 라이센스 전문은 [https://creativecommons.org/licenses/by-sa/4.0](https://creativecommons.org/licenses/by-sa/4.0/) 에서 확인하세요.
