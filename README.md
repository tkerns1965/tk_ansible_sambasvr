# tk_ansible_sambasvr

For use on bare Ubuntu 18.04.2 Live Server

1. sudo apt install -y ansible
2. git clone https://github.com/tkerns1965/tk_ansible_sambasvr.git
3. cd tk_ansible_sambasvr/
4. cp roles/samba/vars/private.yml.sample roles/samba/vars/private.yml
5. nano roles/samba/vars/private.yml
6. ansible-playbook -K samba.yml
