# MQTT Klient vir die Axpert en Pylontech battery

Hierdie is 'n klient wat luister na die MQTT leerbediener vir die Axpert data en Pylontech data.  Dit skryf die data in leers sodat dit geplot kan word of na 'n webbladsy gestuur kan word.



## Installeer die Mosquitto leerbediener

Installeer die leerbediener (broker) vir die Mosquitto MQTT stelsel:

```bash
sudo apt update
sudo apt-get install mosquitto mosquitto-clients
```

Aktiveer die leerbediener:

```bash
sudo service mosquitto start
```

