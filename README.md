# dcos-controller
Install the DC/OS CLI and provision selected demo(s).

#Demos

## Docker Cloud Hello World
Deploys the Docker container version of the Docker Cloud hello-world sample.

### Environment variables

* DOCKERCLOUD_DEMO_HAPROXY_VHOST: the virtual host name for the public exposing of the demo. Typically the DNS name of the ELB e.g. `dcos-cluster-elb-1413204708.eu-west-1.elb.amazonaws.com` or the FQDN of a host in a domain under your control.

