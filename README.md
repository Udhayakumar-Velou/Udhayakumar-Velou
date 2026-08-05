<!-- Animated wave header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFD700,100:FF4B4B&height=200&section=header&text=Hi,%20I'm%20Udhaya%20👋&fontSize=40&fontColor=ffffff&animation=fadeIn" />
</p>

<!-- Typing animation -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=FF4B4B&center=true&vCenter=true&width=500&lines=I+write+code.;Sometimes+it+works.;99%25+debugging%2C+1%25+typing.;Currently+hunting+a+data+science+internship." alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Udhayakumar-Velou&label=Profile%20Views&color=FF4B4B&style=flat" />
  <img src="https://img.shields.io/badge/Status-Debugging...-yellow?style=flat&logo=codeforces" />
</p>

---

### 🚀 About me

- 🎓 MSc Software Engineering & Data Science @ ESILV Paris
- 🔭 Repositioning from full-stack dev → Data Science / ML Engineering
- 🎯 Actively looking for a **6-month internship** in Data Science / ML
- 🧠 Recent work: Credit Risk Modeling (Scikit-learn, FastAPI, MLflow, Docker)
- 🌱 Currently exploring: MLOps, NLP, and secure software development
- 📫 Reach me: udhayakumar2352001@gmail.com | [LinkedIn](https://www.linkedin.com/in/udhayakumar-velou-758723172)

---

### 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,docker,vue,nestjs,postgres,git,java,spring" />
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Udhayakumar-Velou&show_icons=true&theme=radical&hide_border=true&count_private=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Udhayakumar-Velou&layout=compact&theme=radical&hide_border=true" width="40%" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Udhayakumar-Velou&theme=radical&hide_border=true" width="60%" />
</p>

---

### 🐍 Contribution Snake

This one's genuinely fun: a snake "eats" your green contribution squares and moves automatically every day via GitHub Actions.

1. Create `.github/workflows/snake.yml` in this repo with the workflow below.
2. It generates an SVG and commits it to an `output` branch automatically.
3. Embed it here once generated (placeholder below).

```yaml
name: generate animation
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Then embed it here:

```markdown
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Udhayakumar-Velou/Udhayakumar-Velou/output/github-contribution-grid-snake-dark.svg" />
  <img alt="snake" src="https://raw.githubusercontent.com/Udhayakumar-Velou/Udhayakumar-Velou/output/github-contribution-grid-snake.svg" />
</picture>
```

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF4B4B,100:FFD700&height=100&section=footer" />
</p>
