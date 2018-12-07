# Web-based Control Board
AS.Net Core template for sending OSC commands (and more) based on HTTP PUT requests from an HTML client. This template is designed for deploying on a private network, e.g. when controlling one or more audio/video servers and devices connected to the same subnet.
MIT License.

## Installation instructions:
Install .Net Core (Windows or Linux). Run "dotnet run" in the project directory. Open a browser and navigate to https://localhost:5001/main.html

For configuring the web server beyond the default settings (urls, certs, permissions etc.) check out these links: [Kestrel] (https://docs.microsoft.com/en-us/aspnet/core/fundamentals/servers/kestrel?view=aspnetcore-2.2), [http.sys](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/servers/httpsys?view=aspnetcore-2.2) and [everything else](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/servers/?view=aspnetcore-2.2&tabs=windows).

