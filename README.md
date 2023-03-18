
# Creating .NET Core and React Application

## Using Command Line

1. Open a command prompt or terminal window and navigate to the directory where you want to create the project.

2. Enter the following command to create a new .NET Core SPA project:

**`dotnet new react -n MySPA`**


This will create a new .NET Core SPA project named `MySPA` with React as the front-end framework.

3. Once the project is created, navigate to the project directory:

**`cd MySPA`**


4. Run the project using the following command:

**`dotnet run`**


This will compile and start the application. Once the server is started, you will see a message on the console saying "Now listening on: http://localhost:5000". Open a web browser and navigate to http://localhost:5000. This will open the application in the browser.

## Using Visual Studio

1. Open Visual Studio and select "Create a new project".

2. Select "ASP.NET Core Web Application" and click "Next".

3. Enter a name for your project and click "Create".

4. In the "Create a new ASP.NET Core web application" dialog, select "React.js" as the front-end framework and click "Create".

5. Once the project is created, press F5 to start the application.

6. Once the server is started, the application will automatically open in the default web browser.

## Conclusion

Creating a .NET Core single page application is straightforward using both command line and Visual Studio. Running the project is as simple as executing a command or pressing F5 in Visual Studio. Once the application is running, it can be accessed through a web browser at http://localhost:5000.
