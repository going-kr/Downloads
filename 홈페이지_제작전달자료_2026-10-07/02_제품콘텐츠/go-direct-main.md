# GO-DIRECT-MAIN

게시 전 검토 필요: 원본에 임시·미확인 사양이 포함된 초안입니다. 검토 항목은 `90_내부검토_게시금지` 폴더를 참고하세요.

- 원본 식별자: GO-DIRECT-main
- 홈페이지 분류: GO-DIRECT 시스템
- 제품군: GO-DIRECT 시스템
- 권장 페이지 경로: `/products/go-direct-main/`
- 대표 이미지: `03_웹게시용자료/downloads/go-direct-main/product-front.png`
- 설명서 링크: https://going-kr.github.io/Downloads/downloads/go-direct-main/manual.pdf

## 제품 한 줄 소개

RP2040 기반 GO-DIRECT 메인 보드 — 이더넷 · RS-485 2채널 · 확장 I2C 버스 2계통

## 주요 특징 (검토용 초안)

- RP2040 MCU + 16MB 플래시, USB-B 로 프로그램 다운로드
- 이더넷 — WIZ850io 모듈(W5500 · RJ45 일체형) SPI 연결
- RS-485 2채널, 채널 단자마다 +24V 전원 출력 핀 · TX/RX LED
- 포토커플러 절연 스위치 입력 3점 (비상 · UP · D.N), 입력별 LED
- 확장 I2C 버스 2계통 — 기계장치(6핀) · RD장치(5핀)로 확장 보드 연결
- 로터리 스위치 2개(장치갯수 · 장치모드), FRAM, 리셋 감시 IC

## 사양표 (검토용 초안)

| 항목 | 내용 |
|---|---|
| 모델 | GO-DIRECT-MAIN |
| CPU | RP2040 (12MHz 크리스털) |
| 메모리 | 플래시 16MB · FRAM |
| 입력 전원 | DC 24V |
| 이더넷 | WIZ850io 모듈 (W5500, RJ45 일체형) |
| RS-485 | 2채널, 비절연 (단자에 +24V 출력) |
| 디지털 입력 | 3점, 포토커플러 절연 · 무전압 접점 |
| 기계장치 버스 | I2C 6핀 — GO-DIRECT-CB3 |
| RD장치 버스 | I2C 5핀 — GO-STAGE-RD8 · SW5 |
| 확장 보드 전원 | 버스 커넥터로 공급 (+5V · VDD) |
| DMX-SW 단자 | 선택 출력 3 · 아날로그 입력 3 |
| 설정 스위치 | 로터리 2개 (장치갯수 · 장치모드) |
| 프로그램 | USB-B (USB DownLoad) |
| 사용 온도 · 습도 | −10 ~ 50°C · 10 ~ 95% RH (결빙 없음) |
| 고정홀 | 4개, 지름 3.5mm |
| 크기 | 92 × 87 mm |

## 단자·회로·조작 상세

같은 이름의 JSON에 pins, terminals, circuits, controls 데이터가 들어 있습니다. 설명서 편집 HTML에서도 원래 구성을 확인할 수 있습니다.
