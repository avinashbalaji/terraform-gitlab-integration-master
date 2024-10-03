# Terraform GitLab Integration


## Known errors
```
$ ansible-playbook -i hosts install-apache.yml
[WARNING]: Ansible is being run in a world writable directory
(/builds/[MASKED]/terraform-gitlab), ignoring it as an ansible.cfg
```
For this error, use `export ANSIBLE_CONFIG=./ansible.cfg` before running the job#
#very useful code
