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
```git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions


ansible pull allows to run playbook from remote repo like this one.

2.5 install git to use ansible pull
```bash
sudo apt install git
```

3. Pull ansible playbook
```bash
sudo ansible-pull -U https://github.com/elfarsif/ansible.git
```

4. Pull dotfiles
```bash
cd ~
git clone https://github.com/elfarsif/.dotfiles.git
cd .dotfiles
stow .
```

Remember to commit to git you need to switch to ssh link




##zsh auto-sugesstion

1. Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

    ```sh
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```





