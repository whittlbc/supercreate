supercreate
=================

supercreate is a bash script that can be used to easily create a new project with a github repo automatically tied it. It can also be used to both automatically tie in a sandbox-level Heroku Node server and create a new Node-Express project. Obviously, its functionality can be adjusted/tailored to varying levels of rubustness based on the wishes and needs of the user.

Setup:

  - git clone https://github.com/whittlbc/supercreate.git
  - cd supercreate
  - open supercreate script and change the 4 instances of my GH username to whatever yours is

Current use:

(0) To create a new project and GH repo with the same name: 
  
  $ bash supercreate projectName 0

(1) To do everything in (0) above, but also create a new Node-Express project and tie it to a new Heroku Node server

  $ bash supercreate projectName 1


License: MIT 
