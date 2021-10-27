List playbook tasks

    ansible-playbook -i inventory -K playbook1.yml --list-tasks

Run all tasks in a playbook

    ansible-playbook -i inventory -K playbook1.yml

Run tagged tasks in a playbook

    ansible-playbook -i inventory-K playbook1.yml -t <tag>
