# GO-Pi-Zero-Main

게시 전 검토 필요: 원본에 임시·미확인 사양이 포함된 초안입니다. 검토 항목은 `90_내부검토_게시금지` 폴더를 참고하세요.

- 원본 식별자: GO-Pi-Zero-Main
- 홈페이지 분류: 라즈베리파이 · CAN 확장
- 제품군: Senbrix
- 권장 페이지 경로: `/products/go-pi-zero-main/`
- 대표 이미지: `03_웹게시용자료/downloads/go-pi-zero-main/product-front.png`
- 설명서 링크: https://going-kr.github.io/Downloads/downloads/go-pi-zero-main/manual.pdf

## 제품 한 줄 소개

라즈베리파이 Zero 2 장착 메인보드 — 유선 이더넷 · SUB 보드용 CAN 확장 버스 · 절연 RS-485

## 주요 특징 (검토용 초안)

- 라즈베리파이 Zero 2 장착 40핀 헤더, 보드에서 파이로 5V 공급
- 유선 이더넷 — W5500 + RJ45 (LINK · ACT LED)
- CAN (MCP2515) — 16핀 확장 버스로 SUB 보드 연결
- 절연 RS-485 1채널 (CH0) — 절연 전원 + 포토커플러
- BCD 로터리 스위치 2개(10의 자리·1의 자리), SET/MODE 버튼
- DC 전원 입력 → 절연 DC-DC 5V · 3.3V LDO, 역전압·서지 보호

## 사양표 (검토용 초안)

| 항목 | 내용 |
|---|---|
| 모델 | GO-Pi-Zero-Main |
| CPU | 라즈베리파이 Zero 2 장착형 (40핀 헤더) |
| 입력 전원 | DC 24V |
| 내부 전원 | 5V (절연 DC-DC 모듈) · 3.3V (LDO) |
| 이더넷 | W5500, RJ45 1포트 |
| CAN | 1채널, 확장 버스로 SUB 보드 연결 |
| CAN 속도 | 500 kbps (SUB 보드 펌웨어 설정) |
| RS-485 | 1채널, 절연 (CH0) |
| 확장 버스 | 2mm 2×8 직각 소켓 — CAN · I2C(5V) · 전원 |
| 스위치 | BCD 로터리 2개 · SET/MODE 버튼 |
| 상태 표시 | CAN · RS-485 송수신 LED, 절연 전원 LED |
| 사용 온도 · 습도 | −10 ~ 50°C · 10 ~ 95% RH (결빙 없음) |
| 크기 | 75 × 81 mm |

## 단자·회로·조작 상세

같은 이름의 JSON에 pins, terminals, circuits, controls 데이터가 들어 있습니다. 설명서 편집 HTML에서도 원래 구성을 확인할 수 있습니다.
