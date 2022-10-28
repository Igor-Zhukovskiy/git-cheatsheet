# Мои команды

H - HEAD

aro(add remote origin) - remote add origin

aa - add .

ck - checkout

br - branch

com - commit

comam - commit --amend -m

comm - commit -m

come - пустой commit

his - показывает историю в виде графика

refhis - показывает историю в виде графика + reflog

## Быстрая настройка
git config --global --remove-section alias;
git config --global alias.panic "config --list | grep alias | cut -c 7-";
git config --global alias.H "HEAD";
git config --global alias.aro "remote add origin";
git config --global alias.ck "add .";
git config --global alias.ck "checkout";
git config --global alias.br "branch";
git config --global alias.com "commit";
git config --global alias.comam "commit --amend -m";
git config --global alias.comm "commit -m";
git config --global alias.come "commit --allow-empty -m";
git config --global alias.his "log --all --graph --pretty=format:'%C(#f1a729)%h%C(reset) %s%C(cyan)%d %n %C(dim)%b %n %C(dim)%cr - %cn %n'";
git config --global alias.refhis "log --reflog --graph --pretty=format:'%C(#f1a729)%h%C(reset) %s%C(cyan)%d %n %C(dim)%b %n %C(dim)%cr - %cn %n'";