# Introduce new service to internal projcet to:
* Configure rsyslog:
    - Configure an Rsyslog server to collect logs from multiple client systems.
    - Set up filtering to separate logs by service (e.g., nginx, ssh).
    - Forward critical logs to an external monitoring system.
* Configure Kafka:
    - Set up a Kafka cluster with at least one broker.
    - Create a producer to send weather updates (e.g., temperature, humidity) to a topic.
    - Develop a consumer to read and display the updates in real time.
    - Use a Python Kafka library (e.g., kafka-python).

* Configure logstash
* Configure index template, index aliases, ilm policy, inventories, users, roles 
* Run required ansible playbooks for ex: roles, users, index aliases, index templates, ilm policies
* Create ansible playbooks for managing rsyslog, logstash creation and destruction
* Test logs pipeline from rsyslog -> kafka topic -> logstash -> elastic index
