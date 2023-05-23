# Шаг 1

Создать или иметь проект ранее не опубликованный по Git

<img width="1920" alt="image" src="https://github.com/zhombie/git-sample/assets/26120169/1fb436f2-0e6f-4bb6-b3af-a6cede846854">

# Шаг 2

- Открыть терминал
- Перейти в конечный путь проекта (в примере папка git-sample)
- Выполнить команду ```git init``` для инициализации Git в проекте

<img width="1920" alt="Screenshot 2023-05-23 at 11 14 18" src="https://github.com/zhombie/git-sample/assets/26120169/8d11adf2-5c4f-4124-ab5a-8946e0d724a7">

# Шаг 3

Файлы загорелись красным, то есть IDE уже понимает, что Git был инициализирован и файлы пока не залиты в удаленный репозиторий

> ```Initialized empty Git repository in /Users/inmeta/PycharmProjects/git-sample/.git/``` говорит об успешном инициализации и создании папки .git внутри проекта из примера

<img width="1920" alt="Screenshot 2023-05-23 at 11 15 54" src="https://github.com/zhombie/git-sample/assets/26120169/13c5863c-7b45-4059-a789-50396302c466">

# Шаг 4

Выполнить команду ```git add .``` для добавления файлов в список активных изменений для дальнейшей заливки на удаленный репозиторий

> Теперь IDE подсвечивает файлы зеленым цветом, а не красным как раньше

<img width="1920" alt="Screenshot 2023-05-23 at 11 18 05" src="https://github.com/zhombie/git-sample/assets/26120169/e171dc17-7c3a-468e-bff9-790a098be312">

# Шаг 5

Выполнить команду ```git commit -a -m "first commit"```. Все изменения были сохранены с сообщением "first commit" на локальном устройстве и готовы к заливке на удаленный репозиторий

<img width="1920" alt="Screenshot 2023-05-23 at 11 20 14" src="https://github.com/zhombie/git-sample/assets/26120169/7583e3ef-14f3-4b74-85e6-6942d6b575c1">

<img width="1920" alt="Screenshot 2023-05-23 at 11 20 34" src="https://github.com/zhombie/git-sample/assets/26120169/7688e461-733d-4f3a-9b3b-d04528a5864d">

# Шаг 6

Перейти по ссылке https://github.com/

<img width="1920" alt="Screenshot 2023-05-23 at 11 24 00" src="https://github.com/zhombie/git-sample/assets/26120169/a599c029-0ff9-4de4-87da-34f4c2c05f98">

# Шаг 7

Создать удаленный репозиторий на платформе GitHub (есть другие аналоги как GitLab, JetBrains Space, ...)

<img width="1920" alt="Screenshot 2023-05-23 at 11 24 16" src="https://github.com/zhombie/git-sample/assets/26120169/654fe56d-1fd6-4443-919a-4076b36a5af0">

<img width="1920" alt="Screenshot 2023-05-23 at 11 25 15" src="https://github.com/zhombie/git-sample/assets/26120169/d7282fe5-0c26-4dec-9b67-5428da5cf5c3">

<img width="1920" alt="Screenshot 2023-05-23 at 11 25 31" src="https://github.com/zhombie/git-sample/assets/26120169/01ac9684-d48b-44fc-8a10-dab9e085b834">

# Шаг 8

Выполнить команду ```git remote add origin https://github.com/zhombie/git-sample-repository.git``` для добавления ссылки удаленного репозитория

<img width="1920" alt="Screenshot 2023-05-23 at 11 26 51" src="https://github.com/zhombie/git-sample/assets/26120169/bbabe091-0c32-4ce7-b034-9202f00fce91">

Для подтверждения действия можно проверить командой ```git remote -v```

<img width="1920" alt="Screenshot 2023-05-23 at 11 27 07" src="https://github.com/zhombie/git-sample/assets/26120169/2cd0d425-c151-421f-b10e-e8425dcc321d">

# Шаг 9

Выполнить команду ```git push -u origin master``` для заливки локальных коммитов в удаленный репозиторий

<img width="1920" alt="Screenshot 2023-05-23 at 11 29 33" src="https://github.com/zhombie/git-sample/assets/26120169/247e0119-c7b3-4428-8e9c-b4c8ff6f3855">

<img width="1920" alt="Screenshot 2023-05-23 at 11 30 00" src="https://github.com/zhombie/git-sample/assets/26120169/bf22e300-417d-41a4-9bd2-7e0986eec107">
