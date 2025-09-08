## отсортировать каталоги размером более 1ГБ
```
du -t 1G -Ph /folder_name/

##
du -ah /folder_name/ | sort -rh
