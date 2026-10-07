# GO-DIRECT-CB3

게시 전 검토 필요: 원본에 임시·미확인 사양이 포함된 초안입니다. 검토 항목은 `90_내부검토_게시금지` 폴더를 참고하세요.

- 원본 식별자: GO-DIRECT-STAGE3
- 홈페이지 분류: GO-DIRECT 시스템
- 제품군: GO-DIRECT 시스템
- 권장 페이지 경로: `/products/go-direct-stage3/`
- 대표 이미지: `03_웹게시용자료/downloads/go-direct-stage3/product-front.png`
- 설명서 링크: https://going-kr.github.io/Downloads/downloads/go-direct-stage3/manual.pdf

## 제품 한 줄 소개

GO-DIRECT 기계장치 확장 보드 — UP/DOWN 릴레이 3채널 · 리밋 입력 6점 · OCR 입력 3점

## 주요 특징 (검토용 초안)

- 메인 보드(GO-DIRECT-MAIN) 기계장치 버스에 연결하는 I2C 확장 보드
- 릴레이 출력 6개 — 3채널 × UP · DOWN (1a 접점, 채널별 COM)
- 리밋 입력 6점 · OCR 입력 3점, 포토커플러 절연 · 입력별 LED
- 하드웨어 인터록 — 해당 방향 리밋 입력이 ON 일 때만 릴레이 동작
- Board Number 로터리로 I2C 주소 설정 (0~7)
- 6핀 버스 커넥터 2개(병렬)로 다음 보드에 이어 연결

## 사양표 (검토용 초안)

| 항목 | 내용 |
|---|---|
| 모델 | GO-DIRECT-CB3 |
| 확장 IC | MCP23017 (I2C 16비트 I/O 확장) |
| 연결 버스 | 메인 보드 기계장치 버스 (I2C, 6핀) |
| I2C 주소 | 0x20~0x27 (Board Number 0~7) |
| 입력 전원 | 메인 보드에서 공급 (+5V · VDD) |
| 릴레이 출력 | 6점 = 3채널 × UP · DOWN, 1a 접점 |
| 접점 정격 | 5A 250VAC / 5A 30VDC |
| 리밋 입력 | 6점, 포토커플러 절연 |
| OCR 입력 | 3점, 포토커플러 절연 |
| 입력 방식 | 무전압 접점 (보드에서 전원 공급) |
| 인터록 | 리밋 입력 ON 일 때만 해당 릴레이 동작 |
| 표시 LED | 상태 1 · 리밋 입력 6 · OCR 입력 3 |
| 사용 온도 · 습도 | −10 ~ 50°C · 10 ~ 95% RH (결빙 없음) |
| 고정홀 | 4개(지름 3.5mm) · 메인과 동일 |
| 크기 | 92 × 87 mm |

## 단자·회로·조작 상세

같은 이름의 JSON에 pins, terminals, circuits, controls 데이터가 들어 있습니다. 설명서 편집 HTML에서도 원래 구성을 확인할 수 있습니다.
