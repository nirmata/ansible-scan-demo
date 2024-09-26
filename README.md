# ansible-scan-demo
This repository is to demonstrate Nirmata's capability in scanning Ansible playbooks to prevent misconfigurations.

## Generating the JSON file
To see the implications of the configurations without applying any changes to your environment, use the `--check` flag.

```bash
export ANSIBLE_STDOUT_CALLBACK=json
```

```bash
ansible-playbook playbooks/good_vm_setup.yaml --check > good_vm_setup.json
```
