### production
ansible-playbook --extra-vars "theEnvironment=production" deploy_config.yml -i localhost, -c local deploy_config.yml


### stresstest
ansible-playbook --extra-vars "theEnvironment=stresstest" deploy_config.yml -i localhost, -c local deploy_config.yml