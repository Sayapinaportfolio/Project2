# Проект 2: Моделирование изменения балансов студентов
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1. Чтобы проверить, всё ли в порядке с нашими данными и составить список гипотез и вопросов, нам важно понимать: 
- Сколько всего уроков было на балансе всех учеников за каждый календарный день</li>
  <li>Задача №2. Как это количество менялось под влиянием транзакций (оплат, начислений, корректирующих списаний) и уроков (списаний с баланса по мере прохождения уроков) </li>
</ol>

<p>Как решала: Для составления таблицы балансов были написаны несколько подзапросов на основе таблиц с имеющимися данными, все подзапросы были сведены в единый запрос, который отражает все дни 2016 года, в каждый из которых происхоодили списания уроков с балансов и транзакции попокупке новых уроков, а так же кумимулятивная сумма по списанию и покупке, сделана визуализация по данным таблицы баланса.<p>

> <a href="https://github.com/Sayapinaportfolio/My-portfolio/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20%E2%84%962.xlsx">Ссылка на проект</a>

 
 <p>Выводы (итоги):<p>
<ol>
  <li>Итог №1. сделаны выводы по студентам, у которых были покупки уроков, но использованы только 1 или 2 урока</li>
</ol>
