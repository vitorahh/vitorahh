```Csharp

    public class Perfil
	{
		 public string name { get; set; }
		 public int age { get; set; }
		 public string city { get; set; }
		 public List<string> Skills { get; set; }
	}
    public class VitorWillian
    {
        public Perfil getDev()
        {
            Perfil Dev = new Perfil();
            Dev.name = "Willian gomes Vitor";
            Dev.age = 24;
            Dev.city = "Belo Horizonte | MG";

            string[] Hability = { "ReactJS", "C#", "Node", "TypeScript", "Docker", "SQL Server", "Power BI", "SSIS" };

            Dev.Skills = Hability.ToList();

           return Dev;
        }
    }
```
