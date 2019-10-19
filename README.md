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

## Sample Database

Here is a sample database:

database name: loewy_malkovich
| Table | 'stylists' | 
|-|-|
| Columns |   StylistId (PK, NN, AI), Name, Details   |

|    Table   |   'clients'        |
|-|-|
|     Columns  |     ClientId(PK, NN, AI), StylistId (PK, NN), Name       |


## Technologies used

C#, MySQL Workbench, VS Code, EntityFramework, HTML with Razor

## Author

Loewy Malkovich
loewymalkov@gmail.com
oct. 2019

## License

Free use license (2019)