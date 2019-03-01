# tk_ansible_sambasvr

For use on bare Ubuntu 18.04.2 Live Server

1. sudo add-apt-repository universe
2. sudo apt install -y ansible python-pexpect
3. git clone https://github.com/tkerns1965/tk_ansible_sambasvr.git
4. cd tk_ansible_sambasvr/
5. cp .vault_pass.sample .vault_pass
6. nano .vault_pass
7. ansible-playbook -K samba.yml
