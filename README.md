birt-reports
=========

An Ansible role for retrieving BIRT report design files from the git repository and storing report designs to the target machine running birt-viewer web app.

The birt-viewer web-app can be installed by using birt-viewer role.

Requirements
------------

You must have following files in the master playbook files/ folder.

	- git_access_key  - the deployment key for accessing git repo
	- birt.pub - the public key you want to have for birt user as auth key
	- jenkins.pub - the public key you want to add for jenkins access
	
	



