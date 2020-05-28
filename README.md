# Brolio Configuration 

Steps to configure and start working with brolio.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software

```
 Visual Studio for working on Code.
 Mysql Workbench for Database
```
### Configuring

A step by step series of examples that tell you how to get a development env running

 **Visual Studio**

* Open Visual Studio, Click on View Tab on the top, go to the *Team Explorer* in the list.
* Click on the top (Green plugin button) *Manage Connections*.
* Expand *Manage connections* link and open *Connect to a Project*.
* Sign in with your credentials in the *Showing hosted repositories for* dropdown.
* After signing in add *Azure DevOps Server* with URl dev.azure.com.
* You will find the Brolio project in *dev.azure.com/ComitasAG/CoreBusiness* Folder (If you were given the access to Brolio).
* Select the project and click on Clone.

**Mysql Workbench**

 * It is necessary that the data project needs a connection string to a mysql server with a user that has rights to create databases
 * Create a local database and add or update the connection string details in ~\Data\Db.Data\appsettings.json and also in ~\Src\Mvc\Web.config.
 * Then reload the ~\Data\Db.Data, right click on the file, select Debug and run it by click start new instance.
 * All the database will be set and ready to use.




