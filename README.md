# Monitoring with Prometheus and Grafana
Monitoring Linux Server with Prometheus and Grafana. Node and Blackbox exporter. Alert Manager.

<p align="center">
<img alt="Prometheus" width="270px" src="https://raw.githubusercontent.com/devicons/devicon/develop/icons/prometheus/prometheus-original.svg " style="padding-right:10px ;"/> &nbsp
<img alt="Grafana" width="270px" src="https://raw.githubusercontent.com/devicons/devicon/develop/icons/grafana/grafana-original.svg" style="padding-right:10px;" />
</p>
</br>

# Introduction:
Prometheus is a open-source platform for monitoring hardware and services. It collects metrics from the system of any other services that we configured.
# Prereusites
- Linux machine
- Docker and Docker compose installed.

## Setup:
In this repo we are going to see how to setup monitoring of a linux machine.

I’m going to use Docker to setup this process, however you can install binaries as usual. The docker compose consists of multiple components.

- First setup - Prometheus with Grafan. Viewing Server resources usgae using Node Exporter.
- Second setup - Prometheus alert manager for mail alerts for server usage.
- Third setup - Prometheus Blackbox exporter setup to view and monitor website metrics. Also sendd alerts.

For new user edit config **GF_USERS_ALLOW_SIGN_UP=true**

To run this project use ***docker compose up***
# Node Exporter Dashboard:
![image](https://github.com/sagarkrp/Prometheus_Grafana/assets/42873729/096fb27b-af85-4fdb-95bd-655c2a77463f)

# Blackbox Dashboard
![blackbox](https://github.com/sagarkrp/Monitoring_With_Prometheus-and-Grafana/assets/42873729/2dbc07a8-bc27-4866-a293-646420df3d44)
