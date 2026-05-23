[khilesh_skills_dashboard.html](https://github.com/user-attachments/files/28168384/khilesh_skills_dashboard.html)<div align="center">

<!-- Cosmic Moon Banner -->
<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0a0a2e,50:1a1a4e,100:0d0d3d&height=200&section=header&text=Khilesh&fontSize=80&fontColor=c8d6f0&animation=fadeIn&fontAlignY=40&desc=✦%20Front-End%20Developer%20%7C%20UI%20Craftsman%20✦&descAlignY=65&descSize=18&descColor=8899cc" width="100%"/>

<!-- Moon Phase Divider -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=8BA8E0&center=true&vCenter=true&width=700&lines=🌙+Crafting+pixel-perfect+web+experiences;⭐+HTML+%7C+CSS+%7C+JavaScript+%7C+React;🚀+Turning+ideas+into+stunning+UIs;💫+Always+learning%2C+always+building;🌌+Open+to+collabs+%26+new+opportunities" alt="Typing SVG" />

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Khilesh81&color=5b7fba&style=for-the-badge&label=✦+VISITORS)
&nbsp;
![GitHub followers](https://img.shields.io/github/followers/Khilesh81?style=for-the-badge&color=5b7fba&labelColor=0a0a2e&label=Followers)

</div>

---

<img align="right" width="300" src="https://raw.githubusercontent.com/SubhadeepZilong/SubhadeepZilong/main/icons/animation_500_kix5abitof.gif" alt="coding" />

## 🌙 About Me

```js
const khilesh = {
  name      : "Khilesh",
  role      : "Front-End Developer",
  location  : "India 🇮🇳",
  passion   : ["Accessibility", "Performance", "UI/UX"],
  building  : "Fast, beautiful & modern web apps",
  learning  : ["React.js", "Tailwind CSS", "Python"],
  funFact   : "Great UI is felt, not just seen 🌙",
  openTo    : "Collabs · Internships · Freelance"
};
```

<br clear="right"/>

---

## 🛸 Tech Stack & Skills

### 🎨 Frontend Core
<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,react,tailwind&theme=dark" />
</p>

### ⚙️ Tools & Platforms
<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,figma,vercel&theme=dark" />
</p>

### 📊 Data & Backend (Learning)
<p>
  <img src="https://skillicons.dev/icons?i=python,streamlit,nodejs&theme=dark" />
</p>

---

[Uploading
<h2 class="sr-only">Khilesh's interactive skills progress dashboard with category filters and animated bars</h2>

<style>
  .skills-wrap { padding: 1rem 0 1.5rem; }

  .filter-row {
    display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 1.5rem;
  }
  .filter-btn {
    padding: 6px 14px; border-radius: 20px; font-size: 13px; font-weight: 500;
    border: 0.5px solid var(--color-border-secondary); background: transparent;
    color: var(--color-text-secondary); cursor: pointer; transition: all .18s;
  }
  .filter-btn.active, .filter-btn:hover {
    background: var(--color-background-info);
    color: var(--color-text-info);
    border-color: var(--color-border-info);
  }

  .summary-row {
    display: grid; grid-template-columns: repeat(4, minmax(0, 1fr)); gap: 10px; margin-bottom: 1.5rem;
  }
  .sum-card {
    background: var(--color-background-secondary); border-radius: var(--border-radius-md);
    padding: 12px 14px; text-align: center;
  }
  .sum-num { font-size: 22px; font-weight: 500; color: var(--color-text-primary); }
  .sum-lbl { font-size: 12px; color: var(--color-text-secondary); margin-top: 2px; }

  .skills-grid {
    display: grid; grid-template-columns: 1fr 1fr; gap: 10px;
  }

  .skill-card {
    background: var(--color-background-primary);
    border: 0.5px solid var(--color-border-tertiary);
    border-radius: var(--border-radius-lg);
    padding: 14px 16px;
    transition: border-color .18s, opacity .25s, transform .25s;
  }
  .skill-card.hidden { opacity: 0; pointer-events: none; transform: scale(.97); }
  .skill-card:hover { border-color: var(--color-border-secondary); }

  .skill-header {
    display: flex; align-items: center; gap: 10px; margin-bottom: 10px;
  }
  .skill-icon {
    width: 32px; height: 32px; border-radius: var(--border-radius-md);
    display: flex; align-items: center; justify-content: center;
    font-size: 16px; flex-shrink: 0;
  }
  .skill-name { font-size: 14px; font-weight: 500; color: var(--color-text-primary); }
  .skill-cat { font-size: 11px; color: var(--color-text-tertiary); margin-top: 1px; }

  .bar-row { display: flex; align-items: center; gap: 10px; }
  .bar-bg {
    flex: 1; height: 6px; background: var(--color-background-secondary);
    border-radius: 3px; overflow: hidden;
  }
  .bar-fill {
    height: 100%; border-radius: 3px; transform: scaleX(0);
    transform-origin: left; transition: transform 1s cubic-bezier(.16,1,.3,1);
  }
  .bar-pct { font-size: 13px; font-weight: 500; color: var(--color-text-primary); min-width: 32px; text-align: right; }

  .level-badge {
    display: inline-block; font-size: 10px; padding: 2px 8px;
    border-radius: 10px; margin-top: 8px; font-weight: 500;
  }
  .lvl-expert   { background: var(--color-background-success); color: var(--color-text-success); }
  .lvl-strong   { background: var(--color-background-info);    color: var(--color-text-info); }
  .lvl-growing  { background: var(--color-background-warning);  color: var(--color-text-warning); }
  .lvl-learning { background: var(--color-background-secondary); color: var(--color-text-tertiary); }

  .chart-wrap { margin-top: 1.5rem; }
  .chart-title { font-size: 13px; color: var(--color-text-secondary); margin-bottom: 10px; }
</style>

<div class="skills-wrap">

  <div class="filter-row" id="filters">
    <button class="filter-btn active" data-cat="all">All skills</button>
    <button class="filter-btn" data-cat="frontend">Frontend</button>
    <button class="filter-btn" data-cat="tools">Tools</button>
    <button class="filter-btn" data-cat="backend">Backend & Data</button>
  </div>

  <div class="summary-row" id="summary"></div>

  <div class="skills-grid" id="grid"></div>

  <div class="chart-wrap">
    <p class="chart-title">Skill strength overview</p>
    <div style="position:relative; width:100%; height:240px;">
      <canvas id="radarChart" role="img" aria-label="Radar chart of Khilesh's skill levels across HTML, CSS, JavaScript, React, Tailwind, Git, Python, Streamlit">HTML 90, CSS 85, JavaScript 70, React 60, Tailwind 75, Git 65, Python 50, Streamlit 45.</canvas>
    </div>
  </div>

</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js"></script>
<script>
const skills = [
  { name:'HTML5',       cat:'frontend', pct:90, icon:'ti-brand-html5',  bg:'#fae8e0', iconColor:'#993C1D' },
  { name:'CSS3',        cat:'frontend', pct:85, icon:'ti-brand-css3',   bg:'#e6f1fb', iconColor:'#185FA5' },
  { name:'JavaScript',  cat:'frontend', pct:70, icon:'ti-brand-javascript', bg:'#faeeda', iconColor:'#854F0B' },
  { name:'React.js',    cat:'frontend', pct:60, icon:'ti-brand-react',  bg:'#e1f5ee', iconColor:'#0F6E56' },
  { name:'Tailwind',    cat:'frontend', pct:75, icon:'ti-droplet',      bg:'#e1f5ee', iconColor:'#0F6E56' },
  { name:'Responsive',  cat:'frontend', pct:80, icon:'ti-device-mobile', bg:'#eeedfe', iconColor:'#534AB7' },
  { name:'Git',         cat:'tools',    pct:65, icon:'ti-brand-git',    bg:'#fae8e0', iconColor:'#993C1D' },
  { name:'GitHub',      cat:'tools',    pct:65, icon:'ti-brand-github', bg:'#f1efe8', iconColor:'#5F5E5A' },
  { name:'VS Code',     cat:'tools',    pct:85, icon:'ti-code',         bg:'#e6f1fb', iconColor:'#185FA5' },
  { name:'Figma',       cat:'tools',    pct:55, icon:'ti-brand-figma',  bg:'#fbeaf0', iconColor:'#993556' },
  { name:'Python',      cat:'backend',  pct:50, icon:'ti-brand-python', bg:'#eaf3de', iconColor:'#3B6D11' },
  { name:'Streamlit',   cat:'backend',  pct:45, icon:'ti-chart-bar',    bg:'#fcebeb', iconColor:'#A32D2D' },
];

function level(p) {
  if (p >= 80) return { label:'Expert',   cls:'lvl-expert' };
  if (p >= 65) return { label:'Strong',   cls:'lvl-strong' };
  if (p >= 50) return { label:'Growing',  cls:'lvl-growing' };
  return            { label:'Learning', cls:'lvl-learning' };
}

function barColor(p) {
  if (p >= 80) return '#1D9E75';
  if (p >= 65) return '#378ADD';
  if (p >= 50) return '#BA7517';
  return '#888780';
}

function render(cat) {
  const grid = document.getElementById('grid');
  grid.innerHTML = '';
  const visible = cat === 'all' ? skills : skills.filter(s => s.cat === cat);

  visible.forEach(s => {
    const lv = level(s.pct);
    const card = document.createElement('div');
    card.className = 'skill-card';
    card.innerHTML = `
      <div class="skill-header">
        <div class="skill-icon" style="background:${s.bg}">
          <i class="ti ${s.icon}" style="color:${s.iconColor}" aria-hidden="true"></i>
        </div>
        <div>
          <div class="skill-name">${s.name}</div>
          <div class="skill-cat">${s.cat}</div>
        </div>
      </div>
      <div class="bar-row">
        <div class="bar-bg"><div class="bar-fill" data-pct="${s.pct}" style="background:${barColor(s.pct)}"></div></div>
        <span class="bar-pct">${s.pct}%</span>
      </div>
      <span class="level-badge ${lv.cls}">${lv.label}</span>
    `;
    grid.appendChild(card);
  });

  setTimeout(() => {
    grid.querySelectorAll('.bar-fill').forEach(b => {
      b.style.transform = `scaleX(${b.dataset.pct / 100})`;
    });
  }, 60);

  updateSummary(visible);
}

function updateSummary(list) {
  const avg = Math.round(list.reduce((a, s) => a + s.pct, 0) / list.length);
  const expert = list.filter(s => s.pct >= 80).length;
  const strong = list.filter(s => s.pct >= 65 && s.pct < 80).length;
  const top = list.slice().sort((a, b) => b.pct - a.pct)[0];
  document.getElementById('summary').innerHTML = `
    <div class="sum-card"><div class="sum-num">${list.length}</div><div class="sum-lbl">Skills tracked</div></div>
    <div class="sum-card"><div class="sum-num">${avg}%</div><div class="sum-lbl">Avg proficiency</div></div>
    <div class="sum-card"><div class="sum-num">${expert}</div><div class="sum-lbl">Expert level</div></div>
    <div class="sum-card"><div class="sum-num">${strong}</div><div class="sum-lbl">Strong level</div></div>
  `;
}

document.getElementById('filters').addEventListener('click', e => {
  const btn = e.target.closest('.filter-btn');
  if (!btn) return;
  document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
  btn.classList.add('active');
  render(btn.dataset.cat);
});

render('all');

const isDark = matchMedia('(prefers-color-scheme: dark)').matches;
const gridColor = isDark ? 'rgba(255,255,255,0.08)' : 'rgba(0,0,0,0.07)';
const labelColor = isDark ? '#8899cc' : '#5b6a8a';

new Chart(document.getElementById('radarChart'), {
  type: 'radar',
  data: {
    labels: ['HTML5','CSS3','JavaScript','React','Tailwind','Git','Python','Streamlit'],
    datasets: [{
      label: 'Proficiency',
      data: [90,85,70,60,75,65,50,45],
      backgroundColor: isDark ? 'rgba(55,138,221,0.18)' : 'rgba(55,138,221,0.12)',
      borderColor: '#378ADD',
      borderWidth: 1.5,
      pointBackgroundColor: '#378ADD',
      pointRadius: 4,
      pointHoverRadius: 6,
    }]
  },
  options: {
    responsive: true,
    maintainAspectRatio: false,
    scales: {
      r: {
        min: 0, max: 100,
        ticks: { stepSize: 25, color: labelColor, font: { size: 11 }, backdropColor: 'transparent' },
        grid: { color: gridColor },
        angleLines: { color: gridColor },
        pointLabels: { color: labelColor, font: { size: 12 } }
      }
    },
    plugins: {
      legend: { display: false },
      tooltip: {
        callbacks: { label: ctx => ` ${ctx.raw}% proficiency` }
      }
    }
  }
});
</script>
 khilesh_skills_dashboard.html…]()

---

## 🌌 Featured Projects

<div align="center">

| 🚀 Project | 🌙 Description | ⭐ Tech |
|:---:|:---:|:---:|
| [**🎵 Spotify Clone**](https://github.com/Khilesh81/Spotify-Clone) | Music player · dark UI · audio controls · playlists | `HTML` `CSS` `JS` |
| [**🪟 Microsoft Clone**](https://github.com/Khilesh81/Microsoft-clone) | Pixel-perfect Microsoft homepage | `HTML` `Tailwind CSS` |
| [**⚡ Teknix**](https://github.com/Khilesh81/Teknix-) | Modern React app with clean design | `React` `Tailwind` |
| [**📊 Smart Retail Dashboard**](https://github.com/Khilesh81/Smart-retail-dashboard) | KPI dashboards · inventory · billing analytics | `Python` `Streamlit` |
| [**🌐 Web Project 1**](https://github.com/Khilesh81/Web-Project-1) | Foundational frontend showcase | `HTML` `CSS` `JS` |

</div>

---

## 📡 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Khilesh81&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0a0a2e&title_color=8ba8e0&icon_color=c8d6f0&text_color=8899cc&count_private=true" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=Khilesh81&theme=midnight-purple&hide_border=true&background=0a0a2e&ring=8ba8e0&fire=c8d6f0&currStreakLabel=8ba8e0&sideLabels=8899cc&dates=8899cc" />

<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Khilesh81&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0a0a2e&title_color=8ba8e0&text_color=8899cc&langs_count=6" />

</div>

---

## 🌠 Contribution Constellation

<div align="center">
  <img src="https://ghchart.rshah.org/8ba8e0/Khilesh81" width="100%" alt="Khilesh's Contribution Graph"/>
</div>

<br/>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Khilesh81&bg_color=0d0d3d&color=8ba8e0&line=5b7fba&point=c8d6f0&area=true&area_color=1a1a4e&hide_border=true&radius=6" width="100%" alt="Activity Graph"/>
</div>

---

## 🏆 Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Khilesh81&theme=darkhub&no-frame=true&no-bg=true&margin-w=6&column=6" width="100%"/>
</div>

---

## 🌙 Connect With Me

<div align="center">

<br/>

### 🚀 Let's build something amazing together!

<br/>

| Platform | Link |
|:---:|:---:|
| 🐙 **GitHub** | [![GitHub](https://img.shields.io/badge/Khilesh81-Follow%20Me-0a0a2e?style=for-the-badge&logo=github&logoColor=c8d6f0&labelColor=1a1a4e)](https://github.com/Khilesh81) |
| 💼 **LinkedIn** | [![LinkedIn](https://img.shields.io/badge/Khilesh-Connect-0a0a2e?style=for-the-badge&logo=linkedin&logoColor=c8d6f0&labelColor=1a1a4e)](https://linkedin.com/in/khilesh) |
| 🌐 **Portfolio** | [![Portfolio](https://img.shields.io/badge/My%20Portfolio-Visit%20Now-0a0a2e?style=for-the-badge&logo=firefox-browser&logoColor=c8d6f0&labelColor=1a1a4e)](https://khilesh81.github.io) |
| 📧 **Email** | [![Email](https://img.shields.io/badge/Gmail-Say%20Hi!-0a0a2e?style=for-the-badge&logo=gmail&logoColor=c8d6f0&labelColor=1a1a4e)](mailto:your@email.com) |
| 🐦 **Twitter / X** | [![Twitter](https://img.shields.io/badge/Twitter-Follow-0a0a2e?style=for-the-badge&logo=x&logoColor=c8d6f0&labelColor=1a1a4e)](https://twitter.com/khilesh81) |
| 💬 **Discord** | [![Discord](https://img.shields.io/badge/Discord-Chat-0a0a2e?style=for-the-badge&logo=discord&logoColor=c8d6f0&labelColor=1a1a4e)](https://discord.com/users/khilesh81) |
| 📸 **Instagram** | [![Instagram](https://img.shields.io/badge/Instagram-Follow-0a0a2e?style=for-the-badge&logo=instagram&logoColor=c8d6f0&labelColor=1a1a4e)](https://instagram.com/khilesh81) |

<br/>

> *"The best interface is the one that feels inevitable."* 🌙

<br/>

![Wave](https://raw.githubusercontent.com/mayhemantt/mayhemantt/Update/svg/Bottom.svg)

</div>

---

<!-- Moon Footer -->
<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0d0d3d,50:1a1a4e,100:0a0a2e&height=140&section=footer&text=✦%20Thanks%20for%20Visiting%20✦&fontSize=24&fontColor=8ba8e0&animation=fadeIn&desc=🌙%20Keep%20building%20%7C%20Keep%20growing%20%7C%20Keep%20shining%20⭐&descSize=14&descColor=5b7fba&descAlignY=70" width="100%"/>

<div align="center">
  <sub>🌙 Crafted with passion under the moonlight by <a href="https://github.com/Khilesh81"><b>Khilesh</b></a> &nbsp;·&nbsp; ⭐ Star my repos if you like my work! &nbsp;·&nbsp; 🌌 Let's connect!</sub>
</div>
