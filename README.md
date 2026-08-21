<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1A1A2E,50:6C5CE7,100:8A9DFF&height=200&section=header&text=Roky%20Paul&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Game%20Developer%20%C2%B7%20UI%2FUX%20Designer%20%C2%B7%20Frontend%20Developer&descAlignY=58&descSize=17"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=18&duration=3000&pause=1000&color=8A9DFF&center=true&vCenter=true&width=550&lines=Building+The+Sleeping+City+%F0%9F%8C%99;Contributing+to+Podman+%F0%9F%90%8B;Where+aesthetics+meet+code." alt="typing" />

<br/><br/>

<a href="https://roky-paul.vercel.app"><img src="https://img.shields.io/badge/Portfolio-1A1A2E?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/rokypaul"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:roky.paul.sot25@pwioi.com"><img src="https://img.shields.io/badge/Email-8A9DFF?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧊 About

I'm a second-year Computer Science student who builds interactive experiences where design and code meet — atmospheric games, clean design systems, and frontend work I can stand behind end to end.

```yaml
role: Game Developer & UI/UX Designer
currently_building: The Sleeping City — an atmospheric puzzle-platformer (Phaser 3)
currently_learning: Godot 4, systems design, open-source contribution workflows
currently_exploring: Podman — LFX Mentorship application (podman.io Downloads page)
based_in: Bengaluru, India
studying: B.Tech Computer Science, Medhavi Skills University
```

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

**Game Development**
<br/>
<img src="https://skillicons.dev/icons?i=js&theme=dark" height="42"/>&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Phaser_3-FF006E?style=for-the-badge" height="26"/>&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Godot_4-478CBF?style=for-the-badge&logo=godotengine&logoColor=white" height="26"/>&nbsp;&nbsp;
<img src="https://img.shields.io/badge/GDScript-355570?style=for-the-badge" height="26"/>

<br/><br/>

**Frontend & Frameworks**
<br/>
<img src="https://skillicons.dev/icons?i=ts,react,nextjs,html,css&theme=dark" height="42"/>

<br/><br/>

**Backend & Tools**
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,git,github,vercel,vite&theme=dark" height="42"/>

<br/><br/>

**Design**
<br/>
<img src="https://skillicons.dev/icons?i=figma&theme=dark" height="42"/>&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Design_Systems-8A9DFF?style=for-the-badge" height="26"/>&nbsp;&nbsp;
<img src="https://img.shields.io/badge/WCAG_AA-00A896?style=for-the-badge" height="26"/>

<br/><br/>

**Core / DSA**
<br/>
<img src="https://skillicons.dev/icons?i=cpp,java&theme=dark" height="42"/>&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Data_Structures-FF006E?style=for-the-badge" height="26"/>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🐋 Podman Downloads Page
**LFX Mentorship application**
*Fork of [containers/podman.io](https://github.com/containers/podman.io)*

Podman's site had no dedicated downloads page — "Other Install Options" just redirected to install docs. I built one with:

- **OS auto-detection** + manual override
- **Per-distro Linux commands** (Fedora, Debian, Arch, Alpine, openSUSE, Gentoo) — real package-manager syntax, not binary downloads
- **Rootless/daemonless explainer** for first-time users
- **Full accessibility pass** — WCAG AA, keyboard nav, ARIA labels
- **YouTube tie-in** via build-time RSS fetch — zero exposed API keys

Also found two real upstream bugs: a broken Prettier/Husky pre-commit hook and an SSR issue in an existing component.

`Docusaurus` `React` `Accessibility`

**[Live →](https://podmanio.vercel.app/downloads)** · **[Code →](https://github.com/Roky777/podman.io/tree/feature/downloads-page)**

> *Podman mentor reading this — hi 👋 hope the Downloads page was useful.*

</td>
<td width="50%" valign="top">

### 🌙 The Sleeping City
**Solo · Winner, PhysicsWallah Games Hackathon**

A 2D atmospheric puzzle-platformer inspired by INSIDE and LIMBO — a child wakes a forgotten city, and every puzzle teaches a physics concept through environmental storytelling.

- No tutorials, no on-screen text — pure interaction and discovery
- Six districts, each grounded in a different physics domain
- Game design, mechanics, and art direction, end-to-end, solo

`Phaser 3` `JavaScript` `Game Design`

**[Play →](https://roky777.github.io/The-Sleeping-City)** · **[Code →](https://github.com/Roky777/The-Sleeping-City)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📅 Task Tracker
**Solo**

A week-planner app built to prove real production capability in the same stack Podman's own site runs on.

- Priority, category, and date-time tagging
- 24-hour calendar layout
- Filter and search
- Built and deployed entirely solo

`Next.js 16` `React 19` `TypeScript`

**[Live →](https://task-tracker-six-rosy.vercel.app)**

</td>
<td width="50%" valign="top">

### 🎛️ NexusHub
**Team of 5 · Built the Kanban module**

A capstone project: six independent tools unified into one dashboard, built entirely in vanilla HTML, CSS, and JavaScript — no frameworks, no build step.

- Quiz, Expense Tracker, News, GitHub Explorer, Kanban, Home
- My piece: drag-and-drop Kanban board, persistent state (localStorage)
- Followed a shared state → render → events architecture across the team

`Vanilla JS` `HTML5` `CSS3`

**[Live →](https://nexushub-final.vercel.app)** · **[Code →](https://github.com/Roky777/nexushub-final)**

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>


## 💬 Let's Connect

I'm interested in **open-source contribution**, **game development roles**, and collaborating on **educational or narrative-driven projects**.

<br/>

<a href="https://roky-paul.vercel.app"><img src="https://img.shields.io/badge/Portfolio-1A1A2E?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/rokypaul"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:roky.paul.sot25@pwioi.com"><img src="https://img.shields.io/badge/Email-8A9DFF?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br/><br/>

<i>"The best games are those that transport you to another world — where beauty, challenge, and story converge."</i>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=roky777&label=Profile+Views&color=8A9DFF&style=for-the-badge"/>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:8A9DFF,50:6C5CE7,100:1A1A2E&height=100&section=footer"/>
