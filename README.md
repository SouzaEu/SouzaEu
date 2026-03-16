```csharp
    public class Developer
    {
        public string Name       = "Vinícius Souza Carvalho";
        public string Location   = "São Paulo, Brasil";
        public string Profession = "Software developer";
    
        public string[] Languages = { "Python", "Java", "C#", "TypeScript", "Go", "SQL" };
    
        public string[] Skills = {
            "Spring Boot", "ASP.NET", "FastAPI",
            "Next.js", "Angular", "React",
            "Docker", "PostgreSQL", "Redis",
            "n8n", "Playwright", "OpenAI API",
        };
    
        public string CurrentlyBuilding = "nSeven — compliance regulatório para a América Latina";
        public string[] CurrentlyLearning = { "Spring Boot avançado", "Hibernate", "Oracle", "Arquitetura distribuída" };
    
        public Dictionary<string, string> Contact = new()
        {
            { "email",     "vsouzaeu@icloud.com"    },
            { "linkedin",  "linkedin.com/in/souzav"  },
            { "portfolio", "souzadev.vercel.app"     },
        };
    }
    
    var dev = new Developer();
    Console.WriteLine(dev);
