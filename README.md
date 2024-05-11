# ansible
Ansible configuration for my desktop
New Change


There a few changes i have to still automate

-ohmyzsh and p10k are both directly from the repo, the links are in the local.yml file

-automate the extraction of nerdfont
wget -P ~/.local/share/fonts https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/JetBrainsMono.zip \
&& cd ~/.local/share/fonts \
&& unzip JetBrainsMono.zip \
&& rm JetBrainsMono.zip \
&& fc-cache -fv
