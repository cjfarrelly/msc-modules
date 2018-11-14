# Module 1 Labs

## Introduction

As part of my submission I will add a cover page, but not on a public repository.

## Lab 1 - Git

### Description/Aims

Git is a distributed version control system widely used by the software community to collaborate easily on files. Git is essentially a miniature filesystem that uses snapshots; also known as commit points to keep a history of change. Git is distributed meaning that users can share their files easily with each other.

The aims were:
#note the higher level aspirtation and the reference to the lifecycle
1. To install and explore Git for use as a version control tool for a local repository as part of quality control in the SDLC.
2. Integration with other DevOps tools.
3. Ability to track and undo file changes.
4. Readability of file history.

### Method
#No essays please. 3/4 page of concise bullet points. Keep it brief.
The 64-bit version of Git for Windows was downloaded and the install instructions were followed. The GNU General Public License was acknowledged. Visual Studio Code was selected as the default editor to be used by Git. Windows Command Prompt was chosen to use Git from the command line, this option modifies the PATH variable of the Windows Operating System. The default OpenSSL library was chosen for Git to use over HTTPS connections. The default Checkout Windows-style, commit Unix-stlye line endings was chosen for how Git will treat line endings in text files. The default Use MinTTY was chosen as the terminal emulator that Git Bash will use. The default file system caching and Git Credential Manager features were left enabled with symbolic links left disabled. Experimental features were left enabled by default, these were built-in rebase and built-in stash. Git was installed and the Release Notes were viewed.

A repository was created. A sample text file was placed at the base of the newly created repository. The Git status command was ran to confirm the new file's existence. The file was added to the git staging area. The changes were committed. Further changes were made to the document. The Git log command was used to show a complete history of changes. Git reset was used to revert changes back to a previous commit point.

### Results
#likewise bullet points. 
Git was installed successfully on the Windows Operating System. 
Git cmd folder was confirmed to have been added to the PATH environment variable. 
A local repository was created and adequately explored within the time allowed.
#and so on...

### Conclusions

Git is a useful tool not only for DevOps practices but the software industry as a whole. It was extremely easy to download and install with a minimum amount of configuration required. The documentation is exhaustive[2] and easy to follow with very simple but thorough examples.

With Git being a command line tool the possibilities of integrating it with other DevOps tools to complete a process flow appear very possible. Flow's such as Build and Release pipelines for deployments, project management tools for tracking work or even creating release notes by using the commit logs between releases are real world use cases.

The use of command line tools can be somewhat overwhelming at first but once the basics are mastered adding, editing and removing files became instinctive. There are multiple GUI (Graphical User Interface) based tools available for the usage of Git but it would be envisaged that with practice the command line would be out perform these from a user perspective.

The Git log is easy to follow with each commit point having a unique code (SHA-1 checksum)[3] this means that any commit point can be returned to at any stage. With this ease of use in mind and such a complete history it would be understood that more advanced operations such as branching and merging would be a less laborious task.
#If you are looking for 70+ I would suggest getting a bit deeper into the conclusions and to ensure that you reference well to #justify your points.


## Lab 2 - Jira

### Description/Aims

Jira is a project management system used primarily for the oversight of software projects. It gives users a holistic view of project and portfolio data so that they can make proactive, informed decisions based on real time data and forecasting.

The aims were:

1. All project work was to be tracked in the tool.
2. Investigations into the suitability of this tool for a DevOps environment.
3. Availability of api's and plugins for other DevOps tools.
4. Quality of metrics, KPI's, reports and charts for all levels of personnel in a DevOps environment.
5. Cost of the service.
6. Service trust and compliance.

### Method



### Results



### Conclusions



## Lab 3 - Github

### Description/Aims

Github is an online service that allows people to publicly host and share files using the git version control system. It makes things like integration, licensing and sharing of code easy and is a "shop window" for companies and developers alike to showcase their talents.

The aims were:

1. All project files were to be hosted on an online central repository for DevOps purposes.
2. Investigations into the suitability of this service for a DevOps process.
3. Availability of integrations and plugins for other DevOps tools.
4. Security and availabilty of the service.
5. Cost of the service.

### Method



### Results



### Conclusions



## Lab 4 - Jenkins

### Description/Aims

[Jenkins is an open source automation server written in Java.][1] It is a very extendable service through the use of plugins and it's root's in open source. To integrate DevOps automation through pipelines into a company or project it has simple yet powerful capabilities.

The aims were:

1. Project pipelines to be automated through Jenkins.
2. Ease of setup, maintenance and administration.
3. Environment requirements to host Jenkins.
4. Cost of Jenkins.
5. Availability of integrations and plugins.
6. Security and failover of Jenkins.

### Method



### Results



### Conclusions



## Lab 5 - Docker

### Description/Aims

Docker is one of the better know containerization tools that allow developer's to package all required parts of an application into a single container for deployment.

The aims were:

1. Project service to be containerized using docker.
2. Benefits of using docker over convention web service hosting.
3. Ease of securing a docker container.
4. Development experience of the tool (installation, usage, debug etc).
5. Automation capabilities in relation to DevOps pipelines.
6. Cost of Docker.

### Method



### Results



### Conclusions



## References & Bibliography

[1]: https://en.wikipedia.org/wiki/Jenkins_(software)
[2]: https://git-scm.com/docs
[3]: https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History
