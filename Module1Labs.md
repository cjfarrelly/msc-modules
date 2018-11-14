# Module 1 Labs

## Introduction

As part of my submission I will add a cover page, but not on a public repo.

## Lab 1 - Git

### Description/Aims

Git is a distributed version control system widely used by the software community to collaborate easily on files. Git is essentially a miniature filesystem that uses snapshots; also known as commit points to keep a history of change. Git is distributed meaning that users can share their files easily with each other.

The aims were:

1. Ease of install of the tool.
2. Integration with other DevOps tools.
3. Ability to track and undo file changes.
4. Readability of file history.

### Method

The 64-bit version of Git for Windows was downloaded and the install instructions were followed. The GNU General Public License was acknowledged. Visual Studio Code was selected as the default editor to be used by Git. Windows Command Prompt was chosen to use Git from the command line, this option modifies the PATH variable of the Windows Operating System. The default OpenSSL library was chosen for Git to use over HTTPS connections. The default Checkout Windows-style, commit Unix-stlye line endings was chosen for how Git will treat line endings in text files. The default Use MinTTY was chosen as the terminal emulator that Git Bash will use. The default file system caching and Git Credential Manager features were left enabled with symbolic links left disabled. Experimental features were left enabled by default, these were built-in rebase and built-in stash. Git was installed and the Release Notes were viewed.

A repository was created. A sample text file was placed at the base of the newly created repository. The Git status command was ran to confirm the new file's existence. The file was added to the git staging area. The changes were committed. Further changes were made to the document. The Git log command was used to show a complete history of changes. Git reset was used to revert changes back to a previous commit point.

### Results

Git was installed successfully on the Windows Operating System. The Git Bash application was available from the applications menu on the Windows Operating System. The PATH variable update was confirmed by opening a Windows Command Prompt, typing 'set' and pressing the enter key, it was noted that the Git cmd folder was part of the PATH. A Windows Command Prompt was opened and the Git install was verified by typing git and pressing the enter key, help was displayed for common Git commands. The Git install was further tested by typing 'git --version' into the Windows Command Prompt and pressing the enter key this displayed the currently installed version.

### Conclusions



## Lab 2 - Jira

### Description/Aims

Jira is a project management system used primarily for the oversight of software projects. It gives users a wholistic view of project and portfolio data so that they can make proactive, informed decisions based on real time data and forecasting.

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