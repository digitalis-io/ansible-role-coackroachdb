Role Name
=========

This role is a companion for the blog post https://medium.com/@serg-digitalis/cockroachdb-a-devops-story-a8b5389213da

Requirements
------------

Install dependencies first with 

```sh
ansible-galaxy install -r requirements.yml
```


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: all
  name: install cockroachdb
  become: true
  gather_facts: true
  any_errors_fatal: true

  roles:
    - name: ar-cockroachdb
```

License
-------

Apache

Author Information
------------------

https://digitalis.io
