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


### install some Jenkins Extension
build job to remote github with github extension 


