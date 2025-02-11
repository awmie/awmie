
```python
from dataclasses import dataclass

@dataclass
class AboutMe:
    name: str = "Amritava Kole"
    email: str = "amritavakole@gmail.com"
    linkedin: str = "https://www.linkedin.com/in/amritava-kole-521bb0229/"
    website: str = "https://awmie.github.io/aboutme/"
    projects: list = ("Discord AI music Bot", "Chain of Though Project - ChatGroq", "Arcadia Esports", "Haven't listed all yet")
    skills: list = (
        "Python", "JavaScript", "TypeScript", "C++", "HTML5", "CSS3", "PHP", "TailwindCSS", "Three.js",
        "MongoDB", "MySQL", "Node.js", "NPM", "Django", "Flask", "TensorFlow", "Keras", "SciPy", "NumPy",
        "Pandas", "Google Cloud", "Heroku", "Vercel", "Anaconda", "Docker", "Linux", 
        "Adobe After Effects", "Adobe Premiere Pro", "Adobe XD", "Affinity Designer", "Canva"
    )

    def __str__(self):
        return f"👋 {self.name}\n📧 {self.email}\n🔗 {self.linkedin}\n🌐 {self.website}\n" + \
               "\n📌 Projects:\n" + "\n".join(f" - {p}" for p in self.projects) + \
               "\n\n⚡ Skills & Tech Stack:\n" + ", ".join(self.skills)

if __name__ == "__main__":
    print(AboutMe())
```

copy and Run the above code [here](https://pythonline.vercel.app/)
---

<a href="https://github.com/awmie">
  <img height="200" align="center" src="https://github-readme-stats.vercel.app/api?username=awmie&hide_border=true&bg_color=0D1117&title_color=ffffff&text_color=cccccc&icon_color=ffffff&icon=github_rank_logo" />
</a>
<a href="https://github.com/awmie">
  <img height="200" align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=awmie&layout=compact&langs_count=8&card_width=320&hide_border=true&bg_color=0D1117&title_color=ffffff&text_color=cccccc&icon_color=ffffff" />
</a>

---
<a href="https://github.com/awmie/GroqChat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=awmie&repo=GroqChat&hide_border=true&bg_color=0D1117&title_color=ffffff&text_color=cccccc&icon_color=ffffff" />
</a>
<a href="https://github.com/awmie/tishmish">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=awmie&repo=tishmish&hide_border=true&bg_color=0D1117&title_color=ffffff&text_color=cccccc&icon_color=ffffff" />
</a>

---

[![GitHub Streak](https://github-readme-streak-stats-six-olive.vercel.app?user=awmie&theme=github-dark-blue&hide_border=true)](https://git.io/streak-stats)

