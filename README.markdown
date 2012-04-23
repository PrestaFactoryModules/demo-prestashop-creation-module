## A pre-release architecture to create new Prestashop's Modules</center>
#### Integration of Jenkins

<u>sprint 1 :</u>
Jenkins is used to manage 'continuous integration'.
We're planning some configurations into build ant file and some with Jenkins config.
But which one !?

#### first test

problem with user : add user 'jenkins' to 'my group' ... not a 

problem to access github repository :
[Integration Of Jenkins](https://github.com/PrestaFactoryModules/demo-prestashop-creation-module/tree/IntegrationOfJenkins) via jenkins running !

Still have a problem with ssh key when connect to github ... even after add ssh key into profile config from jenkins !
=> running test localy (normal way ) and ADD process of versioning's management into build task (ant process).

[build.xml file](https://github.com/PrestaFactoryModules/demo-prestashop-creation-module/blob/IntegrationOfJenkins/build.xml)


#### install some Jenkins Extension
build job to remote github with github extension ... but cause always news problems !!! :( 

But <u style="color:rgb(240,50,50);">WE Should Start from Sratch</u>

### Running jenkins.war with winstone-hudson.jar
When your're running Jenkins for the very first time, it initialize some values by default.
But they could be change thanks your 'bash terminal' or a file !

I've tried to run Jenkins by using .deb packages and 'apt-get'.
[an upgrade from hudson in fact](https://wiki.jenkins-ci.org/display/JENKINS/Upgrading+from+Hudson+to+Jenkins) but didn't like the default '/var/lib/' path to install Jenkins and workspace ... and other kind of stuff!

Never Mind ... it became quickly hard to manage permission user, shadows, etc instead of running my jobs, and github repositories collaboration.

#### a step by step process to run Jenkins friendly

