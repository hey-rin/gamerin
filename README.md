# 오목 한판

흑돌로 플레이하여 컴퓨터의 백돌보다 먼저 5개의 돌을 잇는 반응형 웹 오목 게임입니다.

## 주요 기능

- 15 × 15 바둑판, 플레이어 흑돌 선공
- 1단계(가볍게), 2단계(도전), 3단계(집중) AI
- 가로·세로·대각선 5목 자동 판정
- 시간 제한 없음
- 승리 5목 강조 및 화면 전체 축하 폭죽·빵빠레
- PC와 모바일 터치 지원

## 실행

설치 없이 `index.html`을 브라우저로 열면 됩니다.

## GitHub와 Vercel

```bash
git init
git add .
git commit -m "오목 게임 완성"
git branch -M main
git remote add origin https://github.com/사용자명/저장소명.git
git push -u origin main
```

Vercel에서 저장소를 연결한 뒤 Framework Preset은 **Other**, Build Command는 비우고 Output Directory는 `.`으로 설정해 배포하세요.
