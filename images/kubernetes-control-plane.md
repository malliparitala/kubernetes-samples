Master:

    API Server
    Scheduler
    Controller Manager
    etcd
  
Nodes:

    - Node1
      Networking
      Kubelet
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
      Networking
      Kubelet
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
      Networking
      Kubelet
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
