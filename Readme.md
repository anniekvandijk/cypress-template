# Project setup

## Cypress and Cucumber documentation

https://docs.cypress.io/guides/overview/why-cypress   
https://example.cypress.io/  
https://github.com/badeball/cypress-cucumber-preprocessor  
https://cucumber.io/docs/tools/general/

## Prequisites

- NodeJS 
- Visual Studio Code or other IDE
- [Cucumber (Gherkin) Full Support](https://marketplace.visualstudio.com/items?itemName=alexkrechik.cucumberautocomplete) plugin for VS Code

## Folders

- e2e: This folder contains all end-to-end tests.
- Fixtures: This folder helps keep data files such as data.json, which can be read directly inside the test scripts.
- Plugins: Helps to modify or extend the internal behavior of Cypress. Users can extend this framework or customize this framework beyond what Cypress gives them by default.
- Support: The support folder contains common files (reusable code, global variables, etc.) that need to be accessed globally inside the framework.

## Cypress commands

Open Cypress UI: ```npx cypress open``` or ```npm run open```   
Run Cypress tests: ```npx cypress runtest``` or ```npm run test```