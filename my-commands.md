# Мои команды

ck - checkout

br - branch

com - commit

comm - commit -m

acomm - пустой commit

tree - показывает историю в виде графика

rtree - показывает историю в виде графика + reflog

## Быстрая настройка
git config --global --remove-section alias;
git config --global alias.ck "checkout";
git config --global alias.br "branch";
git config --global alias.com "commit";
git config --global alias.comm "commit -m";
git config --global alias.acomm "commit --allow-empty -m";
git config --global alias.tree "log --all --graph --pretty=format:'%C(#f1a729)%h%C(reset) %s%C(cyan)%d %n %C(dim)%b %n %C(dim)%cr - %cn %n'";
git config --global alias.rtree "log --reflog --graph --pretty=format:'%C(#f1a729)%h%C(reset) %s%C(cyan)%d %n %C(dim)%b %n %C(dim)%cr - %cn %n'";