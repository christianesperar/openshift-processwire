Processwire on OpenShift
===================

This git repository helps you get up and running quickly with a Processwire installation
on OpenShift.  The database credential will automatically use upon installation and the hook 
script will check if you already completed the installation and remove it upon building.

The simplest way to install this application is to use the [OpenShift QuickStart](https://hub.openshift.com/quickstarts/229-processwire). If you'd like to install it manually, you just need to create a php application with MySQL support by running this command

    rhc app create processwire php-5.4 mysql-5.5 --from-code=git://github.com/christianesperar/openshift-processwire.git

That's it, go to your application and configure.

## Help Wanted
Although, this is already accepted by OpenShift, it still need to test in different scenario. If you are also eager to successfully make ProcessWire fully compatible with OpenShift, please test and submit an issue or pull request if you found something that needs to change.
