<h1 align="center">✦ Anas.fz </h1>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="600" />
</div>

<p align="center">
  Bonjour, moi c'est <strong>Anas</strong> !<br>
  Développeur passionné par la création de projets utiles et bien conçus.
</p>

<p align="center">
  <a href="https://portfolio-five-orcin-41.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Mon_Portfolio-Visit-black?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
</p>

```csharp
namespace AboutMe
{
    public class Person
    {
        public string Name             { get; } = "Anas";
        public string Location         { get; } = "Toulouse, France";
        public string Education        { get; } = "Bachelor Concepteur Développeur Web Full Stack";
        
        public List<string> Languages  { get; } = new() { "TypeScript", "Swift", "C++", "JavaScript" };
        
        public List<string> CurrentlyLearning { get; } = new() 
        {
            "Next.js", "Supabase", "Docker"
        };
        
        public string Goal { get; } = "Créer des projets utiles et bien conçus";
    }
}
