# MAKE_ THE WORLD EXPO 2026 — 캠프 소개 · 브리핑 사이트

인문영재·영재키움 창의융합캠프 &lt;세상을 만드는 사람&gt; 박람회 홍보·브리핑용 원페이지입니다.
`index.html` 하나로 완결되어 있어(외부 라이브러리 없음) 어디서든 바로 열립니다.

## GitHub Pages로 게시하기 (이미 레포가 있는 경우)

1. 이 저장소 루트에 `index.html`을 넣고 커밋·푸시합니다.
   ```bash
   git add index.html
   git commit -m "Add MAKE_ THE WORLD EXPO landing page"
   git push
   ```
2. GitHub 저장소 → **Settings → Pages** 로 이동합니다.
3. **Build and deployment → Source** 를 `Deploy from a branch` 로 두고,
   **Branch** 를 `main` / `/ (root)` 으로 선택한 뒤 **Save**.
4. 1~2분 뒤 상단에 게시 주소가 나타납니다:
   `https://<사용자이름>.github.io/<저장소이름>/`

> 프로젝트 페이지가 아닌 대표 주소로 쓰려면 저장소 이름을
> `<사용자이름>.github.io` 로 만들면 `https://<사용자이름>.github.io/` 로 열립니다.

### 웹에서 바로 올리기 (터미널 없이)
저장소 페이지 → **Add file → Upload files** → `index.html` 드래그 → **Commit changes** →
위 2~4단계로 Pages 설정.

## 수정 방법
- 텍스트·색상·섹션은 `index.html` 안에서 바로 편집할 수 있습니다.
- 색상 팔레트는 파일 상단 `:root` 의 CSS 변수(`--blue`, `--green` 등)에서 한 번에 바꿀 수 있습니다.
- 링크 공유용 미리보기(카카오톡·문자)는 `<meta property="og:...">` 값을 수정하세요.

## 구성
소개 · 컨셉(세상을 만드는 사람) · 감성지능 교육법(SEL) · 3개 존 · 워크샵 흐름 ·
박람회(제작물·다섯 문장 릴레이) · 일정 · 스텝/브리핑 요약 · 푸터
