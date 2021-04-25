# Budget Tracker
![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)


## 💬 Description 
For this project, I updated an existing budget tracker app to allow for offline access and functionality by using IndexedDB and a service worker. This offline functionality includes the ability to enter deposists and expenses, as well as having the offline entries added to the tracker when the app is brought back online. 
This mobile-first app also adds a web manifest to the app's metadata to let users' devices know what they're installing and how the app should look on the home screen. Using MongoDB as the database, this app is deployed to Heroku using MongoDB Atlas.


## 📓 Table of Contents

* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Mock-Up](#mock-up)
* [Installation](#installation)
* [Usage](#usage)
* [Dependencies](#dependencies)
* [License](#license)
* [Badges](#badges)
* [Tests](#tests)
* [Questions](#questions)
* [Contributing](#contributing)


## 🧠User Story
```
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 
```


## 🧩Acceptance Criteria
```
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
```


## 🎨Mock-Up
<br>**The following image shows the web application's appearance and functionality:**</br>
<br>![](public/images/mock-up.png)</br>

## 🔌Installation

The user should clone the repository from GitHub and open up the project in their code editor.
<br>User will need to run node.js and perform an _npm install_ for all necessary dependencies listed below.</br>


## 💻Usage 
To run on _localhost:3001_, please run command _npm start_ to start the server and _control C_ to stop.
<br>[Click me for walkthrough❗️](https://drive.google.com/file/d/1-1pvsp-Cb39Aog0Rt_YPKwxl5enGQCrb/view)</br>



## ✏️Dependencies
<p><a href="https://nodejs.org/">Node.js</a></p>
<p><a href="https://www.npmjs.com/">NPM</a></p>
<p><a href="https://www.npmjs.com/package/express">Express.js</a></p>
<p><a href="https://www.mongodb.com/">MongoDB</a></p>
<p><a href="https://www.npmjs.com/package/mongoose">Mongoose</a></p>


## 🔐License
```
Copyright © MIT. All rights reserved. 
Licensed under the MIT license.
```


## 🏆Badges

![GitHub top language](https://img.shields.io/github/languages/top/tpgent01/budget-tracker?color=red&style=plastic)
<br>![GitHub repo size](https://img.shields.io/github/repo-size/tpgent01/budget-tracker?color=orange&style=plastic)</br>
![GitHub language count](https://img.shields.io/github/languages/count/tpgent01/budget-tracker?color=yellow&style=plastic)
<br>![GitHub closed issues](https://img.shields.io/github/issues-closed/tpgent01/budget-tracker?color=brightgreen&style=plastic)</br>
![GitHub last commit](https://img.shields.io/github/last-commit/tpgent01/budget-trackeri?color=blueviolet&style=plastic)
<br>![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/tpgent01/budget-tracker?color=ff69b4&style=plastic)</br>
![GitHub watchers](https://img.shields.io/github/watchers/tpgent01/budget-tracker?style=social)
<br>![GitHub Repo stars](https://img.shields.io/github/stars/tpgent01/budget-tracker?style=social)</br>



## 📊Tests

To test this project, please see the [Installation](#installation) section.
<br>After the project is on your local, run _npm start_ to start the server and open [Insomnia Core](https://insomnia.rest/products/insomnia) to test API routes.</br>


## ❓Questions

If you have any questions about this projects, please contact me directly at tpgent01@outlook.com. 
<br>You can view more of my projects at https://github.com/tpgent01 👾</br>


## 📌Contributing

Taylor Gentry ©2021 All Rights Reserved.
