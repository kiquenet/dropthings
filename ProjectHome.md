**Update: There's a newer Metro Style Web Dashboard: [Droptiles](http://droptiles.com)**

## Overview ##
Dropthings is a Personalizable Widget powered Web Portal _framework_ that demonstrates the power of **Ajax and Widget Framework** to build Web 2.0 websites as well as Enterprise Dashboards. You can extend the fully functional site in any way you like. You can **build your own widgets**, besides the built-in RSS, Twitter, Flickr, Weather, Stock, HTML and Static Content widgets. You can build widgets that **render data from your own databases** or collects data from your own webservices and renders them using sophisticated rendering controls.
Dropthings is an N-tier web app with nearly **100% automated test coverage** on the business layer as well as 80% automated UI tests that cover all the UI behaviors. It is a great ASP.NET foundation to build your own application upon, benefiting from the highly extensible codebase that embraces _Dependency Injection, Inversion of Control, Repository Pattern, Caching, Instrumentation, and Unit Testable code_.

## See it live ##
http://dropthings.omaralzabir.com/

![http://dropthings.googlecode.com/files/dropthings_demo.gif](http://dropthings.googlecode.com/files/dropthings_demo.gif)

## Who Am I ##
I am the Chief Architect of SaaS Platform, BT (aka British Telecom).
Ex Co-Founder and CTO of the first Web 2.0 Social Start Page [Pageflakes](http://www.pageflakes.com/)


## Features: ##
  * Internationalization - English, French, Spanish and German already supported.
  * Customizable pages and widgets.
  * Drag & Drop personalization.
  * Feature rich widget framework.
  * Very fast page load with caching and advance javascript tricks to make pages smooth and fast.
  * Entity Framework for database access. Uses repository pattern to easily support other databases.
  * jQuery animations.

## License ##
_**Please donate the following license fee to any prominent charity and show me a receipt. I will be happy to send you a written signed license.**_

License: Free for personal use. For commercial use, non-redistributable license costs $399 per server per site. Unlimited license costs $2499. You just need to donate the license fee to a prominent charity and then email me the receipt and I will send you a signed license agreement.

If it is impossible for you to donate, let me know.

Email me at omaralzabir at gmail dot com.

## Install it from Microsoft/Web ##
http://www.microsoft.com/web/gallery/Dropthings.aspx

## Features ##
  * Allow user to add own tabs and put widgets as user likes.
  * Allow user to customize widgets.
  * Configure widgets for specific user roles.
  * Configure different default page setup for different roles - Managers get some widgets,    Employees get different widgets and so on.
  * Ability to define page setup for anonymous users and different page setup for logged in users.
  * Customizable Widget Gallery - show different widgets to different roles.
  * Different column setup for different tabs.
  * Build your own widgets using Silverlight, ASP.NET or plain Javascripts.
  * Host widgets on any page of your website
  * Easy to integrate Dropthings to your own website e.g. http://myoffice.bt.com is built on top of Dropthings.
  * Highly decoupled architecture making good use of Inversion of Control, Dependency Injection.
  * Business and Data Access Layer fully unit testable.

## Why shouldn't I just code it myself? ##

  * Dropthing has 100+ hours of my effort and over 300+ hours of community effort to get where it is now. If you try to build it from scratch, by the time you get to production quality, you would likely have spent more money than just buying commercial license for the code.
  * Dropthings has a highly readable, extensible, maintainable codebase. It has nearly 90% automated test coverage, which makes making changes on the code and delivering new features more productive than the alternatives.
  * Dropthings is a minimalistic framework to build apps on top of it. It’s not a full blown CMS, which you need to spend months learning in order to customize it. The codebase is small, and highly reusable – making it very easy to build bespoke sites on top of it.
  * Dropthings will force your developers to use industry best practices - use Inversion of Control, product unit testable code, build web layer that scales to millions of users.
  * Dropthings is built specifically to be integrated with existing ASP.NET web applications, where other CMS are built to be run as a standalone app.
  * Dropthings uses latest .NET framework and very strong architectural principles – ensuring devs don’t slack on their coding and design skill.
  * Dropthings has good documentation – a whole book, several articles, hundreds of tests to explain the code, video tutorials for learning the source code and building widgets etc.
  * Dropthings is used by world’s largest telco BT to serve 3MM users every day, not to mention Thomson Reuters, Intel, Microsoft UK, Canada Border Protection and so on.

There's a whole book written on how Dropthings works:
[![](http://oreilly.com/catalog/covers/9780596510503_cat.gif)](http://oreilly.com/catalog/9780596510503/)

## Project documentation ##

![http://dropthings.googlecode.com/files/Dropthings%20Architecture.png](http://dropthings.googlecode.com/files/Dropthings%20Architecture.png)

Here's the original article:

[Build Google IG like Portal in 7 days](http://www.codeproject.com/KB/ajax/MakingGoogleIG.aspx)

This latest article explains the recent changes made in Dropthings:

[Web 2.0 AJAX Portal using jQuery, ASP.NET 3.5, Silverlight, Linq to SQL, WF and Unity](http://www.codeproject.com/KB/ajax/Web20Portal.aspx)

On the Wiki tab, you will find some more articles and video tutorials.

## Quick Video Tutorials ##
  * CodeExecutionFlow - Walkthrough of the code execution flow from UI to database.
  * ProjectsWalkthrough - Understanding the projects in the solution
  * AddNewWidget - Add a new widget in less than 5 mins
  * TroubleshootingDatabase - Troubleshoot common database issues and creating new database from scratch.
  * WidgetLoadDataFromDatabase - Create a widget that renders data from a table in database.
  * [AddANewBusinessOperation](http://code.google.com/p/dropthings/wiki/AddANewBusinessOperation) - How to add a new Linq to SQL query, a data access method and a business method consumed from a UI.

See the Wiki for more tutorials.

## Project Urls ##
  * Production site http://dropthings.omaralzabir.com
  * Downloadable releases: http://code.google.com/p/dropthings/downloads/list
  * Source Code http://code.google.com/p/dropthings/source/checkout
  * Blog http://omaralzabir.com

## How to run this ##
  * Install Visual Studio 2008
  * Install [Visual Studio 2008 SP 1](http://www.microsoft.com/downloads/details.aspx?FamilyId=FBEE1648-7106-44A7-9649-6D9F6D58056E&displaylang=en)
  * Install [Silverlight 3 Tools for Visual Studio SP 1](http://www.microsoft.com/downloads/details.aspx?familyid=9442B0F2-7465-417A-88F3-5E7B5409E9DD&displaylang=en)
  * Install[SQL Server 2008 Express SP 1](http://www.microsoft.com/downloads/details.aspx?familyid=01AF61E6-2F63-4291-BCAD-FD500F6027FF&displaylang=en)
  * Install [WCF Rest Starter Kit](http://www.asp.net/downloads/starter-kits/wcf-rest)

If you do not have SQL 2008, then see video tutorial how to get it to work on SQL 2005. But you cannot make it work without VS 2008 SP1 and Silverlight 3 tools for VS SP 1.

## Source Code ##
Click on the "Downloads" tab
[Downloads](http://code.google.com/p/dropthings/downloads/list)

## Production sites using Dropthings ##
BT Business MyOffice portal  http://myoffice.bt.com

## Customers using Dropthings ##
  * Thomson Reuters
  * Intel
  * Microsoft
  * BT


[![](http://omaralzabir.com/plea.png)](http://omaralzabir.com/charity)

## Technologies ##
  * ASP.NET 3.5
  * jQuery
  * ASP.NET AJAX (.NET 3.5)
  * Silverlight
  * Linq to Sql
  * Linq to Xml
  * Inversion of Control
  * Dependency Injection using Unity
  * Enterprise Library loggin, exception handling.
  * Aspect Oriented Programming with [AspectF](http://code.googlecode.com/p/aspectf/)

## What is an AJAX portal ##
A Portal refers to a page that allows users to customize their own homepage by dragging and dropping widgets onto the page. This approach gives users complete control over what content they see on their page, where they want to see it, and how they want to interact with it.

A widget is a discrete piece on a Web page that performs a particular function and comes with its own UI and set of features. Examples of widgets include a to-do-list, an address book, a contact list, an RSS feed, or even a clock, calendar, playlist, stock ticker, weather report, traffic report, dictionary, game, or almost anything you can imagine that can be packaged up and dropped on a Web page. In a corporate environment, widgets can connect to internal systems, such as an Expense Tracker widget that interacts directly with the internal Accounting System. If you are familiar with Sharepoint Portal, then you already know about Widgets. They are called Web parts in Sharepoint’s term and also in ASP.NET 2.0.

Portals are powerful RSS aggregation platform. You can put as many RSS widgets as you like on your page and get fresh content delivered to you as soon as it is published. Some Portal like Pageflakes archives RSS for a long time and thus you can go back in time and read older posts, save posts, and forward interesting articles to your friends.

An Ajax-powered portal is specifically a portal that uses Ajax technologies to create richer experiences for its users. It is one step ahead of previous generation portals like My Yahoo or MSN.com, because it gives you state-of-the-art UI that behaves more like a Windows client application -- with widgets, animations, popups, client side data grids, and other effects not usually found on a non-Ajax Web portal.

## How is ASP.NET AJAX used in this project? ##
It is an N-tier application, with a user interface (UI) layer, a business layer, and a data access layer. I have used ASP.NET AJAX to implement the UI layer of the portal application which includes the homepage and the widgets’ UI. ASP.NET AJAX provides the framework for loading widgets onto the home page, updating widgets without doing any postbacks (via UpdatePanel), and changing page layout by dragging and dropping widgets on the page. It also provides a rich collection of Control Extenders, that add cool effects like fade in/fade out, smooth transitions, and client side animations . You can add to the rich clientside experience by providing auto-completion behavior on text boxes, asynchronous data loading via webservice calls, and client side paging, sorting and many more.

## How is .NET 3.5 used in this project ##
The business layer of the application is built with the Workflow Foundation in .NET 3.0 . Major operations like a first-time user visit, a subsequent user visit, adding a new widget, and creating a new page are all orchestrated using workflow . The workflows contain all the business rules and activities needed to complete each operation. For example, the "New User Visit" workflow creates the user account, populates the user profile with default values, creates some default pages, populates them with specific widgets, etc. Such compound operations are very easy to build with Workflows , which enables you to break the complete workflow operation into smaller chunks named Activities. Each Activity does a very small amount of work. It talks to the data access layer and performs the task. The data access layer is built with .NET 3.5 , utilizing LINQ to SQL .
The web project and the widgets make good use of .NET 3.5 by utilizing lambda expressions , LINQ to SQL, and LINQ to XML. You will use Linq queries to work with collections and database rows. Widgets make good use of Linq to Xml in order to consume XML from external data sources.

Warning: Dropthings.com is a very simple, open-source example of what can be done with AJAX and Microsoft technologies. It is intended for educational purposes only. Dropthings.com has absolutely nothing to do with http://www.pageflakes.com. But this project does a good job to show you how all the new hot technologies work together in a working web application that's production ready.

