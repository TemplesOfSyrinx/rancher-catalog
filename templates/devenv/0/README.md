# Ubuntu Open SSH Daemon

Ubuntu server running with OpenSSH Damon for Visual Studio Code Extension Remote: SSH Development

This service uses the official [TOS Ubuntu OpenSSH](https://hub.docker.com/r/templesofsyrinx/ubuntu-sshd/) image.

## How to use

Start a shell in the container and execute these commands:

adduser <username>  (follow the prompts)

mkdir -m 700 /home/<username>/.ssh  (prepare the ssh directory)

chown <username>:<usergroup> /home/<username>/.ssh
