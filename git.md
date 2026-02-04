
```
# сброс изменений
git reset --hard


# удалить тег локально
git tag -d name_tag

# удалить тег на удаленном репозитории
git push origin --delete name_tag

# проверить что тег удален
git ls-remote --tags origin

# посмотреть куда выполняем push
git remote -v
