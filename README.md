# github-administration

Для того, чтобы использовать Git, нужно:
- записать в config Git имя и почту. Сделать это можно с помощью команд:
<code>
 git config --global user.name "Mona Lisa" 
 git config --global user.email johndoe@example.com
</code>

- установить SSH-соединение. Посмотреть команды можно здесь:
https://docs.github.com/ru/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

- создать репозиторий

- скопировать его через SSH с помощью команды:
git clone + ссылка на репозиторий

##Основные команды git

git add . - индексируем все измененные файлы
git commit -m "Описание" - описание коммита 
git push - выгрузить изменения на удаленный репозиторий
git pull - подтянуть все изменения из удаленного  репозитория 

