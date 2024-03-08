"# SmartTutoring" 

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

Requirements: node, npm, prettier.
https://nodejs.org/en/
Prettier plug-in for IDEs:
Intellij: https://www.jetbrains.com/help/idea/prettier.html
VSCode: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
Also: Check for 'Format on save with prettier' setting
Once you have the repository cloned:
Open a terminal in the repository root directory(command prompt)
Switch to the correct branch: git checkout frontend
Get all the updates from remote branch: git pull origin frontend
Run the FE app: npm start

-----------------------------------------------------------------------------------------------------------
# Getting Started Backend Java Spring Boot App and Setup
JAVA VERSION: 17 

MYSQL VERSION: mysql-installer-community-8.0.31.0 (https://dev.mysql.com/downloads/file/?id=514518)

MAKE SURE TO UNINSTALL ANY PREVIOUS MYSQL SERVER VERSION AND ANY RELATED APPLICATIONS!

Setup Type-> Custom -> Choose the Server, the MYSQL Workbench and the connector/j so in the products to be installed you should see 3 entries:

MYSQL Server 8.0.31 MySQL Workbench 8.0.31 Connector/J 8.0.31 Go Next, hit execute and wait for everything to be installed. Go next and the server configuration will begin. On the Type and Networking page leave everything as it is by default and hit next. On the Authentication Method page default and hit next. On the accounts and roles we need to choose a password for the root user. Let's use "root" and hit next. On the Windows Service page leave everything as it is and hit next. Next page leave everything as default and hit next. On the last page hit execute and wait for everything to finish. After everything finished hit "Finish".

Start mysql workbench after we finished the setup.

