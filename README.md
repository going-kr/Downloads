# Sen Downloads

Sen 제품군 자료 배포용 저장소입니다. 외부에 공유하는 다운로드 링크는 항상 최신 자료를 받을 수 있도록 `public/downloads` 아래의 제품 폴더 루트를 기준으로 운영합니다.

## 공개 자료실과 링크 확인

- 공개 자료실: https://going-kr.github.io/Downloads/
- 사람이 확인하는 전체 자료 목록: `public/index.html`
- 제품별 파일명과 링크: `public/downloads/<제품명>/release.json`

공유용 전체 주소는 공개 자료실 주소 뒤에 `downloads/<제품명>/<파일명>`을 붙입니다.

## 기본 원칙

- 제품별 최신 자료는 각 제품 폴더 루트에 둡니다.
- 외부에 공유한 링크를 유지하려면 파일명을 바꾸지 말고 파일만 교체합니다.
- 과거 자료가 필요하면 각 제품의 `_archive` 폴더에 날짜와 버전으로 보관합니다.
- 파일명은 URL 안정성을 위해 영문 소문자, 숫자, 하이픈(`-`)을 권장합니다.

## 기본 링크 예시

```text
https://going-kr.github.io/Downloads/downloads/zpi-io8r/manual.pdf
https://going-kr.github.io/Downloads/downloads/go-rp2350-cb04t04/pcb-layout.pdf
https://going-kr.github.io/Downloads/downloads/go-rp2350-cb04t04/schematic.pdf
```

## 배포 절차

1. 기존 자료를 남길 필요가 있으면 `_archive/YYYY-MM-DD_vX.Y.Z/` 폴더를 만들고 현재 파일을 복사합니다.
2. 제품 폴더 루트의 파일을 최신 파일로 교체합니다.
3. 파일 구성이 바뀌었으면 해당 폴더의 `README.md`와 `release.json`을 수정합니다.
4. 새 제품이나 자료가 추가되었으면 `public/index.html`과 `public/downloads/README.md`를 수정합니다.
5. 변경 사항을 확인한 뒤 커밋하고 `master` 브랜치에 푸시합니다.

## 버전 표기

```text
v1.0.0  큰 구성 변경 또는 최초 배포
v1.1.0  내용 추가, 자료 세트 변경
v1.1.1  오타 수정, 이미지 교체, 작은 문구 수정
```
