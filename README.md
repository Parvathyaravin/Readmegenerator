# <Creating README Generator: Week-9-Challenge (Node.js)>

## Description

This application, developed with node.js, streamlines the creation of professional README.md files directly from the command line. Its purpose is to reduce the time developers spend on crafting README.md documentation, allowing them to focus more on building, maintaining, and updating their applications. Using the inquirer package in node.js, the application guides users through a series of prompts, covering aspects such as their name, application title, description, installation instructions, usage information, contribution guidelines, test instructions, preferred license, GitHub handle, and primary email. Once all prompts are answered, the application dynamically generates a polished README.md markdown file incorporating the user's inputs.This project marked my initial venture into backend development using node.js, providing valuable insights into problem-solving without a user interface or live browser. Throughout its development, I gained proficiency in importing libraries like inquirer and file system into a node application, implementing prompts within the command line, and utilizing ES6 syntax features such as template literals and arrow functions. Additionally, this project contributed to the reinforcement of previous programming knowledge, particularly in the application of conditional statements.

## Live Screen Recording of Application Functionality

https://github.com/Parvathyaravin/Readmegenerator

## Technologies Used

This project is powered by Node.js v16, and utilizes the inquirer v8.2.4 (node package manager), and file system module (node package manager).

## Installation

1. Clone the repo:
   git clone https://github.com/Parvathyaravin/Readmegenerator

2. Open in VS Code. If you do not have VS code you must install it.

3. Using the terminal, install node.js v16. If you have homebrew, the command should look like the following (brew install node@16), however this may vary and the documentation should be consulted.

4. Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package where project files will be stored.

5. Next, use the terminal to run the command npm i inquirer@8.2.4 to install v8.2.4 of the inquirer.

6. To run the application, within the terminal, type the command node index.js.

## Features

Features of this application include the users ability to generate a professional README.md document straight from the command line. The user will answer a series of prompts about their application, and then a README.md markdown file will be generated based on their responses. Features within the README.md file include a licensing badge which will be appended near the top of the page based on what license the user would like their application to be covered under. As well as a table of contents which includes links to the various sections of the README.md document, that when clicked take the user to the corresponding section. Lastly their is a questions section at the bottom of the generated README.md document where links to the application authors GitHub and email are provided (when clicked, the user will be taken to the authors GitHub account, or to a blank email document where the author is automatically entered as the recipient).

## How to Contribute

Open to collaboration, if you choose to do so open an issue and modify any changes you would like to see on a feature branch and wait for approval before merging to the main branch.
