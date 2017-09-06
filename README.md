## Books API

Books Restful API written in NET Core 2.0.

## Description

A sample of Books Restful API written in NET Core 2.0. This Books API is based on Pluralsight course 
[Building a RESTful API with ASP.NET Core](https://app.pluralsight.com/library/courses/asp-dot-net-core-restful-api-building/table-of-contents) 

## Prerequisite

You need to install the following items in your machine:
* NET Core 2.0 framework
* dotnet cli command
* Microsoft SQL Server

## Installation

1. Clone or download this repository.<br />
   <b>git clone https://github.com/wwardha/NETCore-RESTfulApi-books.git</b>
2. Open <b>NETCore-RESTfulApi-books</b> folder with Visual Studio Code.
3. Add new file appsettings.json in root folder and paste the following code:
   <br /><i>
   {<br/>
        "connectionStrings": {<br/>
            "libraryDBConnectionString": "Server=localhost;Database=LibraryDB;User Id=[Your SQL User Id]; Password=[Your SQL Server Password]"<br/>
        }<br/>
   }</i><br/>
4. Install dependencies with <b>dotnet restore</b>. 
5. Build project by using <b>dotnet build</b>
6. Start the application with <b>dotnet run</b> and Books API will be available on http://localhost/5000

## Technologies

* NET Core 2.0
* Entity Framework Core 2.0