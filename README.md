---
- hosts: all
  become: yes
  tasks:
  - name: ping into on nodes
    ping:


