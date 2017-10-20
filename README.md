# nsg4test

Create a virtual NSG with a client based on ubuntu to test Nuage VNS
Also, it installs a webvirtmgr on KVM host.
You can use a packet.net type 0 server.

Don't forget to copy public key at KVM host!!!

```
ansible-playbook -i hosts -e domain_lab=nuage.lab -e hypervisor=147.75.64.3 deploy.yml
```

