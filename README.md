# ansible-books
My Ansible books for some common installation. Normal installation steps included

### How to use:
1. Install ansible
* `$ sudo apt update`
* `$ sudo apt install software-properties-common`
* `$ sudo add-apt-repository --yes --update ppa:ansible/ansible`
* `$ sudo apt install ansible`
1. Put address of host in host file
2. Edit param `ansible_user` and `ansible_ssh_pass` if necessary
3. Uncomment the roles which should be run in `installer-playbook.yml`
4. Run ansible playbook and provide password if necessary
    `ansible-playbook installer-playbook.yml -i hosts --ask-become-pass`

