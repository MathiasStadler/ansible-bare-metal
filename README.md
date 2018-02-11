# ansible-bare-metal

## hello world playbook.yml

```yml
---
- name: This is a hello-world example
  hosts: ansibleclient01.local
  tasks:
  - name: Create a file called '/tmp/testfile.txt' with the content 'hello world'.
    copy: content="hello world\n" dest=/tmp/testfile.txt
```

## bare metal orange pi zero with ARMBIAN images ARMBIAN images

# TODO 
# https://ansible-tips-and-tricks.readthedocs.io/en/latest/ansible/commands/