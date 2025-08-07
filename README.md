# FoundryVTT-Korean
## Foundry VTT 코어 한글화 모듈

기존의 [코어 한글화 모듈](https://github.com/ShoyuVanilla/FoundryVtt-lang-ko-KR/) 이 업데이트되지 않아 0.8.x 버전에서는 사용할 수 없습니다. 

0.8.x 버전부터는 이 모듈을 사용해주세요.

## 설치

매니페스트 링크 : https://github.com/jbblily/FoundryVTT-Korean/releases/latest/download/module.json

상단의 링크를 부가모듈 > 모듈 설치 > 아래와 같은 가로창에 붙여 넣은 후 설치 버튼을 눌러 다운로드하세요. 

![image](https://user-images.githubusercontent.com/18694887/128638043-aeabf5ce-cec6-4845-a4c2-9cbd81386d6d.png)


## 사용법

1. 셋업 화면의 모듈 목록에서 Translation : Korean [Core]가 다운로드되었는지 확인하세요.
2. 셋업 화면에서 환경설정 > 기본 언어를 Translation : Korean [Core]로 변경한 후, 새로고침하세요.
3. 월드 내에서 Configure settings(톱니바퀴 모양 아이콘) -> Language Preference -> Korean 으로 설정하면 끝!


**월드 내에서 이 모듈을 활성화하지 마세요! 월드에 필요한 모듈이 아닙니다!**

글꼴을 한글 폰트로 변경하고 싶은 분은 Custom css 와 같은 모듈로 조정해주세요.

## 자주 묻는 질문
### Q1: 저널 내에 한글 폰트를 사용하고 싶어요!

A: 월드 내 환경설정에서 '추가 글꼴 설정' 누르세요. 원하는 글꼴 파일을 추가하면 저널에 추가한 폰트를 선택할 수 있게 됩니다.

### Q2: 월드 인터페이스 글꼴을 변경하고 싶어요!

A: 2가지 방법이 있습니다. 

**A1) 브라우저에 글꼴을 설정하기(크롬 브라우저 기준)**

chrome://settings/fonts  <<여기에 들어가셔서 글꼴 설정하시면 파운드리 내의 글꼴도 대체로 변경됩니다.
본인 컴퓨터에 설치되어 있는 글꼴을 선택할 수 있습니다.

본인이 보이는 화면에서만 글꼴이 변경되는 것이므로 다른 사람 컴퓨터에서 보이는 글꼴은 다를 수 있습니다. 

**A2) Custom css 모듈로 웹폰트를 이용해 글꼴 변경하기**

css는 파운드리 버전에 따라 변하므로 F12를 눌러 개발자모드를 연 다음, css 파일을 읽고 그 구조에 맞게 변경해주어야 합니다.

이 방법을 사용하면 나와 상대방의 화면 모두에서 동일한 글꼴로 보입니다.




## 다운그레이드

최신 버전이 아닌, 구 버전의 코어 소프트웨어를 설치한 경우 다운그레이드를 통해 구 버전의 번역을 설치할 수 있습니다. 단, 매니페스트 URL이 아닌, 압축 파일을 통해 수동으로 다운그레이드해야 합니다. (다른 좋은 방법이 있으신 분은 저에게 알려주세요.)

1. 원하는 버전의 링크를 눌러 압축 파일을 다운로드

2. Data/modules 폴더에 압축 해제. lang-ko 폴더를 덮어쓰기 해주세요.

3. 파운드리 재시작

### 구 버전 다운로드 링크

코어 v 0.8.9 : https://github.com/jbblily/FoundryVTT-Korean/archive/refs/tags/v0.2.3.zip

코어 v 9.280: https://github.com/jbblily/FoundryVTT-Korean/archive/refs/tags/v0.3.4a.zip
