# 🧟 BIOHAZARD: SMART-GUN FPS (4-PLAYER CO-OP)

> **스마트폰을 실제 무선 총기(Gun Controller)로 들고 화면을 겨누어 좀비를 처치하는 아케이드 3D 레일건 FPS 게임입니다.**  
> 별도의 앱 설치 없이 스마트폰 브라우저(Safari / Chrome)의 고정밀 자이로스코프 센서만으로 화면을 정밀 조준하고 사격할 수 있습니다.

---

## 🌐 바로 플레이하기 (Live Links)

- **🖥️ PC 게임 메인 화면**: [https://biohazard-gun-fps.onrender.com](https://biohazard-gun-fps.onrender.com)
- **📱 스마트폰 건 컨트롤러**: [https://biohazard-gun-fps.onrender.com/controller.html](https://biohazard-gun-fps.onrender.com/controller.html)
- **🐙 GitHub 공식 저장소**: [https://github.com/minwoo19930301/biohazard-gun-fps](https://github.com/minwoo19930301/biohazard-gun-fps)

> 💡 **접속 방법**: PC 화면에 표시되는 **QR 코드를 스마트폰 카메라로 스캔**하거나 위 모바일 링크로 직접 접속하시면 1P ~ 4P로 자동 배정됩니다.

---

## 🎮 핵심 기능 (Key Features)

### 1. 📱 100% 모바일 자이로 조준 (Zero Mouse Aiming)
- **자유 에임 후버**: 폰을 연결하자마자 번거로운 과녁 강제 없이 **화면에 내 크로스헤어가 즉시 나타나** 폰 방향을 실시간으로 추적합니다.
- **화면 전체 방아쇠**: 모바일 화면 아무 곳이나 터치하면 즉시 총탄 발사 (화면 반동 및 총구 화염 연동).
- **슬라이드 당기기 제스처 & 틸트 장전**:
  - 화면을 **아래로 쓸어내리는 슬라이드 당기기(Rack Slide)** 제스처 (`dy > 45px`).
  - 오락실 건슈팅 스타일의 **스마트폰 각도 꺾기/틸트 모션**.
  - 게임 시작 전 스마트폰에서 직접 장전을 테스트할 수 있는 **실시간 장전 인식 가이드** 탑재.
- **좌우 반전 토글**: 필요에 따라 폰에서 원터치로 `[↔️ 좌우 반전: ON/OFF]` 전환 가능.

### 2. 🎬 다이나믹 3D 카메라 & 3인칭 CCTV 컷씬 + 무전 브리핑
- **4대 섹터 레일 슈터**:
  - **SECTOR 1**: 바이오 격리 복도 (CAM-01 • SECTOR-A AIRLOCK)
  - **SECTOR 2**: B2 유전자 배양 실험동 (CAM-02 • BIO-CULTURE LAB)
  - **SECTOR 3**: B3 원자로 용해로 챔버 (CAM-03 • REACTOR CHAMBER)
  - **SECTOR 4**: 옥상 긴급 헬리패드 (CAM-04 • ROOFTOP HELIPAD)
- **시네마틱 연출**: 섹터 전환 시 80px 블랙 레터박스가 내려오며 **3인칭 천장 보안 감시 카메라 앵글(REC 점멸, 스캔라인, 실시간 타임스탬프)**로 전환.
- **군용 무전 브리핑**: 무전 비프음(`radio_beep`)과 노이즈 효과음과 함께 전술 지휘부(HQ) 및 구조 헬기 조종사 상황 브리핑 자막 송출 후 1인칭 FPS 시점으로 다이나믹 하강 스웁(Swoop).
- **보이지 않는 피격 버그 방지**: 섹터 전환 시 이전 구역의 모든 적 및 독액 투사체 즉시 전량 소멸, 플레이어 정면 가시 영역만 타격 판정.

### 3. 🧟 유기적 3D 몬스터 5종 & 인체 해부학적 모델링
- **마인크래프트 박스 모델 탈피**: 관절형 실린더와 구체, 벌어진 턱뼈와 내부 구강, 붉은/초록 안광을 결합한 생체 호러 모델링.
- **초중장갑 블로터 (탱크 좀비)**: 거대하게 팽창된 복부와 온몸에 6개의 맹독 농포가 돋아난 초대형 헤비 좀비 (`HP 420`, `Speed 0.85`, 스폰 시 묵직한 포효 사운드).
- **천장 기습 크롤러**: 천장에 거꾸로 매달려 기어오다가 플레이어 근처에서 바닥으로 낙하 기습.
- **산성액 스피터**: 원거리에서 녹색 독액 구체를 투척 (날아오는 독액을 총으로 공중 요격 가능!).
- **지그재그 회피 러너**: 좌우 와리가리 스텝을 밟으며 조준을 교란 (`Speed 2.6`, 회피 폭 `1.1m` 밸런스 조정).
- **거대 브루트**: 높은 체력과 파괴적인 공격력을 가진 타이런트 형 보스급 몬스터.

### 4. 👥 최대 4인 동시 멀티플레이어 협동 (4-Player Co-Op)
- 접속 순서대로 고유 플레이어 자동 배정:
  - 🔴 **1P**: RED (`#ef4444`)
  - 🔵 **2P**: BLUE (`#06b6d4`)
  - 🟡 **3P**: YELLOW (`#eab308`)
  - 🟢 **4P**: GREEN (`#22c55e`)
- **개별 크로스헤어**: 4명의 플레이어 조준점이 각자 고유 색상 및 번호 태그와 함께 모니터에 실시간 표시.
- **상단 Co-Op 스코어보드**: 각 플레이어별 킬 점수와 콤보가 실시간 카드로 집계.
- **개별 피격 판정**: 각 플레이어가 겨눈 지점으로 독립 발사되며, 헤드샷/독액 요격 시 사격한 플레이어 고유 색상의 배너 출력.

### 5. ⚡ 광범위 실시간 감도 튜닝 & 테스트 과녁
- **원터치 프리셋**: 책상 근거리(`0.35x` ~ `0.65x`), 표준 모니터(`1.00x`), 거실 대형 TV(`2.80x` ~ `4.50x`).
- **정밀 감도 슬라이더**: `0.1x`부터 `5.0x`까지 실시간 드래그로 미세 조절.
- **손목 회전 각도 폭 조절**: 화면 양끝에 도달하기 위한 폰 회전각 설정 (`좁은 각도 ±18°`, `보통 ±28°`, `넓은 각도 ±42°`).
- **🎯 인터랙티브 모니터 과녁 띄우기**: 폰에서 버튼을 누르면 PC 모니터에 5개의 테스트 과녁이 나타나 회전 각도와 감도를 즉시 테스트.

---

## 🚀 CI/CD 자동화 파이프라인 (Auto-Merge & Auto-Deploy)

1. **GitHub Actions PR 자동 머지 (`.github/workflows/auto-merge.yml`)**:
   - `main` 브랜치를 향해 Pull Request가 생성되거나 업데이트되면 GitHub Actions가 자동으로 검토 후 즉시 머지합니다.
2. **Render 실시간 자동 무중단 배포**:
   - `main` 브랜치에 코드가 푸시되거나 머지되는 즉시 Render가 새 커밋을 감지(`trigger: new_commit`)하여 실서버에 자동으로 무중단 빌드 & 배포를 진행합니다.

---

## 🛠️ 기술 스택 (Tech Stack)

- **Backend**: Node.js, Express, Socket.IO
- **3D Graphics**: Three.js, WebGL
- **Audio Engine**: Web Audio API (외부 파일 없는 고성능 실시간 사운드 신디사이징)
- **Sensor Protocol**: iOS Safari / Android Chrome `DeviceOrientationEvent` & `DeviceMotionEvent` (Quaternions 3D 헤딩 변환)
- **CI/CD & Deployment**: GitHub Actions, Render Cloud Platform

---

## 💻 로컬 실행 방법 (Local Setup)

```bash
# 1. 저장소 클론
git clone https://github.com/minwoo19930301/biohazard-gun-fps.git
cd biohazard-gun-fps

# 2. 의존성 설치
npm install

# 3. 로컬 서버 실행
npm start
```
- 브라우저에서 `http://localhost:3000` 접속
