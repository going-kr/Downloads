# GO-SUB-CB08

게시 전 검토 필요: 원본에 임시·미확인 사양이 포함된 초안입니다. 검토 항목은 `90_내부검토_게시금지` 폴더를 참고하세요.

- 원본 식별자: GO-SUB-CB08
- 홈페이지 분류: 라즈베리파이 · CAN 확장
- 제품군: Senbrix
- 권장 페이지 경로: `/products/go-sub-cb08/`
- 대표 이미지: `03_웹게시용자료/downloads/go-sub-cb08/product-front.png`
- 설명서 링크: https://going-kr.github.io/Downloads/downloads/go-sub-cb08/manual.pdf

## 제품 한 줄 소개

RP2040 기반 확장(SUB) 보드 — 절연 입력 4점 · 릴레이 출력 4점 · CAN 통신

## 주요 특징 (검토용 초안)

- 메인보드(GO-Pi-Zero-Main)에 이어 꽂는 CAN 확장 보드
- 포토커플러 절연 디지털 입력 4점 (공통 COM), 입력별 동작 LED
- 릴레이 접점 출력 4점 (1a, 공통 COM), 출력별 동작 LED
- ADDRESS 로터리 스위치로 보드 ID 설정
- 수·암 확장 커넥터로 확장 보드를 여러 장 이어 연결
- RP2040 MCU + 16MB 플래시, USB 로 펌웨어 다운로드

## 사양표 (검토용 초안)

| 항목 | 내용 |
|---|---|
| 모델 | GO-SUB-CB08 |
| CPU | RP2040 |
| 메모리 | 플래시 16MB |
| 입력 전원 | DC 5V (메인보드 확장 커넥터 또는 USB) |
| 디지털 입력 | 4점, 포토커플러 절연 (공통 COM) |
| 입력 정격 전압 | DC 24V (10mA 이하) |
| 릴레이 출력 | 4점, 1a 접점 (공통 COM) |
| 접점 정격 | 5A 250VAC / 5A 30VDC |
| 연결 방식 | GO-Pi-Zero-Main 에 16핀 2.0mm 커넥터로 연결 |
| 통신 | CAN 500kbps (입출력 상태 송수신) |
| 보드 ID | ADDRESS 로터리 스위치 (BCD) |
| 프로그램 | USB (펌웨어 다운로드) |
| 사용 온도 · 습도 | −10 ~ 50°C · 10 ~ 95% RH (결빙 없음) |
| 크기 | 51 × 81 mm |

## 단자·회로·조작 상세

같은 이름의 JSON에 pins, terminals, circuits, controls 데이터가 들어 있습니다. 설명서 편집 HTML에서도 원래 구성을 확인할 수 있습니다.
