# tk_vncsvr_ansible

For use on bare Ubuntu 18.04.1 Live Server

 1. sudo add-apt-repository universe
 2. sudo apt install -y ansible
 3. git clone https://github.com/tkerns1965/tk_vncsvr_ansible.git
 4. cd tk_vncsvr_ansible/
 5. ansible-playbook -i hosts.ini -K vncsvr.yml 
