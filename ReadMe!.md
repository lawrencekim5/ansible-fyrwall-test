1. [About this Repository](#1)
2. [elpful commands](#2)

## About this Repository <a name="1"></a>
Ansible is a really great tool for automation. I'm working on develping an Ansible playbook that will automate the installation and cutomization of firewalld across multiple machines. I am still in the process of learning Ansible so this repository won't be too advanced, but I hope that it can serve as an easy-to-follow example for other beginners interested in elarning how to use this amazing software.

## Helpfull commands <a name="2"</a>
List playbook tasks

    ansible-playbook -i inventory -K playbook1.yml --list-tasks

Run all tasks in a playbook

    ansible-playbook -i inventory -K playbook1.yml

Run tagged tasks in a playbook

    ansible-playbook -i inventory-K playbook1.yml -t <tag>
