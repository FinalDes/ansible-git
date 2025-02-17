Git
=========

Install git using official packages


## Requirements
add this into requirements.yml
```yaml
---
roles:
  - name: finaldes.git
    version: main
    src: https://github.com/FinalDes/ansible-git.git
    scm: git
```
or
```yaml
---
roles:
  - name: finaldes.git
    version: main
    src: git@github.com:FinalDes/ansible-git.git
    scm: git
```
then run ` ansible-galaxy install -r requirements.yml `


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: finaldes.git

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
