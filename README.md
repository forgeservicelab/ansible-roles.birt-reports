birt-reports
=========

An Ansible role for retrieving BIRT report design files from the git repository and storing report designs to the target machine running birt-viewer web app.

The birt-viewer web-app can be installed by using birt-viewer role.

Requirements
------------

You must have following files in the master playbook files/ folder.

	- git_access_key  - the deployment key for accessing git repo
	- auth_key.pub - the authorized key for the birt user access
	- auth_jenkins.pub - another authorized key for e.g. jenkins access
	
	



