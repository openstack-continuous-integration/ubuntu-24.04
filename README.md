# ubuntu-24.04

This repository relies heavily on [pkgx](https://docs.pkgx.sh/) for its commands (task, ssh, packer, coreutils...) version control.
Please, install it first.

```bash
$ git clone https://github.com/openstack-continuous-integration/ubuntu-24.04.git
$ cd ubuntu-24.04
```

Activate pkgx developement environment.
```bash
$ dev on
env +taskfile.dev^3.37 +git-scm.org
```

```bash
$ task
task: Available tasks for this project:
* init:  Initializes constructor and provisioner repositories
```

Initialize constructor and pprovisioner dependency repositories
```bash
$ task init
```

