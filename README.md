# Домашнее задание к занятию "`Система мониторинга Zabbix. Часть 2`" - `Дедюрин Денис`
---

## Задание 1

### Создаем свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста:
<img src = "img/t1.png" width = 100%>

### Добавляем элемент данных CPU:
<img src = "img/t2.png" width = 100%>

### Добавляем тэг (Resource Type: CPU):
<img src = "img/t3.png" width = 100%>

### Добавляем элемент данных RAM:
<img src = "img/t4.png" width = 100%>

### Добавляем тэг (Resource Type: RAM):
<img src = "img/t5.png" width = 100%>

---

## Задание 2

### Добавляем созданные агенты и назначаем им необходимые шаблоны:
<img src = "img/h1.png" width = 100%>
<img src = "img/h2.png" width = 100%>
<img src = "img/h3.png" width = 100%>

### Переходим в меню Latest Data, чтобы убедиться, что начали появляться данные с добавленных агентов:
<img src = "img/h4.png" width = 100%>

---

## Задание 3

### При попытке добавления созданного вручную шаблона к хосту у которого присоединен шаблон Linux by Zabbix agent и данный шаблон имеет такой же набор элементов данных, то присоединить свой шаблон мы не сможем, пока не осоединим существующий.
<img src = "img/h5.png" width = 100%>

### Осоединяем шаблон Linux by Zabbix agent и добавляем свой.
<img src = "img/h6.png" width = 100%>

### Проделываем аналогичные операции со вторым хостом.

### Переходим в меню Latest Data, чтобы убедиться, что начали появляться данные с добавленных агентов:
<img src = "img/h7.png" width = 100%>

---

## Задание 4

### Создаем свой дашборд:
<img src = "img/db1.png" width = 100%>

### Добавляем графики для 2 хостов:
<img src = "img/db2.png" width = 100%>