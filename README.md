# Домашнее задание к занятию "3.6. Компьютерные сети, лекция 1"

1. Работа c HTTP через телнет.

    **Ответ**: В ответе получил код 301, он означает запрашиваемый ресурс был перемещен на url указынный в заголовке Location
    В нашем случае это редирект на https

![alt](https://github.com/asexsela/sysadmin/blob/master/one.png?raw=true)

2. Повторите задание 1 в браузере, используя консоль разработчика F12.

    **Ответ**: Получили первый ответ с кодом 307
    Запрос с на который был редирект был дольше так как он загружал ресурсы, на сриншроте видно
    В консоли ничего нет(в скриншроте), и да там пусто не потому что я ее открыл после загрузки старницы, там ничего нет!

![alt](https://github.com/asexsela/sysadmin/blob/master/two.png?raw=true)

3. Какой у вас IP адрес в сети интернет?

    **Ответ**: 91.202.196.150

4. Какому провайдеру принадлежит ваш IP адрес? Какой автономной системе AS? Воспользуйтесь утилитой `whois`

    **Ответ**: 
        Провайдер Electrica LLC,
        AS - AS49821

5. Через какие сети проходит пакет, отправленный с вашего компьютера на адрес 8.8.8.8? Через какие AS? Воспользуйтесь утилитой `traceroute`

    **Ответ**: AS49821, AS50817, AS15169

![alt](https://github.com/asexsela/sysadmin/blob/master/five_1.png?raw=true)


6. Повторите задание 5 в утилите mtr. На каком участке наибольшая задержка - delay?

    **Ответ**: Наибольшая задержка на участке 9

![alt](https://github.com/asexsela/sysadmin/blob/master/five.png?raw=true)


7. Какие DNS сервера отвечают за доменное имя dns.google? Какие A записи? воспользуйтесь утилитой dig
    **Ответ** 

    ![alt](https://github.com/asexsela/sysadmin/blob/master/seven.png?raw=true)

8. Проверьте PTR записи для IP адресов из задания 7. Какое доменное имя привязано к IP? воспользуйтесь утилитой dig

    **Ответ** Доменное имя dns.google

    ![alt](https://github.com/asexsela/sysadmin/blob/master/eight.png?raw=true)