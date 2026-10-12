# CHRONOSTASIS

> 움직이면 시간이 멈추고, 멈추면 시간이 흐른다.

게임 디자인 과제로 만든 게임 **Chronostasis**의 소개 웹사이트와 베타 플레이 페이지입니다.
페르소나 4 리바이벌 / 페르소나 3 리로드 공식 사이트의 분위기를 참고했습니다.

## 페이지

| 파일 | 내용 |
| --- | --- |
| `index.html` | 메인 사이트 — 로딩 · 메인 · ABOUT · STORY · SYSTEM · CHARACTER · 베타 플레이 |
| `character.html` | 캐릭터 자세히 보기 (`character.html#01` ~ `#07`) |
| `beta.html` | 웹 게임 베타 — 3인칭 WASD 이동, 움직이면 시간 정지(파랑) / 멈추면 시간 흐름(빨강) |

## 실행

`index.html`을 브라우저로 열면 됩니다. 서버나 설치가 필요 없고, 인터넷이 없어도 동작합니다(글꼴만 온라인에서 불러옵니다).

GitHub Pages로 배포하려면 저장소 **Settings → Pages**에서 브랜치를 `main`, 폴더를 `/ (root)`로 지정하세요.

## 베타 조작법

| 키 | 동작 |
| --- | --- |
| W A S D | 이동 |
| Shift | 달리기 |
| 마우스 | 시점 회전 (화면 클릭 후) |
| 휠 | 카메라 거리 |
| Esc | 마우스 풀기 |

## 폴더 구조

```
├─ index.html
├─ character.html
├─ beta.html
└─ assets/
   ├─ images/   캐릭터·시스템·메뉴 그림
   ├─ videos/   메인 캐릭터·파편·하늘 배경 영상
   ├─ js/       three_bundle.js(3D 엔진) · heroine_glb.js(캐릭터 모델)
   └─ models/   Heroine.glb (캐릭터 모델 원본)
```

## 사용한 것

- [three.js](https://threejs.org) r169 (MIT License) — `assets/js/three_bundle.js`
- 글꼴: Barlow (Google Fonts), VitroPRIDE (눈누)
