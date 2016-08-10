# Intro
Hey there,  
I was so tired of re-installing everything manually that I created this.

# Install instruction
1. Install ansible (latest version)
2. run the following command in this directory:
```ansible-playbook install.yml -i hosts/me```
3. If you have an access right issue just do a ```sudo test``` and enter your password so that sudo is enabled

# Parameters
Manly choose what you want to install with
```
my_machine_uses:
    git: true / false
    git_up : true / false
    ...
```
See all parameters in ```roles/bpiselli.dev_env/defaults/main.yml```

