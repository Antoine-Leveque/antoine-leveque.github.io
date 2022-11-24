---
sidebar_position: 1
---

# LVM
 
## Ajouter du stockage

*Après avoir ajouter le disque au serveur*

```bash
fdisk /dev/{DISK}
```
*réponses fdisk*
```bash
n 
p
t
8e
w
```
```bash
pvcreate /dev/sd{X}
```
```bash
vgextend {VGNAME} /dev/sd{X}
```
```bash
lvextend -l +100%FREE /{PATH}/{TO}/{PATH}
```
```bash
resize2fs /{PATH}/{TO}/{PATH}
```