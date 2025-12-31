## update your inventory 
change the host in `./iventory.ini` to your (mine is testovaci-klobasa in group with the same name)  
and set the username you want to use `ansible_user=<username>`(mine is `tv`)

## and run it like this
```bash
ansible-playbook -i inventory.ini deploy-kiosk.yaml --ask-become-pass
```
