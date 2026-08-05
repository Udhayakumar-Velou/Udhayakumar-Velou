<!-- Terminal-window header (custom animated SVG, lives in /assets) -->
<p align="center">
  <img src="assets/terminal-header.svg" width="700" alt="Terminal header" />
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

### 🏆 Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Udhayakumar-Velou&theme=radical&no-frame=true&row=1&column=6" />
</p>

---

### 📈 Activity Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Udhayakumar-Velou&theme=redical&hide_border=true&area=true" width="90%" />
</p>

---

### 💬 Random Dev Quote

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" />
</p>

---

### 🎧 Now Playing on Spotify

> Live "currently playing" widget — needs a one-time ~10 min setup (deploying a small free service). Shows an animated bar with whatever track you're playing right now, falls back to your last played track otherwise.

<p align="center">
  <img src="https://novatorem-orpin-two.vercel.app/api/spotify" />
</p>

**Setup steps:**
1. Go to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard) → create an app → note the **Client ID** and **Client Secret**. Set the redirect URI to `https://developer.spotify.com/callback`.
2. Visit this URL (replace `YOUR_CLIENT_ID`), log in, and copy the `code` param from the redirected URL:
   `https://accounts.spotify.com/authorize?client_id=YOUR_CLIENT_ID&response_type=code&redirect_uri=https://developer.spotify.com/callback&scope=user-read-currently-playing,user-read-recently-played`
3. Exchange that `code` for a **refresh token** (there's a step-by-step guide in the [novatorem/spotify-github-profile README](https://github.com/novatorem/spotify-github-profile)).
4. Fork [novatorem/spotify-github-profile](https://github.com/novatorem/spotify-github-profile), deploy it to [Vercel](https://vercel.com) (free), and add `SPOTIFY_CLIENT_ID`, `SPOTIFY_CLIENT_SECRET`, and `SPOTIFY_REFRESH_TOKEN` as environment variables in your Vercel project settings.
5. Once deployed, replace the image URL above with `https://YOUR-VERCEL-PROJECT.vercel.app/api/spotify`.

---

### 🎵 My Playlist

> A static, clickable card for a specific playlist — click the cover to open it in Spotify. (Note: this is different from "Now Playing" above — it doesn't update live, it's just a nice badge for a playlist you want to showcase.)

<p align="center">
  <a href="https://open.spotify.com/playlist/4RYa7DVhzcL1BXby733p6j">
    <img src="https://img.shields.io/badge/Spotify-Listen%20to%20my%20playlist-1DB954?style=for-the-badge&logo=spotify&logoColor=white" />
  </a>
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
