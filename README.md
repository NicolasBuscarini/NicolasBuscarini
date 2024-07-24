> *Hello World!* <img src="https://raw.githubusercontent.com/kaueMarques/kaueMarques/master/hi.gif" width="30px">

## <img width="25" alt="about" src="https://raw.github.com/elizarov/elizarov/master/about.png"> Sobre mim

<details>
<summary><b>Code:</b></summary>
	
```csharp
using System;
using System.Collections.Generic;

public class Program
{
    public static void Main()
    {        
        var nicolasProgrammer = new Programmer(
            firstName: "Nícolas",
            lastName: "Paiuca Buscarini",
            locale: "São Paulo, SP",
            dateBirth: new DateTime(2001, 2, 7),
            languages: new List<string> { "C#", "TypeScript", "Python" },
            databaseSkills: new List<string> { "MySQL", "SQL Server", "Oracle" },
            education: new List<string> { "Graduation in Computer Science", "Technical Qualification in Industrial Automation" }
        );
        
        Console.WriteLine(nicolasProgrammer.ToString());
    }
}

public class Programmer
{
    public string FirstName { get; private set; }
    public string LastName { get; private set; }
    public string Locale { get; private set; }
    public DateTime DateBirth { get; private set; }
    public List<string> Languages { get; private set; }
    public List<string> DatabaseSkills { get; private set; }
    public List<string> Education { get; private set; }

    public Programmer(
        string firstName, 
        string lastName, 
        string locale, 
        DateTime dateBirth, 
        List<string> languages,
        List<string> databaseSkills,
        List<string> education)
    {
        FirstName = firstName;
        LastName = lastName;
        Locale = locale;
        DateBirth = dateBirth;
        Languages = languages;
        DatabaseSkills = databaseSkills;
        Education = education;
    }
    
    public string FullName
    {
        get { return $"{FirstName} {LastName}"; }
    }

    public int Age
    {
        get
        {
            var today = DateTime.Today;
            var age = today.Year - DateBirth.Year;
            if (DateBirth.Date > today.AddYears(-age)) age--;
            return age;
        }
    }

    public override string ToString()
    {
        return $"Programmer: {FullName},\n" +
               $"Location: {Locale},\n" +
               $"Birthdate: {DateBirth.ToShortDateString()},\n" +
               $"Age: {Age},\n" +
               $"Languages: {string.Join(", ", Languages)},\n" +
               $"Database Skills: {string.Join(", ", DatabaseSkills)},\n" +
               $"Education: {string.Join(", ", Education)}";
    }
}

```

</details>

Console Output:
```console
Programmer: Nícolas Paiuca Buscarini,
Location: São Paulo, SP,
Birthdate: 07/02/2001,
Age: 23,
Languages: C#, TypeScript, Python,
Database Skills: MySQL, SQL Server, Oracle,
Education: Graduation in Computer Science, Technical Qualification in Industrial Automation

```

## **Skills**  

<details open>
	<summary><b>Linguagens:</b></summary>
	<br>
	<img title="Csharp" alt="Csharp" src="https://icongr.am/devicon/csharp-original.svg?size=50&color=currentColor">  
	<img title="TypeScript" alt="TypeScript" src="https://icongr.am/devicon/typescript-original.svg?size=50&color=currentColor">  
	<img title="Java" alt="Java" src="https://icongr.am/devicon/java-original.svg?size=50&color=currentColor">  
	<img title="Python" alt="Python" src="https://icongr.am/devicon/python-original.svg?size=50&color=currentColor">  
	<img title="JavaScript" alt="JavaScript" src="https://icongr.am/devicon/javascript-original.svg?size=50&color=currentColor">  
</details>

<details>
	<summary><b>Frameworks:</b></summary>
	<br>
	<img title="Git" alt="Git" src="https://icongr.am/simple/git.svg?size=50&color=currentColor&colored=true"> 
	<img title="dotNet" alt="dotNet" src="https://icongr.am/devicon/dot-net-original.svg?size=50&color=currentColor"> 
	<img title="Angular" alt="Angular" src="https://icongr.am/devicon/angularjs-original.svg?size=50&color=currentColor"> 
	<img title="Docker" alt="Docker" src="https://icongr.am/devicon/docker-original.svg?size=50&color=currentColor">  
	<img title="npm" alt="npm" src="https://icongr.am/devicon/npm-original-wordmark.svg?size=50&color=currentColor"> 
	<img title="Bootstrap" alt="Bootstrap" src="https://icongr.am/simple/bootstrap.svg?size=50&color=currentColor&colored=true"> 
</details>

<details>
	<summary><b>Banco de Dados:</b></summary>
	<br>
	<img title="MySQL" alt="MySQL" src="https://icongr.am/devicon/mysql-original.svg?size=50&color=currentColor"> 
	<img title="Oracle" alt="Oracle" src="https://icongr.am/devicon/oracle-original.svg?size=50&color=currentColor"> 
	<img title="SqlServer" alt="SqlServer" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/microsoftsqlserver/microsoftsqlserver-original.svg" style="width: 50px; height: 50px;">
</details>

## **GitHub Estatística**

<!-- <p align="center">
	<img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=NicolasBuscarini&theme=github_dark&hide_langs_below=1"/>
</p> -->
 
<p align="center">
	<img align="center" src="https://github-readme-stats.vercel.app/api?username=NicolasBuscarini&show_icons=true&theme=github_dark&line_height=27" alt="Nicolas github stats"/></p>
<br> 

## **Contato**

- E-mail: [nicolasbuscarini@hotmail.com](mailto:nicolasbuscarini@hotmail.com)

- Rede Sociais: <br>
	<a href="https://www.instagram.com/nicolas.buscarini/" target="_blank">
		<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
	</a>
	<a href="https://www.linkedin.com/in/nicolasbuscarini/" target="_blank">
		<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
	</a>
	<a href="https://api.whatsapp.com/send?l=pt&amp;phone=5511995990960" target="_blank">
		<img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white">
	</a>

_____

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=NicolasBuscarini" alt="NicolasBuscarini">
  <img src="https://user-images.githubusercontent.com/5713670/87202985-820dcb80-c2b6-11ea-9f56-7ec461c497c3.gif" width="45px">
</p>

<img src="https://imgur.com/rilHVxA.png"/> 
