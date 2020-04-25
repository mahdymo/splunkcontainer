# splunkcontainer
A way to build local splunk lab for distributed setup via Kubernetes
Using Kind for building local cluster within VM, this behaves as Distributed Bare Metal. 
After initiating the template, you will still need to complete the distributed setup. 

Once the pods are created you will have two options, whether to work as multiple standalone nodes or distributed mode by assigning each pod a role and integrate the setup (Search Header, Indexer, Licensing management and Forwarder), if required you can add the section for Universal forward if needed to be within the same deployment.
