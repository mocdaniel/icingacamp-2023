<kbd>[To the slides](https://slides.dbodky.me/icingacamp-2023/)</kbd>

# The Times They Are A'Changing
## Running Icinga2 on Kubernetes

Running a highly-available Icinga 2 ecosystem on traditional infrastructure can be a challenge and involves considerable overhead in terms of deployed software, maintenance, and possible single points of failure. Deploying the management plane of the cluster to Kubernetes can solve some of those troubles by capitalizing on Kubernetes’ built-in capabilities regarding service discovery and self-healing. In this session, a brief overview of a best-in-class HA setup of Icinga on traditional environments will be given, before exploring advantages of running the management plane on Kubernetes and presenting our early version of a Helmchart for this purpose.