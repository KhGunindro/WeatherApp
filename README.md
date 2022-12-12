# WeatherApp

<h3>🚩This is an application made for college minor project🚩</h3>

It's a cross platform app which can be run on basically any device but for now we have not added the functionalities for windows and macOS.
It can only run on android and iphone as of now.

tech stack:
1. C#
2. XAML
3. JSON
4. XML
5. .NET

### Design patern used:
MVVM(Model View View-Model)

### How it works?
It's a very simple application. The way how it works is; it uses a free weather api called *Open-Meteo* from where we get our data in the form of JSON.
Then we embed the data in the **model** folder which in turn gives the data to **view-model** then it is presented in form of various GUI objects in the
**view**.
