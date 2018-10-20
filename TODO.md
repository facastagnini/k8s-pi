## TODO

[x] Setup dynamic dns cron
[x] Add ansible task to deploy dashboard
[x] bootstrap.sh should take a number of nodes and auto-generate `inventory`
[ ] Set static IP for master node
[ ] Run ntp update on boot
[ ] Deploy unifi controller
[ ] Auto-renew Let's Encrypt cert
    - plug in usb drive
    - create persistent volume
    - mount persistent volume in traefik controller
    - config acme client with path to persistent volume
[ ] Add ansible task to upgrade cluster
    - https://kubernetes.io/docs/tasks/administer-cluster/kubeadm/kubeadm-upgrade-1-12/
[ ] Install pi-hole
    - Switch to nginx for UDP ingress
[ ] Allow SSH to master node from internet?
    - or run VPN?