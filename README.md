# Openstack Ocata VNX virtual laboratories

This is a set of Openstack Ocata (Feb 2017) tutorial laboratory scenarios based on VNX (http://vnx.dit.upm.es). They are designed to experiment with Openstack free and open-source software platform for cloud-computing.

The following scenarios are available:
- openstack_lab-ocata_4n_classic_ovs. This scenario is made of four virtual machines: a controller node, a network node and two compute nodes, all based on LXC. Optionally, new compute nodes can be added by starting additional VNX scenarios. Openstack version used is Ocata (Feb 2017) over Ubuntu 16.04 LTS. The deployment scenario is the one that was named "Classic with Open vSwitch" and was described in previous versions of Openstack documentation (https://docs.openstack.org/liberty/networking-guide/scenario-classic-ovs.html). It is prepared to experiment either with the deployment of virtual machines using "Self Service Networks" provided by Openstack, or with the use of external "Provider networks". See additional information about this scenario in: https://web.dit.upm.es/vnxwiki/index.php/Vnx-labo-openstack-4nodes-classic-ovs-ocata

- openstack_lab-ocata_4n_classic_ovs-centos. The previous scenario tested over CentOS (not working).
