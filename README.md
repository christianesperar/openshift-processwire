Processwire on OpenShift
===================

This git repository helps you get up and running quickly with a Processwire installation
on OpenShift.  The database credential will automatically use upon installation and the hook 
script will check if you already completed the installation and remove it upon building.

Running on OpenShift
----------------------------

Create an account at https://www.openshift.com

Create a php application with MySQL support

    rhc app create processwire php-5.4 mysql-5.5 --from-code=git://github.com/christianesperar/openshift-processwire.git

That's it, go to your application and configure.
