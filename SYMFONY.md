# Getting Started with Symfony

## Documentation Link

`https://symfony.com/doc/current/index.html`

## Installation with Scoop (Brew Alternative for Windows)

#### Learn About Scoop
`https://github.com/Hamid6426/hamid-learn-log/blob/main/SCOOP.md`

- Launch Powershell without admin
- Go to scoop.sh
- Search for php
- Copy the command and paste it in shell
`scoop install main/php`
- Confirm
`php --version`
- For future updates
`scoop upgrade php`
- Now installing mySQL
`scoop install main/mysql`
Connect to mySQL with
`mysql`
Exit mySQL
`exit`

## Installing Composer

- Go to getcomposer.org
- Download or install using cli
- Set the environment variable PATH for composer in the advance settings

## Download VS Code

- It's easy

## Important Extensions

- Community Material Theme and select any good (My choice Community Material Theme Darker High Contrast)
- PHP Intelephense by Ben Mewburn
- PHPDoc Comment by Rex Shi (works with ctrl+shift+i)
- PHP namespace resolver by Mehedi Hassan (Automatically get the use statement for a function. Made life easy in PHP)
- HTML Snippets by Mohamed Abusaid
- Javascript (ES6) code snippets by Charalampos Karypidis
- Symfony code Snippets and Twig Support by Nadim Al Abdou
- Symfony for VSCode by TheNouillet
- Twig by WhatweDo
- Twig Language and Twig Language 2 by mblode
- VSCode great icons by Emmaneul Beziat
- Bracket Pair Colorizer by Coenraads
- Emmet Live by Yurli Semeniuk

## Project Setup

#### Installing Symfony with Scoop
- Go to https://scoop.sh
- In the search box, search for symfony
- Copy the command which would look like this and paste it in terminal or shell
`scoop install main/symfony-cli`

#### Create New Symfony Project

- On the desktop/projects(for me) or any directory
- Open terminal or shell
- Paste the following line
- With Composer (Preferred)
`composer create-project symfony/skeleton my-symfony-project`
- With Symfony CLI
`symfony new my-symfony-project`
- Move to project directory
`my-symfony-project`
- To check if the PC can run symfony project
`symfony check:requirements`
- To check version of symfony project
`bin/console --version`
- Start the symfony server in the background
symfony server:start -d
- Go to `localhost:8000`
- Open in VS Code: `code .`

## Working in Project Directory

- composer require annotations
- Create a controller in symfony just like laravel
`symfony console make:controller NewController`
- If the maker command doesn't work install maker-bundle
`composer require --dev symfony/maker-bundle`
- Try again with the command
`symfony console make:controller NewController`
