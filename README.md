Role Name
=========

Playbook installing 3 nodes cluster of kafka and zookeeper.

Software version:

OS: ```Ubuntu 22.04.3```

Kafka: ```2.13-3.6.1```

ZooKeeper: ```3.9.1```

JRE: ```11```

Web UI for cluster management available on ```node01``` port ```8085```

Example Playbook
----------------

```ansible-playbook -i /root/ansible-kafka-zk/hosts /root/ansible-kafka-zk/install.yml -bkK -u nurlan```