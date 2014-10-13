vagrant-apache
==============

Vagrantfile for basic apache server setup

* Instructions

Copy the Vagrantfile to the base of your html project 
(The actual site is properly in a subfolder, like "html", right?)

Update the parameters in Vagrantfile to your preferences/needs.

Then open a terminal at the root and run:
~~~
vagrant up
~~~

Once the vm is setup, then run the following to trigger auto-rsync of your
project to the server:
~~~
vagrant rsync-auto
~~~
