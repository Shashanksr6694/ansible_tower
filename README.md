# ansible_tower
Ansible Tower : Configured Tower-cli and created an RBAC structure in Tower by creating organization, teams, users and assigned roles &amp; permissions via the CLI commands. Created provisioning callback template for an instance to configure itself on AWS. Created a workflow template to chain instance provisioning, web app. deployment inventory update/sync, provisioning callback &amp; server configuration tasks together. Created surveys to populate extra variables in playbooks to allow validation for user input.                 Ansible Tower 3.2 features: Isolated node installation, Importing inventory directly from GIT, Smart inventory using built-in fact cache &amp; Diff mode. Ansible Tower Authentication: Integrated an openLDAP server with Tower, Integrated Tower with oneLogin for SAML authentication, Set up Google OAuth &amp; Set up GitHub OAuth.               Notification template: Created a slack notification and associate with job template and run job. Job template: Set up a job template and run a job using inventories, projects &amp; credentials. Inventories: Importing static inventory with tower-manage &amp; Importing AWS inventory. Credentials: Created SCM credential for GitHub, Created cloud credential for AWS. Created machine credentials to connect to AWS machines/instances. Projects: Set up a manual project &amp; Sync from GitHub.              Installations: Standalone with internal database &amp; Standalone with external database. Back-up and restore: Back up Tower machine and then restore to a separate instance. Upgrade: Install 2.4.5 and upgrade to latest from 2.4.5 to 3.0.0 to 3.1.5 to 3.2.1. Clustered installation with external database.
