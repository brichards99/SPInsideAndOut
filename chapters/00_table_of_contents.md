# Table of Contents

Service Portal's position within the ServiceNow framework
Technologies to be included and sources of information to support your learning
General scenario and course approach
Where to find supporting materials

## Part I - Developer Orientation

* [KB0020001](KB0020001.md) The Premise
* [KB0020002](KB0020002.md) Service Portal and the Employee Center
* [KB0020003](KB0020003.md) Kanban and Project Management for this Course
* [KB0020004](KB0020004.md) ServiceNow 'Good Practices' for developers

**EPIC20012 Core Configuration**
* KB0020005 Your own private ServiceNow
**Lab 1 Set up your PDI**
**Lab 2 Set up your organization**
**Lab 3 Build background services**
**Bonus Lab: Set up a Visual Task Board to track your work**
**Bonus Lab: Use an integration to create demo accounts and groups**

## Part II - Low-Code / No-Code Configuration

**EPIC20013 Configure the MVP portal for ITSM**

* [KB0020010](KB0010010.md) ServiceNow's many user interfaces
* KB0020011 Service Portal 'Good Practices'
* KB00200XX Service Portal configuration and administration

**Lab 4 Build your MVP Portal**
**Lab 5 Configure the Service Catalog**
**Lab 5 Configure the Knowledge Base**
**Lab 6 Style the MVP portal**
**Lab 7 Build an IT worker landing page**
**Lab 8 Build a custom service status page**
**Lab 9 Validate your portal by testing workflows and behavior**

**EPIC20014 Build a Rock Band Portal**

* KB00200XX Advanced configuration part 1: Service Catalog, Search
* KB00100XX Advanced configuration part 2: Knowledge, Outage
* KB00100XX Requests and the Standard Ticket Configuration
* KB00100XX Page layouts and widget configurations
* KB0010015 Advanced page and widget configurations
* KB0010016 Stylesheets and images

**Lab 9 Set up your band**
**Lab 10 Create a concert events table**
**Lab 11 Configure a catalog of services for the band**
**Lab 12 Build the portal record and pages**
**Lab 13 Create a portal theme**
**Lab 14 Build the band's knowledge base**
**Lab 15 Enable rock-focused search**
**Lab 16 Validate your portal by testing workflows and behavior**

## Part III - Tweaking, Building, and Hacking

**EPIC20014 Your Widget Toolkit**

* KB0010022 Thinking about widget development
* KB0010023 Built-in development tools
* KB0010024 Basic widget design
* KB0010025 Examining 3 Widgets (Icon Link, Simple List, Form)
* KB0010026 Modifying out of the box widgets

**Lab 16 Modify the Icon Link Widget**
**Lab 17 Modify the Simple List Widget**
**Lab 18  Modify the Form Widget**

* KB0010027 Custom widget development considerations

**Lab 19  Create Your Own Icon Link Widget: with enhanced style**
**Lab 20  Create Your Own Simple List Widget: Service Outages**
**Lab 21  Create Your Own Simple List Widget: Actionable Approvals**
**Lab 22  Create Your Own Simple List Widget: Incidents with modal popups**
**Lab 23  Create Your Own Form Widget: Virtual Machine calculator**
**Lab 25  Create Your Own Icon Link Widget: Current Weather**

* KB00100XX Application Scope and the Service Portal  
* KB00100XX Service Portal architecture deep dive  

**EPICXXXX Create a scoped Service Portal clone**

* KB000000 Make a widget reusable - Options and Dynamicism
* KB000000 Advanced widget design with Angular Services

  * Create a project landing page and widget
* KB0010017 Time out for Portal style and Layout
  * Add a custom font to the /demo portal
  * Build a widget MVC proof of concept using SASS
  * Create a dark mode /SPDark Portal
  * Create role-aware color coding
* KB0010026 Widget Development Toolkit Part 2
* KB0010027 Bootstrap and Service Portal


  * Create a customer Incident list with modal popup




EPICXXXX Create a single page portal

## Part IV - Why would you ever do this?

* KB00200XX Approaches to custom development
* KB0010017 Portal security concepts
* EPICXXXX Advanced widget design with localization
* EPICXXXX Making your widgets supportable: error handling and debugging
* EPICXXXX Portal revision project: error handling
* EPICXXXX Use a Service Portal widget in the fulfiller view
* EPICXXXX Build an admin user management tool
* EPICXXXX Create a word association game
* EPICXXXX Create a quiz game
* EPICXXXX Create a company game / training portal

## Part V - Employee Center and Employee Center Pro

* KB00100XX Employee Center basics
* KB00100XX Configuration tools and basic configuration
* KB00100XX Employee Center To-Dos page configuration
* KB00100XX Add modules to the EmpLoyee Center
* KB00100XX Advanced Portal Navigation
* KB00100XX Taxonomy Topics
* KB00100XX Menus

EPICXXXX Configure a branded /ESC Portal


* Virtual Agent
  * Configure the VA for the help desk
* Employee Center Pro Content Delivery

** Set up ServiceNow news and events in Content Delivery
    * EPIC0010007 Service Portal project: Everything But the Kitchen Sink
    * EPIC0010008 Service Portal project: Your Own Private Utah
    * EPIC0010010 Utility Portals: printing, personal dashboard, digital signage
    * EPIC0010011 Developer's Master Portal

3. Mini Project: ChatGPT inside of Virtual Agent

Agile planning portal
Learning management portal
Tailored knowledge portal



## Sprint Reviews

| Epic                      | Stories                                  |
| ------------------------- | ------------------------------------- |
| EPIC20010 Set up your PDI |                                       |
|| Install plugins                       |
|| Create test users                     |
|| Prime your instance with test records |
| EPIC20011 Set up your organization | |
|| Create development users
|| Create a Script Include with dev utilities
| EPIC20012 Build your MVP Portal | |
|| Create a Portal Record
|| Create a custom theme
|| Script the creation of the MVP portal
| EPIC20013 Configure the MVP portal for ITSM | |
|| Use the Branding Editor to update your MVP’s look and feel                       |
|| Configure the /SP Portal with an OOB Service Catalog                 |
|| Configure the /SP Portal with an OOB Knowledge Base |
|| My Requests and the Standard Ticket Configuration
|| Configure Search Sources
|| Add an external search source
|| Configure the way search results are displayed
|| Update the way records are viewed on the Ticket page
| EPIC20014 Build a Rock Band portal
|| Create band members, crew, and roadies
|| Roll your own landing page
|| Customize widgets with widget options
|| Customize widgets with widget instance configuration
| EPIC200XX  Custom Widget MVP
|| Add a Script Include
||  Build a widget MVC proof of concept using ng-repeat
|| Build a widget MVC proof of concept with a Record Watch
|| Build a widget MVC proof of concept with a JavaScript dependency
||  Build a widget MVC proof of concept with a debugging parameter
| EPICXXXX Create a scoped portal project                                |  |
| EPICXXXX Advanced widget design with localization                      |  |
| EPICXXXX Making your widgets supportable: error handling and debugging |  |
| EPICXXXX Portal revision project: error handlinG                       |  |
| EPICXXXX Use a Service Portal widget in the fulfiller view             |  |
| EPICXXXX Build an admin user management tool                           |  |
| EPICXXXX Create a word association game                                |  |
| EPICXXXX Create a quiz game                                            |  |
| EPICXXXX Create a company game / training portal                       |  |

## Appendices

### Appendix 1 GlideRecord Toolbox

* [The GlideRecord API](a2_01.md)
* GlideQuery API
* [GR Dorks](a2_02.md)
* Table REST API

### Appendix 2 Design Patterns

* Service Portal Widget
* Service Portal Widget with Angular Service
