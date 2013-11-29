This is a repository of ansible playbooks for hosts on WUVT's network.

To execute a playbook on all machines, run 
"ansible-playbook all main.yml -i hosts.cfg -K"
For more info, man ansible-playbook or see http://ansible.cc

Note that RHEL systems prior to RHEL6 require bootstrapping, as they come with 
python <= 2.4, which lacks python-simplejson. The bootstrap.sh script will run 
this on all machines in the "rhel5" category.
