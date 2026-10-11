<!-- ========================================================= -->
<!--                    BANNER (LIGHT / DARK)                  -->
<!-- ========================================================= -->
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="[YOUR_DARK_BANNER_URL]">
  <source media="(prefers-color-scheme: light)" srcset="[YOUR_LIGHT_BANNER_URL]">
  <img alt="[YOUR_NAME] banner" src="[YOUR_LIGHT_BANNER_URL]" width="100%">
</picture>

<br><br>

<!-- ========================================================= -->
<!--                          TITLE                            -->
<!-- ========================================================= -->

# 🌸 Hey there, I'm [YOUR_NAME] 🌸

<!-- ========================================================= -->
<!--                     ANIMATED TYPING                       -->
<!-- ========================================================= -->

<a href="https://github.com/[YOUR_USERNAME]">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3500&pause=1000&color=FF69B4&center=true&vCenter=true&width=650&height=50&lines=[YOUR_TAGLINE_1];[YOUR_TAGLINE_2];[YOUR_TAGLINE_3];[YOUR_TAGLINE_4]" alt="Typing SVG" />
</a>

<br>

<!-- ========================================================= -->
<!--                         BADGES                            -->
<!-- ========================================================= -->

<p align="center">
  <a href="https://github.com/[YOUR_USERNAME]?tab=followers">
    <img src="https://img.shields.io/github/followers/[YOUR_USERNAME]?style=for-the-badge&logo=github&logoColor=white&label=Followers&labelColor=1a1a1a&color=FF69B4" alt="GitHub followers" />
  </a>
  <a href="https://github.com/[YOUR_USERNAME]?tab=repositories">
    <img src="https://img.shields.io/github/stars/[YOUR_USERNAME]?style=for-the-badge&logo=github&logoColor=white&label=Stars&labelColor=1a1a1a&color=FF69B4" alt="GitHub stars" />
  </a>
  <a href="https://github.com/[YOUR_USERNAME]">
    <img src="https://komarev.com/ghpvc/?username=[YOUR_USERNAME]&style=for-the-badge&label=Profile+Views&labelColor=1a1a1a&color=FF69B4" alt="Profile views" />
  </a>
</p>

</div>

<br>

<!-- ========================================================= -->
<!--                        ABOUT ME                           -->
<!-- ========================================================= -->

<div align="center">

## 💖 About Me

</div>

<table align="center" width="100%">
  <tr>
    <td width="65%" valign="top">

<br>

👋 Hi! I'm **[YOUR_NAME]**, a **[YOUR_ROLE]** based in **[YOUR_LOCATION]**.

🔭 I'm currently working on **[YOUR_CURRENT_PROJECT]**

🌱 I'm currently learning **[YOUR_LEARNING_TOPIC]**

🤝 I'm looking to collaborate on **[YOUR_COLLAB_INTEREST]**

💬 Ask me about **[YOUR_TOPICS]**

⚡ Fun fact: **[YOUR_FUN_FACT]**

<br>

  </td>
    <td width="35%" align="center" valign="middle">

<img src="[YOUR_IMAGE_OR_GIF_URL]" alt="[YOUR_NAME]" width="100%" style="border-radius: 20px;" />

  </td>
  </tr>
</table>

<br>

<!-- ========================================================= -->
<!--                        TECH STACK                         -->
<!-- ========================================================= -->

<div align="center">

## 🛠️ Tech Stack

<!-- Edit the list after "i=" with any icon IDs from https://skillicons.dev -->
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=[SKILL_1],[SKILL_2],[SKILL_3],[SKILL_4],[SKILL_5],[SKILL_6],[SKILL_7],[SKILL_8]&perline=8&theme=dark" alt="My Skills" />
</a>

<br><br>

<!-- Optional second row -->
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=[SKILL_9],[SKILL_10],[SKILL_11],[SKILL_12],[SKILL_13],[SKILL_14],[SKILL_15],[SKILL_16]&perline=8&theme=dark" alt="More Skills" />
</a>

</div>

<br>

<!-- ========================================================= -->
<!--                  GITHUB STATS (PINK THEME)                -->
<!-- ========================================================= -->

<div align="center">

## 📊 GitHub Streak

<img src="https://streak-stats.demolab.com?user=[YOUR_USERNAME]&theme=transparent&hide_border=true&background=00000000&ring=FF69B4&fire=EF93C4&currStreakLabel=FF69B4&currStreakNum=F8BBD0&sideLabels=FF69B4&sideNums=F8BBD0&dates=F8BBD0&stroke=F8BBD0" alt="GitHub Streak" />

<br><br>

## 📈 Contribution Activity

<img src="https://github-readme-activity-graph.vercel.app/graph?username=[YOUR_USERNAME]&bg_color=00000000&color=FF69B4&line=EF93C4&point=F8BBD0&area=true&area_color=FF69B4&hide_border=true&title_color=FF69B4" alt="Contribution Activity Graph" width="95%" />

</div>

<br>

<!-- ========================================================= -->
<!--                    CONTRIBUTION SNAKE                     -->
<!-- ========================================================= -->

<div align="center">

## 🐍 Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/[YOUR_USERNAME]/[YOUR_USERNAME]/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/[YOUR_USERNAME]/[YOUR_USERNAME]/output/github-snake.svg">
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/[YOUR_USERNAME]/[YOUR_USERNAME]/output/github-snake.svg" width="95%">
</picture>

</div>

<!--
=========================================================
  GITHUB ACTION FOR THE SNAKE
  Create the file: .github/workflows/snake.yml
  Then run it once from the "Actions" tab (Run workflow).
  It publishes the SVGs to a branch named "output".
=========================================================

name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10
    steps:
      - name: Generate snake SVGs
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
-->

<br>

<!-- ========================================================= -->
<!--                         CONNECT                           -->
<!-- ========================================================= -->

<div align="center">

## 🌐 Let's Connect

<p align="center">
  <a href="https://linkedin.com/in/[YOUR_LINKEDIN_USERNAME]">
    <img src="https://img.shields.io/badge/LinkedIn-FF69B4?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://x.com/[YOUR_X_USERNAME]">
    <img src="https://img.shields.io/badge/X-FF69B4?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
  <a href="https://instagram.com/[YOUR_INSTAGRAM_USERNAME]">
    <img src="https://img.shields.io/badge/Instagram-FF69B4?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
  <a href="https://tiktok.com/@[YOUR_TIKTOK_USERNAME]">
    <img src="https://img.shields.io/badge/TikTok-FF69B4?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok" />
  </a>
  <a href="https://youtube.com/@[YOUR_YOUTUBE_HANDLE]">
    <img src="https://img.shields.io/badge/YouTube-FF69B4?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
  </a>
  <a href="mailto:[YOUR_EMAIL]">
    <img src="https://img.shields.io/badge/Email-FF69B4?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<br>

<sub>✨ Thanks for stopping by, don't forget to leave a ⭐ ✨</sub>

</div>

<!-- ========================================================= -->
<!--                  CAPSULE RENDER FOOTER                    -->
<!-- ========================================================= -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,12&height=140&section=footer&animation=fadeIn&fontColor=FFFFFF" width="100%" alt="Footer wave" />

</div>
