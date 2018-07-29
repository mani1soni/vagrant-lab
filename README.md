# Vagrant lab

Experimental environments using Vagrant. 

## Requirements

- Vagrant
- Virtualbox

## Usage

```
git clone https://github.com/jesusgn90/vagrant-lab
cd vagrant-lab
vagrant up
```
## Architecture

You will build 7 virtual machines using this Vagrantfile. 

1. First machine is named `master` and it includes Wazuh manager (master node), Wazuh API, Elasticsearch, Logstash, Filebeat, Kibana.
2. Second machine is named `client` and it includes Wazuh manager (client node. connected to first machine) and Filebeat.
3. Machines 3-7 are Wazuh agents connected to master node from Wazuh cluster.

## Main packages

- Wazuh manager 3.4.0
- Wazuh API 3.4.0
- Elasticsearch 6.3.2
- Filebeat 6.3.2
- Logstash 6.3.2
- Kibana 6.3.2

## Contribute

1. Fork this repository from `master` branch
2. Test your changes
3. Submit a pull request

That's all!
