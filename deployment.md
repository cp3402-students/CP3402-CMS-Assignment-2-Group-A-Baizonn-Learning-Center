# Development and Deployment Workflow

## Summary of Tools Used

* CMS - `WordPress`
* Documentation and Team Management - `Trello`, `Miro`
* Communication - `Slack`, `What'sApp`
* Local Environments & IDE - `PHP`, `Visual Studio Code`, `XAMPP`
* Version Control - `GitHub`

## CMS - WordPress

## Documentation and Team Management - Trello

Trello, a web-based list making application. We used it to keep track of tasks and the projects progress.

A new Trello account can be registered with any email. Then you can join the existing board using this
link: [https://trello.com/invite/b/668f679767732ecb39846fc4/ATTI59095d56f35e912d7102f69c276dc8802A62BE6D/cp3402-cms-assignment-2-baizonn-learning-center](https://trello.com/invite/b/668f679767732ecb39846fc4/ATTI59095d56f35e912d7102f69c276dc8802A62BE6D/cp3402-cms-assignment-2-baizonn-learning-center). All previous tasks, completed or
otherwise, will be displayed in the board. Anyone new coming to work on and continue developing the site can follow it
as a reference point.

## Documentation and Team Management - Miro

Miro, a web-based WhiteBoard application. We used it to keep track of meeting and the work progress.

A new Miro account can be registered with any email. Then you can join the existing board using this
link: [https://miro.com/app/board/uXjVKuCLVeA=/?share_link_id=123745175472](https://miro.com/app/board/uXjVKuCLVeA=/?share_link_id=123745175472). All previous records, completed or
otherwise, will be displayed in the board. 

## Communication - Slack

Slack is a fantastic tool for communication, especially within teams, and as all the team members had experience using similar application Discord
before it was picked for this project. The primary benefits it offers towards a team-orientated project such as this;

* It's simple to setup and manage
* Offers written communication for multiple users
* File and link uploads
* Offers the basic group requirement of being able to stay up-to-date with the projects development remotely
* It can be used on phones, computers, and tablets

Setup is very simple. It simply requires an email to register a new account.

## Communication - What'sApp

What'sApp is a ideal tool for group communication, and as all the team members had experience using it
before it was picked for this project. The primary benefits it offers a immediatly contaction such as this;

* It's simple to setup and manage
* Offers written communication and voice for multiple users
* File and link uploads
* Screen-sharing
* Offers the basic group requirement of being able to stay up-to-date with the projects development remotely
* It can be used on phones, computers, and tablets

What'sApp is very simple. It simply requires an email to register a new account.

## Local Environments & IDE - PHP, XAMPP, Visual Studio Code

XAMPP for all requirement as Local Host, that can install WP and XAMPP on it.
Visual Studio Code is for any changes for PHP, or CSS majorly.


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



