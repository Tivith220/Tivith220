<!-- ================================================= -->
<!--          GITHUB PROFILE README — MASS EDITION    -->
<!-- ================================================= -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F7FF,100:FF00E5&height=180&section=header&text=Tivith%20B&fontSize=50&fontColor=FFFFFF&animation=fadeIn&fontAlignY=35" />
</p>

<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Tivith+%F0%9F%91%8B;I+build+safety+%26+verification+systems;Welcome+to+my+GitHub+%F0%9F%9A%80" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="400">
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Tivith220&label=Profile%20Views&color=00f7ff&style=flat" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/Tivith220?label=Followers&style=social" alt="Followers" />
</p>

---

## 🧑‍💻 About Me

- 🔭 Currently building **document verification & safety-tech systems**
- 🛡️ Recent work: **Checkey-5** (government document verifier) & **SafeHUD** (door anti-trap safety simulation)
- 🌱 Exploring new ideas across **web + simulation projects**
- 📫 Reach me: **tkumarml@gmail.com**

### 📌 Featured Projects

| Project | Description |
|---|---|
| [**Checkey-5**](https://github.com/Tivith220/Checkey-5) | A government-issued document verifier |
| [**SafeHUD**](https://github.com/Tivith220/SafeHUD) | A safety-concerned door anti-trap system simulation |
| [**redlightgreenlight**](https://github.com/Tivith220/redlightgreenlight) | OpenENV based project |
| [**veil**](https://github.com/Tivith220/veil) | CSS-based project |

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,react,nodejs,python,java,html,css,git,github,figma,vscode&theme=dark" />
</p>

---

## 🟡 Contribution Pac-Man (Live Moving Animation)

<p align="center">
  <img src="https://raw.githubusercontent.com/Tivith220/Tivith220/output/pacman-contribution-graph.svg" />
</p>

> ⚠️ Idhu **real moving animation** — setup pannanum (steps kடைசில irukku), illana image kaamikathu

---

## 🏆 Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Tivith220&theme=dracula&row=1&column=6&margin-w=10&margin-h=10&no-frame=true&no-bg=false" />
</p>

## ⚡ Activity Graph — Neon Cyberpunk

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Tivith220&custom_title=Contribution%20Grid&bg_color=0D1117&color=00F7FF&line=FF00E5&point=FFFFFF&area=true&area_color=00F7FF&hide_border=true&hide_title=false" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Tivith220&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tivith220&layout=compact&theme=radical&hide_border=true&bg_color=0D1117" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Tivith220&theme=radical&hide_border=true&background=0D1117" />
</p>

---

## 🔗 Connect With Me

<p align="center">
  <a href="https://linkedin.com/in/YOUR_LINKEDIN" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://instagram.com/YOUR_INSTA" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>
  <a href="mailto:tkumarml@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF00E5,100:00F7FF&height=100&section=footer" />
</p>

<!-- ================================================= -->
<!--            PAC-MAN ANIMATION SETUP GUIDE          -->
<!-- ================================================= -->

<!--
🟡 PAC-MAN SETUP STEPS (REQUIRED for the animation above to show):

1. Go to github.com/Tivith220/Tivith220
2. Click "Actions" tab
3. Click "set up a workflow yourself"
4. Rename the file to: pacman.yml  (must be inside .github/workflows/)
5. Delete everything in the editor, paste this:

name: generate arcade contribution graphs
on:
  schedule:
    - cron: '0 0 * * *'
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 20
    steps:
      - name: generate contribution graph SVG
        uses: abozanona/pacman-contribution-graph@main
        with:
          github_user_name: Tivith220
          games: 'pacman'
      - name: push SVG to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

6. Click "Commit changes"
7. Go back to "Actions" tab -> click the workflow name on the left
   -> click "Run workflow" button -> confirm
8. Wait 1-2 mins, refresh your profile page -> Pac-Man animation appears

⚠️ COMMON REASON IT DOESN'T SHOW:
- The workflow hasn't been manually run yet (step 7 is required the FIRST time)
- The "output" branch doesn't exist yet — it gets auto-created after step 7 runs successfully
- Check the Actions tab for a red ❌ — click it to see the error log if it failed
-->
