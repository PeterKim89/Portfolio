# Portfolio
![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=firefox&logoColor=#FF7139)
![WIP](https://www.repostatus.org/badges/latest/wip.svg)
## Introduction
A portfolio is an integral part to any developer's success. While it is nice to look back and see how much our skills have developed across projects. A well built portfolio will be one of the main things employers will also see. As time goes on, this portfolio will grow alongside my skills as a programmer and developer.

## Build Process
- Read the user story and acceptance criterias
- View the attached demo portfolio to better understand the challenge
- Begin by writing pseudocode and an abstract website framework
- Create a skeleton of the HTML
- Add semantic tags to the HTML while also filling in structural elements
- Create the style.css with basic elements and possible classes to be used
- Once initial versions of both files are done, begin refactoring them both
- Add comments throughout both files

## Usage
[Deployment](https://peterkim89.github.io/Portfolio/)

The navigation bar includes 3 links which redirect to their respective areas.
Also when a project's picture is clicked, it will redirect to the project's webpage.

[Screenshot](./assets/content/ScreenshotTop.png)

## Code Snippet

The projects class acts as a wrapper for the individual projects. While the card class acts as the container for each project's image/link.
```
.projects {
    display: flex;
    flex-wrap: wrap;
    width: 90%;
    margin-right: 5%;
    margin-left: 5%;
    padding-top: var(--general-padding);
    padding-bottom: var(--general-padding);
    background-color: lightcoral;
    justify-content: center;
}   

.card {
    display: flex;    
    flex-direction: column;
    flex-basis: 30%;
    padding: var(--general-padding);
    border: solid darkblue medium;
}
```

## Contact
[GitHub](https://github.com/PeterKim89) <br>
[LinkedIn](www.linkedin.com/in/peter-kim89)   
[Email]Peter.Kim@uconn.edu

## License
[MIT](https://choosealicense.com/licenses/mit/) <br>
Copyright (c) [2022] [Peter Kim]
