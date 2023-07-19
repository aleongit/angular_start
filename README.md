## Introduction

1. [Getting started with Angular](#1-getting-started-with-angular)
2. [Adding navigation](#2-adding-navigation)
3. TODO: Managing data
4. TODO: Using forms for user input
5. TODO: Deploying an application



## 1. Getting started with Angular
- https://angular.io/start
- https://angular.io/guide/setup-local

- Prerequisites
- Take a tour of the example application
- Create the sample project
- Create the product list
- Pass data to a child component
- Pass data to a parent component


## 2. Adding navigation
- https://angular.io/start/start-routing

- Associate a URL path with a component
- View product details


## 3. Managing data
- https://angular.io/start/start-data

- **Create the shopping cart service**
- Define a cart service
- Use the cart service
- **Create the cart view**
- Set up the cart component
- Display the cart items



## Requeriments / Prerequisites

🖥️ node -v
→ v18.16.0

🖥️ npm -v
→ 9.8.0



## Get Started

- git clone https://github.com/aleongit/angular_start.git
- cd angular_start
- npm install
- ng serve
- http://localhost:4200/



## Dev environment

- node v18.16.0
- npm 9.8.0
- Visual Studio Code 1.80.1
- git version 2.38.0.windows.1
- Postman v10.14.6
- Microsoft Windows [Versión 10.0.19045.3208]




## Setting up the local environment

- Install Prerequisites

- Install the Angular CLI
```
npm install -g @angular/cli
```

- Create a workspace and initial application
```
ng new angular_start
```
```
? Would you like to share pseudonymous usage data about this project with the Angular Team
at Google under Google's Privacy Policy at https://policies.google.com/privacy. For more
details and how to change this setting, see https://angular.io/analytics. No
Global setting: disabled
Local setting: No local workspace configuration file.
Effective status: disabled
? Would you like to add Angular routing? No
? Which stylesheet format would you like to use? CSS
```

- Run the application
```
cd angular_start
ng serve --open
```
- The --open (or just -o) option automatically opens your browser to http://localhost:4200/.



## Run

- cd angular_start
- ng serve
- http://localhost:4200/



## Terminal

- create component `ng generate component name-component`
```
ng generate component product-alerts

CREATE src/app/product-alerts/product-alerts.component.html (29 bytes)
CREATE src/app/product-alerts/product-alerts.component.spec.ts (609 bytes)
CREATE src/app/product-alerts/product-alerts.component.ts (233 bytes)
CREATE src/app/product-alerts/product-alerts.component.css (0 bytes)
UPDATE src/app/app.module.ts (819 bytes)
```
```
ng generate component product-details

CREATE src/app/product-details/product-details.component.html (30 bytes)
CREATE src/app/product-details/product-details.component.spec.ts (616 bytes)
CREATE src/app/product-details/product-details.component.ts (237 bytes)
CREATE src/app/product-details/product-details.component.css (0 bytes)
UPDATE src/app/app.module.ts (935 bytes)
```

- create a service `ng generate service name-service`
```
ng generate service cart

CREATE src/app/cart.service.spec.ts (347 bytes)
CREATE src/app/cart.service.ts (133 bytes)
```


## Doc

### node
- https://nodejs.org/en/download


### angular
- https://angular.io
- https://angular.io/start
- https://angular.io/guide/setup-local

