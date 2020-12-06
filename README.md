# Ansible 1password Role

An Ansible role to create a Vault on 1Password, store a secure note there and share it with another user in the account.

You'll need an account with 1password at https://1password.com/

To configure the playbook:

* clone the repository locally
* Update the variables defined in playbook.yml to suit your 1password account
* Change `OP_SESSION_yourdomain` in roles/op/tasks/main.yml to match your account name

To run the playbook:

> ansible-playbook playbook.yml