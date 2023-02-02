# PingStack-GKE-MultiRegion
TO track changes made to kustomize templates

Seed Cluster:
PingDirectory Location: West

Secondary Cluster:
PingDirectory Location: East

What's included:
pingdirectory
pingfederate
pingdatasync
pingdataproxy
pingdelegator
pingdataconsole
externaldns

#1 install the terraform modules for creating the underlying network infra
#2 firewall rules for bi-directional communication between the two vpc should be configured
#3 install the ping clusters on both clusters using kustomize

Tested!. works!
