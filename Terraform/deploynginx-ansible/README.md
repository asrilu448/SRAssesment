# ansible-roles
#1.wget the ec2.py and ec2.ini 
#2.configure host file with the tags you have used  during AWS terraform creation .
#3.run following command 
ansible-playbook site.yaml -i /etc/ansible/ec2-py -u  ec2-user
