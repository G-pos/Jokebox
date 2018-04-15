[![Logo](https://gpos.postech.ac.kr/download/Jokebox/page/emblem.png)](https://gpos.postech.ac.kr/download/Jokebox/page/jokebox.html)

__C 기반 게임 제작 프레임워크__

당신의 빛나는 상상력,

더이상 기술에 막혀 썩혀두지 마십시오.

![](https://img.shields.io/badge/POSTECH-G--pos-red.svg)
![](https://img.shields.io/badge/Visual%20Studio-2010-blue.svg)
![](https://img.shields.io/badge/Visual%20Studio-2015-blue.svg)
![](https://img.shields.io/badge/Visual%20Studio-2017-blue.svg)

# 설치법
- git
```
git clone https://github.com/G-pos/Jokebox.git
```
- [__다운로드__](https://github.com/G-pos/Jokebox/releases)
  - [__문서__](https://github.com/G-pos/Jokebox/tree/master/doc)


# 게임 제작으로 가는 가장 빠르고 쉬운 길
- __설치 없는 간단한 시작__
  - Visual C++ 2010 솔루션 형태로 제공되어 원형 솔루션을 받아 game.c 소스를 구현하는 것만으로 간단하게 게임을 작성할 수 있습니다.
- __빠르고 쉬운 사용법__
  - 난이도에 따라 함수를 Level별로 분리하고, 거의 모든 절차를 함수 호출 한 번으로 통합하여 처음 사용자가 빠르고 쉽게 배울 수 있도록 하였습니다.
- __절차가 필요 없는 배포__
  - 빌드 결과 폴더를 압축하는 것만으로, 모든 배포 준비가 완료됩니다. Windows Vista SP2 이상의 모든 환경에서 작동이 보장되며, 배포를 위한 이밖의 추가적인 절차는 전혀 필요치 않습니다

# 사양
- Windows Vista SP2 이상
- DirectX 10.1 이상
- Visual C++ 2010 이상

# 사용 기술
- __그래픽__ Direct2D
  - DirectX 10.1 이상에 내장
- __이미지 처리__ Windows Imaging Component
  - Windows Vista 이상에 내장
- __문자 출력__ DirectWrite
  - DirectX 10.1 이상에 내장
- __사운드__ DirectSound
  - 일부 DirectX SDK (Nov, 2009) lib 프레임워크에 내장
  - libvorbis OGG Decoder
    - 프레임워크에 내장 
- __하드웨어 입력/기타__ Windows API

# 제작자
- 이광무 (gwangmu(at)snu.ac.kr)

# License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="크리에이티브 커먼즈 라이선스" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br />이 저작물은 <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">크리에이티브 커먼즈 저작자표시-동일조건변경허락 3.0 Unported 라이선스</a>에 따라 이용할 수 있습니다.
