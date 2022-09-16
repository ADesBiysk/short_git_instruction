Краткая инструкция по работе с git.

1. Если не копировали себе на компьютер репозиторий:
```
git clone git@github.com:Studio-Yandex-Practicum/lomaya_baryery_backend.git
```
 
Если нужно получить все изменения из главной ветки:
```
git pull origin
```

2. После получения задания создаём свою ветку на сайте.
Переходим на страницу со всеми ветками:
![branches](./images/01_branches.png "Переходим на страницу со всеми ветками")

Нажимаем кнопку 'Create new branch':
![new_branches](./images/02_new_branches.png "Нажимаем кнопку 'New branch'")

Вводим название ветки. Название ветки должно быть такое: feature/{внятное название на англ} или fix/{внятное название на англ}. “Внятное название” - название, которое отвечает на вопрос “Что это”. Например, feature/model_user, или fix/readme. 
![branch name](./images/03_branches_name.png "Вводим название ветки.")

4. Получаем информацию о всех ветках:
```
git fetch
```

5. Переключаемся на эту ветку:
```
git checkout feature/model_user
```

6. Когда нужно отправить изменения на сайт:
```
git add .
git commit -m 'Commit description'
git push
```

7. Создаём pull request:
Переходим на страницу с pull requests:
![pull_request](./images/04_pull_request.png "Переходим на страницу с pull requests.")

Создаём новый pull request:
![create_pull_request](./images/05_new_pull_request.png "Создаём новый pull request.")

Заполняем информацию:
![create_pull_request](./images/06_pull_request_info.png "Заполняем информацию.")
