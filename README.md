<div align="center">

# 🎮 THEVINDU'S DEV ARCADE

### Code. Music. Side quests. Repeat.

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2800&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Hey%2C+I%27m+Thevindu+%F0%9F%91%8B;Turning+ideas+into+web+apps;K-pop+in+my+ears.+Code+on+my+screen.;Welcome+to+my+little+corner+of+GitHub." alt="Hey, I'm Thevindu. Turning ideas into web apps. K-pop in my ears, code on my screen." />

<p>
  <a href="https://thevindu.xyz"><img src="https://img.shields.io/badge/OPEN_MY_PORTFOLIO-A78BFA?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Open my portfolio" /></a>
  <a href="https://github.com/Thevindu23?tab=repositories"><img src="https://img.shields.io/badge/EXPLORE_MY_PROJECTS-22D3EE?style=for-the-badge&logo=github&logoColor=101827" alt="Explore my projects" /></a>
</p>

**🇱🇰 Sri Lanka · 🎓 Business Information Systems · 💻 Building things that solve everyday problems**

[🧑‍💻 Player profile](#-player-profile) · [🧰 Inventory](#-my-inventory) · [🚀 Quests](#-the-quest-board) · [🎧 Music](#-the-jukebox) · [🎮 Arcade](#-take-a-game-break)

</div>

---

## 🧑‍💻 Player profile

Hey! I'm **Thevindu Nethmina**, a Business Information Systems undergraduate at the **University of Sri Jayewardenepura**.

I enjoy connecting the business side of a problem with the technical side of a solution. My projects explore web development, useful little tools, and ways to make everyday tasks easier.

```yaml
player: Thevindu23
home_base: Sri Lanka
main_quest: Turn useful ideas into working software
skill_tree: Web development · Databases · Software quality
side_quests: AI tools · Automation · Better user experiences
soundtrack: BLACKPINK · ENHYPEN · BTS
anime_corner: Naruto 🍥
```

> Every project is another level. Every bug is an unexpected boss fight.

## 🧰 My inventory

Tools I've worked with while building and learning:

**🌐 Frontend**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0F172A?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8)

**⚙️ Backend**

![Java](https://img.shields.io/badge/Java-E76F00?style=for-the-badge)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

**🗄️ Data & tools**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

## 🚀 The quest board

| Quest | What it's about | Enter |
| :--- | :--- | :--- |
| 🧠 **PromptPocket** | A place to save and organise reusable AI prompts. | [View repository](https://github.com/Thevindu23/PromptPocket) |
| 🔎 **FindIt** | A lost-and-found portal for connecting people with their missing items. | [View repository](https://github.com/Thevindu23/findit) |
| 🌐 **My Portfolio** | My personal corner of the web, built with React and Tailwind CSS. | [Visit website](https://thevindu.xyz) · [View repository](https://github.com/Thevindu23/My-Portfolio) |

**Also in my project journey:** 🍃 TeaGo — a tea factory and supplier management project using Spring Boot.

## 🎧 The jukebox

**Choose a soundtrack for your visit.** Headphones recommended. 🎶

<p align="center">
  <a href="https://www.youtube.com/results?search_query=BLACKPINK+official+music"><img src="https://img.shields.io/badge/%E2%96%B6_BLACKPINK-F7A8C4?style=for-the-badge&logo=youtube&logoColor=181717" alt="Find BLACKPINK music on YouTube" /></a>
  <a href="https://www.youtube.com/results?search_query=ENHYPEN+official+music"><img src="https://img.shields.io/badge/%E2%96%B6_ENHYPEN-A78BFA?style=for-the-badge&logo=youtube&logoColor=white" alt="Find ENHYPEN music on YouTube" /></a>
  <a href="https://www.youtube.com/results?search_query=BTS+official+music"><img src="https://img.shields.io/badge/%E2%96%B6_BTS-7C3AED?style=for-the-badge&logo=youtube&logoColor=white" alt="Find BTS music on YouTube" /></a>
</p>

*These buttons open YouTube searches—not a live listening status or an embedded music player.*

<details>
<summary>🍥 Unlock the anime side quest</summary>

Some problems need a better algorithm. Others need a short break and a Naruto soundtrack.

[🎵 Find Naruto soundtracks on YouTube](https://www.youtube.com/results?search_query=Naruto+official+soundtrack)

</details>

## 🎮 Take a game break

### 🐛 Mini boss: spot the bug

This function should return the sum of the numbers. Why doesn't it?

```javascript
function totalScore(points) {
  let total = 0;
  for (let i = 0; i <= points.length; i++) {
    total += points[i];
  }
  return total;
}

totalScore([10, 20, 30]); // Expected: 60
```

<details>
<summary>🗝️ Reveal the fix — no peeking!</summary>

The loop takes **one extra turn**! At `i === points.length`, `points[i]` is `undefined`. Adding it to a number produces `NaN`.

Change `i <= points.length` to **`i < points.length`**.

🏆 **Achievement unlocked: Off-by-one survivor.**

</details>

### 🧩 Bonus level: 2048

Merge matching tiles. Aim for 2048. Try not to turn a five-minute break into an entire evening.

[![Play 2048](https://img.shields.io/badge/PLAY_2048-FBBF24?style=for-the-badge&logoColor=black)](https://play2048.co/)

*Opens an external game. The debugging challenge above works here using a click-to-reveal answer.*

<details>
<summary>🎁 Open the mystery chest</summary>

You found: **one imaginary extra life**. ❤️

Use it when your code works locally but not after deployment.

No coins. No signup. Just developer solidarity.

</details>

---

<div align="center">

### 🤝 Want to build something useful?

I'm happy to connect over web development, student projects, and creative tech ideas.

**[🌐 Visit my portfolio](https://thevindu.xyz) · [💻 Explore my repositories](https://github.com/Thevindu23?tab=repositories)**

*Thanks for stopping by. Save your progress, stretch your shoulders, and keep building.* ✨

</div>

<!-- Owner notes (not displayed):
Install this file as README.md at the root of the public Thevindu23/Thevindu23 repository.
Profile/project details are based on information you shared; live repository availability was not verified.
Music links are artist searches. Replace their href URLs with your own playlist URLs if desired.
The animated heading uses readme-typing-svg.demolab.com; badges use img.shields.io.
These external image services may be unavailable. Text and navigation remain usable without them.
No tokens, GitHub Actions, tracking counters, or Spotify account connection are required.
-->
