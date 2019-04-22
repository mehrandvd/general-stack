# Stack Overview

## At a glance
The proposed stack at a glance is:
- **Database**: SQL Server (for relational cases), MongoDB (for NoSQL cases)
- **Backend**: .NET Core, C#, EF Core, Autofac
- **Web Frontend**: TypeScript + (Angular or React or Vue)
- **Mobile Frontend**: Xamarin, Prism

## Database
As in any modern architecture, we need to utilize both Relational databases and NoSql database, we suggest platforms for both. SQL Server for relational scenarios and MongoDB for NoSql scenarios.

## Backend
.NET Core is super fast! In fact faster than any commercial platform so far. To prove it, you can check TechEmpower result for its last 3 rounds. The results are unbelivable!
Using .NET Core enables the team to use C# as a language. If in some situations it is required to use a pure functional language, we can use F#.

We prefer to deploy our server-side applications on linux, preferably on docker.

## Web Frontend
Although our current plan is to use TypeScript + (Angular or React or Vue), but as in a near future **WebAssembly** is getting ready and we believe there is lots of opportunities in it. We plan to bring it on the table soon. We sticked our eyes on technologies like **Blazor**, **Xamarin.WebAssembly** and **Uno.WebAssembly** which are actively working on bringing C# experience into the web with WebAssembly unbelievable performance.

## Mobile Frontend
Xamarin is a well formed and mature technology for mobile development. But to rely on it we need a good training process to train Xamarin developers.

