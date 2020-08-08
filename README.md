# Factory Tracker

  ### By Joseph Pearce

## Description

An application to keep track of Dr. Sneuss's machine repairs. It will be a MVC web application to help manage their engineers, and the machines they are licensed to fix.



## Specifications

| Spec                                                                              | Input                                                          | Output                                      |
| :-------------------------------------------------------------------------------- | :------------------------------------------------------------- | :------------------------------------------ |
| 1. Program will create an Engineer object with name | "Rocky" | "Rocky"  |
| 2. Program will assign a unique id to each Engineer | "Rocky" | Id: 1  |
| 3. Program will allow users to add Machine object to the Engineer List | "Boring" | "Boring" |
| 4. Program will allow users to edit Engineer object | "Rocky" |   "Buster"    |
| 5. Program will allow users to delete Engineer object  | "Rocky" | Null |
| 6. Program will allow users to edit Machine object | "Boring" |  "Trencher"        |
| 7. Program will allow users to delete Machine object | "Ms Jones" | Null |
| 8. Program will provide navigation links to add, view, edit and delete Engineers |  |  |
| 9. Program will provide navigation links to add, view, edit and delete Machines |  |  |



## Languages & Technologies Used:

  ### Programming Languages, Libraries, & Frameworks
  * CSHTML
  * CSS
  * C#
  * Entity Framework
  * MVC
  * MySQL
  * .NET Core
  * Razor

  ### Operating Systems & Programs
  * Brave
  * Microsoft PowerShell
  * Microsoft Windows 10
  * MySQL Workbench
  * Visual Studio Code

## Installation


- _Clone or download this repository located at https://github.com/pearcy/DrSneuss.Solution.git
- _Open the downloaded directory in a text editor of your choice. (VSCode, Atom, etc.)
- _Run \$ dotnet restore to download all dev dependencies_ Ensure that dotnet restore is targeting the directory containing the .csproj file

- _Open the downloaded directory in a text editor of your choice. (VSCode, Atom, etc.)
- _Run \$ dotnet restore to download all dev dependencies_ Ensure that dotnet restore is targeting the directory containing the .csproj file

- Double-click the downloaded .NET Core 2.2 SDK file and run the installer.
- Open your computer's terminal and navigate to the directory bearing the name of the program and containing the top level subdirectories and files.

### Database Setup Instructions

  In the Factory folder run these commands to run migrations to create a new database
- dotnet ef migrations add Initial
- dotnet ef database update

### Run Program

- Enter the command "dotnet build" in the terminal.
- Enter the command "dotnet run" in the terminal. The program should begin to run in the console.


## Known Bugs

- No known bugs.


## Support & Contact Details

  * You are welcome to contact the authors via GitHub with any concerns, feedback, possible contributions, questions, or suggestions.


### Contributors
 
  * [Joseph Pearce]()



### License

  * This program is free to use under the GNU General Public License GPLv3. © 2020 Joseph Pearce. All rights reserved.