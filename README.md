# zabbix-agent
playbook which adds a host to the installation of zabbix-agent and zabbix-server

## Description
Each task is being divided by the roll.
And to add host to zabbix-server, in zabbix-server-api, install, have.

## Usage
### Install
```sh
git clone https://github.com/tetuya0703/zabbix-agent.git
cd zabbix-agent
```
More than 2.4.1 of the version of ansibl is recommended.

### Run
ansible-playbook -i inventory/inventory.ini zabbix_agent.yml

### Options
ansible-playbook -i inventory/inventory.ini zabbix_agent.yml --tags common
Only specific role is carried out.

## License
[MIT](LICENSE)