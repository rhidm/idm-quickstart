# Prerequisites

## Lab Environment
* A dedicated namespace ( this Quickstart will use "example.test" ) that can be delegated as a DNS zone (delegation is unnecessary if there will be no access from outside the lab environment)
* A /28 (or larger) subnet ( this Quickstart will use "172.17.0.0/28" )
* Three physical or virtual servers:
	* Red Hat Enterprise Linux 7 (RHEL7)
	* "Minimal Install"
	* 10 GB storage
	* 1 GB RAM
	* 1 CPU (or vCPU)

## Lab Systems
* 172.17.0.2 : idm-1.example.test
* 172.17.0.3 : idm-2.example.test
* 172.17.0.9 : client7-1.example.test

## Lab Client
A desktop with an SSH client and a web browser (Firefox recommended).
