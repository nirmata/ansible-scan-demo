# ansible-scan-demo
This repository is to demonstrate Nirmata's capability in scanning Ansible playbooks to prevent misconfigurations.

## Generating the JSON file
To see the implications of the configurations without applying any changes to your KVM environment, use the `--check` flag.

```
ansible-playbook kvm_vm_setup.yml --check --json
```
