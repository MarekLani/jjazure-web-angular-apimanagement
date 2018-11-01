# JJ AngularWeb using Angular calling back-end API with Azure API management

SinglePage Angular web application calling back-end rest API published with API management.
TODO: Secure API with Azure Active Directory

## Create Angular project with Visual Studio Code

I created SinglePage Angular (SPA) web project

How to create new Angular project (with routing) - [Using Angular in Visual Studio Code](https://code.visualstudio.com/docs/nodejs/angular-tutorial)
Tutorial for Angular - [Angular Tutorial](https://angular.io/tutorial/toh-pt0)
Use Material Design - [Angular Material](https://material.angular.io/guide/getting-started)

Run web on localhost

```bash
cd jjwebclient
ng serve --open
```

## Create API project with Visual Studio

I created DotNet Core API project jjapi and published to WebApp running on Linux
API URL: https://jjwebapi.azurewebsites.net/api/books

Update SPA project with this url.