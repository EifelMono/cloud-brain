# EF

## [github](https://github.com/aspnet/EntityFrameworkCore)

## DOC

* [EF Doc german](https://docs.microsoft.com/de-de/ef/)
* [EF Doc english](https://docs.microsoft.com/en-us/ef/)

* [EF Core github](https://github.com/aspnet/EntityFrameworkCore)
* [EF Core Roadmap](https://docs.microsoft.com/de-de/ef/core/what-is-new/roadmap)

* [Announcing Entity Framework Core 2.1](https://blogs.msdn.microsoft.com/dotnet/2018/05/30/announcing-entity-framework-core-2-1/)

## www

* [Many to Many](https://blog.oneunicorn.com/2017/09/25/many-to-many-relationships-in-ef-core-2-0-part-1-the-basics/)
* [The Data Farm is Julie Lerman](http://thedatafarm.com/)
* [EFCore.BulkExtensions](https://github.com/borisdj/EFCore.BulkExtensions?fbclid=IwAR17vvprPMUDclcX_8G4XBHn2rxCW1S1U4MT8VQghNXPrSZ6DWFfawgAsdU)
* [sqlbulkcopy](https://docs.microsoft.com/en-us/dotnet/api/system.data.sqlclient.sqlbulkcopy?fbclid=IwAR1kof-3s9izfiS-686tdbvlTrVb0plY2fTMaumS32GbmQlp1vRxA0aDCnA&view=netframework-4.7.2)
* [EntityFrameworkCore Logging in ASP.NET Core](https://wildermuth.com/2018/11/07/EntityFrameworkCore-Logging-in-ASP-NET-Core#disqus_thread)

## PLURALSIGHT

### EF Core

* [Entity Framework Core 2: Getting Started](https://app.pluralsight.com/library/courses/entity-framework-core-2-getting-started/table-of-contents)
* [Entity Framework Core 2: Mappings](https://app.pluralsight.com/library/courses/e-f-core-2-beyond-the-basics-mappings/table-of-contents)
* [Entity Framework Core 2.1: What's New Playbook](https://app.pluralsight.com/library/courses/playbook-ef-core-2-1-whats-new/table-of-contents)

### EF

* [Entity Framework in the Enterprise](https://app.pluralsight.com/library/courses/entity-framework-enterprise-update/table-of-contents)

### others
* [Domain-Driven Design Fundamentals](https://app.pluralsight.com/library/courses/domain-driven-design-fundamentals/table-of-contents)

### Visual Studio

* [SQLServerCompactSQLiteToolbox](https://marketplace.visualstudio.com/items?itemName=ErikEJ.SQLServerCompactSQLiteToolbox)
* [SQLServerCompactSQLiteToolbox Standalone](http://erikej.github.io/SqlCeToolbox/#three)

### Logging ef

```csharp
using (MyDatabaseEntities context = new MyDatabaseEntities())
{
    context.Database.Log = s => System.Diagnostics.Debug.WriteLine(s);
    // query the database using EF here.
}
```

