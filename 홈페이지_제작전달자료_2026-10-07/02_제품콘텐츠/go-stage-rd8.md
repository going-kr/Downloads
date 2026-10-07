# GO-STAGE-RD8

게시 전 검토 필요: 원본에 임시·미확인 사양이 포함된 초안입니다. 검토 항목은 `90_내부검토_게시금지` 폴더를 참고하세요.

- 원본 식별자: GO-STAGE-RD8
- 홈페이지 분류: GO-DIRECT 시스템
- 제품군: GO-DIRECT 시스템
- 권장 페이지 경로: `/products/go-stage-rd8/`
- 대표 이미지: `03_웹게시용자료/downloads/go-stage-rd8/product-front.png`
- 설명서 링크: https://going-kr.github.io/Downloads/downloads/go-stage-rd8/manual.pdf

## 제품 한 줄 소개

GO-DIRECT RD장치 확장 보드 — 릴레이 출력 8점 · 수동 DIP 스위치 · I2C 주소 설정

## 주요 특징 (검토용 초안)

- 메인 보드(GO-DIRECT-MAIN) RD장치 버스에 연결하는 I2C 확장 보드
- 릴레이 출력 8점 (1a 접점, 공통 COM 1개)
- 출력마다 동작 표시 LED, 전원 LED
- 8회로 DIP 스위치(Manual Switch) — ON 하면 해당 릴레이 수동 동작
- Board Number 로터리로 I2C 주소 설정 (0~7)
- 5핀 버스 커넥터 2개(병렬)로 다음 보드에 이어 연결

## 사양표 (검토용 초안)

| 항목 | 내용 |
|---|---|
| 모델 | GO-STAGE-RD8 |
| 확장 IC | PCF8574A (I2C 8비트 I/O 확장) |
| 연결 버스 | 메인 보드 RD장치 버스 (I2C, 5핀) |
| I2C 주소 | 0x38~0x3F (Board Number 0~7) |
| 입력 전원 | +5V — 메인 보드에서 공급 |
| 릴레이 출력 | 8점, 1a 접점 (공통 COM) |
| 접점 정격 | 5A 250VAC / 5A 30VDC |
| 제어 논리 | 확장 IC 출력 Low → 릴레이 ON |
| 수동 조작 | 8회로 DIP 스위치 (ON = 릴레이 ON) |
| 표시 LED | 출력 8 · 전원 1 |
| 사용 온도 · 습도 | −10 ~ 50°C · 10 ~ 95% RH (결빙 없음) |
| 고정홀 | 4개(지름 3.5mm) · 메인과 동일 |
| 크기 | 92 × 87 mm |

## 단자·회로·조작 상세

같은 이름의 JSON에 pins, terminals, circuits, controls 데이터가 들어 있습니다. 설명서 편집 HTML에서도 원래 구성을 확인할 수 있습니다.
