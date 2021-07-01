Javascript - JavaScript (JS) is a lightweight, interpreted or JIT compiled programming language with first-class functions. Most well-known as the scripting language for Web pages, many non-browser environments also use it, such as node.js and Apache CouchDB.

Cucumber - The popular BDD test framework which helps us write automated tests.
[Allure] (http://allure.qatools.ru/) - The Allure Reporter creates Allure test reports which is an HTML generated website with all necessary information to debug your test results and take a look on error screenshots.


Getting Started

Pre-requisites


NodeJS and npm installed globally in the system. (For webdriver v7 node 12.x should be used)
https://nodejs.org/en/download/


JAVA(JDK) installed in the system (Java 8).





Set JAVA_HOME paths correctly in the system.


Chrome browser installed.


Text Editor/IDE (Optional) installed-->Sublime/Visual Studio Code/Brackets. [VS code used while developing the scripts]


Allure on system to generate and open HTML allure reports from allure-results.


Windows/macOS: follow link https://docs.qameta.io/allure/
Linux:  https://launchpad.net/~qameta/+archive/ubuntu/allure/+files/allure_2.4.1~xenial_all.deb
Or
dpkg -i allure_2.4.1~xenial_all.deb
sudo apt-get install -f

Installation process

Setup Scripts

Clone the repository into a folder
Go inside the folder and run following command from terminal/command prompt

npm install

All the dependencies from package.json would be installed in node_modules folder.


Run Tests
npm test

Next step if you wish to generate Allure html report then execute below command -
