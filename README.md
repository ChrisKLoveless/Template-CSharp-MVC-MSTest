# Project NAme

#### Description

## Contributors

* Chris Loveless

## Description
<!-- This project is a simple web application for a business to keep track of Stylists and their Clients. Stylists and Clients have a one to many relationship meaning each Client only belongs to one Stylist. A Stylist can have many clients. The application allows the user to create, update, delete, and view lists of the Stylists they employ and their corresponding clients. The app also includes fields for notes about the clients. -->

## Technologies Used

* _C#_
* _Html_
* _CSS_
* _ASP .NET6_
* _MySQL_
* _MVC_
* _Entity Framework Core_

## Setup/Installation Requirements

* Install MySQL Community Server and MySQL Workbench. Follow the instructions _[here](https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-and-configuring-mysql/)_.
* Clone down the git repo ```https://github.com/ChrisKLoveless/ProjectName.Solution.git``` to the ```desktop``` directory.
* Open the project with VSCode or a different source code editor.
* Restore required packages: change directory to ```ProjectName``` and restore with ```$ dotnet restore```

## Database Setup

* To connect your database, create file ```appsettings.json``` in the production directory ```ProjectName```
* Fill in the file with the following code: Be sure to replace the required fields marked with ```[]``` that must contain the database name, user id, and password.
```
{
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=[DB-NAME-HERE];uid=[YOUR-USERNAME-HERE];pwd=[YOUR-PASSWORD-HERE];"
    }
}
```
* While in the ```ProjectName``` directory use ```$ dotnet build``` to build the program.
* To include this projects' data structure, change directory to ```ProjectName```, and run ```dotnet ef migrations add Initial``` and then run ```dotnet ef database update```
* While in the ```ProjectName``` directory use ```$ dotnet watch run``` to run the program in the browser with a watcher.

## Known Bugs

* If any bugs are found please email a brief description to: ```chriskloveless@gmail.com```

## License
Copyright (c) 2022 Chris Loveless
_[MIT](https://choosealicense.com/licenses/mit/)_