# angular-config
Angular config files explained


## Config files generated by CLI

### .editorconfig

Responsible for setup IDE general configuration regarding identation, whitespace, charset etc it assure those configurations
for the project are the same for all users no matter what IDE each one uses.

### .gitignore

Basic git config file to ignore content undesired at the repository.

### browserslist 

Pick up by angular CLI at the compilation time to optimize code and adjust css, polyfills etc.

### karma.conf.js

Configuration file for karma tests

### package.json

Dependencies and devDependencies of the project

### tsconfig.json

Typescript configuration file 

### tslint.json

Lint configuration

## Commands CLI

### ng serve

Serves the project at local machine

--port 

setup port for the enviroment served

--prod 

config project as production 

### ng generate

guards, services, module, component, application, directive...

--help (list other parameters)

### ng lint

verify projects files to check health and quality of code

### build 

Build project and generate final content 

--prod  (optmizes for production)

