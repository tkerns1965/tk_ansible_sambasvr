# tk_ansible_sambasvr

For use on bare Ubuntu 18.04.2 Live Server

1. sudo apt install -y ansible
2. git clone https://github.com/tkerns1965/tk_ansible_sambasvr.git
3. cd tk_ansible_sambasvr/
4. cp .vault_pass.sample .vault_pass
5. nano .vault_pass
6. ansible-playbook -K samba.yml
