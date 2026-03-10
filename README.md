<!-- HEADER -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=160&section=header&text=Alex%20%E2%80%94%20ALEX-RPL&fontSize=48&fontColor=c8ff00&animation=twinkling&fontAlignY=38&desc=Student%20Developer%20%7C%20PHP%20%C2%B7%20Laravel%20%C2%B7%20Learning%20Next.js%20%26%20Python&descAlignY=60&descSize=14"/>
</div>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=DM+Mono&weight=500&size=17&pause=1000&color=C8FF00&center=true&vCenter=true&width=500&height=60&lines=Halo!+Aku+Febri%2C+dipanggil+Alex+%F0%9F%91%8B;Pelajar+RPL+yang+suka+ngoding+%F0%9F%92%BB;Laravel+%7C+PHP+%7C+MySQL+%7C+CSS+frameworks;Lagi+belajar+Next.js+%26+Python+%F0%9F%94%A5;Building+in+public+%E2%80%94+on+going!+%F0%9F%9A%80" />
  </a>
</div>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=ALEX-RPL&label=Profile+Views&color=c8ff00&style=flat-square" />
  &nbsp;
  <img src="https://img.shields.io/github/followers/ALEX-RPL?label=Followers&style=flat-square&color=c8ff00&labelColor=111" />
  &nbsp;
  <a href="https://ALEX-RPL.github.io">
    <img src="https://img.shields.io/badge/Portfolio-c8ff00?style=flat-square&logo=firefox&logoColor=000" />
  </a>
</div>

---

## `$ whoami`

```ts
const alex = {
  nama:       "Mohamad Febri Hansyah",
  panggilan:  "Alex",
  username:   "ALEX-RPL",
  status:     "🎓 Pelajar RPL — aktif belajar & ngoding",
  lokasi:     "Indonesia 🇮🇩",

  sudahBisa: {
    backend:   ["PHP", "Laravel", "MySQL"],
    frontend:  ["HTML", "CSS", "Tailwind CSS", "Bootstrap", "Bulma"],
  },

  lagiBelajar: ["Next.js", "Python", "Data Engineering"],

  portfolio:   "on going — coming soon! 🚧",
  openCollab:  true,
  motto:       "Mulai dulu, sempurnain sambil jalan.",
};
```

---

## 🛠️ Tech Stack

<div align="center">

**Sudah Bisa ✅**
<br>
<img src="https://skillicons.dev/icons?i=php,laravel,mysql,html,css,tailwind,bootstrap&perline=7" />

**Lagi Dipelajari 🔥**
<br>
<img src="https://skillicons.dev/icons?i=nextjs,python,typescript&perline=7" />

**Tools**
<br>
<img src="https://skillicons.dev/icons?i=git,github,vscode,figma&perline=7" />

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=ALEX-RPL&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&title_color=c8ff00&icon_color=c8ff00" />
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=ALEX-RPL&theme=tokyonight&hide_border=true&ring=c8ff00&fire=ff2d78&currStreakLabel=c8ff00" />
</div>

<div align="center">
  <img width="42%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ALEX-RPL&theme=tokyonight&hide_border=true&layout=compact&langs_count=6&title_color=c8ff00" />
</div>

---

## 🚧 Projects — On Going

> Portofolio masih dalam proses! Ini yang lagi dikerjain:

| Project | Stack | Status |
|:---|:---|:---:|
| 🌐 **Web App CRUD** — sistem manajemen dengan auth & dashboard | `Laravel` `PHP` `MySQL` `Tailwind` | 🔨 60% |
| 📊 **Data Pipeline** — ETL sederhana CSV → database → visualisasi | `Python` `Pandas` `SQLite` | 🔨 30% |
| ⚡ **Portfolio v2** — upgrade ke Next.js + TypeScript | `Next.js` `TypeScript` `Tailwind` | 📅 10% |

---

## 🗺️ Learning Roadmap

```
✅ HTML & CSS          ████████████████████ 85%
✅ PHP & Laravel       █████████████████░░░ 75%
✅ MySQL               ████████████████░░░░ 70%
🔥 Python              ███████░░░░░░░░░░░░░ 35%
🔥 Next.js             █████░░░░░░░░░░░░░░░ 25%
🔥 Data Engineering    ████░░░░░░░░░░░░░░░░ 20%
```

---

## 🏆 GitHub Trophies

<div align="center">
  <img width="100%" src="https://github-profile-trophy.vercel.app/?username=ALEX-RPL&theme=tokyonight&no-frame=true&no-bg=true&column=6&margin-w=4" />
</div>

---

## 🐍 Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/ALEX-RPL/ALEX-RPL/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ALEX-RPL/ALEX-RPL/output/github-contribution-grid-snake.svg"/>
    <img alt="snake" src="https://raw.githubusercontent.com/ALEX-RPL/ALEX-RPL/output/github-contribution-grid-snake.svg"/>
  </picture>
</div>

<details>
<summary><b>⚙️ Setup snake animation</b></summary>

Buat file `.github/workflows/snake.yml` di repo `ALEX-RPL/ALEX-RPL`:

```yaml
name: Snake Animation
on:
  schedule: [{ cron: "0 */12 * * *" }]
  workflow_dispatch:
jobs:
  generate:
    permissions: { contents: write }
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with: { target_branch: output, build_dir: dist }
        env: { GITHUB_TOKEN: "${{ secrets.GITHUB_TOKEN }}" }
```
</details>

---

## 🤝 Connect

<div align="center">

<a href="https://ALEX-RPL.github.io">
  <img src="https://img.shields.io/badge/Portfolio-c8ff00?style=for-the-badge&logo=firefox-browser&logoColor=000"/>
</a>
&nbsp;
<a href="https://github.com/ALEX-RPL">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

<br/>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer&animation=twinkling"/>
</div>

<div align="center">
  <sub>masih pelajar, tapi serius ngodingnya 🔥 · made with ❤️ in Indonesia</sub>
</div>
