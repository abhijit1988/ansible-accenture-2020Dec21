# First uninstall the existing Ansible 
```
apt-get remove ansible -y 
```

# Now Install Python Package Manager
```
apt-get install python-pip -y 
```


# Now Install ansible 2.8 via pip
```
pip install ansible==2.8
which ansible
/usr/local/bin/ansible-playbook --version
```

