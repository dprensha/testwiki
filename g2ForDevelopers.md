---
subtitle: Helping New Developers Contribute Sooner
title: G2 For Developers
---

Purpose
=======

Historically, it takes months for a new developer to acclimate to the G2
project, its development teams (DevTeams), and organizational structure.
How can the amount of time required to contribute be reduced? Hopefully,
this document will reduce the lag time by collecting useful information
for new developers.

Overview
========

G2 is an application for the National Nuclear Security Administration
(NNSA) that helps this agency manage funding of nuclear nonproliferation
activities. G2 currently manages over \$2 billion of the NNSA's \$13.9
billion-dollar 2018 budget. The following
[video](https://www.youtube.com/watch?v=BEwz3IA8NQ8) provides a
high-level overview of G2.

Nonproliferation activities are in the areas of infrastructure,
maintenance, safety, and security. G2 enables the NNSA to make decisions
about which projects receive funding based on risk to their missions.
Infrastructure includes buildings, roads, power supplies, and equipment
just to mention a few. In addition, G2 provides the ability to schedule
when funding will be distributed.

G2 provides the ability to schedule training events for security
personnel at the Y-12 National Security Complex. As part of nuclear
security, G2 maintains an inventory of equipment containing radioactive
sources including abandoned devices. Primary inventory consists of
medical devices used in imaging equipment and in medical processing of
human blood and tissue.

Customers
---------

The project was started in 2007 and after 10 years continues to gain
additional customers within the NNSA. Current customers include:

-   NA-50 PE - Office of Safety, Infrastructure and Operations

-   NA-21 GMS - Global Material Security

-   NA-23 - M3 - Material Management and Minimization

-   NA-24 - Nonproliferation and Arms Control

-   NA-80 - Office of Counterterrorism and Counterproliferation

-   NA-193 - Capabilities Based Investments (CBI)

-   NA-10 - Office of Defense Programs

Each customer is represented by a product owner (PO) which represents
the business interests of their organization. POs are members of one or
more agile teams.

Functionality
-------------

An overview of G2's functionality is as follows:

  Module                 Description
  ---------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Inbox                  Links to modules in G2 that may contain items of interest. Visible links are limited to the modules a user has been granted access.
  Asset Management       Provides ability to maintain data on infrastructure assets
  Program Management     At various WBS levels, provides the ability to see costs, commitment, and carry over versus plan. Displays percent complete versus plan.
  WBS Dashboard          WBS stands for Work Breakdown Structure which contains the hierarchical organization of projects managed by G2. This dashboard provides the ability to search projects and display only those matching the criteria entered.
  Financial Dashboard    By default, displays a dashboard of monthly financial summary data. Includes extensive search capability of processed transactions. Provides the ability to combine funding requests into FinPlans.
  Activity Funding       Provides the ability to request funding for a project managed by G2 by performer, fund type, and activity. Until this feature was developed, G2 did not contain the ability to request funding below the level of a project.
  Funding Requests       Provides the ability for a project to request funding by performer, fund type, and B&R. If approved, requested funds would come from funding already in the G2 project.
  FinPlan                Short for Financial Plan, provides the ability to transfer money from one project to another. If approved, requested funds would come from funding already in the G2 project.
  Browse Transactions    Views financial transactions that are under review or ones that have been processed
  Funding Adjustment     Mechanism for adding funding to projects managed by G2 from external projects that are not part of G2. Likewise provides the ability to remove funding from G2 projects to external projects not managed by G2.
  Monthly Costs          Enables organizations to manage monthly performer costs
  Year End Forecasting   Provides the ability to specify how funds will be spend through the remainder of a fiscal year
  BCR                    Short for Baseline Change Request. Involves adjusting milestones, creating new tasks or cancelling existing ones, adjusting project metrics, or adjusting budget of a project.
  Schedule               
  Event Manager          Scheduling and tracking of nuclear security training events at the Y-12 National Security Complex
  GIS                    Provides ability to visualize data on maps
  Inventory              Inventory of radiological, nuclear, and alternative technological sources and devices
  SPA                    An Office of Radiological Security assessment module for inventory
  Search & Secure        Tracks radioactive material and nuclear assets identified during NNSA assessments
  Travel                 Allows organizations to manage travel expenditures
  Reports                G2 contains extensive reporting capabilities. Data from some reports have many of which are reported to Congress
  Proposal               Manages proposals received from solicitations
  Safety Management      Provides the ability to perform, review, compare, and evaluate a site's conformity to safety standards

Roles and Permissions
---------------------

G2 users are assigned to roles which in turn have specific permissions.
And roles are connected to modules in G2. For example, a user can be
assigned to the "***Funding Request: User***" role which would enable
them to view, create, edit, and submit a funding request. Role and
permission configuration are managed in the G2 database and is
configured per module.

Workflow
--------

Changing data requires approval by appropriate authorities. The roles
that perform these approvals, the order in which they occur, and any
actions allowed at each level make up the "workflow." Workflow for each
module is independent and is configured in database.

Organizational Structure
========================

[Ty Deschamp](mailto:Tyson.Deschamp@NNSA.Doe.Gov) is the Federal Program
Manager for the G2 project and is in Washington, DC. Oak Ridge National
Laboratory (ORNL) is the primary contractor to the NNSA while Argonne
National Laboratory (ANL) develops the GIS capabilities. ORNL partners
with the companies Cadre5 and Acato Information Management, LLC.

[Tim Wynn](mailto:wynntg@ornl.gov) oversees the project at ORNL, [Chris
O'Neal](mailto:Chris.Oneal@cadre5.com) is the technical lead at Cadre5,
and [Cathy Toth](mailto:cathy.toth@acatoim.com) from Acato oversees
quality assurance on the project. Located in Knoxville, Tennessee,
Cadre5 develops enterprise and scientific software. Located in Oak
Ridge, Acato specializes in providing software quality assurance
services.

Development Organization
========================

Development follows the "Essential Configuration" of the Scaled Agile
Framework (SAFe). For detailed information about SAFe, please refer to
the [SAFe web site](https://www.scaledagileframework.com/). Agile teams
consist of a SCRUM Master (SM), PO, and DevTeam which is made up of
developers and testers. SM roles are part time as they are also
developers or testers on their respective DevTeam.

Currently each agile team has their own code branch for development. At
the end of each iteration (sprint), changes are merged into trunk and
deployed to the staging environment. Plans are underway to switch to
feature-based development. In this scenario, each feature will have a
corresponding code branch. Once complete, feature changes would be
merged into trunk.

G2 agile teams are organized as follows:

-   X-Men

-   Honey Badgers

-   Punk Pandas

-   EPSG3857

-   Core Team 2

-   Core Team 4

-   Autobots

-   DevOps

X-Men
-----

Originally named Core Team 1, this team primarily develops features for
NA-21 GMS. Their responsibilities include:

-   Financial Dashboard

-   Funding Requests

-   Activity Funding

-   Inventory (of Radiological and Nuclear material)

-   SPA -- Sustainability and Protection Assessment

-   Year End Forecasting

-   Search and Secure

-   Event Manager

Honey Badgers
-------------

Originally named Core Team 3, this team primarily develops and enhances
features for NA-50 PE. Their responsibilities include:

-   Asset Management

-   Infrastructure Planning

-   Program Management

-   Builder

-   DevOps

Punk Pandas
-----------

This team was created when Core Team 3 was divided into two teams.
Consequently, this team was numbered next is succession and was
originally known as Team 5. This team develops for several subsystems
including NA-50 PE, NA-24, and NA-80. Their responsibilities include:

-   Proposals

-   DevOps

-   Automation

EPSG3857
--------

Creatively named after EPSG (European Petroleum Survey Group) and 3857
(the projected coordinate system used by G2), this team is primarily
located at ANL and develops all GIS functionality.

Core Team 2
-----------

This team is dedicated to designing the user experience for NA-50 PE but
consults with other agile teams on design issues and standards for the
project.

Core Team 4
-----------

Primarily develops for NA-50 PE, this team's responsibilities include:

-   BCRs

-   Spend Plans

-   Notifications

-   Infrastructure Planning

-   Program Management

-   DevOps

Autobots
--------

This team is dedicated to automated testing and was formed at the start
of the 9.2 Program Increment (release).

DevOps
------

This team is primarily dedicated to operations of the development,
staging, training, and production environments. Development efforts deal
with securing access to the G2 application through the Web Application
Firewall or WAF. DevOps development is performed by other teams.

DevOps maintains separate environments for development, staging
(testing), training, and production. Separate servers are maintained for
database, web sites, reporting, and tools. The following servers are
involved:

  Server           Purpose
  ---------------- -----------------------------------------------------------------------
  NN1DEVDB03       Development database server
  NN1STGDB03       Staging database server
  NN1PRDDB03       Production database server
  NN1TRNDB03       Training database server for customer use
  NN1QADB03        QA database server (current copy of production for comparison)
  NN1DEVDW03       Development data warehouse server
  NN1STGDW03       Staging data warehouse server
  NN1PRDDW03       Production data warehouse server
  NN1TRNDW03       Training data warehouse server for customer use
  NN1QADW03        QA data warehouse server (current copy of production for comparison)
  NN1DEVAPP03      Development application server
  NN1STGAPP03      Staging application server
  NN1PRDAPP03      Production application server
  NN1TRNAPP03      Training application server for customer use
  NN1QAAPP03       QA application server (current copy of production for comparison)
  NN1DEVAPPMAP01   Development mapping (GIS) server
  NN1STGAPPMAP01   Staging mapping (GIS) server
  NN1PRDAPPMAP01   Production mapping (GIS) server
  NN1TRNAPPMAP01   Training mapping (GIS) server for customer use
  NN1QAAPPMAP01    QA mapping (GIS) server (current copy of production for comparison)
  NNOPSTOOLS03     Contains development tools for use by select distributed team members

Team Web Sites
--------------

Currently each team has a dedicated development web site. Each team's
URL is related to their original number and is summarized below.

  Team            Development Web Site
  --------------- ----------------------------
  X-Men           <https://t1dev.g2.doe.gov>
  Honey Badgers   <https://t3dev.g2.doe.gov>
  Core Team 4     <https://t4dev.g2.doe.gov>
  Punk Pandas     <https://t5dev.g2.doe.gov>
  EPSG3857        ?????

Developer Tools
===============

-   [Visual Studio 2017
    Professional](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Professional&rel=15)
    -- Microsoft's development IDE

-   [Visual Studio
    Code](https://code.visualstudio.com/docs?dv=win&wt.mc_id=DX_841432&sku=codewin) -
    For React development

-   [SQL Server Management Studio
    (SSMS)](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-2017)
    -- Microsoft's database development IDE

-   [SQL
    Prompt](https://www.red-gate.com/products/sql-development/sql-prompt/?gclid=EAIaIQobChMIi-z0z6Db3AIVQjyBCh3LNwvqEAAYASAAEgLuyfD_BwE)
    -- Redgate product for writing t-SQL

-   [SQL
    Compare](https://www.red-gate.com/products/sql-development/sql-compare/?gclid=EAIaIQobChMIqJrjsqLb3AIV2AeBCh0BPA2fEAAYASAAEgJFbvD_BwE)
    -- Redgate product for comparing and deploying SQL Server schemas

-   [Discord](https://discordapp.com/) -- Instant messaging (Contact
    [Chad Gilbert](mailto:Chad.Gilbert@cadre5.com) at Cadre5 for access)

-   BlueJeans (Video conferencing service provided through ORNL)

-   [TortoiseSVN](https://tortoisesvn.net/downloads.html) -- Interface
    to version control system for application code and documentation

-   [AnkhSVN](https://ankhsvn.open.collab.net/) -- Subversion support
    for Visual Studio

-   [Git](https://git-scm.com/downloads) -- version control system used
    for the database

The project also has several standards documents for development:

-   Architecture

-   Coding

-   Database

-   Report Color Scheme

-   Style Guide

These can be found in the ***G2 Documents/Standards*** folder in the
[Subversion
repository](https://svn.cadre5.com/svn/utbattelle-g2-documentation/trunk).
Contact [Chris O'Neal](mailto:Chris.Oneal@cadre5.com) for access to this
repository.

Development
===========

G2 is a C\# web application developed using Microsoft Visual Studio
Professional Edition, Visual Studio Code for React development, and SSMS
for database development.

Visual Studio Solution
----------------------

The G2 solution contains the following projects:

  Project              Description
  -------------------- ---------------------------------------------------------------------------------------------------------------
  C5.SSRS              
  G2.Business          Business objects
  G2.Core              
  G2.Data              Data access layer
  G2.Domain            Domain objects used by most projects
  G2.Mobile.Services   
  G2.Routes            
  G2.SharePoint        
  G2.SPA               
  G2.Web               Startup project and presentation layer. UI currently contains a mix of ASPX, MVC, and React (newest features)

The solution extensively uses .Net framework, but the following
non-Microsoft libraries are used:

  Library           Description
  ----------------- ----------------------------------------------
  AutoMapper        
  Epdfcreator       
  Epmergepdf        
  Log4net           
  OfficeWriter      SoftArtisan library for creating Excel files
  Newtonsoft.Json   
  Antlr3.runtime    
  WebGrease         

Running Solution Locally
------------------------

Running the solution locally is simple, just modify the
SQLConnectionString entry in the user.config file to access the
appropriate team database. For example, if a new developer is working on
the X-Men team this setting would be changed as follows:

\<add key=\"SQLConnectionString\" value=\"Data
Source=nn1devdb03.ornl.gov;Initial Catalog=G2Team1;Persist Security
Info=True;User ID=g2;Password=g2pass!!; Min Pool Size=10; Application
Name=G2-Dev\"/\>

And the password when running from code is g2pass! -- that is g2pass
followed by an exclamation point. Just trying to be very clear here .

Visual Studio Code
------------------

Visual Studio Code is used for React development. React development uses
the following packages:

  Package   Description
  --------- -------------
            

SSMS
----

Redgate's SQL Prompt is essential for database development using SSMS.
Extensive snippets and utilities have been developed for use by the
project. Contact [Mark Brown](mailto:Mark.Brown@cadre5.com) at Cadre5
for more information about snippets and additional database tools.

Version Control
---------------

The application version control system used is Subversion and [source
code access](https://svn.cadre5.com/svn/utbattelle-g2-app/branches) is
managed by Cadre5. [Chris O'Neal](mailto:Chris.Oneal@cadre5.com) should
be contacted for access. TortoiseSVN is the Subversion client that
integrates seamlessly with Windows Explorer and AnkhSVN provides
Subversion integration with Visual Studio.

[Database version control](https://code.ornl.gov/bor/g2db) uses Git and
is also managed by Cadre5. [Chris O'Neal](mailto:Chris.Oneal@cadre5.com)
should be contacted to gain access to database repositories.

Database
========

Central to G2 is a SQL Server database; currently SQL Server 2016 is
used. Development is performed using the server NN1DEVDB03. The database
is managed by Cadre5 with support from DevOps at ORNL. [Mark
Brown](mailto:Mark.Brown@cadre5.com) at Cadre5 is the senior database
developer on the project.

Currently each agile team has their own database for development. At the
end of each iteration (sprint), database changes are merged into the G2
database and deployed to the staging environment. Plans are underway to
switch to feature-based development. In this scenario, each feature will
have a corresponding database. Once complete, database changes would be
merged into the common G2 database.

The Version 9.1 G2 database contains the following quantities of items
(approximately):

-   Tables -- 1105

-   Views - 97

-   Stored procedures -- 3982

-   Functions - 1045

-   Triggers - 1369

-   Table Types - 316

-   Roles -- 11 (custom)

-   Schemas -- 52

Schema
------

Schema are used for organizing objects and each loosely corresponds to a
module in G2. The following list describes the existing schema:

  Schema                    Description
  ------------------------- ---------------------------------------------------------------------------------------------------------------------------
  Activity                  Contains Activity Funding related objects
  ArchivedPlanning          
  Assessment                
  AssetManagement           Contains Asset Management related objects
  Audit                     Contains objects related to auditing of data changes in G2
  Baseline                  Contains Baseline Change Request (BCR) objects
  BudgetFormulation         Contains Budget Formulation objects
  Builder                   
  Calendar                  Contains scheduling (calendar) objects for Event Manager
  Contact                   
  CostSharing               
  CostSubmission            
  Deployment                Contains objects related to deploying database changes
  DW                        Contains data warehouse objects
  Event                     
  FileImport                Contains general purpose objects related to importing data from files
  FIMS                      
  Financial                 Contains Financial related objects
  G2                        Contains objects that are commonly used by most modules
  Geo                       Contains geospatial objects which are part of GIS module
  Inquiry                   
  Inventory                 Contains Inventory objects related to radioactive inventory
  MDI                       
  Mobile                    
  Notification              
  OtherCosts                
  Performance               
  Planning                  
  PreservationOfSnapshots   
  ProgramManagement         
  Proposal                  Contains Proposal module related objects
  ProspectiveFunding        Contains Funding Requests related objects
  Radtrax                   
  Report                    Contains Report related objects
  ReportArchive             
  ReportParameter           
  ReportPMAX                
  ReportProjectControl      
  SearchAndSecure           Contains Search and Secure related objects
  Security                  Used by Security
  SnapShot                  Contains objects related to auditing data changes to select tables
  SPA                       Contains SPA module related objects
  SPAArchive                
  STARS                     
  Sustain                   Contains Sustainability related objects which is part of SPA
  Tools                     
  Travel                    Contains Travel module related objects
  Workflow                  Contains objects related to providing workflow functionality
  xGen                      Contains generated stored procedures used for simple table access and manipulation
  xGenCustom                Contains customized stored procedures used for table access and manipulation that was too complicated for xGen procedures
  YearEndForecast           Contains Year End Forecast module related objects

Acronyms
========

The following acronyms will be encountered:

  Acronym            Stands For
  ------------------ --------------------------------------------
  BCR                Baseline Change Request
  BNR and B&R        Budget and Reporting
  FinPlan            Financial Plan
  HQ                 Headquarters
  HQAFP and HQ AFP   Headquarters Approved Funding Program
  NFWA               No Funds Work Authorization
  WBS                Work Breakdown Structure
  FY                 Fiscal Year
  AY                 Appropriation Year
  STARS              Standard Accounting and Reporting System
  IP                 Infrastructure Planning
  ART                Alarm Response Training
  PRDT               Personal Radiation Detector Training
  TTX                Table Top Exercise
  TTXCV              Table Top Exercise Coordination Visit
  EM                 Event Manager
  SS                 Search and Secure
  LEA                Law enforcement Agency
  NSAT               Nuclear Security Alarm Training
  ETC                Estimate to Complete
  SPA                Sustainability and Protection Assessment
  YEF                Year End Forecasting
  NLSA               National Level Sustainability Assessment
  EOC                Elements of Cost
  NSDD               Nuclear Smuggling Detection and Deterrence
  ORS                Office of Radiological Security
  GMS                Global Material Security
  M3 and MMM         Material Management and Minimization
  INS                International Nuclear Security
  IDD                In-Device Delay
  KPI                Key Performance Indicator
  SMP                Safety Management Protection
