# 🎨 Custom Theme Variants for Dhruv Aparnathi

This guide provides 1-click aesthetic swaps inspired by the design references you shared.

---

## 🔴 Variant 1: Persona 5 / Crimson Phantom (Reference: Screenshot 1)
> **Vibe**: High-contrast aggressive red, phantom mask aesthetic, stark black and crimson.

### 1. Banner & Typing SVG
Replace the top `capsule-render` URL:
```html
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0:#000000,30:#1a0000,60:#b30000,100:#ff1744&height=240&section=header&text=DHRUV%20APARNATHI&fontSize=52&fontColor=ffffff&fontAlignY=38&animation=twinkling&desc=%E2%98%85%20PHANTOM%20ARCHITECT%20%E2%80%A2%20FULL%20STACK%20DEV%20%E2%98%85&descFontSize=16&descAlignY=62&descAlign=50" width="100%" />
```

Typing SVG color: change `color=00F5D4` to `color=FF1744`.

### 2. Activity Wave & GitHub Stats
- **Activity Graph**:
  ```html
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=dhruvaparnathi&custom_title=PHANTOM%20CONTRIBUTION%20STREAM&bg_color=000000&color=FF1744&line=FF1744&point=FFFFFF&area=true&area_color=4A0000&hide_border=true" width="100%" />
  ```
- **Stats Card**:
  ```html
  <img src="https://github-readme-stats.vercel.app/api?username=dhruvaparnathi&show_icons=true&theme=blood&hide_border=true&bg_color=000000&title_color=FF1744&icon_color=FF1744&text_color=FFFFFF" />
  ```
- **Streak Card**:
  ```html
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=dhruvaparnathi&theme=blood&hide_border=true&background=000000&ring=FF1744&fire=FF1744&currStreakLabel=FF1744" />
  ```

---

## 🟣 Variant 2: Tokyo Ghoul / Dark Synthwave (Reference: Screenshot 2)
> **Vibe**: Kaneki dark aesthetic, violet neon, deep navy obsidian, cyber telemetry.

### 1. Banner & Typing SVG
```html
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0:#050510,25:#12072b,60:#2e0854,100:#7b2cbf&height=240&section=header&text=DHRUV%20APARNATHI&fontSize=52&fontColor=ffffff&fontAlignY=38&animation=twinkling&desc=%E2%97%86%20CYBER%20ENGINEER%20%E2%80%A2%20HIGH%20CONCURRENCY%20%E2%97%86&descFontSize=16&descAlignY=62&descAlign=50" width="100%" />
```
Typing SVG color: change `color=00F5D4` to `color=C77DFF`.

### 2. Activity Wave & Stats
- **Activity Graph**:
  ```html
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=dhruvaparnathi&custom_title=SYNTHWAVE%20TELEMETRY&bg_color=050510&color=C77DFF&line=9D4EDD&point=00F5D4&area=true&area_color=240046&hide_border=true" width="100%" />
  ```
- **Stats Card**:
  ```html
  <img src="https://github-readme-stats.vercel.app/api?username=dhruvaparnathi&show_icons=true&theme=radical&hide_border=true&bg_color=050510&title_color=C77DFF&icon_color=00F5D4&text_color=E0AAFF" />
  ```

---

## ⚙️ How to Activate the Automated Contribution Snake:
1. Ensure your repository is named exactly `dhruvaparnathi/dhruvaparnathi`.
2. Commit the `.github/workflows/snake.yml` file to your `main` branch.
3. Go to your repository settings -> **Actions** -> **General** -> **Workflow permissions**, and select **"Read and write permissions"**, then click **Save**.
4. Run the workflow manually from the **Actions** tab once, or wait for the cron schedule (runs automatically every 12 hours). It will output the animated snake SVG directly to your `output` branch!

