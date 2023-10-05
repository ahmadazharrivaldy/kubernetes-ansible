# kubernetes-ansible

## Install Ansible
```
sudo apt-add-repository ppa:ansible/ansible
sudo apt update && sudo apt install -y ansible
```
## How to use
Check connectivity
```
ansible -i hosts all -m ping
```
Run ansible playbook
```
ansible-playbook -i hosts install-k8s-containerd.yml
```
