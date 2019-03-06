# tk_ansible_sambasvr

For use on bare Ubuntu 18.04.2 Live Server

1. sudo apt-add-repository -y ppa:ansible/ansible
2. sudo apt install -y ansible python-pexpect
3. git clone https://github.com/tkerns1965/tk_ansible_sambasvr.git
4. cd tk_ansible_sambasvr/
5. cp roles/samba01/vars/private.yml.sample roles/samba01/vars/private.yml
6. nano roles/samba01/vars/private.yml
7. cp roles/samba02/vars/private.yml.sample roles/samba02/vars/private.yml
8. nano roles/samba02/vars/private.yml
9. ansible-playbook -K samba01.yml
10. ansible-playbook -K samba02.yml
