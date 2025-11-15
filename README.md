<h1 align="center">Hi 👋, I'm Pratyaksh Jain</h1>
<h3 align="center">Young innovator • Web Developer • Robotics & AI enthusiast</h3>

---

## 🚀 About Me  
- 👨‍🎓 11th grade student from India  
- 🧠 Passionate about **Robotics, Machines, AI, Web Development,Tech**
- 🤝 **Interned with multiple NGOs**, contributing to education, community upliftment, and youth empowerment  
- 💻 Completed **CS50** and currently exploring advanced software projects  
- 🌱 Learning **AI, game dev, and advanced web systems**  
- 🌍 Founder of **Harmoney**, a youth-led initiative empowering underprivileged kids  
- 🎥 Running a **Instagram channel** & building creative tech content  
- 💡 Dream: Build cutting-edge tech + get into a top engineering college
- 🎥 **Created the YouTube Channel- "Rhyme “Apple", which crossed 90,000+ views within one month**  

---

## 🛠️ Tech Stack  
**Frontend:** HTML, JavaScript*(learning)*  
**Backend:** Python, Flask *(learning)*  
**Other:** Git, GitHub, APIs, AI Tools  
**Currently Exploring:** AI, autonomous robotics, and cloud hosting  

---

## 🔥  Projects  
### 🌿 **Harmony – Youth Empowerment Website**  
A clean, responsive website built for my NGO initiative. Hosted on Netlify + GitHub.

### 🧪 **Bulk WhatsApp Sender**  
A smart automation tool that lets users send bulk WhatsApp messages efficiently for outreach, announcements, and campaigns. Built with a simple interface and fast execution.

### 🎮 **Tic Tac Toe Game (Web / Python)**  
A fun, lightweight implementation of Tic-Tac-Toe featuring clean UI and smooth logic. Great example of game fundamentals and interactive design.

---

## 🏆 Achievements  
- 🎓 **CS50 Certified**  
- 📚 Built multiple websites from scratch  
- 📊 Published blogs on **Medium** (CSR, SDGs, ESG & more)  
- 🎤 Active in **Model United Nations (MUN)**  
- 🚀 Campus Ambassador at **Veritas St. Paul’s MUN 2025**  

---

## 📈 GitHub Stats  
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pratyakshjain&show_icons=true&theme=tokyonight" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pratyakshjain&layout=compact&theme=tokyonight" height="170" />
</p>
<!-- GitHub Readme Stats -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pratyakshjain&show_icons=true&count_private=true&theme=tokyonight" alt="Pratyaksh's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pratyakshjain&layout=compact&theme=tokyonight" alt="Top Languages" />
</p>

<!-- GitHub Streak / Trophies -->
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=pratyakshjain&theme=tokyonight" alt="streak stats" />
  <img src="https://github-profile-trophy.vercel.app/?username=pratyakshjain&theme=tokyonight&margin-w=10" alt="trophies" />
</p>
name: Generate Contribution Snake GIF

on:
  schedule:
    - cron: '0 0 * * 0' # runs weekly (UTC). Change as you like.
  workflow_dispatch: {}

jobs:
  build-snake:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4
      - name: Set up Node.js
        uses: actions/setup-node@v4
        with:
          node-version: '18'
      - name: Install contrib-snake generator
        run: |
          npm install -g @platane/snk
      - name: Generate snake GIF
        run: |
          snk --user pratyakshjain --output contrib-snake.gif --theme dark --dimensions 700 160
      - name: Commit generated GIF
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "41898282+github-actions[bot]@users.noreply.github.com"
          git add contrib-snake.gif || true
          git commit -m "chore: update contribution snake" || echo "no changes to commit"
          git push
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
<p align="center">
  <img src="./contrib-snake.gif" alt="Contribution Snake" />
</p>
<h1 align="center">Hi 👋 I'm Pratyaksh Jain</h1>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pratyakshjain&show_icons=true&count_private=true&theme=tokyonight" />
</p>

<p align="center">
  <img src="./contrib-snake.gif" alt="Contribution Snake" width="700"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=pratyakshjain&theme=tokyonight" />
  <img src="https://github-profile-trophy.vercel.app/?username=pratyakshjain&theme=tokyonight" />
</p>


---

## 🤝 Connect With Me  
🌐 Portfolio/Website: *Coming Soon*  
📷 Instagram (Tech): *DM me to collaborate*  
✉️ Reach me anytime for projects, collabs, or learning together!

---

⭐ **“Building cool things today that my future self will be proud of.”**  
