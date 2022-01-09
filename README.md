# Git with Ansible

Role installing and configuring git

## Optional Parameters

 * `git_user` - OS user to configure git
 * `git_user_name` - Name to display for git
 * `git_user_email` - Email to display for git

## Testing

Credit: Tested with vagrant image from [@geerlingguy's Ansible for Devops](https://github.com/geerlingguy/ansible-for-devops)

Run the following from the test directory:

### Initial Install
```
ansible-galaxy install -r requirements.yml
vagrant up
```

### Reapply provisioning
```
vagrant provision
```

