Role Name
=========

Playbook installing 3 nodes cluster of kafka and zookeeper.

Software version:

```
ansible [core 2.16.2]
  config file = None
  configured module search path = ['/root/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/local/lib/python3.10/dist-packages/ansible
  ansible collection location = /root/.ansible/collections:/usr/share/ansible/collections
  executable location = /usr/local/bin/ansible
  python version = 3.10.12 (main, Nov 20 2023, 15:14:05) [GCC 11.4.0] (/usr/bin/python3)
  jinja version = 3.1.3
```

OS: ```Ubuntu 22.04.3```

Kafka: ```2.13-3.6.1```

ZooKeeper: ```3.9.1```

JRE: ```11```

Web UI for cluster management available on ```node01``` port ```8085```

Example Playbook
----------------

```ansible-playbook -i /root/ansible-kafka-zk/hosts /root/ansible-kafka-zk/install.yml -bkK -u nurlan```