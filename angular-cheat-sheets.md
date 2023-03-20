## Angular Cheat sheet

## Installation

Install Angular CLI: `npm install -g @angular/cli`


## Disable caching:
- `ng config cli.cache.enabled false:`  Disable caching
- `ng cache`: Configures Angular CLI caching settings
- `ng cache off`: Disable caching
- `ng cache disable [key]`: Disable caching for a specific key
- `ng cache clear`: Clear the cache
- `ng cache clear [key]`: Clear the cache for a specific key


# ng Commands

## General
- `ng version`: Displays Angular CLI version
- `ng help`: Displays available commands
- `ng doc`: Opens the official Angular documentation
- `ng new <app-name>`: Creates a new Angular application
- `ng test`: Runs unit tests
- `ng e2e`: Runs end-to-end tests*
- `ng build`: Compiles into an output directory
- `ng deploy`: Deploys the application*
- `ng update`: Updates the Angular version for the app
- `ng add`: Adds support for an external library to the app
- `ng generate`: Generates code
- `ng lint`: Runs linting on the app
- `ng xi18n`: Extracts i18n messages from the app
- `ng run`: Runs an architect target with an optional custom builder
- `ng config`: Configures Angular CLI options
- `ng analytics`: Configures Angular CLI analytics settings
- `ng completion`: Adds autocomplete to the Angular CLI
- `ng format`: Formats code in the current project
- `ng generate`: Generates code
- `ng lint`: Runs linting on the app

## NG serve options
- `ng serve`: Builds the app and launches a server
- `ng serve --open`: Opens the app in the default browser
- `ng serve --port 4201`: Runs the app on a different port
- `ng serve --host`: Runs the app on a different host
- `ng serve --ssl`: Runs the app over HTTPS
- `ng serve --ssl-key`: Runs the app over HTTPS with a custom key
- `ng serve --ssl-cert`: Runs the app over HTTPS with a custom certificate
- `ng serve --proxy-config`: Runs the app with a proxy
- `ng serve --live-reload`: Runs the app with live reload
- `ng serve --live-reload-client`: Runs the app with live reload and a custom client
- `ng serve --open-page`: Opens a specific page when the app launches
- `ng serve --hmr`: Runs the app with hot module replacement
- `ng serve --hmr-warning`: Runs the app with hot module replacement and a custom warning
- `ng serve --poll`: Runs the app with polling
- `ng serve --poll-interval`: Runs the app with polling and a custom interval
- `ng serve --disable-host-check`: Runs the app with host checking disabled
- `ng serve --public-host`: Runs the app with a custom public host
- `ng serve --deploy-url`: Runs the app with a custom deploy URL
- `ng serve --base-href`: Runs the app with a custom base href
- `ng serve --vendor-chunk`: Runs the app with a custom vendor chunk
- `ng serve --common-chunk`: Runs the app with a custom common chunk
- `ng serve --named-chunks`: Runs the app with named chunks
- `ng serve --extract-css`: Runs the app with CSS extraction
- `ng serve --watch`: Runs the app with watch mode
- `ng serve --progress`: Runs the app with progress reporting
- `ng serve --verbose`: Runs the app with verbose logging
- `ng serve --extract-licenses`: Runs the app with license extraction
- `ng serve --show-circular-dependencies`: Runs the app with circular dependency reporting
- `ng serve --preserve-symlinks`: Runs the app with symlink preservation

### Generating Code

- Class: `ng g c <name>`
- Component: `ng g c <name>`
- Directives: `ng g d <name>`
- Enum: `ng g e <name>`
- Route guards: `ng g g <name>`
- Interfaces: `ng g i <name>`
- Modules: `ng g m <name>`
- Pipes: `ng g p <name>`
- Services: `ng g s <name>`
- Schematics: `ng g schematics <name>`
- Universal: `ng g universal <name>`


## Enhancing Development

- Implement lazy loading for improved load performance
- Use Angular forms for building and validating user-entry forms
- Leverage your Observable pipelines to process multiple datasets
- Modify or create schematics to generate code how you want it
- Use Angular Material, a UI component library built specifically for Angular applications
- Take advantage of RxJS, a library for reactive programming that is included with Angular
- Follow the official Angular style guide to ensure consistency and maintainability in your codebase
- Use the Angular language service extension for Visual Studio Code or other editors to get real-time feedback on your code
- Utilize the Angular Router for client-side navigation within your application
- Consider using ngrx, a state management library that helps you manage complex data flows in your application

## Add-ons

- Add server side rendering: `ng add @nguniversal/express-engine`
- Add ESLint using: `ng add @angular-eslint/schematics`
- Add Prettier using: `ng add @angular-eslint/schematics`
- Add rxjs-tslint: `ng add rxjs-tslint`
- Add Angular Material: `ng add @angular/material`

## npm Add-ons
- Add RxJS: `npm install rxjs`
- Add Angular Forms: `npm install @angular/forms`
- Add Angular Router: `npm install @angular/router`
- Add Angular HttpClient: `npm install @angular/common/http`
- Add Angular animations: `npm install @angular/animations`
- Add NgRx: `npm install @ngrx/store @ngrx/effects @ngrx/entity @ngrx/store-devtools`
- Add Angular Universal: `npm install @nguniversal/module-map-ngfactory-loader`
- Add ngx-translate: `npm install @ngx-translate/core @ngx-translate/http-loader`
- Add Angular Flex Layout: `npm install @angular/flex-layout`
- Add Angular CDK: `npm install @angular/cdk`



Resources
- The official Angular documentation: https://angular.io/docs
- The Angular CLI documentation: https://angular.io/cli
- Angular Material documentation: https://material.angular.io/
- RxJS documentation: https://rxjs.dev/
- The official Angular style guide: https://angular.io/guide/styleguide
- ngrx documentation: https://ngrx.io/
- Angular in Depth, a blog with in-depth articles on Angular topics: https://blog.angularindepth.com/
