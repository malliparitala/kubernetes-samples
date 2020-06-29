control Plane's components 

    make global decisions about the cluster (like scheduling), as well as 
    detecting and responding to cluster events (like starting up a new pod, when no of replicas are not matching)
    
    kube-api-server: 
        exposes the Kubernetes API
        front-end for the control-plane
        
    etcd:
        highly available key-value store for all cluster data
        
    kube-scheduler:
        watches for "newly created pods with no assigned node" and selects a node for them to run on.
        
    kube-controller-manager:
        runs controller processes, include:
            Node controller
            replication controller
            endpoints controller
            serive account & token controllers
            
    cloud-controller-manager:
        embeds cloud-specific control logic
        let's you link your cluster into your cloud provider's api and 
        seperates out the components that interact with cloud platform from components that just interacts with your cluster.
        following controllers can have cloud provider dependencies:
            node controller
            route controller
            service controller
        
