## Airalo Test Challenge

## Getting started
```
git remote add origin https://github.com/IAMRAAJRSARWAN/fe-api-airalo-cypress.git
git branch -M main
git push -u origin main
```

## Installation - Local

```
Clone Repo: 

git clone https://github.com/IAMRAAJRSARWAN/fe-api-airalo-cypress.git

npm installation of packages: 

npm install or npm i 
```

## Project Setup
```
Directory:
    Cypress
        api - contains all API Tests
        e2e - contains all Ui Tests
        fixtures - contains locators, currency, tariff test data's
        services - contains endpoints, paylods, global common settings 
```

## Usage
```
Cypress Config Designed to use Both UI and API Tests Suites

To Execute Ui Tests: All Tests Will Execute
    npx cypress run | npm run cy:run:ui
    
To Execute API Tests: All Tests Will Execute
    npx cypress run --env testType=api | npm run cy:run:api
    
To Build and Show Report:
    npx allure serve allure-results | npm run cy:allure:generate
    
```

## Authors and acknowledgment
```
Saravanan Rajamanickam
Airalo Test Challenge
```

## License

For open source projects, say how it is licensed.

## Project status

If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.