About

AdHoc commands

1. ansible -i inventory -m yum -a "name=httpd state=present" web01 --become
	installed httpd service in EC2 instance.
2. ansible -i inventory -m service -a "name=httpd state=started enabled=yes" web01 --become
	starting the httpd servie in EC2 instance.
3. ansible -i inventory -m copy -a "src=index.html dest=/var/www/html/index.html" web01 --become
	copying a file to index.html of EC2 instance web01 from local instance Ansible Control Machine
