# E.C.B.E - E-Commerce Back-End

[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)

## Description

This is a back-end for an e-commerce application. It's uses Express and Sequelize to interact with a MSQL Database to retrieve, create, update, or delete products, categories and tags of those products.

A video walkthrough has been recorded to demonstrate its functions. 

> Github Repository Link: [https://github.com/Bickolus/ecbe](https://github.com/Bickolus/ecbe)
>
> Video Link for Setup: [https://user-images.githubusercontent.com/96181899/155817343-114a2397-bf0a-4865-b2e2-031ac541c256.mp4](https://user-images.githubusercontent.com/96181899/155817343-114a2397-bf0a-4865-b2e2-031ac541c256.mp4)
> Video Link for Tests: [https://user-images.githubusercontent.com/96181899/155817349-6817b6af-c724-4c99-ac46-55c589876072.mp4](https://user-images.githubusercontent.com/96181899/155817349-6817b6af-c724-4c99-ac46-55c589876072.mp4)

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Example](#example)
4. [License](#license)
5. [Questions](#questions)

## Installation

Type "npm install" in the console to install the dependancies this application requires (Express, MySQL2, Dotenv, and Sequelize). You would also need a MySQL server running to be able to create the database and seed it with items. 

## Usage

In order to run this program, a couple things need to be done. Firstly, the user must create a database by logging into their mySQL server ("mySQL -u root -p" in a terminal), then typing "source ./db/schema.sql". Secondly, seed the database by typing "node ./seeds/index.js" in another terminal. Thirdly, type "npm start" to run the server. Your localhost:3001/api/ URL will now display objects. Use a program like Insomnia to check out GET, POST, PUT, DELETE http methods.

## Example

### Gifs of the Program Running

![Gif of TETA running](./images/ecbe-demo-01.gif)

![Gif of TETA running](./images/ecbe-demo-02.gif)

![Gif of TETA running](./images/ecbe-demo-03.gif)

### Video Demonstration

#### Setting up

https://user-images.githubusercontent.com/96181899/155817343-114a2397-bf0a-4865-b2e2-031ac541c256.mp4

#### Testing Routes

https://user-images.githubusercontent.com/96181899/155817349-6817b6af-c724-4c99-ac46-55c589876072.mp4

## License

This project is not under any license.

## Questions

My GitHub Page: [Bickolus](https://github.com/Bickolus)

If you have any additional questions, please contact me at smbraza97@gmail.com.
