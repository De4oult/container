# Container

This is a container built in __Golang__.
The system deployed in a default container is __Kali Linux__.


## Instructions

Store your __ROOTFS__ to `containers/` and run `container.go` with cmd-args:
```bash
go run container.go run [name/of/rootfs] [command]
```

---
### Example (default project):
The default repository contains __Kali ROOTFS__ in `containers/`(`containers/kali`).

```bash
go run container.go run kali /bin/bash 
```
This command will run /bin/bash on a standard __Kali ROOTFS__.

