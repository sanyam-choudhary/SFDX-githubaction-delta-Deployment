# Salesforce DX Project: Next Steps

Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.

## How Do You Plan to Deploy Your Changes?

Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

## Configure Your Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)

## Control+shift+P on keyboard to create a project with manifest with Standard Salesforce template

## create .github/workflows folders
## create feature.yml,master.yml,QA.yml,tag.yml

## created tags and pushed to github

## git tag prod-start 
## git tag qa-start
## git tag sit-start
## git tag uat-start 

## git push -- tags

## to install nvm and node with the latest version
## create environment variable in github>>settings>>New Environment>>QA>>SF_QA_ORG__AUTH_URL>>SF_NO_DESTRUCTIVE

## install sfdx cli on system so that we can get auth url 
## SF_QA_ORG__AUTH_URL
## sfdx auth:device:login -a <ORG ALIAS> -r <ORG URL>
## sfdx force:org:display --verbose -u <ORG ACTIVE USERNAME WITH SYSTEMADMIN PROFILE>

## https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_install_cli.htm#sfdx_setup_install_cli_linux
## sfdx --version  (to check cli version)
## create the username,password and org url handy to run the below commands in terminal 
## sfdx auth:device:login -a QA -r https://wiprolimited-b6-dev-ed.my.salesforce.com
## sudo npm install sfdx-cli --global
## sudo npm install @salesforce/cli --global
## sudo npm install -g n
## curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
## nvm install node

## removed name line from sfdx-project.json (getting error unexpected JSON) 
## restarted the VS Code
## The auth error was due to space in the command
## to mention the workflow in the .forceignore 
## destrutive and pacakge in .gitignore
## to instal the delta plugin 