# webmvcframework - PHP Web MVC Framework
The webmvcframework package is an object oriented PHP framework that uses MVC architectural design pattern for building web applications with MySQL database and HTML.<br><br>
It offers to developers a complete set of functionalities for rapid development of data intensive web applications. Generally, it provides services for system decomposition that developers can do at different levels when they coding a complex web application. Firstly it entire implements services for realizing the MVC design pattern decomposition between PHP code and the HTML code of the GUI. However, this is not the only feature provided by the Framework for acting on the application's decomposition.<br>
The Component Based Development, used for building many Framework’s features, permits to developers another more level of applications decomposition and software reuse. Framework’s components, in fact, realizes common Aspects that can occurs, in a similar way, into different web applications. Many of these aspects are regarding database, for example: data listing, data listing and sorting, data listing and filtering, data listing and pagination, record management and common table’s operations for select, insert, delete and update records. Framework offers a set of pre-built components for implementing the necessary server logic for these common database management aspects.These components are itself MVC objects with a Controller, are easy to use and developers can aggregate them into a root controller by using a composite criteria for building complex application pages. A component GUI can also easily adapted or replaced to reflect the application’s experience simply by modifying or replacing its HTML template with a custom one. Component’s server logic will remain fully reusable without the need of any source code modifications.<br>
See the docs folders for more information<br/><br/>
## How to install
To install download and copy it into an Apache web folder. Then go to the config directory and modify application.config.php according to your MySQL server configuration and Apache web folder you used to deploy your application.<br/><br/>
By default framework is provided with simple examples.<br>
I will provide further examples in the future to illustrate all its functionalities.<br/><br/>
## How to autogenerate PHP Model classes from your MySQL database
The util directory contains a file named <strong>app_create_beans.php</strong>. <br>
Run it from your browser or from command line for executing ORM autogeneration engine<br>
Warning ! <br>
Before running it you must configure MySQL access parameters by modifying <strong>util\mysqlreflection\mysqlreflection.config.php</strong> according to your MySQL configuration.<br>
After running the generation utility the autogenerated PHP classes were placed into the models\beans directory.
## UML Diagrams of framework classes
### Overview
![alt tag](https://raw.githubusercontent.com/rcarvello/webmvcframework/master/docs/framework.png)
### Dispatcher
![alt tag](https://raw.githubusercontent.com/rcarvello/webmvcframework/master/docs/Dispatch and Create MVC Instance.png)

#### See the docs folders for more information
[Documentation link](https://github.com/rcarvello/webmvcframework/tree/master/docs")
