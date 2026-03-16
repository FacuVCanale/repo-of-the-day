<div align="center">

# Repo of the Day

**One repo. Every day. No noise.**

A dead-simple page that surfaces a single standout GitHub repository each day — picked from the freshest trending projects, zero clutter.

[**See today's pick →**](https://facuvcanale.github.io/repo-del-dia/)

---

<img src="https://img.shields.io/badge/dependencies-0-brightgreen" alt="zero dependencies">
<img src="https://img.shields.io/badge/framework-none-black" alt="no framework">
<img src="https://img.shields.io/github/deployments/FacuVCanale/repo-del-dia/github-pages?label=live&color=blue" alt="deploy status">

</div>

## How it works

1. Fetches the most starred repos created in the last 7 days via the GitHub Search API
2. Picks one deterministically using a date-based hash — everyone sees the same repo on the same day
3. Displays it. That's it.

Single HTML file. No build step. No backend. No tracking.

## Run locally

```bash
git clone https://github.com/FacuVCanale/repo-del-dia.git
open repo-of-the-day/index.html
```

## License

MIT
