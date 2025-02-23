```c#
public UserInfo GenerateUserInfo()
{
    var userInfo = new UserInfo()
    {
        FirstName = "Ali",
        LastName = "Poustdouzan",
        Email = "ali.poustdouzan@gmail.com",
        Job = ".Net Developer",
        YearsOfExperienceInDotNet = 17,
        InterestedIn = new List<string>()
        {
            ".Net Framework 2 to Dotnet 9",
            "ASP.NET Core Web API",
            "EFCore",
            "End-To-End Encryption",
            "SQL Server, T-SQL",
            "Software Architecture (Mostly Onion)",
            "Microservices",
            "Blazor (Both ServerSide-WebAssembly)"
        },
    };
    return userInfo;
}

```
