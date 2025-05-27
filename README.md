# security-configs
SSH client configurations

-Disables password authentication

-Uses specific identity files

-Enables strict host key checking

To use:
1. Copy `ssh/ssh_config_example` to `~/.ssh/config`
2. Modify paths and hosts as needed
3. Ensure permissions are correct (`chmod 600 ~/.ssh/config`)
