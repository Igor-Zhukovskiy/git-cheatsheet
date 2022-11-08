# Мои команды

H - HEAD

rem - remote

stat - status

aa - add .

ck - checkout

br - branch

com - commit

comam - commit --amend -m

comm - commit -m

come - commit --allow-empty

his - показывает историю в виде графика

refhis - показывает историю в виде графика + reflog

## Быстрая настройка
git config --global --remove-section alias;
git config --global alias.H "HEAD";
git config --global alias.rem "remote";
git config --global alias.stat "status";
git config --global alias.aa "add .";
git config --global alias.ck "checkout";
git config --global alias.br "branch";
git config --global alias.com "commit";
git config --global alias.comam "commit --amend -m";
git config --global alias.comm "commit -m";
git config --global alias.come "commit --allow-empty -m";
git config --global alias.his "log --all --graph --pretty=format:'%C(#f1a729)%h%C(reset) %s%C(cyan)%d %n %C(dim)%b %n %C(dim)%cr - %cn %n'";
git config --global alias.refhis "log --reflog --graph --pretty=format:'%C(#f1a729)%h%C(reset) %s%C(cyan)%d %n %C(dim)%b %n %C(dim)%cr - %cn %n'";