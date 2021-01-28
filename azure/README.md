# Azure Webserver Policies

The policies in this folder govern creation and lifecycle of web servers on Microsoft Azure.

## Policies

* **enforce-ssh**:  This policy verfies that Linux virtual machines have a public SSH key assigned for the admin user and that password based SSH authetication is disabled.  This policy is a hard mandatory.
* **enforce-module-vm**: This policy verifies that all virtual machines are created with the *webserver-azure* module located in the csmith organization private module registry.  This policy is a soft mandatory. 
* **check-api**: This policy checks an api and validates returned data.  In this test case, the returned data will be "yes" or "no".  This policy is advisory.
