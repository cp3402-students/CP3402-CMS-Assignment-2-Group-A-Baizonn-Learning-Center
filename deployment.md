# Development and Deployment Workflow

## Summary of Tools Used

* CMS - `WordPress`
* Documentation and Team Management - `Trello`, `Miro`
* Communication - `Slack`, `What'sApp`
* Local Environments & IDE - `PHP`, `WordPress`, `Visual Studio Code`
* Version Control - `GitHub`

## CMS - WordPress

## Documentation and Team Management - Trello

Trello, a web-based list making application. We used it to keep track of tasks and the projects progress.

A new Trello account can be registered with any email. Then you can join the existing board using this
link: [https://trello.com/b/KYotjzhS/workflow](https://trello.com/b/KYotjzhS/workflow). All previous tasks, completed or
otherwise, will be displayed in the board. Anyone new coming to work on and continue developing the site can follow it
as a reference point.

## Communication - Discord

Discord is a fantastic tool for communication, especially within teams, and as all the team members had experience using
it before it was picked for this project. The primary benefits it offers towards a team-orientated project such as this;

* It's simple to setup and manage
* Offers both written and voice communication for multiple users
* Screen-sharing
* File and link uploads
* Offers the basic group requirement of being able to stay up-to-date with the projects development remotely
* It can be used on phones, computers, and tablets

Setup is very simple. It simply requires an email to register a new account.

Some discord servers employ a phone verification security system to be able to join, however this will not be necessary
for this project.

## Local Environments & IDE - Docker, PHP Storm
Docker is a widely used virtualization software/platform. The team used a Docker container to house and run applications 
for the projects development.

Before work began on the theme it was decided that PHP Storm would be used. It was not a difficult decision given its 
popularity, syntax highlighting features, integration, intuitive and friendly UI, and so on.

## Version Control - GitHub

Version control was done through GitHub. Multiple branches were used, primarily Main, Staging, and Development.

The workflow for a member to commit a change to the project, would go as follows; Create a new branch, commit changes to
it and then merge it with the development branch. Before the merge would be accepted it would need to be reviewed by
other members in the pull request.

### Set up for version control with local environment
1. Set up GitHub Repository
2. Connect Repo on Local Git location
3. Set up XAMPP with WordPress in PHP Admin on the local repository


### Hosting 
We figure out working on online hosting services helps us better work on the same time and anywhere without technical issue in some member's device.
Therefore we start an instance on AWS LightSail
1. Create AWS LightSail Instance
2. Set up Location Singapore
3. Select Word Press as platform
4. Pick 2GB RAM program
5. Finish setting then activate Static IP for member to join WP editing
6. Go console and type `cat bitnami_application_password`
7. Then Run the istance to start work



