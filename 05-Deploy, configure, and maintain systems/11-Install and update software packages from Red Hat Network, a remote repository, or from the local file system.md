# Install and update software packages from Red Hat Network, a remote repository, or from the local file system
## 5.2. WORKING WITH PACKAGES
### 5.2.1. Searching Packages
```shel
~]$ yum search vi nano
```

### 5.2.2. Listing Packages
```shell
~]$ yum list all
~]$ yum list kernel* libvirt*
~]$ yum list installed kernel* libvirt*
~]$ yum list available kernel* libvirt*
~]$ yum repolist
```

To list both enabled and disabled repositories use the following command. A status column is added to the output list to show which of the repositories are enabled.

```shell
~]$ yum repolist all
~]$ yum repoinfo
```
