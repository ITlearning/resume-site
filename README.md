# Resume Site

`resume-site/index.html`은 공용 배포용 이력서 페이지입니다.

## Local Preview

```bash
cd resume-site
python3 -m http.server 4173
```

브라우저에서 `http://localhost:4173` 접속

## PDF Export

1. 브라우저에서 페이지 열기
2. 인쇄 (`Cmd/Ctrl + P`)
3. 용지: A4
4. 배율: 100% (필요 시 97%)
5. 여백: 기본 또는 최소

## GitHub Pages Deploy

이 저장소의 `main` 브랜치에 `resume-site/` 변경을 push 하면
`.github/workflows/deploy-pages.yml`이 자동 배포합니다.

### GitHub Pages 초기 설정(한 번만)

1. Repository `Settings -> Pages`
2. Source: `GitHub Actions` 선택

