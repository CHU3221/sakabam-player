# Sakabam-Player

웹 브라우저에서 바로 연주할 수 있는 사카밤바스피스 형태의 스타일로폰(건반 악기) 웹 애플리케이션입니다.  
STELLIVE 소속 아오쿠모 린(Aokumo Rin)님의 목소리를 활용한 팬메이드 2차 창작 프로젝트입니다.

![Sakabam-Player Preview](https://raw.githubusercontent.com/CHU3221/sakabam-player/main/docs/sakabam-preview.png)

---

## 소개

이 프로젝트는 팬 커뮤니티 유저들이 웹 환경에서 가볍고 재미있게 즐길 수 있도록 설계된 인터랙티브 웹 악기입니다.

별도의 설치나 다운로드 없이 브라우저에서 즉시 실행되며, 마우스 클릭이나 모바일 터치 슬라이딩을 통해 부드러운 피치 벤드(Pitch Bend) 효과와 함께 연주할 수 있습니다.

주요 목표:

- 별도 앱 설치 없는 Web-first 환경
- 반응형 Canvas 기반의 직관적인 UI
- Web Audio API를 활용한 자연스러운 소리 연결
- 가이드라인을 준수하는 건전한 팬 창작물 생태계 지향

---

## 목차

1. [주요 특징](#주요-특징)
2. [사용 기술](#사용-기술)
3. [실행 및 사용 방법](#실행-및-사용-방법)
4. [저작권 및 출처 (Copyright & Attribution)](#저작권-및-출처-copyright--attribution)

---

## 주요 특징

- **인터랙티브 건반 UI**: Canvas API를 활용해 창 크기에 맞춰 유동적으로 렌더링되는 2옥타브 와이드 건반
- **자연스러운 슬라이딩 연주**: Web Audio API의 `playbackRate`를 활용하여 끊김 없는 피치 벤드(Pitch Bend) 구현
- **크로스 플랫폼 지원**: PC(마우스 이벤트) 및 모바일(터치/제스처 이벤트) 완벽 대응
- **Zero-Dependency**: 외부 라이브러리 없이 순수 HTML/CSS/Vanilla JS만으로 경량화 구축

---

## 사용 기술

### Frontend

- HTML5 (Canvas API)
- CSS3 (반응형 디자인, Flexbox)
- Vanilla JavaScript (ES6+)
- Web Audio API

### Infra (배포 환경)

- Cloudflare Pages / 개인 도메인 연동
- 정적 웹 호스팅 (Static Web Hosting)

---

## 실행 및 사용 방법

별도의 빌드 과정 없이 웹 브라우저 접속만으로 즉시 구동됩니다.

### 1. 접속 방법
배포된 링크에 접속하여 이용할 수 있습니다.
- **Demo Link**: [https://sakabam-player.chucode.com](https://sakabam-player.chucode.com)

### 2. 조작 방법
- **PC 환경**: 캐릭터의 배(건반) 부분을 마우스로 클릭하거나, 클릭한 상태로 좌우로 드래그하여 슬라이딩 연주를 할 수 있습니다.
- **모바일 환경**: 화면의 건반을 터치하거나, 터치한 상태로 부드럽게 문질러 연주합니다.

---

## 저작권 및 출처 (Copyright & Attribution)

이 프로젝트는 관련 2차창작 가이드라인을 준수하여 제작된 팬메이드 2차창작 프로젝트입니다.

프로젝트에 사용된 `.wav` 음원은 **STELLIVE 소속 Aokumo Rin**과 관련된 음원을 기반으로 제작되었습니다.

원본 음원은 **[린 다시보기](https://www.youtube.com/@rinreplay) 채널에 게시된 [라이브 방송 영상의 약 28:20 지점](https://www.youtube.com/watch?v=uroym15AjuQ&t=1700s)에서 발췌하여 사용했습니다.**

- 원본 음원 및 관련 지적재산권에 대한 모든 권리는 해당 저작권자에게 귀속됩니다.
- 본 프로젝트는 해당 음원 및 원본 콘텐츠에 대한 권리를 주장하지 않으며, 팬메이드 2차창작 프로젝트의 목적으로만 사용합니다.
- 본 프로젝트는 STELLIVE 또는 Aokumo Rin과 공식적인 제휴, 후원 또는 협력 관계가 없습니다.
- 원본 콘텐츠의 이용 및 2차창작물의 배포에 관한 자세한 사항은 해당 공식 2차창작 가이드라인을 참고하시기 바랍니다.

---

This project is a fan-made derivative work created in accordance with the applicable fan-work guidelines.

The `.wav` audio assets used in this project are based on audio associated with **Rin Aokumo**, a talent affiliated with **STELLIVE**.

The original audio was **extracted from approximately the 28:20 mark of a livestream archive posted on the replay/archive channel.**

- All rights to the original audio and related intellectual property belong to their respective copyright holders.
- This project does not claim ownership of the original audio or source material. The audio is used solely for the purpose of this fan-made derivative work.
- This project is not officially affiliated with, endorsed by, sponsored by, or otherwise associated with STELLIVE or Rin Aokumo.
- Please refer to the applicable official fan-work guidelines for further information regarding the use and distribution of derivative works.