# Angular
## Introduction
* Open source javascript MVC framework for web application and allow you to create reactive single page application
* Only 1 HTML file and bundle of JS(JavaScript) got from server
* Good user experience
### Version
 - Angular JS(2010) 
 - Angular 2(2016) 
 - Angular 4(2016 dec)......
 - Angular 11/12(2020)
 ## What angular do?
 * Allow us to mix static html code and dynamic things in our code
 * It is not a tool to allow us to write static html files
 ## Install angular using syntax(In terminal)
 * To install globally this is the syntax of angular cli
		``npm install -g @angular/cli``
* To check installation of node & npm 
 	``npm -v``
	``node --v ``
 * For update
	``npm install -g npm``
* To check version
 ``ng --version``
 * Application development (for coding)
 ->Visual studio code
  ### NPM (Node Package Manager)
 ->To install libraries, package and aslo scripts
 ### Angular CLI
 -> Generate, build, run and deploy angular applications
 ->Fastest and easiest 
 ->It uses ```package.json``` file to install all necessary libraries, packages for angular
 * some cli commands are
 * ``ng build `` --->compile an angular app into an output directory
 * ``ng serve`` --->build & serve your application, rebuild on file changes
 * ``ng generate``--->Generate/Modifies files based on a schematic
 * ``ng test``---> Runs unit tests on a given project
 ## Create angular application
 * Angular CLI helps us to setup workspace & initial application quickly, which includes necessary npm libraries and dependencies for application
 * create new project --->``ng new projectname``
## Run angular application
* use angular CLI --->``ng serve``[to build application]
* ``ng serve -o``--->  here -o refers to open automatically in default browser
* use npm command ---> ``npm start``
* Default --->``http://localhost:4200``to see the application
* stop build process in terminal --->``ctrl+ c``
## Files in angular
#### ng serve
* keep watching source files, rebuilt and refresh automatically
* Basically bring up development server (create bundles)
#### package.json
* you can see all dependencies of your project , Third party packages and devdependencies
#### e2e
* end to end testing
#### nodemodules
* all dependencies was installed  in this folder
#### app.component
* always a template
#### main.ts
* this file executes first
*  entry point to angular application
#### index.html
* only web page in angular application called Single Page Application
- ``app.module.ts``--->Root module
- ``app.component.ts``--->Root Component
## Angular Component
#### HTML template
* Regular HTML with angular syntax to communicate with component class
* Every component has an HTML template that declares how that component render
#### Component Class
* Is a typescript class includes properties and methods
* properties---> store data
* methods--->logic  for component
* Component--->[Template + Class + metadata]
#### Component Metadata
* Extra data for component by angular api to execute component such as location of HTML and CSS files of component, selector, providers etc..
## Generate angular component
- To generate -->``ng generate component componentName``
- Shortcut -->``ng g c componentName``
* It will create a html file, css file, class file and test file
* @component decorator used to specify metadata for component class and it is a function & include different config for the component
## Module
* one or more components and services
## Typescript
* Superset of JS
* It doesn't run in browser. so, it is compiled to JS(Javascript) 
* In angular, TS(TypeScript) is compiled to JS
* It provides support for decorator
## Event binding 
* Listen for events and HTML
* event in parenthesis``( )``
## Data binding 
* Communication between Ts of your component, business logic & template
* Binding data to view
## Class binding 
* eg : <h2 [class.text-danger]="haserror">
 ## Property binding 
* Properties---> DOM (Document Object Model)
* Property values can change
## Interpolation
* Used for one way data binding 
* ``{ { } }``--->delimiter/template expression [This delimiter  convert to string]
* You can't write block expression here
## Two-way data binding 
* Sharing data between component class and template
* It supports using ngmodel directive and also setter and getter methods
## NgModule
* Collect code into functional sets
* It has NgModel, NgStyle, NgClass etc
* NgModel--->(Two way data binding to an HTML form element, to display data property and update that property)
## NgModel directive
* Syntax--->``[ ( ) ]`` (banana box syntax)
* It synchronize value from UI to a property and vice versa
* [ ( ) ] = [ ] +( )  where ( )--->binds an event, [  ]--->binds attribute
## Dependency Injection
* The framework creating instance of things and injecting them into places where they need
* Tell angular to use where
* Inversion of control and decoupled code(Provide modules)
## pipes
* This pipe operator( | ) transforms data only for view
* This allow us to transform data before displaying them in the view
* eg: {{name | lowercase }}
## Filters
* This filter operator select a subset of items from array and return it as new array
## Directive
* Directives are classes that add additional behavior to elements in your Angular applications. With Angular's** built-in directives**, you can manage forms, lists, styles etc..
#### Structural directive
* modify layout in DOM
#### Attribute directive
* change the behavior / appearance
### Decorator
* Expression that evaluates to a function allowing annotation of classes at design time
* ``@ ``---> denotion of decorator
## Service
* Business logic
* A class with a specific purpose
* For sharing data, implement logic and external interaction
* creating service file---> ``ng g s servicename``
### Injectable
* Tells angular that this service itself as dependency if we want to inject a service into another service **injectable** decorator is must
* if **@Injectable** is removed then it will be consider as plain typescript
## Forms
* It provides built-in validators, custom, async and form object representation
* Two approaches
	* ** Template driven** [logic in template markup]--->these are tied to template directives must provide custom validator directive that wrap validation functions
	* ** model driven /reactive form** [logic in component class]--->define custom validators as functions, that receive a control to validate
## Difference between reactive form and template form
* **Template form** 
	 easy to use ,		
	formsmodule	,	
	Ngmodel					
*  **reactive form**
	full powered,
	 reactiveformsmodule,
	  Formgroup and formcontrol
## Form Validation
* It is an integral part of managing any set of forms
* apply in form control objects in formgroup
## Routing
 * it done using routermodule
 * ``<router-outlet></router-outlet>``---> navigating html pages
 ## Http - Hypertext Transfer Protocol
- It send request & receive response  
- Http works based on request /response pairs  
- Stateless protocol [no request needed (to connect with another)]  
- Client-server protocol
 
