# Consul Cluster Setup Using Ansible

## Requirements
* vagrant

## TO RUN
* **STEP-1**
```
vagrant up
```

* **STEP-2**
```
vagrant ssh controller
```

* **STEP-3**
```
cd /home/vagrant/projects/playbooks
```

* **STEP-4**
```
ansible-playbook -i hosts/cluster-hosts.ini cluster-setup.yml
```
# Supported/Tested OS
* CentOS/7
