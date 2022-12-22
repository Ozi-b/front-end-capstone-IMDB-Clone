# front-end-capstone

# Project Overview

Modern & Interactive front-end replication web application of IMDb. Developed and designed from scratch.

Contains 5 main components which are the Main card, Cast, Reviews, Details, and More to Explore.

The goal of this project was to immitate a web page of a popular website both visua

# Tech Stack

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Postgresql](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white)

# How to run locally

    -First clone this repo
    -Navigate to the ./server/ folder
    -Set up a postgresql database on your machine by using the migration.sql and seed.sql files
    -Edit the config.js file to replace the dev 'connectionString' with your database url
    -Run command 'npm install' inside ./server/ folder to install dependencies
    -Use command 'node server.js' to start server
    -Navigate to ./client/ folder
    -Run command 'npm install' to install dependencies
    -Run command 'npm run dev' to start
    -CTRL click on the link and enjoy the site!

# Git workflow commands

    -git checkout -b your-branch-name
    -git push
    -Do your work here
    -git add . ; git commit -m ''; git push         //so you can switch branches
    -git checkout dev
    -git pull
    -git checkout your-branch-name
    -git merge dev
    -Resolve conflicts if any
    -git add . ; git commit -m ''; git push
    -Open your branch in GitHub and create a pull request

# ERD link

    - https://lucid.app/lucidchart/890b3f39-5378-4000-a8bc-5e77fbf38390/edit?viewport_loc=392%2C151%2C955%2C788%2C0_0&invitationId=inv_e36371f7-b570-4fe2-9dc4-f10acfbd05a3

# Wireframe link

    - https://excalidraw.com/#json=PiZ1zFGmrLQ8KbhyDkbRR,pxMbE2CyCNU3b5Enz_GpVw

# Contributers

    -Dustin Swartzbaugh
        Contributed: User reviews component, reviews page, window background, MySQL migration/seed files
        GitHub: https://github.com/Swartz-D/
        LinkedIn: https://www.linkedin.com/in/dustin-swartzbaugh-8933b67a/
    -Alex Burris
        Contributed: Navbar, Details, Reviews Table
        GitHub: https://github.com/AlexTheHomebody
        LinkedIn: https://www.linkedin.com/in/alex-d-burris/
    -Bekmambet Alimbekov
        Contributed: More to explore, seed file in database
        LinkedIn: https://www.linkedin.com/in/bekmambet-alimbekov-00a1b924b/
        Github: @BAlimbekov
    -Brian Ortiz
       Contributed: cast, nav bar, menu modal, and server migration/seed
       GitHub: https://github.com/Ozi-b
       LinkedIn: https://www.linkedin.com/in/brian-ortiz-543477233/
    -Travis Henry
        Contributed: Primary card, Server, DB seed and migration file
        GitHub: https://github.com/Travis-Henry
        LinkedIn: https://www.linkedin.com/in/travis-henry-7aa50b247
