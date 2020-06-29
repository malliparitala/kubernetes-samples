Node components
    run on every node
        maintaining running pods
        providing the kuberenetes runtime environment
        
    kubelet:
        agent that makes sure that containers are running in a pod
        
    kube-proxy:
        network proxy, implementes part of the kubernetes service concept.
        maintain network rules on nodes
        
    container runtime:
        responsible for running containers
        supports several container runtimes (like docker, containerd, CRI-O, and any implementation of kubernetes CRI(Container Runtime Interface))
