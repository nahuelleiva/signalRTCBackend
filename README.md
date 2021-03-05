# signalRTCBackend
Backend developed in C# that serves a signaling server for the "WebToWeb" videocall application.

Recommended Visual Studio 2019 and at least .NET Core 3.1, otherwise you'll need to upgrade your tools

* Clone or download the code.
* Open the .sln file with Visual Studio 2019.
* Update the ```Startup.cs``` file, in the ```ConfigureServices``` function change the localhost URLs to the ones you are executing the Ionic/Electron project.
* Run the project, that's it!
* It's a console application so a console will remain opened for you to work with your WebToWeb application.
