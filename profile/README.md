# go-slurmstack

**slurmstack builds a Slurm cluster on OpenStack from one Go binary.**
Terraform creates the private network, the router, the floating IP, an NFS
server and the workers; the go-ansible engine, linked into the same binary,
configures munge, NFS, Slurm, an LDAP directory and the software stack. No
Python, no `ansible-playbook`, host keys pinned from the server consoles
instead of trusted on first use. Linux and macOS, pure Go.

- Landing: <https://go-slurmstack.github.io/>
- Documentation: <https://go-slurmstack.github.io/docs/>

The source code is not public yet; it is available on request.
