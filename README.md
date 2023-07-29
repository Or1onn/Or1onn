<h1 align="center">Hi there, I'm <a href="https://github.com/Or1onn" target="_blank">Orhan</a>
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32" /></h1>

### <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> About me:


```c#
using System;

namespace AboutMe
{
    public class Person
    {
        public string? Name { get; set; }
        public string? Surname { get; set; }
        public int Age { get; set; }
    }


    public class Knowledge
    {
        public List<string?> Languages { get; set; }
        public List<string?> DataBase { get; set; }
        public List<string?> Technology { get; set; }
        public List<string?> DevOps { get; set; }
        public List<string?> ML_DL { get; set; }
        public List<string?> Design { get; set; }
        public List<string?> Others { get; set; }
    }


    internal class Program
    {
        static void Main(string[] args)
        {
            Person person = new Person();
            Knowledge knowledge = new Knowledge();

            person.Name = "Orhan";
            person.Surname = "Salahetdinov";

            person.Age = 18;

            knowledge.Languages = new() { "C", "C++", "C#", "Python", "JavaScript", "TypeScript" };

            knowledge.DataBase = new() { "MSSQL", "MYSQL", "SQLite" };

            knowledge.Technology = new()
             {
              ".NET", "ASP.NET", "WinForms", "WPF", "ADO.NET", "EntityFramework",
              "jQuery", "Expo", "JWT", "NPM", "NodeJS", "Unity", "Redux",
              "Xamarin", "Yarn", "QT", "CMake", "Electron.js"
             };

            knowledge.DevOps = new() { "Azure", "Docker", "Kubernetes" };
            
            knowledge.ML_DL = new() { "OpenCV", "TensorFlow" };
            
            knowledge.Design = new() { "React", "XAML", "HTML", "CSS", "SASS", "QML", "Markdown", "Bootstrap"};
            
            knowledge.Others = new() { "Figma", "Canva", "Linux", "Jira", "Notion", "Postman", "Swagger", "Trello", "Slack", "Obsidian" };
        }
    }
}
```
---

<div align="center">
<a href="https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2FOr1onn"><img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FOr1onn&labelColor=%23555555&countColor=%23F0B354"/></a>
</div>
