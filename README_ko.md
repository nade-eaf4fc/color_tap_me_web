# 컬러 Tap me 이미지 생성기

[日本語](README.md) | [English](README_en.md) | [中文](README_zh.md) | [한국어](README_ko.md)

X(구 Twitter)의 "Tap me" 컬러 이미지를 생성하는 브라우저 기반 도구입니다.

**→ [도구 열기](https://nade-eaf4fc.github.io/color_tap_me_web/)**

![스크린샷](img/screenshot.png)

---

## 예시

| 원본 | 결과 1 (감마 없음) | 결과 2 (감마 = 5) |
|--------|---------|----------|
| ![Before](img/woman_with_a_parasol_-_madame_monet_and_her_son_1983.1.29_short1920.jpg) | ![After1](img/apply_gamma/woman_with_a_parasol_-_madame_monet_and_her_son_1983.1.29_short1920_processed_gamma=0.png) | ![After2](img/apply_gamma/woman_with_a_parasol_-_madame_monet_and_her_son_1983.1.29_short1920_processed_gamma=5.png) |

→ [예시 트윗 보기](https://x.com/dare_aka2/status/2044358889244885471)

---

## 감마 보정 효과

감마 보정을 적용하면 어두운 이미지에서도 색상 정보를 보존하기 쉬워집니다.

| 감마 보정 없음 (gamma = 0) | 감마 보정 있음 (gamma = 5) |
|---|---|
| ![gamma=0](img/apply_gamma/woman_with_a_parasol_-_madame_monet_and_her_son_1983.1.29_short1920_processed_gamma=0.png) | ![gamma=5](img/apply_gamma/woman_with_a_parasol_-_madame_monet_and_her_son_1983.1.29_short1920_processed_gamma=5.png) |

---

## 사용 방법

1. 페이지에 접속합니다
2. 이미지를 드래그 앤 드롭하거나, 클릭하여 PNG / JPG / WebP 파일을 선택합니다
3. **처리** 버튼을 누릅니다
4. 처리된 이미지를 확인하고 **이미지 저장**을 클릭하여 다운로드합니다
5. X에 게시합니다

### X 게시 가이드라인

- 단일 이미지의 경우 **2:1 ~ 3:4** 비율이 최고로 표시됩니다
- 한 변이 **2048px 이상**이면 더 잘 작동합니다
- **4096px를 초과**하면 X의 압축으로 인해 색상이 보일 수 있습니다

---

## 면책사항

- 표시 환경, 모니터, OS, 애플리케이션 등 다양한 요소의 영향으로 모든 환경에서 같은 결과가 나올 수 없습니다.
- 모든 이미지 처리는 브라우저에서 로컬로 실행됩니다. 업로드된 이미지는 서버로 전송되거나 저장되지 않습니다.
- 본 도구 사용으로 인한 어떠한 손실이나 피해에 대해서도 제작자는 책임을 지지 않습니다.

---

## 예시 이미지

**Claude Monet**, *Woman with a Parasol – Madame Monet and Her Son* (1875)

- **출처:** National Gallery of Art / Wikimedia Commons
- **출처 URL:** https://www.nga.gov/artworks/61379-woman-parasol-madame-monet-and-her-son
- **권리 상태:** 퍼블릭 도메인 / CC0 오픈 액세스 이미지
- **수정 사항:** 리포지토리 예시용으로 리사이즈
- **크레딧:** Courtesy National Gallery of Art, Washington

---

## 라이센스

MIT License © [@dare_aka2](https://x.com/dare_aka2) & [@nade_eaf4fc](https://x.com/nade_eaf4fc)
