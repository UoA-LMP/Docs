<h1 align='center'><img src="pantsss.png" width="130px"/><br/> Media Production</h1>

  
[About](#about)  
[Dev stack](#dev-stack)  
[Why the pants?](#why-the-pants)  

Technical documentation can be found in the [UAMediaProd Docs Wiki](https://github.com/UAMediaProd/Docs/wiki). Go there to learn more about our processes, plans, and technical guides.
  
## About
The Media Production team at The University of Adelaide is located within the Online Programs Team (OPT) and acts as a central service inside the University. As the team has evolved from AdelaideX to Online Programs, so too has the desire to formalise an Open Source environment to work from and allow for future growth into adopting a [Serverless](https://serverless.css-tricks.com/) philosophy to allow design and development teams to focus on making content and using tools with GitHub. 

Official documentation is found on [our Confluence Instance](https://adelaide.atlassian.net/wiki/spaces/LMP/overview) within the walls of The University of Adelaide. (Internal only; SSO access required)

## Dev stack
<br/>
<p align='center'><img src="devstack.svg"/><br/></p>

GitHub will be the heart of our development toolset for new creations from hereon out. The main benefit this gives us is being able to use [GitHub Pages](https://pages.github.com/) in our DevOps for hosting rather than our previous closed-source approach to our own servers for front-end content. Using GitHub allows us to integrate with other services like [Glitch](https://glitch.com/) for Node.js server-side code for applications inside the Media team and our central [Media Hub project](https://github.com/UAMediaProd/Media-Hub).

We still plan on supporting our GitLab instance for the time being until we migrate our previous projects to GitHub as we work on them. However, the existing files on our [SQL, Web and Python servers](https://lti-adx.adelaide.edu.au/course-units/all/) will remain as we are currently unsure how far they have been re-used within the University and will maintain those servers for the legacy projects for MyUni projects *only* and for applications requiring Python and SQL databases.

### Migration plan
The migration from GitLab → GitHub is planned to be an ongoing task for when our workload is light, or as a timely piece of MOOC refresh processes. The majority of our interactives are used inside [MOOCs on EdX](https://www.edx.org/school/adelaidex) and are safe to update as we go along, especially if we keep our current `LTI-ADX` legacy support ongoing.

### A note on GitLab
Future plans are to investigate the ownership of our current `BATS` and `WILD` servers and to include a Node.js installation there and only require our server for server-only tasks so we're Serverless-ish at the bare minimum.

## Why the pants?
Tan pants
