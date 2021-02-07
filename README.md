[![Build Status](https://drone-ci.hopto.org/api/badges/Diesel-Net/heimdall/status.svg)](https://drone-ci.hopto.org/Diesel-Net/heimdall)

# heimdall
https://heimdall.site/

## Requirements
- Ansible 2.10+

## Deploy to Docker Swarm
```bash
ansible-playbook deploy.yaml -i inventories/dev/hosts --vault-id ~/.tokens/master_id
```
