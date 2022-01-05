# Ansible-galaxy

```bash

ansible-galaxy collection install rohitarora7.example

test.yaml

- hosts: localhost
  roles:
  - role: shubhamtatvamasi.example.superman
  
  
  
  
create 

ansible-galaxy collection init rohitarora7.example  
  
  
ansible-galaxy role init roles/superman 

cd meta 
runtime.yml
 
 requires_ansible: ">=2"

ansible-galaxy collection build

ansible-galaxy collection publish rohitarora7-example-1.0.0.tar.gz --token token_key

```

  
  
