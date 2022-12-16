About

Inventory and Ping Module.

inventory file and ping command using ansible, inventory consists config, ping is ssh'ed.

1. ansible -i inventory -m ping web01
2. ansible -i inventory -m ping web02
3. ansible -i inventory -m ping db01
4. ansible -i inventory -m ping websrvgrp
