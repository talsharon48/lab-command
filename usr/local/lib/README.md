change utility vm - a vm that the script tries to ssh to and take the kube:admin pass
change every ocp4 url in the files (to our env instead of ocp4.example.com)
put the kubeconfig of the env at /root/.kubeconfig
check all ssh's to worker nodes and masters
change ocp4_stop_crio_service ocp4_stop_kubelet_service ocp4_start_crio_service ocp4_start_kubelet_service functions to suit for out ocp4-cluster

Masters:
master01
master02
master03

Workers:
worker01
worker02
worker03
