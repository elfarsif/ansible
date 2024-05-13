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

4. Manually install oh-my-zsh (I know i know isnt that the whole point of ansible, im new lol)
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

##zsh auto-sugesstion

1. Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

    ```sh
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```
## nerd font install

https://medium.com/@almatins/install-nerdfont-or-any-fonts-using-the-command-line-in-debian-or-other-linux-f3067918a88c

wget -P ~/.local/share/fonts https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/JetBrainsMono.zip \
&& cd ~/.local/share/fonts \
&& unzip JetBrainsMono.zip \
&& rm JetBrainsMono.zip \
&& fc-cache -fv




