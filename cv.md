# Aliaksei Bely

## Contacts

- Phone: (33) 352-61-54
- e-mail: alex_bely@mail.ru

## About me

### I am a software developer and my initial path was to be a back-end developer but now I'd like to be a full-stack developer. Being skilled in both ways brings more opportunities. I participated in two projects and I used to be both in back-end and front-end development. Besides I was in charge of some DevOps automation and repository maintenance.

### Besides my everyday work involved a lot of communication via different channels: emails, meetings, instant chatting. I am familiar with teamwork and cooperation.

### Now I have a long job break because of military service but I want to prepare for my returning learning new stuff about front-end development.

## Skills

### As a back-end developer I'm experienced with .NET Framework, .NET-compatible programming languages (C#/VB.NET) and some related technologies like SQL-databases, Azure Cloud infrastructure.

### My front-end experience includes JavaScript programming using Backbone library and JQuery/Underscore.js underneath.

### Also I'm familiar with Azure Devops services: team boards, repositories, CI/CD pipelines.

## Code examples

Test example from [Codewars](https://www.codewars.com/)

```cs
public static string[] Solution(string str)
{
    var even = str.Where((x, y) => y % 2 == 0);
    var odd = str.Where((x, y) => y % 2 != 0);
    var result = even.Zip(odd)
        .Select(t => string.Concat(t.First, t.Second)).ToList();

    if(str.Length % 2 != 0)
    {
        result.Add(string.Concat(str.Last(), '_'));
    }

    return result.ToArray();
}
```

## Work experience

### I participated in two projects. The first one was a CRM system. I was in charge of the back-end development of some financial operations and simple DevOps automation. The main language was VB.NET as the system is pretty legacy and written with VB.NET. For DevOps routine and Task Management TFS and Azure Devops were used.

### The second project is from the Legal area. It is an electronic discovery software and I participated in both back-end and front-end development. Server side was written with C#. And the UI was made with Backbone so I've used JS as the main language.
