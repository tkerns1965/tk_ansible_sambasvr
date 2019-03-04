# tk_ansible_sambasvr

For use on bare Ubuntu 18.04.2 Live Server

1. sudo apt-add-repository -y ppa:ansible/ansible
2. sudo apt install -y ansible
3. git clone https://github.com/tkerns1965/tk_ansible_sambasvr.git
4. cd tk_ansible_sambasvr/
5. cp roles/samba/vars/private.yml.sample roles/samba/vars/private.yml
6. nano roles/samba/vars/private.yml
7. ansible-playbook -K samba.yml
