```c#
public UserInfo GenerateUserInfo()
{
    var userInfo = new UserInfo()
    {
        FirstName = "Ali",
        LastName = "Poustdouzan",
        Email = "ali.poustdouzan@gmail.com",
        Job = ".Net Developer",
        YearsOfExperienceInDotNet = 15,
        InterestedIn = new List<string>()
        {
            ".Net 6",
            "ASP.NET Core Web API",
            "EF Core",
            "End-To-End Encryption",
            "SQL Server, T-SQL",
            "Software Architecture",
            "Microservice",
            "Blazor (Both ServerSide-WebAssembly)"
        },
    };
    return userInfo;
}

```
