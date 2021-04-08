# Курсовой проект к модулю "Введение в тестирование"

## Правила выполнения курсового проекта

- Объект тестирования: интернет-магазин https://henderson.ru.
- Обратите внимание, что сайт НЕ ТЕСТОВЫЙ, поэтому не надо совершать на нем покупки и прочие подобные действия.
- Скопируйте [здесь] https://docs.google.com/spreadsheets/d/1Nl2_n46HvTIdv7JpbNLjOtMcWSuYpblZjyxlsBFKanY/edit?usp=sharing) шаблон таблицы на  свой Google-диск, указав в названии файла фамилию, имя и группу вместо Name, Surname, Group.
- В своей таблице прикрепляйте ссылки на результаты тестирования по каждому заданию.
- Проследите, чтобы в ваших гугл-документах и таблицах была открыта возможность комментировать всем пользователям в интернете, кому предоставлена ссылка.
- Когда выполните все 5 заданий (задание 3.2* по желанию), прикрепите в личном кабинете ссылку на свою таблицу с решениями и ожидайте проверки преподавателя.
- Курсовой проект считается принятым, когда все 5 заданий (кроме задания 3.2.* по желанию) приняты преподавателем.

Файл для заполнения результатов тестирования можно найти [здесь](https://docs.google.com/spreadsheets/d/1Nl2_n46HvTIdv7JpbNLjOtMcWSuYpblZjyxlsBFKanY/edit?usp=sharing).

## Задание 1

Написать чек-лист для функциональной проверки [личного кабинета зарегистированного пользователя](https://henderson.ru/cabinet/) (включая функционал разделов) на сайте https://henderson.ru/.

**Требования к выполнению:**
* Чек-лист должен представлять собой структурированный (многоуровневый) список, который содержит набор позитивных и негативных проверок компонентов объекта тестирования.
* При составлении списка проверок должны учитываться различные варианты состояний страниц. Например, при проверке функционала "Мои отзывы" мы проверяем не только состояние без отзывов, но и с ними.
* Мы ожидаем от вас проверку функционала личного кабинета без учета хедера и футера страницы, то есть то, что есть в этой [области](https://prnt.sc/112e3e7).
* Шаблон для чек-листа можно найти [здесь](https://docs.google.com/spreadsheets/d/1Nl2_n46HvTIdv7JpbNLjOtMcWSuYpblZjyxlsBFKanY/edit?usp=sharing).

## Задание 2

Написать набор тест-кейсов на проверку функционала восстановления пароля.

**Требования к выполнению:**
* Тест-кейсы должны покрывать все, что описано в требованиях по [ссылке](https://docs.google.com/document/d/12deDbATIy0Xps8MiWvumNqHISfAlFc4etY8F4lPcqJ4/edit?usp=sharing), и учитывать позитивные и негативные кейсы.
* Мы ожидаем от вас минимум 20 тест-кейсов.
* Шаблон для выполнения находится [здесь](https://docs.google.com/spreadsheets/d/1Nl2_n46HvTIdv7JpbNLjOtMcWSuYpblZjyxlsBFKanY/edit?usp=sharing).

## Задание 3

3.1. На основе [скриншота](https://prnt.sc/114niqm) создать не менее трех баг репортов.
Шаблон для заведения баг-репортов можно найти [здесь](https://docs.google.com/spreadsheets/d/1Nl2_n46HvTIdv7JpbNLjOtMcWSuYpblZjyxlsBFKanY/edit?usp=sharing).


3.2*. Найти баг в функционале "Написать отзыв" в карточке товара и составить на него баг-репорт. 
Если найдете несколько - замечательно!
Шаблон для заведения баг-репортов можно найти [здесь](https://docs.google.com/spreadsheets/d/1Nl2_n46HvTIdv7JpbNLjOtMcWSuYpblZjyxlsBFKanY/edit?usp=sharing)

## Задание 4

Вы тестируете страницу карточки товара. Из ТЗ вы знаете, что товар может стоить от 1 рубля до 10 000 000 рублей. К сожалению, на сайте в данный момент товаров с такой ценой нет, а разработчик бекенда в отпуске, поэтому вам нужно протестировать верстку страницы карточки товара с максимальной и минимальной ценой самостоятельно.
Ваша задача - самостоятельно определить, как проще это реализовать.

**Требования к выполнению:**
* Предоставьте решение в виде скриншотов страницы карточки товара с минимальной и максимальной ценой товара.
* Решение присылайте в форме, указанной [здесь](https://docs.google.com/spreadsheets/d/1Nl2_n46HvTIdv7JpbNLjOtMcWSuYpblZjyxlsBFKanY/edit?usp=sharing).

## Задание 5

Бекенд разработчик говорит, что мы отправляем данные с сайта в неправильном формате и просит вас помочь найти нужный запрос. Фронтенд разработчик ушел в отпуск в поход без связи, а документация пропала.

Известно, что проблема в данных, которые уходят в post запросе по адресу https://api.mindbox.ru/v3/js/operations/sync, и происходит это скорее всего при работе с личными данными пользователя (например авторизация, личный кабинет, просмотр корзины).

Ваша задача - изучить ответы и запросы при работе с сайтом; найти, как же выглядят параметры deviceUUID, requestId и status, и приложить скриншот искомого превью в таблицу с решениями.


