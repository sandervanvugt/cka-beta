restricted access CKA 4/ed beta

to set up the cluster, use the following:
1.	install 5 virtual machines, using Ubuntu LTS server 24.04
2.	on all nodes, use ./setup-container.sh and ./setup-kubetools.sh to install the generic parts required for creating the cluster. These parts will be pre-installed on the exam.
3.	if you need to create a HA cluster, only on ONE control node, use the ./setup-lb-ubuntu.sh script to set up the loadbalancer 
after this preliminary steps, you are supposed to know what you are doing. 
