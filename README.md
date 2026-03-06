# bbangtrailrun

빵트레일런

## Cloudflare Pages

이 프로젝트는 Next.js 정적 export(`output: "export"`)를 사용하므로 Cloudflare Pages에 배포할 수 있습니다.

### CLI 배포

```bash
npm run cf:login
npm run cf:build
npm run cf:deploy
```

### 로컬 미리보기

```bash
npm run cf:build
npm run cf:preview
```

### Cloudflare Dashboard 설정

- Framework preset: `None`
- Build command: `npm run build`
- Build output directory: `out`
