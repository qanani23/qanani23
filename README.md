<!-- ==================== HERO BANNER ==================== -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=280&color=gradient&customColorList=6,11,20,30&text=KENENI%20%7C%20Full%20Stack%20Developer&fontSize=55&fontAlignY=40&animation=fadeIn&fontColor=ffffff&desc=Building%20Startups.%20Writing%20Scalable%20Code.%20Trading%20Precision.&descAlignY=65&descAlign=50"/>
 </p>

<!-- ==================== TYPING ANIMATION ==================== -->

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=00F7FF&center=true&vCenter=true&width=700&lines=Full+Stack+Developer;Startup+Builder;UI%2FUX+Focused+Engineer;Forex+Trader;Relentless+Problem+Solver+🚀"/>
</p>

<!-- ==================== VISITOR COUNTER ==================== -->

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=qanani23&label=Profile%20Views&color=blueviolet&style=for-the-badge"/>
</p>

---

# 👋 About Me

- 🚀 Building scalable startup products  
- 💻 Passionate about full-stack development  
- 📈 Interested in trading & capital growth  
- 🎯 Focused on performance, UI/UX & clean architecture  

---

# 🌐 Portfolio

<p align="center">
  <a href="https://keneni.netlify.app/">
    <img src="https://img.shields.io/badge/View%20My%20Portfolio-00F7FF?style=for-the-badge&logo=vercel&logoColor=black"/>
  </a>
</p>

---

# 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,ts,nodejs,express,firebase,tailwind,python,figma,git,linux" />
</p>

---

# 📊 GitHub Analytics

<p align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=qanani23&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117" />
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=qanani23&layout=compact&theme=radical&hide_border=true&bg_color=0d1117"/>
</p>

---

# 🔥 Streak Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=qanani23&theme=radical&hide_border=true&background=0D1117"/>
</p>

---

# 🐍 Contribution Snake Animation

(You must enable GitHub Actions for this to work)

```yaml
# .github/workflows/snake.yml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: qanani23
          outputs: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
