# Jenkins Agent Implemtation Overview Guides

1. Must install same java version on jenkins agent nodes
2. Must have network connectivity to jenkins agent nodes
3. `generate ssh-key pairs` in `jenkins master nodes`
4. Must have `public ssh key` in `~/.ssh/authorized_keys` file path
5. Must create a directory in `jenkins slaves` to run the `jenkins pipelines jobs`
6. `mkdir /opt/jenkins && chmod 755 /opt/jenkins`
7. Add `Jenkins agent` from Jenkins master and connect via `ssh connection`