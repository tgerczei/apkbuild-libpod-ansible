# apkbuild-libpod-ansible: a simple playbook to automate software packaging for Alpine Linux

## Usage

### Pre-requisites
<ul>
<li>Ansible 2.9+</li>
<li>collection containers.podman</li>
<li>libpod</li>
<li><i>directory</i> /home/<strong>user.handle</strong>/alpine-<strong>package.name</strong></li>
<li><i>directory</i> /home/<strong>user.handle</strong>/alpine-<strong>package.name</strong>/packages</li>
<li><i>file</i> /home/<strong>user.handle</strong>/alpine-<strong>package.name</strong>/APKBUILD_<strong>package.version</strong></li>
</ul>

Developed and tested on Gentoo GNU/Linux with ZFS via fuse-overlayfs and crun in rootless mode.

### Variables
<ul>
<li>alpine_version</li>
<li>user.name</li>
<li>user.email</li>
<li>user.handle</li>
<li>package.name</li>
<li>package.version</li>
</ul>

### Invocation
ansible-playbook alpine-builder.yaml
