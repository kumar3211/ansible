---
- hosts: all
  become: yes
  tasks:
  - name: install git on all nodes
   apt:
    name: git
    stage: present

