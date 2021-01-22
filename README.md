```Csharp
	
public class Profile
{
    public string name { get; set; }
    public int age { get; set; }
    public string city { get; set; }
    public string[] Skills { get; set; }
}
public class VitorWillian
{
   public Profile getDevFullstack()
    {
      Profile Dev = new Profile();
      Dev.name = "Willian gomes Vitor";
      Dev.age = 24;
      Dev.city = "Belo Horizonte | MG";
      Dev.Skills = new string[] { "ReactJS - TS", "C#", "Aspx", "NodeJS - TS", "Docker", "SQL Server", "Power BI", "SSIS"};

     return Dev;
   }
}
```
