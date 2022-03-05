# zsh-theme

It's a gentoo zsh-theme using robbyrussell features (also, I use *agnoster* in super user :)).


1. Install oh-my-zsh via curl:
```
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
2. Create the **~/.oh-my-zsh/themes/gentoo_plus_robbyrussell.zsh-theme** file and set on ~/.zshrc:
```
ZSH_THEME="gentoo_plus_robbyrussell"
```

##### Bonus: K8s plugin
> at the end of ~/.zshrc put:
```
source ~/.oh-my-zsh/plugins/kube-ps1/kube-ps1.plugin.zsh
PROMPT='$(kube_ps1)'$PROMPT
```