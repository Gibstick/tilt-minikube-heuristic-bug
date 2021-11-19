tilt's minikube detection does not work in this case. Steps:

1. ./start.sh
2. tilt up

Tilt will fail to deploy because it thinks the context is production.

To delete everything, run cleanup.sh
