# Networking basics #1:

**Resources:**

* [What is localhost](https://en.wikipedia.org/wiki/Localhost)
* [What is 0.0.0.0](https://en.wikipedia.org/wiki/0.0.0.0)
* [What is the hosts file](https://www.makeuseof.com/tag/modify-manage-hosts-file-linux/)
* [Netcat examples](https://www.thegeekstuff.com/2012/04/nc-command-examples/)

**Commands**

* ``ifconfig``
* ``telnet``
* ``nc``
* ``cut``

## Environment
 
* Language: Bash
* Operating System: Ubuntu 20.04 LTS

## Description of each file:

| Files          |Desription
|:----------------|:-------------------------------:|
|0-change_your_home_IP |Bash script that configures an Ubuntu server with the below requirements.
|1-show_attached_IPs |Bash script that displays all active IPv4 IPs on the machine it’s executed on.
|100-port_listening_on_localhost |Bash script that listens on port 98 on localhost.

## Tasks :page_with_curl:

* **0. Change your home IP**
  * [0-change_your_home_IP](0-change_your_home_IP)
  * A Bash script that configures an Ubuntu server with the below requirements.
    - Requirements:
    - localhost resolves to 127.0.0.2
    - facebook.com resolves to 8.8.8.8.

* **1. Show attached IPs**
  * [1-show_attached_IPs](1-show_attached_IPs)
  * A Bash script that displays all active IPv4 IPs on the machine it’s executed on.

* **2.Port listening on localhost**
  * [100-port_listening_on_localhost](100-port_listening_on_localhost)
  * A Bash script that listens on port 98 on localhost.
