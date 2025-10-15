

# 👋 Hi, I'm MohammadReza Y.

### Full Stack Developer | Python & Django Specialist

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=8B5CF6&center=true&vCenter=true&width=435&lines=Full+Stack+Developer;Python+%26+Django+Expert;Clean+Code+Enthusiast;Passionate+Learner" alt="Typing SVG" />

[![GitHub followers](https://img.shields.io/github/followers/MohammadReza.Y?style=social)](https://github.com/MohammadReza.Y)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=Linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat&logo=Gmail&logoColor=white)](mailto:youremail@example.com)

</div>

---

## 🎯 About Me

Full Stack Web Developer specializing in **Python** and **Django**, proficient in modern UI design with **TailwindCSS** and database management with **MySQL**. 

Passionate about building web applications that are:
- 🚀 Fast and Responsive
- 📈 Scalable and Maintainable  
- 🎨 User Experience Focused
- 💡 Built with Clean Code Principles

---

## 🛠️ Technical Skills

<div align="center">

### Backend Development
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### Frontend Development
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Alpine.js](https://img.shields.io/badge/Alpine.js-8BC0D0?style=for-the-badge&logo=alpine.js&logoColor=black)

### Database & Tools
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 💼 Featured Projects

<div align="center">

### 🛒 Laptop & Computer Store

\`\`\`
Professional e-commerce website with MVC architecture
\`\`\`

**✨ Key Features:**
- 📦 Smart product and inventory management
- 🛍️ Advanced shopping cart with automatic calculations
- 🔍 Advanced search with smart filters
- 📱 Fully responsive design (Mobile First)
- 🗄️ Optimized relational database

**🔧 Tech Stack:** Django • MySQL • TailwindCSS • Alpine.js

---

### 🏋️ Diet & Fitness Website

\`\`\`
Comprehensive health and fitness platform
\`\`\`

**✨ Key Features:**
- 🥗 Personalized diet plans
- 💪 Professional fitness tips and workouts
- 👥 User and program management panel
- 📊 Progress tracking and personal statistics
- 🎨 Modern and user-friendly design

**🔧 Tech Stack:** Django • PostgreSQL • JavaScript • CSS Grid

</div>

---

## 📊 GitHub Statistics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=MohammadReza.Y&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=8B5CF6&icon_color=14F195&text_color=FFFFFF"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MohammadReza.Y&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=8B5CF6&text_color=FFFFFF"/>

</div>

<div align="center">

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=MohammadReza.Y&theme=tokyonight&hide_border=true&background=0D1117&ring=8B5CF6&fire=14F195&currStreakLabel=8B5CF6)](https://git.io/streak-stats)

</div>

---

## 🏆 Achievements

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=MohammadReza.Y&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 📫 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/yourprofile)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:youremail@example.com)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/yourusername)

</div>

---

<div align="center">

### 💭 Currently...

*Working on new projects and improving my skills*  
*I'd love to collaborate with you!* ✨

[![Profile Views](https://komarev.com/ghpvc/?username=MohammadReza.Y&color=8B5CF6&style=for-the-badge)](https://github.com/MohammadReza.Y)

---

**⭐ Like my projects? Give them a star!**

</div>
`;


export const ReadmeEditor = () => {
  const [markdown, setMarkdown] = useState(defaultReadme);
  const [showPreview, setShowPreview] = useState(true);

  const handleCopy = () => {
    navigator.clipboard.writeText(markdown);
    toast.success("Copied!", {
      description: "README copied to clipboard"
    });
  };

  const handleDownload = () => {
    const blob = new Blob([markdown], { type: "text/markdown" });
    const url = URL.createObjectURL(blob);
    const a = document.createElement("a");
    a.href = url;
    a.download = "README.md";
    document.body.appendChild(a);
    a.click();
    document.body.removeChild(a);
    URL.revokeObjectURL(url);
    toast.success("Downloaded!", {
      description: "README.md file downloaded"
    });
  };

  return (
    <div className="grid grid-cols-1 lg:grid-cols-2 gap-6 h-full">
      <Card className="p-6 bg-gradient-to-br from-card/50 to-card backdrop-blur-sm border-primary/20">
        <div className="flex items-center justify-between mb-4">
          <h2 className="text-xl font-bold bg-gradient-to-r from-primary to-accent bg-clip-text text-transparent">
            Editor
          </h2>
          <div className="flex gap-2">
            <Button
              variant="outline"
              size="sm"
              onClick={handleCopy}
              className="border-primary/30 hover:bg-primary/10"
            >
              <Copy className="w-4 h-4 ml-2" />
              Copy
            </Button>
            <Button
              variant="outline"
              size="sm"
              onClick={handleDownload}
              className="border-accent/30 hover:bg-accent/10"
            >
              <Download className="w-4 h-4 ml-2" />
              Download
            </Button>
          </div>
        </div>
        <Textarea
          value={markdown}
          onChange={(e) => setMarkdown(e.target.value)}
          className="min-h-[600px] font-mono text-sm bg-background/50 border-primary/20 focus:border-primary/50 transition-all"
          placeholder="Write your README here..."
          dir="ltr"
        />
      </Card>

      <Card className="p-6 bg-gradient-to-br from-card/50 to-card backdrop-blur-sm border-accent/20">
        <div className="flex items-center justify-between mb-4">
          <h2 className="text-xl font-bold bg-gradient-to-r from-accent to-primary bg-clip-text text-transparent">
            Preview
          </h2>
          <Button
            variant="outline"
            size="sm"
            onClick={() => setShowPreview(!showPreview)}
            className="border-accent/30 hover:bg-accent/10"
          >
            <Eye className="w-4 h-4 ml-2" />
            {showPreview ? "Hide" : "Show"}
          </Button>
        </div>
        {showPreview && (
          <div className="min-h-[600px] overflow-auto bg-background/50 rounded-lg p-6 border border-accent/20">
            <div
              className="prose prose-invert max-w-none prose-headings:text-foreground prose-p:text-muted-foreground prose-a:text-primary hover:prose-a:text-accent prose-strong:text-foreground prose-code:text-accent"
              dangerouslySetInnerHTML={{
                __html: `<iframe srcdoc="${markdown
                  .replace(/"/g, "&quot;")
                  .replace(/\n/g, "&#10;")}" 
                  style="width: 100%; min-height: 600px; border: none; background: #0d1117; color: #c9d1d9;" 
                  sandbox="allow-same-origin"></iframe>`,
              }}
            />
          </div>
        )}
      </Card>
    </div>
  );
};
