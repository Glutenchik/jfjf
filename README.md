# Установка на сервер Git 

# Создание директории, которая будет подключена к репозитории
```root@vanisimo056:~# mkdir name_hhh
root@vanisimo056:~# cd name_hhh
root@vanisimo056:~/name_hhh#```

# Подключение к репозитории
```root@vanisimo056:~/name_hhh# git remote add origin https://github.com```

# Добавление файлов

```root@vanisimo056:~/name_hhh# git add README.md
root@vanisimo056:~/name_hhh# cp /var/www/html/index.html ~/name_hhh/
root@vanisimo056:~/name_hhh# git commit -m "Добавлен сайт и файл"```

# Загрузка файлов

```root@vanisimo056:~/name_hhh# git push -u origin mainO```


