# Zabbix Monitoring for Snom Phone
## Usage

> Snom SNMP documentation: https://service.snom.com/display/wiki/How+to+setup+SNMP 

Important note:
- You need to use **SNMPv1**
- You need to add your Zabbix Server or Proxy IP address to the phone settings: **Web Interface** > **Advanced** > **Network** > **SNMP**

Once the template is installed and assigned to the hosts, Zabbix will start monitoring the following:

After importing and linking this template to your Snom Phone hosts, Zabbix will automatically collect and monitor the following data:
- ICMP availability checks
- SNMP agent status
- Uptime (currently provided as a string)
- Count of successful and failed calls
- Firmware version
- Active registrations

## Compatibility
This template is designed for Zabbix Server 6.0 or later.
