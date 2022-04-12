# OmpSs-2 Cluster + DLB

This meta-repository contains the OmpSs-2@Cluster programming model with load
balancing via DLB.

OmpSs-2@Clusters is based in the original OmpSs-2 and most of the documentation also valid.

* OmpSs-2 User Guide: https://pm.bsc.es/ompss-2-docs/user-guide
* OmpSs-2 Specification: https://pm.bsc.es/ompss-2-docs/spec
* OmpSs-2 Examples: https://pm.bsc.es/gitlab/ompss-2/examples
* OmpSs-2 Docker Images: https://hub.docker.com/r/bscpm/ompss-2
* OmpSs-2 Release Notes: [NEWS.md](./NEWS.md)

# Getting Started

Firstly, clone this repository to your local computer:

```
$ git clone https://github.com/paulmcarpenter/ompss-2-cluster-dlb.git
$ cd ompss-2-cluster-dlb
```

Then, run the command below to download all the submodules in the relevant 
subfolders.

```
$ git submodule update --init
```

Once these sources are downloaded, follow the installation instructions that are
detailed in the [User Guide](https://pm.bsc.es/ompss-2-docs/user-guide).
