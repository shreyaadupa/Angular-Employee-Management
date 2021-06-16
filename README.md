-----**Context**------

We are going to develop a Employee Management application using Angular JS.

**What is Employee Management application?** - Every organization has a employee management application/portal to manage employee information(eg; adding new hire details, updating existing employee information, deleting the employee information when they leave the org)

I have Installed NodeJS and Angular CLI in my Mac, and created a skeleton(draft) project for Employee Management(Angular Based).

Included instructions for you to setup angular in your machine(do this before anything)

Included employee management project requirements at the end of this file.

Let's keep improvising the project requirements, and I'll keep adding more instructions to install needed tools as i learn.


------**Setup - Do these before you start anything**---------

------**Step 1 - Install NodeJs**-------
   
   https://nodejs.org/en/ - Install _"Recommended for most users"_
   
   Verify NodeJS Installation/Version - Run command
                  _**npm -version**_

------**Step 2 - Install the Angular CLI(Command Line Interface)**--------

  https://angular.io/guide/setup-local -> Go to "**Install the Angular CLI**" section

  Open Terminal in Mac -> Run command 
            _**npm install -g @angular/cli**_
  
  Verify Angular Installation/Version - Run command 
               _**ng version**_
  
------**Step 3 - Create Angular Project**-------- 
  
  Create a folder in your machine to organize all your angular apps - I created one with **angular-apps**
  
  Switch(cd) into the angular apps specific directory via Mac Terminal 
   
  Run below command:  
      ng new projectnameofyourchoicehere
         eg: _**ng new angular-employee-management** _
   
   
 ------**Git Installation Instructions and Commands**------
     To Do
   
 -------**References:**-------
   
   Followed this to create Initial Skeleton angular project - https://www.youtube.com/watch?v=i7KaVFOXNUQ&ab_channel=TylerPottsTylerPotts
   
 -------**Questions?**--------
   
   Add your questions here
   
-------**Employee-Management Project Requirements:**--------
  
 Each of this below **Feature(EPIC)** will have **User Stories**(smaller chunks of tasks to complete a feature)
  
  **Features(EPICs) needed:**
   
   1. **Add Employee**- To Enter New Joinee information
      User Stories: TBD
   2. **Update Employee** - To Update existing employee information
      User Stories: TBD
   3. **Remove Employee**- When Employee's Leaves the organization
      User Stories: TBD
   4. **Apply a Leave Request**
      User Stories: TBD
   5. **Approve/Deny Leave Request** - Manager to approve or deny the leave request
      User Stories: TBD
   

-------**Any Thoughts/Ideas?**--------
   
   Pitch in your ideas here
  
  
------Ignore below for now: These were added by default while I was creating a project------------
# AngularEmployeeManagement

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
