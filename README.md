# Cretaceous Client

#### _A web-based client for the [Cretaceous API](https://github.com/igl-myrick/CretaceousApi.Solution)._

#### By _**India Lyon-Myrick**_

## Technologies Used

* _C#_
* _.NET_
* _Git_

## Description

_A website designed to interface with the [Cretaceous API](https://github.com/igl-myrick/CretaceousApi.Solution). The website features a homepage, which takes you to an index page with a list of the API's animals. From here you can create new animals, or view existing animals. Each animal listed in the API has its own page with information on the animal. In addition to adding new animals to the API, the user has the ability to edit or delete existing animals._

## Setup/Installation Requirements

* _You will need [.NET](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) and [Git](https://git-scm.com/downloads/) in order to run the program. Additionally, you will need to install and run the [Cretaceous API](https://github.com/igl-myrick/CretaceousApi.Solution), which has its own requirements._

_1: Clone the repository to a folder of choice on your machine (by either using the "Code" button on the GitHub page, or in a terminal application using `https://github.com/igl-myrick/CretaceousClient.Solution`)._

_2: At this point, you will need the [Cretaceous API](https://github.com/igl-myrick/CretaceousApi.Solution) installed and running in a terminal._

_3: Using a terminal application such as Git Bash or Windows Command Prompt, navigate to the top level of the program folder, then into the `CretaceousClient` folder._

_4: When the program is running, navigate to `https://localhost:7187` to view and use the website._

## Known Bugs

* _After making an API call which modifies the database (namely through the POST, PUT, and DELETE routes), the user has to refresh the page for the new information to show up._