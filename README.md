# medicube PDRN Pink Collagen Exosome Shot — DE

메디큐브 PDRN 핑크 콜라겐 엑소좀 샷 앰플 7500, 독일 시장용 상세페이지 리뉴얼 제안.
포트폴리오 목적의 비공식 작업물입니다.

## 구성

| 파일 | 내용 |
|---|---|
| `index.html` | 페이지 본체 (28KB) |
| `assets/Gm_01~06` | 섹션별 디자인 이미지 |
| `assets/mv_loop.mp4` | 섹션 3 제형 영상 (이음매 없는 루프) |
| `assets/frames/` | 제형 인터랙티브 뷰어 프레임 90장 |

## 구현 요소

- **인터랙티브 제형 뷰어** — 드래그·스와이프로 프레임 스크럽, 미조작 시 자동 재생
- **아코디언** — `<details>` 시맨틱 마크업, 키보드·스크린리더 지원
- **사용주기 캘린더** — 고농도 사용일 순차 점등 (CSS 애니메이션)
- **번역 바** — 스크롤 위치에 따라 현재 섹션의 한국어 번역 자동 전환
- 반응형, 키보드 포커스, `prefers-reduced-motion` 대응

## GitHub Pages 배포

1. 새 저장소 생성 (Public)
2. 이 폴더의 내용을 저장소 루트에 업로드
3. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / 폴더 `/ (root)` → Save
4. 1~2분 후 `https://<아이디>.github.io/<저장소명>/` 에서 확인
