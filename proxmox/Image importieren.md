
```bash
qm create <ID> --memory 2048 --core 2 --name ubuntu-cloud-2204 --net0 virtio,bridge=<bridgename>
qm importdisk <ID> noble-server-cloudimg-amd64.img <Storage>
qm set <ID> --scsihw virtio-scsi-pci --scsi0 local-lvm:vm-8010-disk-0
qm set <ID> --boot c --bootdisk scsi0
```

