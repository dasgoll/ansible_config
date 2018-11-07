### production
ansible-playbook --extra-vars "theEnvironment=production"  -i localhost, -c local deploy_config.yml


### stresstest
ansible-playbook --extra-vars "theEnvironment=stresstest"  -i localhost, -c local deploy_config.yml






#####
ansible-playbook /tmp/goll.yml -i localhost, --extra-vars  variable_one='jameel'

