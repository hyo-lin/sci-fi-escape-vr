# 🚀 Escape Bomb of Sci-fi (EBS)

> "위험한 공상과학 세계에서 탈출하라!"

**Escape Bomb of Sci-fi**는 플레이어가 공상과학 세계 속 3개의 스테이지를 통과하며 폭탄을 설치하고 현실 세계로 탈출하는 **스릴러·역동적인 VR 탈출 게임**입니다.  

팀원: 이효린, 김다빈, 조수민

---

## 🎮 게임 개요

- **장르:** 스릴러 / 액션 / 퍼즐
- **플랫폼:** Unity VR
- **컨셉:** 공상과학 세계에서 정해진 미션을 수행하고 최종적으로 로봇이 지키는 창고에서 폭탄을 설치해 현실로 탈출하는 게임
- **조작 방식:**
  - WASD: 이동
  - G: 물체 잡기 (Grab)
  - Ty: 컨트롤러 방향 제어
  - UI 버튼으로 다음 씬 이동 및 종료

---

## 🧠 게임 스토리 및 목표

- Player는 어느 날 갑자기 미지의 공상과학 세계에 눈을 뜨게 됩니다.
- **3개의 스테이지**를 클리어하고 로봇이 지키는 공간에서 폭탄을 설치하여 **현실 세계로 복귀**하는 것이 최종 목표입니다.

---

## 🧩 게임 규칙 및 구성

| STAGE | 내용 | 규칙 | 보상 |
|-------|------|------|------|
| **Stage 1** | 에너지셀 보관실 | 5개의 에너지셀 수집 후 활성화 칩을 획득하여 문을 연다 | 다음 스테이지 진입 |
| **Stage 2** | 실험실 | 8개의 핑크 오브젝트를 찾아서 철장 문과 대문을 연다 | 다음 스테이지 진입 |
| **Stage 3** | 폭탄 창고 | 로봇들을 피하며 폭탄을 찾아 정해진 위치에 설치 | 게임 엔딩 |

- **공통 규칙:** 지정된 공간에 특정 물체들을 정확히 놓아야 목표 달성
- **제한 시간:** Stage 1, 2에 적용 (UI 타이머 표시)
- **게임 오버:** Stage 3에서 로봇과 충돌 시

---

## 🎨 공간 및 디자인 특징

### Opening
- 신비한 이펙트 + 책 애니메이션으로 스토리 설명
- Grab 시 UI 팝업 → 8초 후 스테이지 소개

### Stage 1
- 실험실 분위기, 기계 소리 강조
- 무중력 느낌의 오브젝트
- 유리창 밖 눈 내리는 효과

### Stage 2
- 음산한 분위기의 랩실
- 인체 해부도 바닥, 녹슨 캐비닛, 빈 침대 등 배치
- 카펫 충돌 효과 + 이중 문 열림 시스템

### Stage 3
- 거대 창고 + 로봇 순찰
- 충돌 시 물리적 반응 (박스 튕김)
- 보라색 워프 이펙트

### Ending
- 따뜻한 음악과 함께 머그컵 grab → UI 등장

---

## 🖥️ 주요 기능

- Grab Interaction
- Direct Interaction
- AI Navigation (Stage 3)
- 충돌 이펙트 및 파티클 연출
- Stage Clear / Fail 시 UI 처리
- 시간제한 / 오브젝트 수 추적 UI
- UI 기반 씬 전환 버튼 및 종료 기능

---

## 🔊 사운드 디자인

- **Opening:** 신비로운 BGM
- **Stage 1:** 기계음 + 오브젝트별 피드백
- **Stage 2:** 호러 BGM + grip/drop 효과음
- **Stage 3:** 전자음 기반 긴장감 조성
- **Ending:** 편안한 분위기의 마무리

---

## 🧰 사용 에셋 목록

- **Opening**: JustPlay, Magic Effects FREE  
- **Stage 1**: SCI-FI Barrels 40 Sample, scifiProps, sci-fi small sound pack  
- **Stage 2**: Western Audio&Music, Hit Effects FREE, Horror Elements, Free Laboratory Pack, Hospital Horror Pack, Abandoned Asylum  
- **Stage 3**: Sentry Robot, Yughues Free Bombs, Sci-Fi Construction Kit  
- **Ending**: Interior House Assets  



---

## 🧪 개발 화면 (스크린샷)

 ![image](https://github.com/user-attachments/assets/485446aa-2972-4eaa-998b-5daddd82a29d)
![image](https://github.com/user-attachments/assets/73fd230b-b3da-461d-adeb-162837739bf0)
![image](https://github.com/user-attachments/assets/51315db8-2b34-4498-b250-b67094b0fac7)

## 🕹️영상
게임 프롤로그
![vr1](https://github.com/user-attachments/assets/4d74db3d-4af8-46fb-ad53-54fca4606c1d)

Stage 1
![vr2](https://github.com/user-attachments/assets/49e7fb7c-48cb-4603-a366-a51086abef66)

Stage 2
![vr3](https://github.com/user-attachments/assets/f09202b8-e92e-43f0-8eb9-0d3c6755a3f7)

Stage 3
![vr4](https://github.com/user-attachments/assets/53abdc25-e524-40c0-bc2b-20a64e6e5cd7)
