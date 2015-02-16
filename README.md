playbooks-init
======================================================================

This is a simple playbook to play with Ansible.

Synopsis
----------------------------------------------------------------------

Set up `directory you will write playbooks` based on `defined playbooks pattern`.



How to use
----------------------------------------------------------------------

### set directory to setup and pattern via prompt

```shell-session
$ ansible-playbook -i localhost, path/to/playbooks-init/playbooks-init.yml
```

### set directory and pattern via cli (--extra-vars)

```shell-session
$ ansible-playbook -i localhost, path/to/playbooks-init/playbooks-init.yml --extra-vars="dir=`path/to/dir` pattern_name=`pattern_name`"
```



Add patterns and use it
----------------------------------------------------------------------

1. Add new roles to work as role on ansible to `roles` directory.
2. Specify new role's name via prompt or args of `--extra-vars` with cli.

