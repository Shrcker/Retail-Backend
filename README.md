<h1 id='description'>Retail Backend Challenge <a href="https://opensource.org/licenses/MIT"><img alt="The MIT License" src="https://img.shields.io/badge/License-MIT-yellow.svg" /></a></h1><br />This project is a web browser accessed SQL Database that uses Sequelize, Express, and DotEnv to create a seamless and easy to use database editor and viewer. This instance of the application assume a retail setting for this database, so it has established relationships between product, categories, and tags and assumes most incoming data will follow this format. <br /><strong>Link:</strong> <a href=https://github.com/Shrcker/Retail-Backend>Github Link</a>

https://github.com/Shrcker/Retail-Backend/assets/156132310/2ae48a10-75b0-4fea-a220-5d2aa3b0c35f

<br /><h3>Table of Contents</h3><ol><li><a href="#description"><span>Description</span></a></li><li><a href="#installation"><span>Installation</span></a></li><li><a href="#usage"><span>Usage</span></a></li><li><a href="#credits"><span>Credits</span></a></li><li><a href="#license"><span>License</span></a></li><li><a href="#questions"><span>Questions</span></a></li></ol><br /><h2 id='installation'>Installation</h2><br />Download the repository from Github, then open the project in a code editor, such as Visual Studio Code, and access the repo from the editor's terminal. Once open, you can run npm install to install the project's dependencies and then login to your SQL server through MySQL to source the schema.sql in the db directory (you can do this by calling within MySQL: "SOURCE db/schema.sql"). After this, exist MySQL and seed the new database by inputting "node seeds/index" to the terminal (only do this if you wish to sample the schema. If you'd like to use your own database entries, then skip this step). Finally, enter your MySQL login credentials to the .env.EXAMPLE file and remove the ".EXAMPLE" suffix from the file. Then, run "node server" and the application will launch onto your localhost server, which you may access from your browser or a server testing program like Insomnia.<br /><h2 id='usage'>Usage</h2><br />You may use the base code and logic and adapt it to your own database-based projects to provide an easy way to test your server-side routing. You may also refer to this code as a learning tool if you're still getting the hang of back-end development.<br /><h2 id='credits'> Credits</h2><br /> Most credit for the application's structure goes to the OSU Coding Bootcamp for providing the starting code that I then added the routing to.<br /><h2 id='license'>License</h2><br />The MIT License<br /><h2 id='questions'>Questions</h2><br />Who is the project's host?<br />It's Shrcker; link to their profile: <a href="https://www.github.com/Shrcker">Link</a><br />You can contact them through email: tanner.shirkey@gmail.com
