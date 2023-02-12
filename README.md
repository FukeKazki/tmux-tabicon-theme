# tmux-tabicon-theme
[tmux-tabicon](https://github.com/mocaffy/tmux-tabicon) のテーマを置くリポジトリ
## インストール例
```
git clone https://github.com/mocaffy/tmux-tabicon-theme.git ~/.config/tmux/tabicon-theme/
```

tmux.conf
```conf:tmux.conf
set -g @tmux-tabicon-themes-dir ~/.config/tmux/tabicon-theme/
set -g @plugin 'mocaffy/tmux-tabicon'
run '~/.config/tmux/plugins/tpm/tpm'
```
