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

3. Pull ansible playbook
```bash
sudo ansible-pull -U https://github.com/elfarsif/ansible.git
```

4. Manually install oh-my-zsh (I know i know isnt that the whole point of ansible, im new lol)
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```




There a few changes i have to still automate

-ohmyzsh and p10k are both directly from the repo, the links are in the local.yml file

-automate the extraction of nerdfont
wget -P ~/.local/share/fonts https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/JetBrainsMono.zip \
&& cd ~/.local/share/fonts \
&& unzip JetBrainsMono.zip \
&& rm JetBrainsMono.zip \
&& fc-cache -fv


-zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions


