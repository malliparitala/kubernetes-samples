kubeadm :   Easily bootstrap a secure kubernetes cluster

kubectl :   

Master:

    kube-api-server
    kube-scheduler
    kube-controller-manager
    cloud-controller-manager
    etcd
  
Nodes:

    - Node1
      Kubelet
      kube-proxy
      Container Runtime
      -   pod1
          -   container1
              container2
              container3
              ...
      -   pod2
          -   container1
              container2
              container3
              ...
      -   pod3
          -   container1
          -   container2
          -   container3
              ...
      OS

    - Node2
      kubelet
      kube-proxy
      Container Runtime
      -   pod1
          -   container1
              container2
              container3
              ...
      -   pod2
          -   container1
              container2
              container3
              ...
      -   pod3
          -   container1
          -   container2
          -   container3
              ...
      OS

    - Node3
      Kubelet
      kube-proxy
      Container Runtime
      -   pod1
          -   container1
              container2
              container3
              ...
      -   pod2
          -   container1
              container2
              container3
              ...
      -   pod3
          -   container1
          -   container2
          -   container3
              ...
      OS
