# 안전 패스 퀘스트

50~60대 현장 근로자를 위한 **7단계 산업안전 교육 게임** (`index.html` + `js/quiz-sets.js`).

## 실행

### GitHub Pages (온라인)

배포 주소: **https://jdjhzero-design.github.io/safetyrules7/**

처음 404가 나오면:

1. [저장소 Settings → Pages](https://github.com/jdjhzero-design/safetyrules7/settings/pages) 이동
2. **Build and deployment** → Source: **GitHub Actions** 선택
3. **Actions** 탭에서 `Deploy to GitHub Pages` 워크플로가 완료될 때까지 1~3분 대기

### 로컬

`index.html`을 브라우저에서 더블클릭하거나:

```powershell
start d:\game\safetyrules7\index.html
```

## 게임 흐름 (7단계 × 학습 1회 + 퀴즈 2문제)

1. **눈도장 공부방** — 핵심 수칙 학습
2. **기본 문제 (1/2)** — 현장 상황 판단
3. **심화 문제 (2/2)** — 조금 더 까다로운 상황 (부분 준수·예외 판단)
4. 결과 팝업 → 다음 단계

총 **14문제** 전부 정답 시 **🏆 명예 안전소장** 화면 표시.

**처음부터 다시하기**를 누르면 문제 세트 A → B → C 순으로 바뀝니다 (각 세트 14문제, 내용 전부 다름).

## 7단계 주제

| 단계 | 주제 |
|------|------|
| 1 | TBM (아침을 여는 10분) |
| 2 | 달비계 |
| 3 | 밀폐공간 |
| 4 | 지붕수리 |
| 5 | 온열질환 |
| 6 | 이동식 사다리 |
| 7 | 예초기 |

## 기술

- `index.html` + `js/quiz-sets.js` (HTML + Tailwind CDN + Vanilla JS)
- 고령자 UX: 큰 글씨, 고대비, 원터치 버튼
- TTS 대비: `tts-readable`, `aria-live`, 시나리오/해설용 클래스명

## 참고

교육용 배포 시 `index.html`과 `js/quiz-sets.js`를 함께 복사하세요.
