<img src="imgs\2048px-Angular_full_color_logo.svg.png" alt="2048px-Angular_full_color_logo.svg" style="zoom:20%;" />

# Angular CLI Commands

#### [Angular CLI Docs](https://angular.io/cli)

| Angular CLI command       | Description                                                                                      |
| ------------------------- | :----------------------------------------------------------------------------------------------- |
| **ng new <project-name>** | _Creates a new Angular project with the specified name._                                         |
| **ng serve**              | _Compiles and serves the application, rebuilding it on file changes._                            |
| **ng build**              | _Compiles the application into an output directory._                                             |
| **ng test**               | _Runs unit tests in a project._                                                                  |
| **ng e2e**                | _Runs end-to-end tests in a project._                                                            |
| **ng generate**           | _Generates a new component, directive, pipe, service, class, interface, enum, module, or guard._ |
| **ng add**                | _Adds a new library or capability to a project_                                                  |
| **ng update**             | _Updates the Angular framework and its dependencies to the latest version._                      |
| **ng lint**               | _Runs linting on the project's TypeScript code to check for syntax and style issues_             |
| **ng help**               | _Shows the Angular CLI help page_                                                                |

---

<img src="imgs\2048px-Angular_full_color_logo.svg.png" alt="2048px-Angular_full_color_logo.svg" style="zoom:20%;" />

# Angular Modules

[Angular Modules Docs](https://angular.io/guide/architecture-modules)

| Angular Modules      | Description                                                                                                                                                              |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **NgModule**         | _An Angular decorator used to define a module that collects and organizes related components, directives, pipes, and services into functional units._                    |
| **Declarations**     | _An array of components, directives, and pipes that belong to a module and are available for use within its components_                                                  |
| **Imports**          | _An array of other modules that a module depends on and whose components, directives, and pipes are available for use within its components._                            |
| **Exports**          | _An array of components, directives, and pipes that a module makes available to other modules that import it_                                                            |
| **Providers**        | _An array of services, factories, or values that a module contributes to the global dependency injection system or makes available for injection within its components._ |
| **Bootstrap**        | _An array of components that are automatically instantiated when an Angular application is launched_                                                                     |
| **Entry components** | _A type of component that is not referenced in a template but is dynamically created at runtime, typically as a modal or dialog box_                                     |
| **Lazy loading**     | _A technique for loading modules on demand, as needed, to improve application startup time and reduce initial load times_                                                |

---

<img src="imgs\985px-Laravel.svg.png" alt="985px-Laravel.svg" style="zoom:20%;" />

# Laravel Artisan Commands

#### [Laravel docs](https://laravel.com/docs/8.x/artisan)

| Artisan commands                                 | Description                                                                                             |
| :----------------------------------------------- | :------------------------------------------------------------------------------------------------------ |
| **php artisan help <command>**                   | _brings up a "help" screen which displays and describes the command's available arguments and options._ |
| **php artisan serve**                            | _Starts a development server for the Laravel application._                                              |
| **php artisan make:model <ModelName>**           | _Generates a new model class_                                                                           |
| **php artisan make:controller <ControllerName>** | _Generates a new controller class_                                                                      |
| **php artisan make:middleware <MiddlewareName>** | _Generates a new middleware class_                                                                      |
| **php artisan make:migration <MigrationName>**   | _Generates a new database migration_                                                                    |
| **php artisan migrate**                          | _Runs all outstanding database migrations_                                                              |
| **php artisan migrate:rollback**                 | _Rolls back the last batch of executed database migrations_                                             |
| **php artisan tinker**                           | _Launches an interactive REPL shell for the Laravel application_                                        |
| **php artisan route:list**                       | _Displays a list of all registered routes for the application_                                          |
| **php artisan make:auth**                        | _Generates authentication scaffolding, including views and controllers, for the Laravel application._   |

---

<img src=".\imgs\Logo-composer-transparent.png" alt="2560px-Npm-logo.svg" style="zoom:20%;" />

# Composer Commands

#### [Composer docs](https://getcomposer.org/doc/)

| Composer Commands                   | Description                                                                            |
| ----------------------------------- | -------------------------------------------------------------------------------------- |
| **composer install**                | _Installs all the packages listed in the `composer.json` file of a project_            |
| **composer update**                 | _Updates all the packages listed in the `composer.json` file to their latest version._ |
| **composer require <package-name>** | _Installs a new package in the project and adds it to the `composer.json` file._       |
| **composer remove <package-name>**  | _Removes a package from the project and updates the `composer.json` file._             |
| **composer show**                   | _Lists all installed packages, their versions, and their dependencies._                |
| **composer self-update**            | _Updates the Composer installation itself to the latest version._                      |

---

<img src="imgs\React-icon.svg.png" alt="React-icon.svg" style="zoom:20%;" />

# React Commands

#### [React docs](https://react.dev/learn/start-a-new-react-project)

| React Commands                      | Description                                                                                                                                             |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **npx create-react-app <app-name>** | _Creates a new React application with the specified name._                                                                                              |
| **npm start**                       | _Starts a development server for the React application_                                                                                                 |
| **npm run build**                   | _Builds the production-ready version of the React application_                                                                                          |
| **npm test**                        | _Runs all tests in the React application_                                                                                                               |
| **npm install <package-name>**      | _Installs a new package in the React application_                                                                                                       |
| **npm uninstall <package-name>**    | _Removes a package from the React application_                                                                                                          |
| **npm run eject**                   | _Removes the abstraction layer provided by Create React App and exposes the underlying configuration files, allowing for more advanced customizations._ |
| **npm run lint**                    | _Runs linting on the project's JavaScript code to check for syntax and style issues._                                                                   |
| **npm run format**                  | _Automatically formats the project's JavaScript code to adhere to a consistent coding style._                                                           |

---

<img src="imgs\React-icon.svg.png" alt="React-icon.svg" style="zoom:20%;" />

# React modules

#### [React docs](https://react.dev/learn/start-a-new-react-project)

| React modules    | Description                                                                                   |
| ---------------- | --------------------------------------------------------------------------------------------- |
| **React**        | _The core library for building user interfaces in React_                                      |
| **ReactDOM**     | _A package that provides DOM-specific methods that can be used at the top level of a web app_ |
| **React Router** | _A library for handling routing in React applications._                                       |
| **Axios**        | _A library for making HTTP requests from a React application_                                 |
| **PropTypes**    | _A package that provides runtime type checking for React props_                               |
| **Redux**        | _A predictable state container for JavaScript apps_                                           |
| **React Redux**  | _A package that provides the bindings between React and Redux_                                |
| **Moment.js**    | _A library for parsing, validating, and manipulating dates and times in JavaScript._          |
| **React Native** | _A framework for building mobile applications using React_                                    |
| **Enzyme**       | _A testing utility for React that provides tools for working with React components_           |

---

<img src=".\imgs\Git-Icon-1788C.png" alt="2560px-Npm-logo.svg" style="zoom:20%;" />

# Git Commands

#### [Git docs](https://git-scm.com/docs)

| Git Commands                   | Description                                                                                         |
| ------------------------------ | --------------------------------------------------------------------------------------------------- |
| **git init**                   | _Initializes a new Git repository in the current directory._                                        |
| **git clone <repository URL>** | _Clones an existing Git repository from the specified URL to a new directory on the local machine._ |
| **git add <file(s)>**          | _Adds one or more files to the staging area in preparation for a commit_                            |
| **git commit -m "<message>"**  | _Commits changes to the local repository with a descriptive message._                               |
| **git push <remote> <branch>** | _Pushes local commits to the specified branch on the remote repository._                            |
| **git pull <remote> <branch>** | _Fetches and merges changes from the specified remote repository and branch._                       |
| **git status**                 | _Displays the current status of the working directory and staging area._                            |
| **git log**                    | _Displays a log of all previous commits in the repository_                                          |
| **git branch**                 | _Lists all local branches in the repository_                                                        |
| **git checkout <branch>**      | _Switches to the specified branch_                                                                  |

---

<img src="imgs\2560px-Npm-logo.svg.png" alt="2560px-Npm-logo.svg" style="zoom:20%;" />

# NPM Commands

#### [NPM docs](https://docs.npmjs.com/cli/v7/commands)

| NPM Commands                         | Description                                                                                       |
| ------------------------------------ | ------------------------------------------------------------------------------------------------- |
| **npm init**                         | _Initializes a new npm package in the current directory, creating a `package.json` file._         |
| **npm install <package>**            | _Installs a package as a dependency for the current project._                                     |
| **npm install <package> --save-dev** | _Installs a package as a development dependency for the current project._                         |
| **npm uninstall <package>**          | _Removes a package from the current project's dependencies_                                       |
| **npm update <package>**             | _Updates a package to the latest version in the current project_                                  |
| **npm outdated**                     | _Lists any outdated packages that are currently installed in the current project._                |
| **npm publish**                      | _Publishes the current package to the npm registry for others to use._                            |
| **npm search <query>**               | _Searches the npm registry for packages matching the specified query._                            |
| **npm run <script>**                 | _Runs the specified script defined in the `scripts` section of the `package.json` file._          |
| **npm audit**                        | _Checks for any known security vulnerabilities in the packages installed in the current project._ |

---

<img src=".\imgs\logo-with-shadow.png" alt="2560px-Npm-logo.svg" style="zoom:20%;" />

# Vite Commands

#### [Vite Docs](https://vitejs.dev/guide/cli.html)

| Vite Commands                                  | Description                                                                                   |
| ---------------------------------------------- | --------------------------------------------------------------------------------------------- |
| **vite init**                                  | _Initializes a new Vite project, creating a `package.json` file and installing dependencies._ |
| **vite dev**                                   | _Starts a development server with hot reloading enabled_                                      |
| **vite build**                                 | _Builds the production-ready version of the project in the `dist` directory_                  |
| **vite serve**                                 | _Serves the production-ready version of the project using a static file server_               |
| **vite create <template-name> <project-name>** | _Creates a new Vite project using a predefined template._                                     |
| **vite optimize**                              | _Runs the Vite optimizer to optimize the production build._                                   |
| **vite inspect**                               | _Prints debugging information about the current Vite configuration and plugins._              |
| **vite plugin <command>**                      | _Manages Vite plugins, with subcommands for adding, removing, and listing plugins._           |
| **vite ssr**                                   | _Builds and serves the server-rendered version of the project_                                |
| **vite test**                                  | _Runs tests for the project using a testing framework like Jest or Mocha._                    |

---

<img src="imgs\2560px-Node.js_logo.svg.png" alt="2560px-Node.js_logo.svg" style="zoom:20%;" />

# NodeJS Commands

#### [NodeJS docs](https://nodejs.org/en/docs)

| NodeJS Commands                             | Description                                                                 |
| ------------------------------------------- | --------------------------------------------------------------------------- |
| **node**                                    | _Starts a Node.js REPL (Read-Eval-Print Loop) shell_                        |
| **node <file>**                             | _Runs the specified JavaScript file with Node.js._                          |
| **node --version**                          | _Displays the version of Node.js currently installed on the system_         |
| **node --help**                             | _Displays a list of available Node.js command line options_                 |
| **node package.json**                       | _Runs scripts defined in the `scripts` section of the `package.json` file._ |
| **node -e "<script>"**                      | _Evaluates the specified script using Node.js_                              |
| **node --inspect <file>**                   | _Enables debugging for the specified file_                                  |
| **node --experimental-modules <file>**      | _Enables ECMAScript modules for the specified file._                        |
| **node --max-old-space-size=<size> <file>** | _Sets the maximum memory size for Node.js when running the specified file._ |
| **node --trace-warnings <file>**            | _Enables tracing for warnings when running the specified file._             |

---

<img src="imgs\JQuery-Logo.svg.png" alt="JQuery-Logo.svg" style="zoom:20%;" />

# JQuery Commands

#### [JQuery Docs](https://api.jquery.com/)

| JQuery Commands                        | Description                                                                                                 |
| -------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **$(selector)**                        | _Selects an HTML element using a CSS-style selector_                                                        |
| **$(selector).click(handler)**         | _Binds a click event handler to the selected element(s)_                                                    |
| **$(selector).hide()**                 | _Hides the selected element(s)_                                                                             |
| **$(selector).show()**                 | _Displays the selected element(s)_                                                                          |
| **$(selector).addClass(class)**        | _Adds a CSS class to the selected element(s)_                                                               |
| **$(selector).removeClass(class)**     | _Removes a CSS class from the selected element(s)_                                                          |
| **$(selector).toggleClass(class)**     | _Toggles a CSS class on the selected element(s)._                                                           |
| **$.get(url, data, callback)**         | _Sends an HTTP GET request to the specified URL and invokes the callback function with the response data._  |
| **$.post(url, data, callback)**        | _Sends an HTTP POST request to the specified URL and invokes the callback function with the response data._ |
| **$(selector).attr(attribute, value)** | _Sets the specified attribute to the specified value on the selected element(s)._                           |
