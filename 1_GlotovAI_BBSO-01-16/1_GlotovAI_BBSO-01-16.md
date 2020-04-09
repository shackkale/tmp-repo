<center>МИНОБРНАУКИ РОССИИ
<br>Федеральное государственное бюджетное образовательное учреждение высшего образования</br>

**"МИРЭА - Российский технологический университет"**

**РТУ МИРЭА**
<br>Институт комплексной безопасности и специального приборостроения</br>
<br>Кафедра:"Интеллектуальные Системы Информационной Безопасности"</br>

Отчет по лабораторной работе по дисциплине:
<br>"Программные средства оперативно-аналитического поиска"</br>

**"Сбор данных о компаниях из открытых источников информации"**</center>
<p style='text-align: right;'> Выполнил: студент 4 курса,
<p style='text-align: right;'> группа ББСО-01-16,
<p style='text-align: right;'> Глотов Александр Игоревич
<p style='text-align: right;'> Принял: Захарчук Иван Илларионович
<center>Москва, 2020</center>

### Цель работы:  
Научиться собирать данные из открытых источников информации.

### Исходные данные:  
ОC Linux Mint 19.3 Tricia, Shodan, whois, 2шз.

### Варианты решения задачи:  

#### Вариант 1:  
Использовать онлайн сервисы ( Shodan, 2ip ) для поиска открытой информации о цели.

#### Вариант 2:  
Использовать консольные утилиты ( whois ) для поиска информации.

### Общий план выполнения:  
1) Сканирование веб приложений при помощи поисковика Shodan.
2) Использование утилиты whois для просмотра открытых данных о домене и о его владельце
3) Сбор информации через сервис 2ip

Данные действия необходимо повторить для следующих 5 целей:  
- Procter & Gamble Company  
- Verizon Communications Inc.  
- Citigroup Inc.  
- AbbVie Inc.  
- Boeing Company  

### Содержание ЛР:  

| Признаки              | Procter & Gamble Company                         | Verizon Communications Inc.             | Citigroup Inc.         | AbbVie Inc.                     | Boeing Company                    |
|:---------------------:|:-------------------------------------:|:---------------------------------------:|:-------------------------------------:|:--------------------------------------:|:--------------------------------:|
| Сайт                  | https://us.pg.com/                | https://www.verizon.com          | https://www.citigroup.com   | https://www.abbvie.com/             | https://www.boeing.com/ |
| IP Netblock           | 104.208.0.0 - 104.215.255.255           | 152.176.0.0 - 152.199.255.255           | 104.106.253.187                         | 52.6.171.167            | 130.76.0.0 - 130.76.255.255                      |
| Местоположение        | Boydton                                    | Ashburn                               | New York                              | Ashburn                                | Bothell                       |
| Телефон               | +1.5139831000                         | +1-800-900-0241                         | +1-631-712-7472                       | +1.8479388258                       | +1-843-641-3770                  |
| E-mail администратора | piregistrar.im@pg.com              | swipper@verizonbusiness.com                       | raymond.i.pena@citi.com                   | internetnameregistrar@abbvie.com                     | mark.w.hunter2@boeing.com         |
| Открытые порты        | 80 443                                | 80 443                                  | 80 443                                | 80 443                                 | 80 443                           |
| Хостинг               | Microsoft Azure |  ANS Communications, Inc | Citicorp Global Information Network | Amazon Technologies Inc. | The Boeing Company                   |
| Веб-технологии        | Google Tag Manager |  Microsoft ASP.NET jQuery Adobe DTM                              |   Bootstrap Font Awesome jQuery                                    | Google Tag Manager jQuery                                       | AddThis jQuery RequireJS |

### Вывод:
Мы научились искать информацию в открытых источниках.
