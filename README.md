# [Deborah Kurata, Pluralsight.com ] Angular 2: Getting Started [ENG, 2016]

Original SRC:  
https://github.com/DeborahK/Angular2-GettingStarted


Application:

![Application](/img/pic1.png?raw=true)

![Application](/img/pic2.png?raw=true)

![Application](/img/pic3.png?raw=true)

![Application](/img/pic4.png?raw=true)


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


<br/>

### Setting up an Angular 2 Application

![Application](/img/pic5.png?raw=true)

Source codes from Original Project

    $ npm install
    $ npm start

![Application](/img/pic6.png?raw=true)

<br/>

### 04. Introduction to Components

![Application](/img/pic7.png?raw=true)


![Application](/img/pic8.png?raw=true)


<br/>

Creating the App Component


![Application](/img/pic9.png?raw=true)

![Application](/img/pic10.png?raw=true)

![Application](/img/pic11.png?raw=true)

<br/>

### 05. Templates, Interpolation, and Directives

05_04-Using a Component as a Directive

![Application](/img/pic12.png?raw=true)

![Application](/img/pic13.png?raw=true)

![Application](/img/pic14.png?raw=true)

![Application](/img/pic15.png?raw=true)
