The Elastic Stack - ELK
=========
Requirements
------------
	Oracle Java JDK 1.8
	Ansible 2.0
	
Role Variables
--------------
```
elasticsearch_version: "6.x" # tested on 5.x and 6.x
elasticsearch_host: <ip>
elasticsearch_port: <port> # default 9200
kibana_port: <port> # default 5601
```

Example Playbook
----------------
Test playbook:
```
---
- hosts: Test
    remote_user: root
    roles:
    - role: ./tradecore-elk
```

License
-------
BSD

Author Information
------------------
@vidojeg
