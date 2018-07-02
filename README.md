# Confluence Add-on Using ACE (Atlassian Connect Express)

This repository contains code examples for creating simple confluence addons.

## Set up

### Register the [cloud instance](https://www.atlassian.com/ondemand/signup/form?product=confluence.ondemand,jira-software.ondemand,jira-servicedesk.ondemand,jira-core.ondemand&developer=true) and follow the steps here

   1.Setup the app descriptor(atlassian-connect.json) with necessary modules (find one from this repository)

   2.Add credentials.json file to project root with the following information

    {
    "hosts": {
        "<domain-name-of-the-cloud-instance>/wiki": {
            "username": "admin",
            "password": "**atlassian-password**"
        }
    }
}


3.`npm install`

4.`npm start`

[More Information here](https://bitbucket.org/atlassian/atlassian-connect-express/src/master/README.md#markdown-header-install-dependencies).
