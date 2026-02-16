<!-- ═══════════════════════════════════════════════════════════
     ⚙️  SETUP REQUIRED for two animated elements:
     1. Snake contribution animation  →  create file:
        .github/workflows/snake.yml   (content below in comments)
     2. 3D contribution graph         →  create file:
        .github/workflows/3d-contrib.yml  (content below in comments)
     Everything else renders immediately.
═══════════════════════════════════════════════════════════ -->

<!-- HEADER WAVE -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=6C63FF&height=140&section=header&text=Ahmed%20Tayebi&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Product%20Engineer%20%26%20UI%2FUX%20Designer&descAlignY=58&descSize=16&animation=fadeIn"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3500&pause=1000&color=6C63FF&center=true&width=600&height=45&lines=Mobile+%C2%B7+Web+%C2%B7+Design+%C2%B7+All+in+one;Flutter+%C2%B7+React+%C2%B7+Next.js+%C2%B7+Figma;Turning+ideas+into+digital+products;Open+to+remote+%26+serious+projects)](https://git.io/typing-svg)

**Algeria 🌍 · Open to Remote**

*"I don't build websites. I engineer digital products that mean something."*

</div>

<br/>

---

## ⚡ What I Build

<table>
  <tr>
    <td align="center"><strong>📱 Mobile Apps</strong></td>
    <td align="center"><strong>🌐 Web Products</strong></td>
    <td align="center"><strong>✦ UI/UX Design</strong></td>
  </tr>
  <tr>
    <td align="center">Flutter · Dart</td>
    <td align="center">Next.js · React</td>
    <td align="center">Figma · Design Systems</td>
  </tr>
  <tr>
    <td align="center">Firebase · REST APIs</td>
    <td align="center">TypeScript · Tailwind</td>
    <td align="center">UX Research · Prototypes</td>
  </tr>
  <tr>
    <td align="center">Cross-platform first</td>
    <td align="center">Performance-obsessed</td>
    <td align="center">Product-thinking</td>
  </tr>
</table>

---

## 💻 Tech Stack

<div align="center">

**Mobile**

[![My Skills](https://skillicons.dev/icons?i=flutter,dart,firebase&theme=dark)](https://skillicons.dev)

**Frontend**

[![My Skills](https://skillicons.dev/icons?i=react,nextjs,ts,tailwind&theme=dark)](https://skillicons.dev)

**Backend & Tools**

[![My Skills](https://skillicons.dev/icons?i=nodejs,supabase,git,github,vscode&theme=dark)](https://skillicons.dev)

**Design**

[![My Skills](https://skillicons.dev/icons?i=figma,ae,ps&theme=dark)](https://skillicons.dev)

</div>

---

## 🚀 Current Focus

→ Shipping production-grade Flutter apps at scale  
→ Deepening system design & backend architecture  
→ Building products that solve real problems  

---

## 📊 GitHub Stats

<!-- 3D CONTRIBUTION GRAPH (requires GitHub Action — see setup note at top) -->
<div align="center">
  <img src="https://raw.githubusercontent.com/ahmedtayebi/ahmedtayebi/main/profile-3d-contrib/profile-night-rainbow.svg" width="100%" alt="3D Contribution Graph"/>
</div>

<br/>

<!-- ACTIVITY GRAPH -->
<div align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=ahmedtayebi&bg_color=0A0A0F&color=6C63FF&line=6C63FF&point=E8E8F0&area=true&area_color=6C63FF&hide_border=true&radius=8" alt="Activity Graph"/>
</div>

<br/>

<!-- STATS CARDS -->
<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=ahmedtayebi&show_icons=true&theme=transparent&title_color=6C63FF&icon_color=6C63FF&text_color=E8E8F0&bg_color=0A0A0F&border_color=1E1E2E&border_radius=10" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ahmedtayebi&layout=compact&theme=transparent&title_color=6C63FF&icon_color=6C63FF&text_color=E8E8F0&bg_color=0A0A0F&border_color=1E1E2E&border_radius=10" />

<br/><br/>

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=ahmedtayebi&ring=6C63FF&fire=FF6B6B&currStreakLabel=6C63FF&background=0A0A0F&border=1E1E2E&dates=8888A8&sideLabels=8888A8&border_radius=10)](https://git.io/streak-stats)

</div>

<br/>

<!-- SNAKE ANIMATION (requires GitHub Action — see setup note at top) -->
<div align="center">
  <img src="https://raw.githubusercontent.com/ahmedtayebi/ahmedtayebi/output/github-contribution-grid-snake-animated.svg" alt="Snake Animation" width="100%"/>
</div>

---

## 🤝 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmedtayebi)
[![Dribbble](https://img.shields.io/badge/Dribbble-EA4C89?style=for-the-badge&logo=dribbble&logoColor=white)](https://dribbble.com/ahmedtayebi)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@ahmedtayebi.dev)

*Open to serious projects, collaborations, and remote opportunities.*

</div>

<!-- FOOTER WAVE -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=6C63FF&height=100&section=footer"/>

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=ahmedtayebi&color=6C63FF&style=flat-square)
&nbsp;
<sub>// Ahmed Tayebi · Product Engineer · Algeria · 2026</sub>

</div>

<!-- ═══════════════════════════════════════════════════════════
GITHUB ACTIONS SETUP — copy each block to the correct file path

━━━ FILE 1: .github/workflows/snake.yml ━━━

name: Snake Animation
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ahmedtayebi
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-animated.svg?color_snake=6C63FF&color_dots=#0d1117,#1a1a2e,#2d2b55,#6C63FF,#8b83ff
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

━━━ FILE 2: .github/workflows/3d-contrib.yml ━━━

name: 3D Contribution Graph
on:
  schedule:
    - cron: "0 18 * * *"
  workflow_dispatch:
jobs:
  build:
    runs-on: ubuntu-latest
    name: generate-github-profile-3d-contrib
    steps:
      - uses: actions/checkout@v3
      - uses: yoshi389111/github-profile-3d-contrib@0.7.1
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          USERNAME: ahmedtayebi
        with:
          settings_json: >-
            {
              "githubUserName": "ahmedtayebi",
              "defaultSettings": {
                "fileName": "profile-night-rainbow.svg",
                "backgroundColor": "#0A0A0F",
                "type": "NORMAL"
              }
            }
      - run: |
          mkdir -p profile-3d-contrib
          cp -f profile-3d-contrib.svg profile-3d-contrib/profile-night-rainbow.svg || true
      - uses: actions/upload-artifact@v3
        with:
          name: profile-3d-contrib
          path: profile-3d-contrib
      - uses: stefanzweifel/git-auto-commit-action@v4
        with:
          commit_message: "Update 3D contribution graph"

═══════════════════════════════════════════════════════════ -->
