<!-- 
  =========================================
  🚨 INSTRUCTIONS TO MAKE THE SNAKE VISIBLE 🚨
  =========================================
  To make the contribution snake grid work and show up on your profile:
  1. Create a repository on GitHub named exactly your username: "SonuSuraj1807".
  2. Create a folder structure inside that repo: `.github/workflows/`
  3. Create a file inside named `snake.yml` and paste the following content:

  name: Generate Datas

  on:
    schedule: # Run every 12 hours
      - cron: "0 */12 * * *"
    workflow_dispatch:
    push:
      branches:
      - main

  jobs:
    generate:
      runs-on: ubuntu-latest
      timeout-minutes: 10
      
      steps:
        - name: generate github-contribution-grid-snake.svg
          uses: platane/snk/svg-only@v3
          with:
            github_user_name: ${{ github.repository_owner }}
            outputs: |
              dist/github-contribution-grid-snake.svg
              dist/github-contribution-grid-snake-dark.svg?palette=github-dark
            
        - name: push github-contribution-grid-snake.svg to the output branch
          uses: crazy-max/ghaction-github-pages@v3.1.0
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  =========================================
-->

<div align="center">

<!-- 🔥 ANIMATED HEADER BANNER - MAXIMUM CHAOS MODE 🔥 -->
<img src="https://capsule-render.vercel.app/api?type=venom&color=gradient&customColorList=0,2,2,5,30&height=300&section=header&text=SURAJ%20RAO&fontSize=90&fontColor=fff&animation=twinkling&fontAlignY=30&desc=⚠️%20WARNING:%20This%20Profile%20Contains%20Dangerously%20High%20Levels%20of%20Overfitting%20⚠️&descAlignY=55&descSize=16" width="100%"/>

<br>

<!-- THE MOST DRAMATIC ENTRANCE EVER -->
<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="50">
<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="50">
<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="50">

<br>

<!-- ANIMATED TYPING SVG - NOW WITH MORE CHAOS -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&duration=2500&pause=800&color=FF6EC7&center=true&vCenter=true&multiline=true&repeat=true&random=false&width=900&height=100&lines=%F0%9F%91%8B+Yo!+I'm+Suraj+Rao+%26+I'm+BUILT+DIFFERENT+%F0%9F%92%AA;%F0%9F%A7%A0+Data+Science+student+who+overfits+to+coffee+%E2%98%95%EF%B8%8F;%F0%9F%90%9B+I+don't+create+bugs%2C+I+create+statistical+anomalies+%F0%9F%93%88;%F0%9F%94%A5+My+brain+has+too+many+epochs+running;%F0%9F%8E%AF+I+debug+at+3AM+like+a+mass+legend;%F0%9F%92%80+Sleep+is+just+a+weak+regularization+technique;%F0%9F%A4%AF+I+THINK+THEREFORE+I+OVERFIT" alt="Typing SVG" /></a>

</div>

---

<!-- 🎭🎭🎭 THE LEGENDARY INTRO - BUCKLE UP 🎭🎭🎭 -->

<div align="center">

## 🚨 STOP SCROLLING. YOU FOUND THE FUNNIEST DEVELOPER/DATA SCIENTIST ON GITHUB. 🚨

<img src="https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif" width="400">

<br>

> **Plot twist:** I mass mass mass mass mass train neural networks for a living and my GPU hasn't exploded... yet.

<br>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Permanent+Marker&size=22&duration=2000&pause=500&color=F8D866&center=true&vCenter=true&repeat=true&width=700&height=50&lines=Welcome+to+my+GitHub+%F0%9F%8E%89+Please+keep+your+arms+inside+the+vehicle;This+profile+is+FDA+approved+for+stress+relief+%F0%9F%98%82;Side+effects+include:+importing+pandas+as+pd+and+laughing" alt="Typing SVG" /></a>

</div>

---

<div align="center">

## 🧠 Who Is This Absolute Legend? (It's Me. I'm The Legend.)

</div>

<table>
<tr>
<td width="50%">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="100%">

</td>
<td width="50%">

### Hey there! I'm **Suraj Rao** 👋

- 🎓 **Big brain energy** — Mass mastered the art of Googling `ValueError: shapes not aligned` before you even design the layers
- 💻 **Data Scientist & Web Dev** — which means I mass mass mass clean datasets and break CSS grids on BOTH ends
- 🧠 **200 IQ Moves:** I write training scripts that not even I understand. That's called *job security*.
- 🏆 **CEO of "It Converged On My Machine"**
- 🎭 **Professional at pretending to understand the deep math behind neural networks**
- 🌍 Based in India 🇮🇳 — where the models run on chai ☕
- 🔥 I mass mass mass solve problems that don't exist, then create regex patterns that can't be solved
- 🤓 **Fun fact:** I mass mass mass have dreams in PyTorch. The tensors don't align there either.

</td>
</tr>
</table>

<div align="center">

<!-- ME EXPLAINING MY CODE -->
<table>
<tr>
<td align="center">
<b>Me explaining my model to senior devs</b><br><br>
<img src="https://media.giphy.com/media/gEvab1ilmJjA82FaSV/giphy.gif" width="220">
</td>
<td align="center">
<b>Senior devs looking at my code</b><br><br>
<img src="https://media.giphy.com/media/l3q2K5jinAlChoCLS/giphy.gif" width="220">
</td>
<td align="center">
<b>My model in production</b><br><br>
<img src="https://media.giphy.com/media/dJYoOVAWf2QkU/giphy.gif" width="220">
</td>
</tr>
</table>

</div>

---

<div align="center">

## 🎪 The "About Me" But Make It UNHINGED

</div>

```python
class SurajRao(DataScientist, FullStackDeveloper, CaffeineDependentLifeForm):
    
    def __init__(self):
        self.name = "Suraj Rao"
        self.username = "SonuSuraj1807"
        self.location = "India 🇮🇳 (timezone: whenever the training finishes)"
        self.iq = float('inf')  # trust me bro
        self.mass_intelligence = "so intelligent it's scary (or overfitted)"
        self.brain = "runs on mass parallel processing epochs"
        self.coffee_consumed_today = 99999
        self.bugs_created = self.bugs_fixed + 1  # always one epoch ahead 😤
        self.mass_skills = ["Mass Debugging", "Mass Wrangling", "Mass Matplotlib Styling"]
        
    def get_daily_mass_schedule(self):
        return {
            "05:30": "🚽 Throne time. Best architecture designs happen here. No cap.",
            "06:00": "Alarm rings. Check GPU status. Still running. Mass sleep continues.",
            "09:00": "Wake up. Open VS Code. Regret.",
            "09:05": "Mass Google 'how to change legend position in matplotlib'",
            "10:00": "Attend meeting. Camera off. Still in bed importing pandas.",
            "12:00": "Mass lunch break (actually 2 hours of dataset cleaning memes)",
            "14:00": "Write 200 lines of code. Get 199 dimension mismatch errors.",
            "15:30": "🚽 Round 2. Coffee hits different. Solved 3 matrix issues in there.",
            "16:00": "Mass mass mass mass mass StackOverflow session",
            "18:00": "'Just one more epoch' — the biggest lie I tell myself",
            "22:00": "Find a bug. It's been there since SIH 2024.",
            "03:00": "Still training. Questioning existence.",
            "04:00": "IT CONVERGED!! *touches nothing ever again*"
        }
    
    def mass_mass_mass_introduction(self):
        return "I am mass mass mass mass mass intelligent, mass funny, mass coding 24/7"
    
    def superpower(self):
        return "I can mass mass mass mass mass mass mass mass mass mass mass mass mass mass" \
               " mass mass mass mass mass mass mass mass mass mass mass mass mass mass debug"
```

---

<div align="center">

## 🎬 My Life As A Data Scientist — The Movie

</div>

<table align="center">
<tr>
<td align="center" width="200">

### 🎬 Act 1: "The Awakening"
<img src="https://media.giphy.com/media/077i6AULCXc0FKTj9s/giphy.gif" width="180">
<br>
*Opens VS Code*
<br>
*Sees 47 shape errors*
<br>
*"This is fine"* 🔥

</td>
<td align="center" width="200">

### 🎬 Act 2: "The Struggle"
<img src="https://media.giphy.com/media/13HgwGsXF0aiGY/giphy.gif" width="180">
<br>
*Tries to fix 1 bug*
<br>
*Creates 7 more*
<br>
*"I'm a genius"* 🧠

</td>
<td align="center" width="200">

### 🎬 Act 3: "The Denial"
<img src="https://media.giphy.com/media/l1J9EdzfOSgfyueLm/giphy.gif" width="180">
<br>
*Googles error message*
<br>
*First result from 2011*
<br>
*Still works* 💀

</td>
<td align="center" width="200">

### 🎬 Act 4: "The Miracle"
<img src="https://media.giphy.com/media/26ufdipQqU2lhNA4g/giphy.gif" width="180">
<br>
*`warnings.filterwarnings('ignore')`*
<br>
*EVERYTHING WORKS*
<br>
*I'M A GOD* ⚡

</td>
</tr>
</table>

---

<div align="center">

## 😂 DEVELOPER STRESS RELIEF ZONE 😂
### (You Need This. Trust Me.)

<img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" width="350">

</div>

<details>
<summary>🤣 Click here if your code doesn't work (spoiler: it never does)</summary>

<br>

<div align="center">

<img src="https://media.giphy.com/media/1BXa2alBjrCXC/giphy.gif" width="300">

<br>

**Developer Therapy Session:**

```
🩺 Doctor: "Where does it hurt?"
💻 Me: *points at node_modules and NaN loss*

🩺 Doctor: "How long has this been going on?"
💻 Me: "Since npm install and model.fit()"

🩺 Doctor: "Have you tried turning it off and on again?"
💻 Me: "That's... that's my whole job"

🩺 Doctor: "I'm prescribing you mass mass mass mass mass mass mass mass mass mass mass rest"
💻 Me: "ERROR: rest is not defined"
```

</div>

</details>

<details>
<summary>🧘 Click here for Developer Meditation (You'll Need It)</summary>

<br>

<div align="center">

<img src="https://media.giphy.com/media/xT5LMHxhOfscxPfIfm/giphy.gif" width="300">

```
🧘 Close your eyes...
🧘 Take a deep breath...
🧘 Repeat after me:

"The bug is not my fault"
"The model convergence is not my fault"
"The dataset was already biased"

...

"Okay maybe it is my fault"
"But I mass mass mass mass mass mass refuse to accept it"
"random_state=42 will fix everything"
"If not, mass mass mass revert to last commit"
"May the mass mass mass force compile"
```

</div>

</details>

<details>
<summary>🎰 Click for a Random Meme That Describes My Life</summary>

<br>

<div align="center">

<table>
<tr>
<td align="center">
<b>"Works on my machine"</b><br>
<img src="https://media.giphy.com/media/NV4cSrRYXXwfUcYnua/giphy.gif" width="200">
</td>
<td align="center">
<b>"Just mass mass mass mass mass mass mass mass mass mass mass mass mass mass mass mass mass mass restart the server"</b><br>
<img src="https://media.giphy.com/media/KEYEpIngcmXlHetDqz/giphy.gif" width="200">
</td>
<td align="center">
<b>"I'll fix it tomorrow"</b><br>
<img src="https://media.giphy.com/media/QMHoU66sBXqqLqYvGO/giphy.gif" width="200">
</td>
</tr>
<tr>
<td align="center">
<b>"Reading my own code after 2 weeks"</b><br>
<img src="https://media.giphy.com/media/WRQBXSCnEFJIuxktnw/giphy.gif" width="200">
</td>
<td align="center">
<b>"When the tests pass on first try"</b><br>
<img src="https://media.giphy.com/media/11sBLVxNs7v6WA/giphy.gif" width="200">
</td>
<td align="center">
<b>"When production goes down at 5 PM"</b><br>
<img src="https://media.giphy.com/media/3o7TKSjRrfIPjeiVyM/giphy.gif" width="200">
</td>
</tr>
</table>

</div>

</details>

---

<div align="center">

## 🧪 Mass Mass Mass Intelligence Report Card

</div>

```
╔══════════════════════════════════════════════════════════════╗
║                   🏫 SURAJ'S REPORT CARD                    ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  Debugging Skills:      A+++ (mass mass mass level)          ║
║  Google-Fu:             S-TIER (I find answers before         ║
║                         the question exists)                  ║
║  Copy-Paste from SO:    LEGENDARY                             ║
║  Actually Reading Docs: F- (what are docs?)                   ║
║  Coffee Consumption:    CRITICAL HIGH ☕☕☕☕☕               ║
║  Sleep Schedule:        ERROR 404                             ║
║  Code Quality:          "It works, don't touch it"            ║
║  Git Commits:           "fixed stuff" "fixed stuff again"     ║
║  Variable Naming:       df, df2, temp_df, df_final_v3         ║
║  Meeting Attendance:    Present (camera off, training models) ║
║  Mass IQ Level:         Over 9000 🧠💥                       ║
║                                                              ║
║  Overall Grade: A+ (self-graded, obviously)                  ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

---

<div align="center">

## 🤯 The 5 Stages of Model Training (Starring Me)

</div>

<table align="center">
<tr>
<td align="center" width="180">

**1️⃣ DENIAL**
<br>
<img src="https://media.giphy.com/media/3o7btPCcdNniyf0ArS/giphy.gif" width="150">
<br>
*"There's no way*
*this model has NaN loss,*
*my code is perfect"*

</td>
<td align="center" width="180">

**2️⃣ ANGER**
<br>
<img src="https://media.giphy.com/media/l1J9u3TZfpmeDLkD6/giphy.gif" width="150">
<br>
*"WHO FORGOT TO*
*NORMALIZE THIS*
*DATASET?!"*
<br>
*git blame: it was me*

</td>
<td align="center" width="180">

**3️⃣ BARGAINING**
<br>
<img src="https://media.giphy.com/media/uA8WItRYSRkfm/giphy.gif" width="150">
<br>
*"Dear God, if this*
*loss value drops, I'll*
*write docstrings"*

</td>
<td align="center" width="180">

**4️⃣ DEPRESSION**
<br>
<img src="https://media.giphy.com/media/ISOckXUybVfQ4/giphy.gif" width="150">
<br>
*CUDA out of memory*
<br>
*Opens LinkedIn*
<br>
*Is farming still a thing?*

</td>
<td align="center" width="180">

**5️⃣ ACCEPTANCE**
<br>
<img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" width="150">
<br>
*`lr = 0.0`*
<br>
*Look, the loss curve*
*is completely flat!*
<br>
*Ships it* 🚀

</td>
</tr>
</table>

---

<div align="center">

## 🎭 Developer Memes That Are Basically My Autobiography

<table>
<tr>
<td align="center">
<img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" width="220">
<br><b>Me pretending to understand<br>the codebase</b>
</td>
<td align="center">
<img src="https://media.giphy.com/media/unQ3IJU2RG7DO/giphy.gif" width="220">
<br><b>When my mass mass mass mass<br>code passes all tests</b>
</td>
<td align="center">
<img src="https://media.giphy.com/media/Vuw9m5wXviFIQ/giphy.gif" width="220">
<br><b>Deploying on Friday at 5PM<br>like a true psychopath</b>
</td>
</tr>
<tr>
<td align="center">
<img src="https://media.giphy.com/media/lP8xu5t2DLGG045H8F/giphy.gif" width="220">
<br><b>When the intern asks<br>"what does this do?"</b>
</td>
<td align="center">
<img src="https://media.giphy.com/media/citBl9yPwnUOs/giphy.gif" width="220">
<br><b>Reading mass mass mass mass<br>error logs at 3 AM</b>
</td>
<td align="center">
<img src="https://media.giphy.com/media/xUPGcguWZHRC2HyBRS/giphy.gif" width="220">
<br><b>When "npm audit fix" actually<br>fixes something</b>
</td>
</tr>
</table>

</div>

---

<div align="center">

## 🏆 My GitHub Trophy Cabinet (Yes, I'm Flexing HARD)

💪 *Behold my mass mass mass mass mass mass mass achievements* 💪

<img src="https://github-profile-trophy.vercel.app/?username=SonuSuraj1807&theme=radical&no-frame=true&no-bg=true&margin-w=15&margin-h=15&column=7" width="100%" />

<img src="https://media.giphy.com/media/3o6fJ1BM7R2EBRDnxK/giphy.gif" width="200">

</div>

---

<div align="center">

## 📊 Stats That Prove I Have No Life Outside Code (And I'm Proud)

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=SonuSuraj1807&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=FF6EC7&icon_color=F8D866&text_color=FFFFFF&ring_color=FF6EC7" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=SonuSuraj1807&theme=radical&hide_border=true&background=0D1117&ring=FF6EC7&fire=F8D866&currStreakLabel=FF6EC7" />

<br>

<img width="55%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SonuSuraj1807&layout=donut-vertical&theme=radical&hide_border=true&bg_color=0D1117&title_color=FF6EC7&text_color=FFFFFF&langs_count=8" />

<br>

<img src="https://media.giphy.com/media/3oKIPnAiaMCJ8dO8dW/giphy.gif" width="200">

<sub>*These numbers are real. My social life isn't.*</sub>

</div>

---

<div align="center">

## 📈 Contribution Graph (Sleep Deprivation Visualized In Real-Time)

<img src="https://github-readme-activity-graph.vercel.app/graph?username=SonuSuraj1807&bg_color=0D1117&color=FF6EC7&line=F8D866&point=FFFFFF&area=true&area_color=FF6EC7&hide_border=true&custom_title=Suraj's%20Contribution%20Graph%20(aka%20Proof%20I%20Need%20Help%20%F0%9F%86%98)" width="100%"/>

</div>

---

<div align="center">

## ⚡ Tech Stack (Things I Mass Mass Mass Mass Mass Pretend to Know)

<img src="https://media.giphy.com/media/juua9i2c4fYQE/giphy.gif" width="300">

<br><br>

<img src="https://skillicons.dev/icons?i=js,ts,react,nextjs,nodejs,express,python,django,flask,mysql,postgres,mongodb,docker,aws,git,github&perline=8" />
<br>
<img src="https://skillicons.dev/icons?i=vscode,linux,figma,postman,firebase,vercel,netlify,npm,anaconda,jupyter,sklearn,tensorflow,pytorch,opencv,html,css&perline=8" />

<br>

> 💡 *I know mass mass mass mass mass all of these.* **\*narrator: he knows 3 of them\***

</div>

---

<div align="center">

## 🎪 The Error Message Hall of Fame (My Greatest Hits Album)

</div>

<details>
<summary>🏆 Click to see my beautiful collection of failures (mass mass mass failures)</summary>

<br>

<div align="center">
<img src="https://media.giphy.com/media/9J7tdYltWyXIY/giphy.gif" width="250">
</div>

<br>

| # | Error | My Reaction | My "Solution" | Time Spent |
|---|-------|-------------|---------------|------------|
| 1 | `ValueError: shapes not aligned` | 😱 "WHAT" | `.T` transposed random matrix | 4 hours |
| 2 | `OutOfMemoryError: CUDA out of memory` | 💀 *soul leaves body* | `batch_size = 1` | 6 hours |
| 3 | `NameError: name 'pd' is not defined` | 🤡 "But I JUST ran that cell" | Re-run cells above | 2 hours |
| 4 | `TypeError: Cannot read property of null` | 😤 "JavaScript you LIAR" | Blamed JS. Rightfully. | 3 hours |
| 5 | `Segmentation fault (core dumped)` | 🪦 *writes will* | Googled "farming jobs near me" | 8 hours |
| 6 | `git merge conflict` | 🔥🔥🔥 | `git reset --hard` and mass mass mass pretended nothing happened | 5 hours |
| 7 | `ENOSPC: no space left on device` | 📦 "HOW" | 47 `node_modules` = 900GB apparently | 1 hour |
| 8 | `Maximum call stack size exceeded` | 🌀 *infinite loop of sadness* | My code is as recursive as my pain | forever |
| 9 | `Loss is NaN` | 📉 "WHY" | Lowered learning rate to `1e-9` | 6 hours |
| 10 | `Cannot find module 'happiness'` | 😢 | Still searching... | ongoing |

</details>

---

<div align="center">

## 🎯 Current Life Status (100% Real, 0% Cap)

</div>

```
██████████████████████████████  99%  Mass Mass Mass Mass Mass Mass Mass Mass Debugging
█████████████████████████████░  95%  Being Absolutely HILARIOUS
████████████████████████████░░  90%  Questioning Every Life Choice
██████████████████████████░░░░  85%  Pretending I Know What I'm Doing
███████████████████████░░░░░░░  75%  Coffee In My Veins ☕☕☕
████████████████████░░░░░░░░░░  65%  Googling "How to mass mass center a div"
█████████████████░░░░░░░░░░░░░  55%  Making Memes Instead of Code
████████████░░░░░░░░░░░░░░░░░░  40%  Imposter Syndrome (it's real folks)
████████░░░░░░░░░░░░░░░░░░░░░░  27%  Sleep (optional DLC I can't afford)
██░░░░░░░░░░░░░░░░░░░░░░░░░░░░   7%  Touching Grass
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   0%  Reading Documentation  
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   0%  Mass Mass Having a Normal Sleep Schedule
```

---

<div align="center">

## 😂 When People Ask "What Do You Do For Fun?"

<table>
<tr>
<td align="center">
<img src="https://media.giphy.com/media/AOSwwqVjNZlDO/giphy.gif" width="230">
<br><b>Me: "I code for fun!"<br>Also me coding for fun:</b>
</td>
<td align="center">
<img src="https://media.giphy.com/media/3o6Zt481isNVuQI1l6/giphy.gif" width="230">
<br><b>When someone says "coding<br>is easy" in front of me</b>
</td>
<td align="center">
<img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" width="230">
<br><b>Me at mass mass mass mass<br>hackathons at 4 AM</b>
</td>
</tr>
</table>

</div>

---

<div align="center">

## 🐍 Watch This Snake Devour My Contributions (Like Bugs Devour My Code)

<!-- 
  CRITICAL INFO FOR SNAKE VISIBILITY:
  The contribution snake requires a GitHub action output. If the branch 'output' or the action is not yet setup,
  the raw.githubusercontent.com path below will return a 404. Pointing to the generator (platane) works as a
  flawless fallback preview! We use your username here so that once you trigger your workflow, it works automatically!
-->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SonuSuraj1807/SonuSuraj1807/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SonuSuraj1807/SonuSuraj1807/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/SonuSuraj1807/SonuSuraj1807/output/github-contribution-grid-snake-dark.svg" width="100%" />
</picture>

</div>

---

<div align="center">

## 💬 Quotes That Live In My Head Rent-Free

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" width="80%" />

<br>

> *"It works on my machine"* — Every developer ever, especially me, MASS especially me  
> *"I'll mass mass mass refactor this later"* — Me, 3 years ago. That code got promoted before I did.  
> *"Just one more commit before bed"* — Famous last words at 2 AM. It's now 7 AM.  
> *"I'm mass mass mass mass mass mass mass mass not mass mass mass addicted to mass mass mass coding"* — Me, mass mass coding at 4 AM
> *"99 little bugs in the code, 99 little bugs... Take one down, patch it around... 127 little bugs in the code"* — My life story

<br>

<img src="https://readme-jokes.vercel.app/api?theme=radical&hideBorder&qColor=%23FF6EC7&aColor=%23F8D866" alt="Jokes Card" width="500" />

</div>

---

<div align="center">

## 🎵 Vibing While Mass Mass Mass Debugging (Music = Fewer Bugs, Probably)

<img src="https://media.giphy.com/media/tqfS3mgQU28ko/giphy.gif" width="250">

<br>

[![spotify-github-profile](https://spotify-github-profile.kittinanx.com/api/view?uid=31ekyfoywqw244opx5tyh4byta5i&cover_image=true&theme=novatorem&show_offline=true&background_color=0d1117&interchange=true&bar_color=FF6EC7)](https://github.com/kittinan/spotify-github-profile)

<br>

<sub>🎧 *Currently listening to: the sound of mass mass mass compilation errors* 🎧</sub>

</div>

---

<div align="center">

<!-- ANIMATED VISITOR COUNTER -->
<img src="https://komarev.com/ghpvc/?username=SonuSuraj1807&style=for-the-badge&color=FF6EC7&label=PROFILE+STALKERS+👀" />

<br><br>

<!-- MEME: This is fine -->
<img src="https://media.giphy.com/media/QMHoU66sBXqqLqYvGO/giphy.gif" width="250">

<br>

### 🚨 ATTENTION: You've scrolled this far. There's no going back. 🚨

<br>

```
                    🏆 CONGRATULATIONS! 🏆
    ┌─────────────────────────────────────────────┐
    │                                             │
    │   You've reached the bottom of my README!   │
    │                                             │
    │   Your reward:                              │
    │                                             │
    │   ⭐ Star this repo                         │
    │   👀 Follow me                              │
    │   🍕 Send pizza                             │
    │   💰 Venmo me mass mass mass $$              │
    │                                             │
    │   (just kidding about the last two)         │
    │   (or am I? 👀)                             │
    │                                             │
    └─────────────────────────────────────────────┘
```

<br>

<!-- ANIMATED JOKE -->
<img src="https://readme-jokes.vercel.app/api?theme=radical&hideBorder&qColor=%23FF6EC7&aColor=%23F8D866" alt="Jokes Card" width="500" />

<br>

<!-- ANOTHER JOKE API -->
<img src="https://readme-jokes.vercel.app/api?theme=tokyonight&hideBorder&qColor=%2300BFFF&aColor=%23FFD700" alt="Jokes Card 2" width="500" />

<br><br>

<!-- FINAL MEME -->
<img src="https://media.giphy.com/media/Vuw9m5wXviFIQ/giphy.gif" width="300">

<br>

*"I came, I saw, I mass mass mass mass mass mass mass mass mass debugged"* — Suraj Rao, probably

</div>

<!-- ANIMATED FOOTER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=200&section=footer&text=Thanks%20for%20visiting!%20Now%20go%20touch%20some%20grass%20🌱&fontSize=24&fontColor=fff&animation=twinkling&fontAlignY=65" width="100%"/>
