# qm guest passwd

> Set the password for a user on QEMU/KVM Virtual Machine Manager.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Set a password for a specific user in a virtual machine interactively:

`qm {{[g|guest]}} passwd {{vm_id}} {{username}}`

- Set an already hashed password for a specific user in a virtual machine interactively:

`qm {{[g|guest]}} passwd {{vm_id}} {{username}} --crypted 1`
