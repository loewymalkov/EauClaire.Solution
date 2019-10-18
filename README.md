# EauClaire Hair Salon

Hair salon webapp to browse stylists and their clients.

## Use

An MVC web app for a Hair Salon to store stylists and assign clients to them. Built as an independent code review for Epicodus' C# program. 

## Set-up

- enter 'git clone https://github.com/loewymalkov/HairSalon.Solution.git' in a terminal
- navigate to 'HairSalon' project folder and enter 'dotnet restore command'
- must use MySQL Workbench to create database:
  - create a database called loewy_malkovich
  - create two tables: 'stylists' and 'clients'
  - follow the database specs for more details on the columns in each table
- enter 'dotnet watch run' from 'HairSalon' project folder

## Specs

| Behavior | Input | Output | 
|-|-|-|
| As the salon owner, I need to be able to see a list of all stylists.| | |
| As the salon owner, I need to be able to select a stylist, see their details, and see a list of all clients that belong to that stylist.| | |
| As the salon owner, I need to add new stylists to our system when they are hired.| | |
| As the salon owner, I need to be able to add new clients to a specific stylist. I should not be able to add a client if no stylists have been added.| | |
| | | |
| | | | 

## Sample Database

Here is a sample database:

database name: loewy_malkovich


| | | |
| Table | 'stylists' |   Row    |
| Columns |   StylistId     |         |
|       |            |
|       |            |
|       |            |

## Technologies used

C#, MySQL Workbench, VS Code, EntityFramework, HTML with Razor

## Author

Loewy Malkovich
loewymalkov@gmail.com
oct. 2019

## License

Free use license (2019)