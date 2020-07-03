## Key Notes / Tips
- No Hands-on problems, 50 (sometimes long) Multiple Choice questions in 2 Hours.
- The choices are very similar to each other. Option to flag a question and review it at the end is handy.
- Proctor is relatively strict, must not deviate eyes from the screen.

## Resources:

1. Link to the Study guide. [Exam Guide](<https://www.qlik.com/us/-/media/files/training/global-us/qlik-sense-certification-exam-study-guide-en.pdf?la=en>)
2. Qlik Continuous Classroom material. [Link](<https://learning.qlik.com/mod/page/view.php?id=24702#home>)
3. Create Qlik account for certification. (https://www.qlik.com/de-de/services/training/qlik-sense-certification)
4. Book the test in Pearsonvue. (https://home.pearsonvue.com/qlik)

## Approach

1. Go through Qlik Continuous Classroom material.
2. Test yourself on Qualification exam to get a feel of the questions. (https://www.qlik.com/us/services/training/certifications-and-qualifications)

## Continuous Classroom Notes

### Business Analyst

1. Getting Started with Qliksense -> Review of lessons learned
    - Has good overview material.
2. Foundations of Building Visualiztions -> Which Charts to use
    - Chart selection help


### Data Architect




## Notes

### Business Analyst

#### 1. Identify Requirements
1. Based on business requirements, identify Qlik products, needed for the solution (QSE,
QDC, QABDI, ODAG, Qlik Core, Attunity, Insight Bot, NPrinting, etc.)
    - QSE- Qlik Server Edition
    - QDC- Qlik Data Catalyst
2. Explain Qlik Sense features (e.g., smart search, responsive design, accessibility
features, themes, etc.) and how they impact app design
3. Describe the differences between the Qlik deployment options
4. Based on business requirements, identify KPIs, dimensions and measures,
5. Ask appropriate questions to understand the needs of the potential users of the Qlik
Sense application
6. Identify user types and their typical devices to use to access apps
7. Explain the purpose of APIs, server-side extensions (such as R, Python), Qlik
GeoAnalytics, web mashups, widgets, section access
8. Explain and interpret results from Qlik Associative Engine
9. Identify Qlik Cognitive Engine uses
10. Consider performance during data loading and application development (removing
unused columns, consider calculation condition)
#### 2. Prepare and Load Data
1. Create a basic data model using Data Manager (e.g., spreadsheets, CSV, flat files,
QVDs, etc.)
2. Define the steps to load and associate data
3. Apply filters while loading data in Data Manager
4. Manually create data table in Data Manager (creates Inline Load script)
5. Explain synthetic keys and possible methods of resolution
6. Create folder and file data connections
7. Leverage data connections already in Qlik Sense Enterprise
#### 3. Design Applications
1. Based on the business requirements and desired insight, determine the optimal
number of charts, correct chart type, order of dimensions, use of color, and measures
2. Design the order of the sheets in an application to provide an overall flow matching
the expectations of the user journey (DAR concept)
3. Select object types appropriate for the required data analysis (e.g., a line chart to
show a trend over time)
4. Understand when and why to use an alternate chart recommendation
5. Identify the proper expression to create the appropriate visualization to meet the
business requirements
6. Explain the impact of using mobiles devices on app design
7. Leverage appropriate method for data comparisons (filters, bookmarks, alternate
states, set analysis)
Page 5
8. Distinguish between situations when data security requirements need to use section
access or security rules
#### 4. Develop Applications
1. Add dimensions, measures, and objects
2. Use the latest objects and features in the Visualization Bundle, e.g., trellis chart, Profit
& Loss pivot table
3. Use Advanced Authoring features, e.g., specify a default landing sheet, native
container object, etc.
4. Set up visualizations with alternate states
5. Change the grid size after adding objects
6. Create and use variables
7. Use custom color in charts (e.g., ColorMix, CSS colors, If statements, etc.)
8. Know what extensions are and when to use them
9. Create a story
10. Create master items
11. Apply filters and create bookmarks
12. Use advanced functions like AGGR and set analysis
13. Perform tasks around making a production ready application (e.g., create a thumbnail
image, appropriate title, etc.)
14. Use Insight Advisor to generate visualizations
15. Use chart suggestions to change visualization type
16. Select appropriate screen layout


### Data Architect

#### 1. Identify Requirements for Data Models
1. Given a set of business objectives, determine KPIs, dimensions or measures
2. Given customer requirements, determine an appropriate solution to meet the
customer needs (e.g., data, variables, master items, GeoAnalytics, advanced analytics
integration)
3. Interpret app security requirements
#### 2. Design Data Models
1. Given a data set, identify quality issues and potential solutions
2. Determine the expected effects of data quality issues
3. Given a data set, determine the relationships among data and how the relationships
will affect the Qlik Sense data model (e.g., performance, accuracy, scalability)
4. Use various methods and explain considerations for connecting to different types of
data sources
#### 3. Build Data Models
1. Describe the circumstances under which different load strategies should be used
(including On-Demand App Generation (ODAG), incremental load
2. Explain load techniques and functions relevant to data transformation and filtering
3. Understand the data profiling capabilities in Data Manager (e.g., sorting, bucketing,
splitting)
4. Understand the differences between Data Load Editor and Data Manager and how and
when to use each or both for loading data
5. Given a scenario, determine how to resolve table association issues (e.g., synthetic
keys, circular references)
6. Explain the circumstances under which QVD and QVX files and/or n-tiered data
architectures should be recommended
7. Describe the use and properties of fact tables and dimension tables
8. Explain how to resolve complex calendar scenarios
9. Explain the use and effects of different types of JOINs, KEEPs and CONCATENATE
10. Given business requirements, determine appropriate section access configuration
11. Explain the use of control statements and/or variables
12. Explain scenarios in which data filtering should be used and how to filter
13. Given a script, determine the cause and/or solution for a script error
14. Add items to the master library, including set analysis expressions and variables
15. Identify and explain the use of Qlik connectors
16. Explain how to convert a QlikView document into Qlik Sense app
17. Identify scenarios for and how to use calculated dimensions.
18. Illustrate how to replace null values in a dataset
19. Utilize ETL within the Qlik Sense environment to support a variety of analysis
requirements (e.g., building data models, layering of QVDs, incremental loading)

#### 4. Validate Data
1. Explain the purpose and functionality of Qlik Sense troubleshooting tools or functions
(e.g., debugger, script log)
2. Explain the purpose and functionality of the Data Model Viewer
3. Use visualization to validate the data model


### System Administrator

#### 1. Identify Requirements
• Evaluate hardware, software, and network to determine if minimum requirements are
met for projected number and size of applications, for initial deployment and
expected future growth
• Describe workflows for setting up and configuring a single-node or multi-node Qlik
Sense Enterprise site (physical or virtual)
• Understand requirements and implications for a multi-cloud deployment
• Identify scenarios in which a multi-cloud deployment is needed
• Understand the implications of virtual and/or cloud-based deployments (e.g., Amazon
Web Services, VMware)
• Set up the connector for Advanced Analytics Integration (AAI) [also called Server-Side
Extensions]
• Explain the Qlik Sense services and their dependencies
• Identify scalability, capacity, and resilience requirements for a multi-node site and the
services to run on each node (e.g., set up a floating central node)
• Plan a Qlik Sense deployment
• Determine data connectivity requirements
• Evaluate the security requirements
• Determine license requirements
• Set up user accounts to perform the installation
• Determine required user directory connection(s)
• Determine the type of virtual proxy to use and implications of the different
authentication methods (e.g., the new JSON Web Tokens (JWT) authentication
method)
• Determine type of scheduler (master/slave) needed to support tasks
• Use the customer/partner portals to gather installation files, associated release notes
and manuals, keeping updated about current product modifications/changes
• Use the online help, Qlik Community, Qlik Branch, Support Portal, and other online
resources for help, technical briefs and documentation
#### 2. Install and Set Up Qlik Sense Enterprise
• Analyze Windows server management console settings to determine the appropriate
configuration for the setup (e.g., required ports are available, firewall settings)
• Demonstrate how to create and configure a network file share
• Install Qlik Sense
• Apply server licenses (including Qlik Licensing Service and signed license keys)
• Configure user access rules
• Install and manage self-signed and third-party certificates (has knowledge of
OpenSSL)
• Set up services for each node
• Configure the user directory connector(s) (e.g., Active Directory, LDAP, Excel/CSV)
Page 9
• Configure user groups, security rules, and streams
• Configure appropriate type of scheduler (master/slave) and reload tasks
• Configure Qlik Sense load balancing rules between nodes
• Set up virtual proxies and authorization
• Set up security rules to restrict/grant access to system, streams and apps (including
groups and custom properties)
• Set up authentication and authorization
• Set up user accounts (either internal to firewall or external)
• Install extensions, and understand the implications
• Apply and evaluate the given configuration of Qlik Sense Services within Windows
Services Applet and Qlik Sense Management Console
• Configure the proxy service (changing a port, moving from HTTP to HTTPS,
configuring a white list, setting up anonymous access, adding a virtual proxy, extra
headers, etc.)
• Explain the use of memory usage settings
• Install or uninstall Qlik Sense software updates
• Configure centralized logging
• Qlik Web Connectors (separately licensed product)
#### 3. Manage Content/ Monitor & Maintain
• Explain the different views in QMC and methods to manage resources
• Locate Windows and Qlik Sense log files, know their purpose, and interpret content to
troubleshoot problems
• Use Log Collector and Cockpit for troubleshooting
• Diagnose and resolve the root cause of problems
• Manage applications – publishing, unpublishing, importing, reassigning, moving apps
between streams
• Troubleshoot and resolve user access problems, including section access
• Troubleshoot and resolve security rule problems
• Troubleshoot and resolve user management problems
• Troubleshoot and resolve application and task problems
• Troubleshoot certificate issues using MMC
• Manage and maintain users (token allocation, delete users, etc.)
• Apply different roles for various users (root, content, audit, etc.)
• Locate resources in various folder of the service cluster (Qlik Sense environment)
• Define custom properties for apps, rules, users
• Use audit functionality to validate rules, etc.
• Troubleshoot and validate data connections
• Set up environment to deploy authentication links (for Desktop, QSE, and Mobile)
• Create and manage tasks according to given resources
• Use License Monitor to validate license information and manage licenses
• Use the Qlik Sense Service Dispatcher (QSD) to launch and manage Migration Service,
Data Profiling Service, Chart Sharing Service, Broker and Hub Service
Page 10
• Use the Operations Monitor in the QMC and Hub for the performance history of
hardware utilization, active users, app sessions, results of reload tasks and errors and
warnings.
• Deploy the custom connectors
• Modify memory usage settings according to changes in the environment
• Create library for database connections, and assign correct rights to them
• Configure governance applications for monitoring
• Set up delegate administration for the QMC using rules based access
• Complete a system backup/restore
• Use appropriate switches in settings files (e.g., SSL for communication between
services, Repository, Program Files, differences between audit, trace, and system logs)
• Monitor simple performance usage through Task Manager
• Modify, repair, update or uninstall Qlik Sense
• Use troubleshooting tools (e.g., Fiddler and Google Dev tools) to resolve issues
• Use the customer/partner portals to log, update, and monitor a support case
• Install and use the Log Monitor, Reloads Monitor, and Sessions Monitor
• Explain the impact of settings for Min and Max Working Set
• Explain how to see pagefile usage and adjust if necessary
• Qlik Licensing Service (QLS) (understand it replaces LEF, understand what it is and
when to use it)
• Troubleshoot ODAG app history and space consumption
