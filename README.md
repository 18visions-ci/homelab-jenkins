# homelab-jenkins

Ansible playbooks to deploy a Jenkins Controller on a Proxmox VM.

## Roles

- **common**: Installs dependencies.
- **jenkins**: Installs and configures Jenkins.
- **firewall**: Opens port 8080 for Jenkins.
- **postinstall**: Displays the initial Jenkins admin password.

## Usage

Run the playbook with:

```sh
ansible-playbook -i <inventory_file> [main.yaml](http://_vscodecontentref_/1)
