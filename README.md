##  Continuous Integration with Jenkins, Ansible, Artifactory, Sonarqube and PHP
Ansible Playbook to automate the deployment of a web solution. Covering the usage of static assignments(import) and dynamic assignments(include) to automate the process of configuring multiple target servers. Check [ci-jaasp](https://github.com/brpo01/ci-jassp-14/blob/master/ci-jaasp.md) for project documentation. You can find the project implementation at [ansible-config-mgt](https://github.com/brpo01/ansible-config-mgt) & [php-todo](https://github.com/brpo01/php-todo)


## Intro
The following project demonstrates the setup of continuous integration for a PHP-based application.

## TOOLS USED
|TOOL            |DESCRIPTION                                                                                                                                  |
|----------------|---------------------------------------------------------------------------------------------------------------------------------------------|
|Jenkins         |A Continuous Integration automation server tool. it was used to configure multibranch pipelines, build, test and deploy the application           |
|Ansible         |A configuration management tool. Applied in the automation of the server configurations.                                                     |
|Artifactory     |Binaries and artifacts repository management tool. Packaged artifacts were uploaded to its repository                                                   |
|Sonarqube       |A Continuous inspection tool for perform code quality analyisis. Automatic reviews are also done on static code analysis, code smells.       |
|PHP             |Scripting language for the application                                                                                                       |

