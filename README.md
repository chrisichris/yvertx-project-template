yvertx-project-template
======

This is a project template for [yvertx](https://github.com/chrisichris/yvertx 
the [yeti](http://mth.github.com/yeti/) language support for 
[vert.x](https://github.com/vert-x/vert.x).

The template is based on vert.x 2.0 and yeti 0.9.7. 

Note that the template is still in development. Please help and report  
issues to the 
[vert.x-googlegroup](https://groups.google.com/forum/?fromgroups#!forum/vertx)

Installation
===========

Your need Java7 jdk installed.

Git-clone this template to your project directory and update 
the `project.yeti` file, to include the groupId arftifactId and version of your
project.

There is no other installation required. Also not of vert.x or yeti both
will be downloaded by the project (and for the project only)

Usage
=====

Start coding your verticle in `mods/main~main~1/main.yeti`. For a manual look at
[yvertx-core-manual](https://github.com/chrisichris/yvertx/blob/master/core_manual_yeti.md).

run your veritcle with

    >java -jar ybuilder.jar vertx:main


You can also run a repl inside a verticle:

    >java -jar ybuilder.jar vertx:repl

You can run any of the vert.x commands with:

    >java -jar ybuilder.jar vertx:cmd

ie to run a verticle

    >java -jar ybuilder.jar vertx:cmd run verticle.name

To see all the vertx related commands use

    >java -jar ybuilder.jar vertx:


