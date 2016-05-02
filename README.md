# [Deborah Kurata, Pluralsight.com ] Angular 2: Getting Started [ENG, 2016]

Original SRC:  
https://github.com/DeborahK/Angular2-GettingStarted


### Prepare Environment for Development

I will work on Ubuntu 14.04

**Docker, Atom should be installed**

    $ mkdir -p /projects/dev/
    $ cd /projects/dev/

    $ git clone https://github.com/marley-angularjs/Angular-2-Getting-Started
    $ cd Angular-2-Getting-Started/

    $ docker pull marley/centos6-for-dev
    $ docker run -i -t -p 80:3000 --name angular2 -v /$(pwd):/projects/angular2 marley/centos6-for-dev /bin/bash


<br/>

    Host machine:

    $ chown -R marley /projects/dev/Angular-2-Getting-Started/
    $ chmod -R 777 /projects/dev/Angular-2-Getting-Started/

<br/>

    $ cd /projects/dev/Angular-2-Getting-Started/
    $ atom .
