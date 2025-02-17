# Практическая работа 17 - Компонентный подход

## Задание 1

1. На протяжении нескольких занятий вы работали над проектом Library. Необходимо переписать его, следуя правилам компонентного подхода (пример компонента - футер, хедер, книга, рейтинг, модальное окно, поиск и т.д.).
В папке этого задания должен быть файл index.html, и папка src с исходниками-компонентами.
2. Добавить уведомления. На каждое действие пользователя (добавление книги, использование фильтра, изменение рейтинга) должно появляться уведомление на панели уведомлений.
3. Добавить страницу "History", которая показывает всю историю уведомлений.
4. Модальное окно детали книги. Когда пользователь нажимает на книгу, должно появиться модальное окно, в котором можно установить тег, например "Best of List", "Classic Novels" или создать новый тег.
5. *Задеплоить проект на netlify.com (разобраться самостоятельно, используя [руководство](https://www.netlify.com/blog/2016/10/27/a-step-by-step-guide-deploying-a-static-site-or-single-page-app/))

### Требования

- Файловая структура (см. описание выше)
- Использование компонентов (модулей)
- Использование синтаксиса import/export
- Не использовать устаревшие операторы (var, и тд)

PS. в index.html может лежать весь html, но так же можно разбить его на модули и вставлять в DOM через специальные методы. Инициатива при выборе дополнительных инструментов привествуется (webpack, rollup и т.д.)

#### Критерии оценки: 
- 0 - задание не выполнено
- 1-4 - задания выполнены, но есть недоработки
- 5 - задание выполнено и соответствует требованиям, исправлены комментарии тренера, если имеются
