# ansible
Ansible configuration for my desktop

How to run this:

1.Install ansible
```bash
sudo apt update
sudo apt install ansible
```

2.check for installed binary
```bash
which ansible-playbook
which ansible-pull
```

ansible pull allows to run playbook from remote repo like this one.

2.5 install git to use ansible pull
```bash
sudo apt install git
```

3. Pull ansible playbook
```bash
sudo ansible-pull -U https://github.com/elfarsif/ansible.git
```

##zsh auto-sugesstion

1. Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

    ```sh
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```





