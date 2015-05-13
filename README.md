supercreate
=================

supercreate is a bash script that can be used to easily create a new project with a github repo automatically tied it. It can also be used to both automatically tie in a sandbox-level Heroku Node server and create a new Node-Express project. Obviously, its functionality can be adjusted/tailored to varying levels of rubustness based on the wishes and needs of the user.

Setup:

  - git clone https://github.com/whittlbc/supercreate.git
  - chmod +x supercreate
  - add supercreate dir to $PATH
  - cd supercreate
  - open supercreate script and change the 4 instances of my GH username to whatever yours is

Current use:

  - To create a new project and GH repo with the same name: 
  
    $ supercreate projectName 0

  - To do everything in action 0, but also create a new Node-Express project and then tie it to a new Heroku Node server

    $ supercreate projectName 1



License: MIT 
