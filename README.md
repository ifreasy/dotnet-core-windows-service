# dotnet-core-windows-service

* .NET Core 3.1 支持

ASP.NET Core 3增加了一个非常有意思的功能Worker Service.他是一个ASP.NET Core模板,他允许我们创建托管长期的运行的后台服务,这些服务具体实现IHostedService接口的后台任务逻辑,他被成为"托管服务".同时他们可以部署到windows中Windows服务，以及Linux守护程序。

* 创建
    > `dotnet new worker -o WorkerService`


发布方式

dotnet restore

dotnet publish

使用

>WorkerServicesName.exe install
>WorkerServicesName.exe start

>WorkerServicesName.exe stop
>WorkerServicesName.exe uninstall

## 参考
[https://www.cnblogs.com/yyfh/p/12159091.html](https://www.cnblogs.com/yyfh/p/12159091.html)
