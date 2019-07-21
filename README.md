# TICK Stack Example Setup

Basic setup using `docker-compose` to setup containers for InfluxDB, Chronograf and Kapacitor. Then an example config for running telegraf on the host and sending the data to the InfluxDB container.

**Notes**

- No passwords are used
- Ports are restricted to localhost 127.0.0.1
- All data is mounted from `./data/<service>` except RO configs
