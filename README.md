# Ansible for IBM i collections demo

This demo allows you to use the sample playbooks directly in the Ansible Tower. Please use https://github.com/airwangyun/ansible_for_i.git as SCM source when creating Ansible Tower demo project. 

Here are some descriptions:

ansible.cfg defines the configurations for Ansible running on IBM i. 

collections/requirements.yml defines the IBM i collections used in the demo playbooks. 

The playbooks in the root directory can be running directly via Ansible Tower. In the template of Ansible Tower, the playbooks can be selected from the drop down list. For example, ibmi-sql-sample.yml can be selected from the drop down list when creating a template to run sql tasks against IBM i endpoint. 

For Ansible for IBM i collections documentations, please visit: https://ibm.github.io/ansible-for-i/index.html
