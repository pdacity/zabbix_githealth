> Version 1.0 - (20190117)

### Zabbix Template for GitLab health check

for Zabbix 3.x (Zabbix 2.x was not tested)

zabbix-agent must be installed on the monitored node

### Install

* define macros {$GIT_TOKEN} for each host
* copy userparameter_githealth.conf into /etc/zabbix/zabbix_agent.d (http or https)
* inport Template 
* restart zabbix_agent

### Files

* template_githealth.xml - Zabbix template 
* userparameter_githealth.conf - Zabbix userparameters file

### References


### Version

* 1.0 - initial





