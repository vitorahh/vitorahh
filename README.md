```Csharp
	
public class Profile
{
    public string name { get; set; }
    public int age { get; set; }
    public string city { get; set; }
    public string[] Skills { get; set; }
}
public class Developer
{
   public Profile getDevFullstack()
    {
      Profile Dev = new Profile();
      Dev.name = "Willian gomes Vitor";
      Dev.age = 28;
      Dev.city = "Belo Horizonte | MG";
      Dev.Skills = new string[] { "React JS", "React Native", "C#", "NodeJS", "Docker", "SQL Server", "MongoDb"};

     return Dev;
   }
}
```
