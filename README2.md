# Git basics

1. Создаем репу на гитхабе
2. Клонируем себе на ПК репу

   git clone ...

3. Создаем ветку локально

   git checkout -b <branc-name>

4. Запушим ветку в удаленный репозиторий

   git push --set-upstream origin <branc-name>

5. Вносим изменения на ветке
6. Коммитиим изменения

   git commit -m "changes i've done"

7. Пушим изменения в удаленную репу

   git push

8. Создаем пулл реквест в удланном репозиторий.

9. Мержим.
10. В настройках github->Pages выбираем ветку, с которой будет рисоваться деплой.

Опционально:

- притянуть измененмия с ветки <br1> в другую <br2>, находясь на ветке <br1>:

  git merge <br2> --no-ff

## Alias

[alias]
co = checkout
ci = commit
br = branch
st = status
hist = log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short

## Links:

1. https://githowto.com/aliases
