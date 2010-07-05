# Ruboto Script Playground

This repository exists so that I can edit Ruboto (Ruby on Android) scripts and pull them down to my handset using script_market.

## Getting Ruboto IRB

The Ruboto IRB app can be on the android market or at: [http://github.com/ruboto/ruboto-irb](http://github.com/ruboto/ruboto-irb)

## Pointing Script Market to an existing github project

Script Market (script_market.rb) can set up a directory inside a github project as a script source. 
Here's how to point your Script Market to the demos directory in this project:

1) Run Script Market (script_market.rb) from your scripts list
2) Menu -> Add Github source
3) Enter any name for this source (e.g., Playgorund Demos)
4) Enter the project user name "rscottm"
5) Enter the project name "ruboto-script-playground"
6) Enter the project branch "master"
7) Enter the desired directory "demos"
8) Menu -> Save

If you uninstall Ruboto IRB, this information will be lost.

## Creating your own script project

If you'd like to create you own github script source for script_market.rb, follow these instructions:

1) Create a new github project under your github account
2) Follow the github directions for setting up the project when you create
3) Create a directory for your scripts
4) You will need to create an empty version of each script on your local repository and push it to gitub
5) Push everything to github
6) Follow the directions above to set up this source in Script Market
7) After the script is initially created on your local clone, you will be able to make changes on github