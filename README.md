<!-- HEADER -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=160&section=header&text=YOUR_NAME&fontSize=52&fontColor=c8ff00&animation=twinkling&fontAlignY=38&desc=Full%20Stack%20Developer%20%7C%20Open%20Source%20%7C%20Building%20in%20Public&descAlignY=60&descSize=15"/>
</div>

<!-- TYPING -->
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=DM+Mono&weight=500&size=18&pause=1000&color=C8FF00&center=true&vCenter=true&repeat=true&width=480&height=60&lines=const+dev+%3D+%22YOUR_NAME%22+%F0%9F%91%8B;Building+things+that+scale+%F0%9F%9A%80;Open+source+%7C+Clean+code+%7C+Ship+fast+%E2%9A%A1;Available+for+freelance+%F0%9F%9F%A2" />
  </a>
</div>

<br/>

<!-- BADGES -->
<div align="center">
  <img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&label=Profile+Views&color=c8ff00&style=flat-square" />
  &nbsp;
  <img src="https://img.shields.io/github/followers/YOUR_USERNAME?label=Followers&style=flat-square&color=c8ff00&labelColor=111" />
  &nbsp;
  <a href="https://YOUR_USERNAME.github.io">
    <img src="https://img.shields.io/badge/Portfolio-c8ff00?style=flat-square&logo=firefox&logoColor=000" />
  </a>
  &nbsp;
  <a href="https://linkedin.com/in/YOUR_USERNAME">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://twitter.com/YOUR_USERNAME">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white" />
  </a>
</div>

---

## `$ whoami`

```ts
const YOUR_USERNAME = {
  name:     "YOUR_NAME",
  role:     "Full Stack Developer",
  location: "Indonesia 🇮🇩",
  company:  "YOUR_COMPANY / Freelance",

  stack: {
    frontend:  ["React", "Next.js", "TypeScript", "Tailwind"],
    backend:   ["Node.js", "Go", "Python", "FastAPI"],
    database:  ["PostgreSQL", "MongoDB", "Redis"],
    devops:    ["Docker", "AWS", "GitHub Actions", "Nginx"],
  },

  currentlyLearning: ["Rust", "Web3", "AI/ML Engineering"],
  openToWork: true,
  contact: "hello@YOUR_DOMAIN.com",
} as const;
```

---

## 📊 GitHub Stats

<div align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&title_color=c8ff00&icon_color=c8ff00" />
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=tokyonight&hide_border=true&ring=c8ff00&fire=ff2d78&currStreakLabel=c8ff00" />
</div>

<div align="center">
  <img width="38%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&theme=tokyonight&hide_border=true&layout=compact&langs_count=8&title_color=c8ff00" />
  <img width="58%" src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&bg_color=1a1b27&color=c8ff00&line=c8ff00&point=ffffff&hide_border=true" />
</div>

---

## 🚀 Featured Projects

<div align="center">

| Project | Stack | Status |
|:---|:---|:---:|
| 🛒 **[ShopEngine](https://github.com/YOUR_USERNAME/project-one)** — full-stack e-commerce w/ Stripe | `Next.js` `MongoDB` `Stripe` | ✅ Live |
| 💬 **[ChatVerse](https://github.com/YOUR_USERNAME/project-two)** — real-time messaging app | `Socket.io` `Redis` `PostgreSQL` | ✅ Live |
| 📊 **[DataViz](https://github.com/YOUR_USERNAME/project-three)** — ML-powered analytics dashboard | `Python` `FastAPI` `Recharts` | ✅ Live |
| 🤖 **[AI Doc QA](https://github.com/YOUR_USERNAME/project-four)** — RAG document assistant | `OpenAI` `Langchain` `Pinecone` | ✅ Live |
| ⚙️ **[CLI DevTools](https://github.com/YOUR_USERNAME/project-five)** — open-source dev toolbox | `Go` `Cobra` `Docker` | ✅ Live |

</div>

---

## 🛠️ Tech Stack

<div align="center">

**Frontend**
<br>
<img src="https://skillicons.dev/icons?i=ts,react,nextjs,tailwind,html,css,figma&perline=7" />

**Backend & DB**
<br>
<img src="https://skillicons.dev/icons?i=nodejs,go,python,fastapi,postgres,mongodb,redis&perline=7" />

**DevOps & Tools**
<br>
<img src="https://skillicons.dev/icons?i=docker,aws,github,githubactions,nginx,linux,vscode&perline=7" />

</div>

---

## 🏆 Achievements

<div align="center">
  <img width="100%" src="https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=4" />
</div>

---

## 🐍 Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake.svg"/>
    <img alt="snake" src="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake.svg"/>
  </picture>
</div>

<details>
<summary><b>🔧 Setup snake animation (click)</b></summary>

Create `.github/workflows/snake.yml`:

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

## 📝 Latest Blog Posts

<!-- BLOG-POST-LIST:START -->
- [🚀 How I Built a Real-time Chat App with 1000+ Concurrent Users](https://dev.to/YOUR_USERNAME)
- [⚡ Next.js 15 — What's New and Why It Matters](https://dev.to/YOUR_USERNAME)
- [🐳 Docker in 2025: A Developer's Practical Guide](https://dev.to/YOUR_USERNAME)
- [🔒 JWT vs Session Auth — When to Use Which](https://dev.to/YOUR_USERNAME)
<!-- BLOG-POST-LIST:END -->

---

## 🤝 Connect

<div align="center">

<a href="https://YOUR_USERNAME.github.io">
  <img src="https://img.shields.io/badge/Portfolio-c8ff00?style=for-the-badge&logo=firefox-browser&logoColor=000"/>
</a>
&nbsp;
<a href="mailto:hello@YOUR_DOMAIN.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<a href="https://linkedin.com/in/YOUR_USERNAME">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="https://twitter.com/YOUR_USERNAME">
  <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white"/>
</a>
&nbsp;
<a href="https://dev.to/YOUR_USERNAME">
  <img src="https://img.shields.io/badge/Dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white"/>
</a>

</div>

<br/>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer&animation=twinkling"/>
</div>

<div align="center">
  <sub>⭐ star my repos if they helped you · built with ❤️ in Indonesia</sub>
</div>
