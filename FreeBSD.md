## #1 packagesite.txz permission denied

### Problem Des.

```
root@xxx:~ # pkg install screen
Updating FreeBSD repository catalogue...
pkg: http://pkg.FreeBSD.org/freebsd:10:x86:64/quarterly/meta.txz: Permission denied
repository FreeBSD has no meta file, using default settings
pkg: http://pkg.FreeBSD.org/freebsd:10:x86:64/quarterly/packagesite.txz: Permission denied
Unable to update repository FreeBSD
All repositories are up-to-date.
```

### Problem Sol.

Sol.1 Allow IP from outside

Sol.2 restart ipfw
