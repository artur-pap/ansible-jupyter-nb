# Usage

Check the performed changes:

    ansible-playbook --check --diff -i {your-inventory-file} {your-playbook}.yml

Apply the performed changes:

    ansible-playbook -i {your-inventory-file} {your-playbook}.yml
