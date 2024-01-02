# Eau Claire's Salon

#### An MVC web app for managing employees and clients at a hair salon.

#### By Aidan Williams

## Technologies Used

* _C#_
* _.NET_

## Description

A web app where a hair salon owner can manage the salon's stylists and their respective clients.

## Setup Instructions

1. Clone this repo.
2. Open MYSQL Workbench and connect to your local server.
3. Select Server > Data Import in your toolbar.
4. Select 'Import from Self-Contained File' under Import Options and select the .sql file located in this repo's directory.
5. Select 'Start Import' under the Import Progress tab.
6. Navigate to this project's production directory.
    1. Create a file called "appsettings.json"
    2. Add the following code to the file (username and password credentials are for your local server):
    
        `{
          "ConnectionStrings": {
            "DefaultConnection": "Server=localhost;Port=3306;database=aidan_williams;uid=[YOUR-USERNAME-HERE];pwd=[YOUR-PASSWORD-HERE];"
          }
        }`
7. Open your terminal (e.g., Terminal or GitBash) and navigate to this project's production directory.
8. Run `dotnet run` in the command line.
9. Visit https://localhost:5001/ in your web browser.
10. Optionally, you can run `dotnet build` to compile this website without running a local server.

## Known Bugs

* _No known bugs._

## License

_[GPL](https://en.wikipedia.org/wiki/GNU_General_Public_License)_

Copyright (c) _2023_ _Aidan Williams_