# <Creating README Generator: Week-9-Challenge (Node.js)>

## Description

In an effort to reduce the time developers spend writing their README.md files, this application was developed using node.js to generate polished README.md documents from the command line. They will be able to spend more time developing, updating, and maintaining their applications as a result. This application asks the user a series of questions using inquirer (node package manager). It asks for the user's name, GitHub handle, primary email, application description, installation instructions, usage guidelines, contribution guidelines, test instructions, and what kind of license they want their application to be covered under. The application uses the user's inputs to create a professional README.md markdown file after all prompts have been completed.

## Live Screen Recording of Application Functionality

https://drive.google.com/file/d/1BtbWqPDxDK96kuvcQfE56Zb8pLCCdZgB/view

## Screenshots


## Installation

1. Clone the repo:
   git clone git@github.com:DecodePlaymaker/mystery.git

2. Open in VS Code. If you do not have VS code you must install it.

3. Using the terminal, install node.js v16. If you have homebrew, the command should look like the following (brew install node@16), however this may vary and the documentation should be consulted.

4. Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package where project files will be stored.

5. Next, use the terminal to run the command npm i inquirer@8.2.4 to install v8.2.4 of the inquirer.

6. To run the application, within the terminal, type the command node index.js.