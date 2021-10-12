# Family Promise Service Tracker

Family Promise helps local communities coordinate their compassion to address the root causes of family homelessness. They tap existing local resources to empower families towards economic stability. Families come to them in crisis; they help them rebuild their lives with new skills and ongoing support. They address the issue holistically, providing prevention services before families reach crisis, shelter and case management when they become homeless, and stabilization programs once they have secured housing to ensure they remain independent.

Family Promise needs a way to track and visualize the services they provide external to the shelter to gain actionable insights.

Our goal is to build a generalizable monitoring and evaluation (M&E) platform that meets Family Promise's needs, with an eye toward additional potential use cases that would be useful for many other organizations.

You can find the deployed project at [a.familypromiseservicetracker.dev/](a.familypromiseservicetracker.dev/).

<br>
<br>

![https://mit-license.org](https://img.shields.io/packagist/l/doctrine/orm.svg)
![https://reactjs.org](https://img.shields.io/badge/react-v16.13.1-blue)
![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)

- DO NOT fork the repo. Clone directly!
- run: `npm install` to download all dependencies.
- run: `npm start` to start your local development server.

> When using Okta for authentication, the app will need to run locally on port 3000.

### Key Features

- Admin users can add / edit / delete employees, add / edit / delete programs, add / edit / delete services types & add / edit / delete services.
- Program Managers can add / edit / delete programs, add / edit / delete services types & add / edit / delete services.
- Service Managers can view and add / edit / delete services.
- All users can update their profile image and names.

#### Front end deployed to AWS Amplify.

#### [Back end](https://github.com/Lambda-School-Labs/family-promise-service-tracker-be-a) built using:

#### Node.js with Postgres

- point one
- point two
- point three

# Installation Instructions

create your project repo by forking or using this as a template.
run: `npm install` to download all dependencies.
run: `npm start` to start the live server. Note: must be running on localhost:3000
g

# Map setup

Setting up map for dashboard:

Must have a token setup in a .env.local file (must create file on fresh clone) with the following format for map to render
`REACT_APP_MAPBOX_TOKEN = "Token string"`

# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a [code of conduct](./CODE_OF_CONDUCT.md). Please follow it in all your interactions with the project.

## Issue/Bug Request

**If you are having an issue with the existing project code, please submit a bug report under the following guidelines:**

- Check first to see if your issue has already been reported.
- Check to see if the issue has recently been fixed by attempting to reproduce the issue using the latest master branch in the repository.
- Create a live example of the problem.
- Submit a detailed bug report including your environment & browser, steps to reproduce the issue, actual and expected outcomes, where you believe the issue is originating from, and any potential solutions you have considered.

### Feature Requests

We would love to hear from you about new features which would improve this app and further the aims of our project. Please provide as much detail and information as possible to show us why you think your new feature should be implemented.

### Pull Requests

If you have developed a patch, bug fix, or new feature that would improve this app, please submit a pull request. It is best to communicate your ideas with the developers first before investing a great deal of time into a pull request to ensure that it will mesh smoothly with the project.

Remember that this project is licensed under the MIT license, and by submitting a pull request, you agree that your work will be, too.

#### Pull Request Guidelines

- Update the README.md with details of changes to the interface, including new plist variables, exposed ports, useful file locations and container parameters.
- Ensure that your code conforms to our existing code conventions and test coverage.
- Include the relevant issue number, if applicable.
- You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

## Documentation

See [Backend Documentation](https://github.com/Lambda-School-Labs/family-promise-service-tracker-be-a) for details on the backend of our project.

## Contributors

### **Front-End Team (Labs 35)**

|                                          [Adam Purdy](https://github.com/PurdyRad)                                          |                                       [Jason Corchado](https://github.com/JasonCorchado)                                        |                                             [Jonathan Calderon](https://github.com/Jonathan1600)                                             |
| :-------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------: |
|       [<img src="https://avatars.githubusercontent.com/u/76630666?v=4" width = "200" />](https://github.com/PurdyRad)       |      [<img src="https://avatars.githubusercontent.com/u/77353218?v=4" width = "200" />](https://github.com/JasonCorchado)       |            [<img src="https://avatars.githubusercontent.com/u/70250506?s=400" width = "200" />](https://github.com/Jonathan1600)             |
|                    [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/PurdyRad)                    |                   [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/JasonCorchado)                    |                          [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/Jonathan1600)                           |
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/adam-purdy/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/jason-corchado/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/jonathan-calderon-silberman/) |

|                                      [Monica Zwissler](https://github.com/Monicascz)                                      |                                         [Robert Allen](https://github.com/robertjallen)                                         |
| :-----------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------: |
|     [<img src="https://avatars.githubusercontent.com/u/73200302?v=4" width = "200" />](https://github.com/Monicascz)      |      [<img src="https://avatars.githubusercontent.com/u/20561145?s=400" width = "200" />](https://github.com/robertjallen)      |
|                  [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/Monicascz)                   |                    [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/robertjallen)                    |
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/monicascz) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/robertallendev/) |

<br>

### **Back-End Team (Labs 35)**

|                                       [Adam Selter](https://github.com/blackcatwizard)                                       |                                     [Domenic Scarcella](https://github.com/DomenicScarcella)                                      |                                         [Jay Ponce de Leon](https://github.com/jaypdl)                                          |                                    [Matthew Ellis](https://github.com/MatthewEllisTx/)                                     |
| :--------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|    [<img src="https://avatars.githubusercontent.com/u/73545965?v=4" width = "200" />](https://github.com/blackcatwizard)     |     [<img src="https://avatars.githubusercontent.com/u/76451364?s=400" width = "200" />](https://github.com/DomenicScarcella)     |          [<img src="https://avatars.githubusercontent.com/u/20601752?v=4" width = "200" />](https://github.com/jaypdl)          |   [<img src="https://avatars.githubusercontent.com/u/77289520?v=4" width = "200" />](https://github.com/MatthewEllisTx/)   |
|                 [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/blackcatwizard)                  |                   [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/DomenicScarcella)                   |                       [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/jaypdl)                       |                [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/MatthewEllisTx/)                |
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/adam-selter/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/domenicscarcella/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/jayponcedeleon/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/mbellistx/) |

|                                      [Monica Zwissler](https://github.com/Monicascz)                                      |                                           [Nick Samples](https://github.com/samplesn08)                                           |                                            [Weston Woodard](https://github.com/SpicyLunchbox)                                            |
| :-----------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------: |
|     [<img src="https://avatars.githubusercontent.com/u/73200302?v=4" width = "200" />](https://github.com/Monicascz)      |         [<img src="https://avatars.githubusercontent.com/u/53315294?v=4" width = "200" />](https://github.com/samplesn08)         |          [<img src="https://avatars.githubusercontent.com/u/69223774?s=400" width = "200" />](https://github.com/SpicyLunchbox)          |
|                  [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/Monicascz)                   |                      [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/samplesn08)                      |                        [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/SpicyLunchbox)                        |
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/monicascz) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/nicholas-samples/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/weston-woodard-76709988/) |

<br>

### **Front-End Team (Labs 33)**

|                                                        [Hussain Ali](https://github.com/princeali415)                                                        |                                                   [Ruben Ramirez](https://github.com/rubesworld)                                                   |                                                 [Bryan Diaz](https://github.com/bdiaz12345)                                                 |                                               [Jose Robles](https://github.com/jcrobles1989)                                                |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: |
| [<img src="https://res.cloudinary.com/dyp2opcpj/image/upload/v1618184678/images/gij4edsbp3709samouln.jpg" width = "200" />](https://github.com/princeali415) | [<img src="https://res.cloudinary.com/water-my-plants/image/upload/v1618698077/ruben-ramirez.jpg" width = "200" />](https://github.com/rubesworld) | [<img src="https://res.cloudinary.com/water-my-plants/image/upload/v1619463650/bryanD.png" width = "200" />](https://github.com/bdiaz12345) | [<img src="https://res.cloudinary.com/water-my-plants/image/upload/v1619477734/Jose.png" width = "200" />](https://github.com/jcrobles1989) |
|                                  [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/princeali415)                                   |                              [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/rubesworld)                               |                           [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/bdiaz12345)                           |                          [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/jcrobles1989)                          |
|            [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/hussain-ali-58a9b690/)             |         [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/rubenandresramirez)         |    [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/bryan-diaz-816a081b9/)    |       [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/jcroblesorozco/)       |

<br>

### **Back-End Team (Labs 33)**

|                                                [Chris Sutton](https://github.com/suttonchristopher)                                                |                                                [Brandon O'Neal](https://github.com/brandononeal)                                                 |
| :------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------: |
| [<img src="https://res.cloudinary.com/water-my-plants/image/upload/v1619474173/ChrisS.jpg" width = "200" />](https://github.com/suttonchristopher) | [<img src="https://res.cloudinary.com/water-my-plants/image/upload/v1619473829/BrandonON.jpg" width = "200" />](https://github.com/brandononeal) |
|                           [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/suttonchristopher)                           |                            [<img src="https://github.com/favicon.ico" width="32"> ](https://github.com/brandononeal)                             |
|         [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/suttonchristopher/)         |          [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="32"> ](https://www.linkedin.com/in/brandonaoneal)           |
