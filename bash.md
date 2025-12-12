## Полезные команды
```
# отсортировать каталоги и файлы размером более 1ГБ
du -t 1G -Ph /folder_name/

# показывает размер всех файлов и папок в директории /folder_name/ отсортированный по убыванию
du -ah /folder_name/ | sort -rh

#
netstat -an | grep :9093 | wc -l

#
openssl s_client -connect example.com:443 -debug

# Запустите top, нажмите 'H' (включить Threads), затем 'f' → добавьте колонку "WCHAN"
top -p $pid

pid=$(pgrep -f 'data-prepper')
echo "Data Prepper PID: $pid"
