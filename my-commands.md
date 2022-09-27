# Мои команды

ck - checkout

br - branch

com - commit

comm - commit -m

## Примеры

git log --decorate --stat --graph --pretty=format:"%d %Cgreen%h%Creset (%ar - %Cred%an%Creset), %s%n"

log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all

как я хочу выводить лог?

Обычный коммит без боди должен состоять из 3 строчек

#<commit-hash=short,yellow> <commit-name> <branch-ref=>
<commit-body=dim>
<commit-rel-date> by: <commiter-name>



## Быстрая настройка
git config --global --remove-section alias;
git config --global alias.ck "checkout";
git config --global alias.br "branch";
git config --global alias.com "commit";
git config --global alias.comm "commit -m";
git config --global alias.acomm "commit --allow-empty -m";

<!-- сломалось -->
git config --global alias.tree "log --all --graph --pretty=format:"%C(#f1a729)%h %C(reset) %s%C(cyan)%d %n %C(dim) %b %C(reset) %n %C(dim) %cr - %cn %n"";
git config --global alias.tree "log --all --graph --pretty=format:"%C(dim)(%b)%C(reset) %n"";
git config --global alias.tree "log --all --graph --pretty=format:"%C#f1a729%h %Creset %s%Ccyan%d %n %Cdim %b"";
git config --global alias.tree "log --all --graph --pretty="format: %C(#f1a729)%h %C(reset) %s%C(cyan)%d %n %C(dim) %b %C(reset) %n %C(dim) %cr - %cn %n"";