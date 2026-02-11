# Ansible Assignment 1-3

## Description
1. This playbook configures hostnames and interface descriptions on two routers using Ansible.
2. This playbook configures three loopback interfaces on each router and enables EIGRP routing.
3. This playbook configures NTP, logging, timezone settings, and conditional banners based on router role.

## How to Run
```
ansible-playbook -i inventory.ini assignment1.yaml
```
```
ansible-playbook -i inventory.ini assignment2.yaml
```
```
ansible-playbook -i inventory.ini assignment3.yaml
```

## Screenshot
See screenshots/execution.png
