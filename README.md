# [Udemy] Angular 2 with TypeScript for Beginners: The Pragmatic Guide [ENG, 2016]




I'm working on Ubuntu 14.04 LTS

Prepare Environment:

    $ cd /projects/dev/
    $ mkdir angular2
    $ cd angular2

    $ docker run -i -t -p 80:3000 --name angular2 -v /$(pwd):/projects/angular2 marley/centos6-for-dev /bin/bash


To write anything from container:

    # chown -R marley /projects/dev/Angular-2-with-TypeScript-for-Beginners/

    # chmod -R 777 /projects/dev/Angular-2-with-TypeScript-for-Beginners/


I will create better container later.

[Marley](http://marley.org)
___

### 01_-_Getting_Started_with_Angular_2

03_-_Setting_Up_the_Development_Environment

    $ su - root

pass: root

    # npm install -g typescript
    # npm install -g typings


04_-_Your_First_Angular_2_App

We had copied project files to our project from archive

    $ cd /projects/angular2
    $ npm install
    $ npm start
