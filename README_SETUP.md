# Hexo + Stellar quick setup

1. Edit `_config.yml`
   - `url: https://YOUR_GITHUB_ID.github.io` → your real GitHub id

2. Create GitHub repo
   - repo name must be: `YOUR_GITHUB_ID.github.io`

3. Push this project to that repo

4. In GitHub repo settings:
   - **Pages** → Source: `Deploy from a branch`
   - Branch: `gh-pages` / root

5. Push to `main` branch
   - GitHub Actions will build/deploy automatically.

## Local preview

```bash
npm install
npx hexo clean
npx hexo s
```

Open: http://localhost:4000
