# kubernetes-ansible

## Install Ansible
```
sudo apt-add-repository ppa:ansible/ansible
sudo apt update && sudo apt install -y ansible
```
## How to use
Check connectivity
```
ANSIBLE_HOST_KEY_CHECKING=False ansible -i hosts all -m ping
```
Run ansible playbook
```
ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook -i hosts install-kube-containerd.yaml 
```
