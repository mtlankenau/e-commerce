# E-Commerce
[![License](https://img.shields.io/badge/License-ISC-red.svg)](https://opensource.org/licenses/ISC)

## Application Video Tutorial
<a href="https://vimeo.com/manage/videos/650882819/1d43a0120b">Click here to watch me walk you through my application!</a>

## Description
Fully functional back end for an e-commerce site that uses Express.js API configured to use Sequelize ORM to interact with a MySQL database.

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Tests](#tests)
* [Questions](#questions)

<a name="install"></a>
## Installation
In order to successfully use this project, the user must have Node.js installed on their machine. This will give the user access to a number of Node's modules, most importantly 'mysql2', 'sequelize', and 'dotenv'. Within MySQL shell, type 'source db/schema.sql' to create the appropriate database. Then, in the terminal, type 'npm run seed' in order to run the seed files and populate the database with initial data. The user should create a '.env' file at the root directory and add their MySQL database, username, and password information, as server.js uses envrionmental variables for this information. Lastly, to begin running the application, type 'npm start' in the command line terminal.

<a name="usage"></a>
## Usage
This project is intended to be used as means of maintaining and expanding upon a database for e-commerce related items. It uses object relational mapping to easily access, edit, add, and delete items from a database. This back-end code could be integrated with a front-end for a fully functional e-commerce website.

<a name="license"></a>
## License
Notice: this application is covered under the ISC license.

<a name="contribute"></a>
## Contributing
If you would like to contribute to this project, submit a pull request within the repository.

<a name="tests"></a>
## Tests
In order to test this project, I recommend installing a JavaScript testing framework, such as Jest, and following their documentation for installation requirements, file structure, syntax, etc. This project is not currently setup with any JavaScript testing frameworks.

<a name="questions"></a>
## Questions
Have more questions about this particular project? Explore one or all of the following options:
* Shoot me an email at <a href = "mailto: mtlankenau@gmail.com">mtlankenau@gmail.com</a>
* Explore my profile on Github by <a href="https://www.github.com/mtlankenau">clicking this link</a>
