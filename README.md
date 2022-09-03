# orm-ecommerce - [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
Back end code for an e-commerce site using Express.js API
## **Description**
The `orm-ecommerce` application is built as back end code for an e-commerce site. This allows users to view, modify delete, and create existing and new categories, products, and tags.

## **Table of Contents**

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Technology](#technology)
- [Questions](#questions)

## **Installation**

To install this application, make a `clone` of this repository to your local machine. Open the repository in your code editor of choice 🖥️ 

## **Usage**

Once the repository is cloned to your local machine, then:

Launch from the Terminal:
- Install the required packages by running `npm i` in your applicable terminal
- Update the `.env` file with your `MySQL username` and `MySQL password`.
- Run the `schema.sql` in mysql to create and populate existing tables.
- Run `node seeds/index.js` to seed the database with test data.
- Run `node server.js` in your applicable terminal
- Open `Insmonia` to run the following API GET, POST, PUT, and DELETE routes to successfully create, update, and delete data in the database.

Create Schema from the MySQL Shell and Seed Database:

![Walkthrough of orm-ecommerce Initiation]()

GET Routes for All Categories, All Products, and All Tags:

![Walkthrough of GET Routes for All in Insomnia]()

GET Routes for Single Categories, Single Products, and Single Tags:

![Walkthrough of GET Routes for Singles in Insomnia]()

POST, PUT, and DELETE Routes for Categories:

![Walkthrough of POST, PUT, and DELETE Routes for Categories in Insomnia]()

POST, PUT, and DELETE Routes for Products:

![Walkthrough of POST, PUT, and DELETE Routes for Products in Insomnia]()

POST, PUT, and DELETE Routes for Tags:

![Walkthrough of POST, PUT, and DELETE Routes for Tags in Insomnia]()

## **License**

<p>
MIT License

Copyright &copy; 2022 Cheryl Caitano

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

</p>

## **Technology**

- [JavaScript](https://www.javascript.com/) Scripting Language
- [Node](https://nodejs.org/en/) JavaScript runtime
- [npm](https://www.npmjs.com/) Inquirer, msql2, sequelize, console.table
- [Express]() Express.js
- [MySQL](https://dev.mysql.com/doc/) MySQL Database
- [Sequelize](https://www.npmjs.com/package/sequelize) Sequelize
## **Questions**

For any questions or contributions please contact me on Github or by e-mail:

[Github Profile](https://www.github.com/ccaitano)  
[Email Me](mailto:cheryl.caitano@gmail.com)

Will update in the future to add delete functionality and the ability to view employees by department and by manager.