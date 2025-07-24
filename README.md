<main style="width: 100%;">

<div style="width: 100%;">
    <img src="imgs/header.gif" alt="Header" align="center" style="width: 100%; object-fit: cover; object-position: 50% 50%;"/>
</div>

</br>

<h1 align="center">Hi 👋, I'm Marcelo</h1>

<h3 align="center" style="padding: 0px 20px;">
   Passionate .NET & C# developer focused on cloud-native solutions with Azure, Azure DevOps and Terraform.
</h3>

</br>

- 🔭 I’m currently working at <a href="https://www.volvo.com/" target="_blank">Volvo</a>  
- 🌱 Currently learning: Machine Learning, Prompt Engineering, and .NET technologies  
- ⚡ Working on a personal project: **LineNex**, focused on industrial automation

</br>

```cs
using System;
using System.Collections.Generic;

namespace GitHubProfile
{
    class Bio : IDeveloper, ISkills
    {
        public string Name { get; } = "Marcelo";
        public int Age { get; } = 21;
        public string Location { get; } = "Curitiba, PR - Brazil";

        public List<string> Languages { get; } = new()
        {
            "C#", "Java", "JavaScript", "TypeScript", "Python"
        };

        public List<string> Skills { get; } = new()
        {"Backend", "DevOps", "Cloud", "Frontend", "Always learning"};

        public Bio()
        {
            Console.WriteLine($"👋 Hello, my name is {Name}");
            Console.WriteLine($"🎂 I am {Age} years old");
            Console.WriteLine($"📍 I live in {Location}");
            Console.WriteLine($"💼 My skills include:");
            Skills.ForEach(skill => Console.WriteLine($" - {skill}"));
            Console.WriteLine($"💻 I work with the following programming languages:");
            Languages.ForEach(lang => Console.WriteLine($" - {lang}"));
        }

        static void Main(string[] args) { _ = new Bio(); }
    }
    
    interface IDeveloper
    {
        string Name { get; }
        int Age { get; }
        string Location { get; }
        List<string> Languages { get; }
    }

    interface ISkills
    {
        List<string> Skills { get; }
    }
}
```

<h3 align="center" style="margin-top: 2rem; font-size: 1.5rem;">Technologies That I Know</h3>

<div align="center" style="width: 100%; display: flex; justify-content: center; align-items: center; gap: 0.5rem; margin-top: 1rem;">

[![Techs](https://skillicons.dev/icons?i=dotnet,cs,azure,angular,docker,visualstudio,java,python,terraform,grafana,prometheus,js,ts,html,css,aws,nodejs,eclipse,gherkin,obsidian,postman,figma,git,vscode,powershell,&perline=9)](https://skillicons.dev)
</div>

<h3 align="center" style=" margin-top: 2rem; font-size: 1.5rem;">Connect With Me</h3>

<div align="center" style="width: 100%; display: flex; justify-content: center; align-items: center; gap: 0.5rem; margin-top: 10px; margin-bottom: 10px;">

<a href="https://www.linkedin.com/in/rafael-leal-machado-4966261b3/" target="blank">
    <img align="center" src="https://user-images.githubusercontent.com/88904952/234979284-68c11d7f-1acc-4f0c-ac78-044e1037d7b0.png" alt="linkedin" height="50" width="50"/>
</a>

<a href="https://www.instagram.com/rafael_rlm_/" target="blank">
    <img align="center" src="https://user-images.githubusercontent.com/88904952/234981169-2dd1e58f-4b7e-468c-8213-034ba62156c3.png" alt="instagram" height="50" width="50"/>
</a>

</div>

</br>

<picture>
    <source
        media="(prefers-color-scheme: dark)"
        srcset="https://github.com/marcelowf/marcelowf/blob/output/github-contribution-grid-snake-dark.svg"
    />
    <source
        media="(prefers-color-scheme: light)"
        srcset="https://github.com/marcelowf/marcelowf/blob/output/github-contribution-grid-snake.svg" />
  <img
    alt="github-snake"
    src="https://github.com/marcelowf/marcelowf/blob/output/github-contribution-grid-snake.svg"
    />
</picture>

</main>
