## Different types of hypervisor ?
Yes you have type 1 and type 2
#### Type 1 :
Type 1 hypervisors are the most efficient and performant hypervisors.
They are performant because they access directly to your hardware without having an in between operating system.
And can be used in production environnement to deploy virtual machine efficiently and reliably
Exemple : [ESXi](https://www.vmware.com/products/cloud-infrastructure/esxi-and-esx),[Proxmox](http://proxmox.com) or [HyperV](https://learn.microsoft.com/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v)
#### Type 2 :
Type 2 hypervisors are the most versatile and easy of use.
They are installed directly onto your operating system. They are less performant than type 1.
And mostly used for testing environnement due to there ease of use and simplicity.
Exemple : [VirtualBox](https://www.virtualbox.org). [VMWare Workstation](https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion)

*tag:*
#virtualization 