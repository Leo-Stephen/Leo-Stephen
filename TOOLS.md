# 🔧 TOOLS USED TO CREATE THIS PROFILE

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,13,30&height=120&section=header&text=DEVELOPER%20TOOLKIT&fontSize=42&fontColor=bb86fc&animation=fadeIn&fontAlignY=32" alt="header"/>
</div>

This document lists all the tools and resources used to create my GitHub profile README. These tools have been instrumental in creating a visually appealing and interactive profile that showcases my skills and projects.

## 🔄 GitHub Actions Workflows

<div align="center">
  <table>
    <tr>
      <td>
        <ul>
          <li><b><a href="https://github.com/lowlighter/metrics">GitHub Metrics</a></b> - Comprehensive GitHub metrics with customizable plugins</li>
          <li><b><a href="https://github.com/Platane/snk">Snake Animation</a></b> - GitHub contribution graph animation</li>
        </ul>
      </td>
    </tr>
  </table>
</div>

## 📊 Stats & Metrics

<div align="center">
  <table>
    <tr>
      <td>
        <ul>
          <li><b><a href="https://github.com/anuraghazra/github-readme-stats">GitHub Readme Stats</a></b> - Customizable GitHub stats</li>
          <li><b><a href="https://github.com/DenverCoder1/github-readme-streak-stats">GitHub Readme Streak Stats</a></b> - Contribution streak stats</li>
          <li><b><a href="https://github.com/Ashutosh00710/github-readme-activity-graph">GitHub Activity Graph</a></b> - Contribution activity graph</li>
          <li><b><a href="https://github.com/antonkomarev/github-profile-views-counter">GitHub Profile Views Counter</a></b> - Visitor counter</li>
        </ul>
      </td>
    </tr>
  </table>
</div>

## 🎨 Visual Elements

<div align="center">
  <table>
    <tr>
      <td>
        <ul>
          <li><b><a href="https://shields.io/">Shields.io</a></b> - Custom dynamic badges</li>
          <li><b><a href="https://simpleicons.org/">Simple Icons</a></b> - Icons for badges</li>
          <li><b><a href="https://github.com/DenverCoder1/readme-typing-svg">Readme Typing SVG</a></b> - Typing animation</li>
          <li><b><a href="https://github.com/kyechan99/capsule-render">Capsule Render</a></b> - Header/footer images</li>
        </ul>
      </td>
    </tr>
  </table>
</div>

## 🎮 Fun Elements

<div align="center">
  <table>
    <tr>
      <td>
        <ul>
          <li><b><a href="https://github.com/PiyushSuthar/github-readme-quotes">GitHub Readme Quotes</a></b> - Developer quotes</li>
          <li><b><a href="https://github.com/ABSphreak/readme-jokes">GitHub Readme Jokes</a></b> - Random developer jokes</li>
          <li><b><a href="https://github.com/Platane/snk">Snake Animation</a></b> - GitHub contribution graph animation</li>
          <li><b><a href="https://github.com/seanprashad/slackmoji/">GitHub Octocat Animation</a></b> - Animated Octocat</li>
        </ul>
      </td>
    </tr>
  </table>
</div>

## ⚙️ Configuration Files

My profile uses the following GitHub Actions workflow files:

1. **metrics.yml** - Configures the GitHub Metrics workflow

   ```yaml
   name: GitHub Metrics
   on:
     schedule:
       - cron: "0 0 * * *" # Runs daily
     workflow_dispatch: # Or manually trigger it
   jobs:
     github-metrics:
       runs-on: ubuntu-latest
       permissions:
         contents: write
       steps:
         - uses: lowlighter/metrics@latest
           with:
             token: ${{ secrets.METRICS_TOKEN }}
             # Additional configuration...
   ```

2. **snake.yml** - Configures the Snake Animation workflow
   ```yaml
   name: Generate Snake Animation
   on:
     schedule:
       - cron: "0 0 * * *" # Runs once daily
     workflow_dispatch:
   jobs:
     build:
       runs-on: ubuntu-latest
       permissions:
         contents: write
       steps:
         - uses: Platane/snk@v3
           # Additional configuration...
   ```

## 🚀 How to Use These Tools

Most of these tools can be used by including specific URLs in your README.md file. For example:

1. **GitHub Metrics**: Requires setting up a GitHub Action workflow
2. **Shields.io**: Use URLs like `https://img.shields.io/badge/LABEL-MESSAGE-COLOR`
3. **Readme Typing SVG**: Generate custom typing animations through their website
4. **Snake Animation**: Set up a GitHub Action workflow to generate and update the animation

## 🔍 Preview Tools

You can preview your README using these tools:

- [Markdown Live Preview](https://markdownlivepreview.com/) - Paste your README to preview
- [VS Code with Markdown Preview](https://code.visualstudio.com/docs/languages/markdown) - Preview in VS Code

---

<div align="center">
  <div style="background-color: #1a1b27; border-radius: 10px; padding: 15px; max-width: 600px; margin: 20px auto; border: 2px solid #bb86fc;">
    <pre style="color: #8be9fd; font-family: 'Courier New', monospace; text-align: center; margin: 0;">
┌───────────────────────────────────────────────┐
│                                               │
│   <span style="color: #f1fa8c;">Feel free to use these tools for your own profile!</span>      │
│                                               │
└───────────────────────────────────────────────┘
    </pre>
  </div>
</div>
<!-- You can preview this README using these tools: -->
<div align="center">
  <a href="https://markdownlivepreview.com/"><b>Markdown Live Preview</b></a> - Paste your README to preview<br>
  <a href="https://code.visualstudio.com/docs/languages/markdown"><b>VS Code with Markdown Preview</b></a> - Preview in VS Code
</div>
