# How to use todo.md:
"- [ ]" Incomplite tasks
"- [x]" Complite tasks

- [x] сделать 3 спрайта для всего проекта (общий, лендинг и ошибки)
- [x] убрать из static/img изображения, которые должны быть в upload
- [x] переименовать изображения, дав им понятные имена.
- [x] Поправить CSS (должно быть 3 файла) 
- [x] Переименовать шрифты. А то у вас есть "OpenSans" и "Open_Sans".
- [x] Убрать Arial Bold из шрифтов, потому что это и так стандартный шрифт

Для Юры подправить curses:

- [x] 1. subheader-courses - неразбериха в этом блоке, много лишних "обреток" и соответсвенно ненужных классов. Хватило бы div>div>ul*2>li*2>a или что то в этом роде.
- [x] 2. Сайдбар и контент были разьеденены,( я там немного ковырялся, так что не пугайся сильно )
- [x] 3. table-course  почему -то не влазят вместе с сайдбаром. Скорее всего потому что ты не указал padding 0 для table-up>ul
- [x] 4. блок wrapper clearfix не нужен. Вместо него должен быть просто див, который обьеденяет контент и сайдбар, так же как и на всех других стрнацах: class="main", c шириной 960 px и margin 0 auto 