### Setupmac

[Ansible](https://www.ansible.com/) playbook to quickly setup 
a Mac.

To setup run the following command :
```
curl -s https://raw.githubusercontent.com/arjunurs/setupmac/master/start.sh | /bin/bash
```

If you already have ansible installed or prefer running it directly, execute the following :
```
ansible-playbook -i ./hosts playbook.yml --verbose
```

#### Uninstall

If you want to undo all the changes that `setupmac` did, run 

```
start.sh uninstall
```
