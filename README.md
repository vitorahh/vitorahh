```Csharp
	
public class Perfil
{
	 public string name { get; set; }
	 public int age { get; set; }
	 public string city { get; set; }
	 public string[] Skills { get; set; }
}
public class VitorWillian
{
	public Perfil getDev()
	{
	    Perfil Dev = new Perfil();
	    Dev.name = "Willian gomes Vitor";
	    Dev.age = 24;
	    Dev.city = "Belo Horizonte | MG";
	    Dev.Skills = new string[] { "ReactJS", "C#", "Aspx", "NodeJS", "TypeScript", "Docker", "SQL Server", "Power BI", "SSIS"};

	   return Dev;
	}
}
```
