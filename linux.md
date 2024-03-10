## Part 1. Установка ОС
>* Версия Ubuntu после установки

![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux1-1.png)

## Part 2. Создание пользователя
>* Создаем пользователя

![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux2-1.png)

>* Вывод списка пользователей

![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux2-2.png)

## Part 3. Настройка ОС

>* Новое имя машины

![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux3-1.png)

>* Установка временной зоны

![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux3-2.png)

>* Вывод информации о сетевых интерфейсах

![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux3-4.png)

__lo (loopback device)__ - виртуальный интерфейс, присутствующий по умолчанию в любом linux. Он используется для отладки сетевых программ и запуска серверных приложений на локальной машине. С этим интерфейсом всегда связан адрес 127.0.0.1. У него есть dns-имя - localhost.

>* Удаление старого и получение нового ip от dhcp сервера

![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux3-5.png)

__DHCP - Dynamic Host Configuration Protocol__

>* Внешний IP адрес
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux3-6.png)

>* IP-адрес шлюза, он же ip-адрес по умолчанию
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux3-7.png)

>* Изменение файла /etc/netplan/*.yaml
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux3-8.png)

>* Пропинговка удальеных хостов 1.1.1.1 и ya.ru
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux3-9.png) 

## Part 4. Обновление ОС

>* Обновление системных пакетов
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux4-1.png)

## Part 5. Использование команды sudo

* __sudo__ - позваляет временно поднимать привелегии и выполнять задачи администрирования системы с максимальными правами.

>* Добавление пользователя в группу с привелегиями sudo, переключение на этого пользователя и смена hostname
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux5-1.png)

## Part 6. Установка и настройка  службы времени

>* Вывод команды с корректным временем
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux6-1.png)

## Part 7. Установка и использование текстовых редакторов

>* VIM для сохранения и выхода нажал ESC и прописал :wq и имя документа
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux7-1.png)

>* NANO Для сохранения нажал ^O ввел имя файла и подтвердил. Вышел через ^X
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux7-2.png)

>* JOE Для сохранения и выхода нажал ^KX, ввел имя файла и подтвердил
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux7-3.png)

>* VIM Для выхода без сохранения ESC -> :q! -> ENTER
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux7-4.png)

>* NANO Для выхода без сохранения нажал ^X -> N
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux7-5.png)

>* JOE Для выхода без сохранения нажал ^C -> y
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux7-6.png)

>* VIM Для поиска :/что ищем
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux7-7.png)

>* VIM Для замены :s/что заменить /чем заменить
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux7-8.png)

>* NANO Для поиска :^W-> что ищем
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux7-9.png)

>* NANO Для замены :^\ -> что заменить -> чем заменить ->Y
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux7-10.png)

>* JOE Для поиска ^K F -> что ищем -> I
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux7-11.png)

>* JOE Для замены ^K F -> что заменить R -> чем Y
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux7-12.png)

## Part 8. Установка и базовая настройка сервиса SSHD

* установка openssh-server и настройка конфигурации
* sudo systemicl start sshd
* sudo systemicl start sshd
* отображение наличия процесса
__ps__ - выводит сведения о процессах в статическом виде
__-e__ - позволяет выбрать все процессы
__| grep sshd__ - пойск по выводу через пайп

![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux8-1.png)

* reboot
* netstat -tan
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux8-2.png)

__-tan:__
__-a__ - показывает состаяние всех сокетов, обычно сокеты используемые серверными процессами не показываются 
__-n__ - показывает сетевые адреса как числа. netstat показывает адреса как символы
__-t__ отображает TCP подключения
__Proto__ - содержит тип протокола
__Recv-Q__ - счетчик байтов не скопированных программой пользователя из этого сокета
__Send-Q__ - счетчик байтов не подтвержденных удаленным узлом
__Local Addres__ - адрес и номер порта локального конца сокета
__Foreign Addres__ - адрес и номер порта удаленного конца сокета 
__State__ - состояние сокета
__LISTEN__ - сокет ожидает входящих подключений
__SYS_SENT__ - сокет находящийся в режиме активной попытки установки подключения
__0.0.0.0__ - немаршрутизированный адрес IPv4, который используется в качестве адреса по умолчанию или адреса пользователя

 ## Part 9. Установка и использование утилит top, htop

 * Uptime 9 min
 * 1 user
 * Load average 0.00, 0.01, 0.00
 * Task: 123 total
 * %CPU: 0.1 us, 0.0 sy, 0.0 ni, 99.9 id, 0.0 wa, 0.0 hi, 0.0 si, 0.0 st
 * MIB Mem: 7957.3 total, 7099.0 free, 230.4 used, 627.9 buff/cache
 * PID 1411
 >* htop сортровка по PID
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux9-1.png)

 >* htop  сортровка по PERCENT_CPU
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux9-2.png)

 >* htop сортировка по PERCENT_MEM
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux9-3.png)

 >* htop сортировка по TIME
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux9-4.png)

 >*htop фильтр по процесу sshd
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux9-5.png)

 >* htop пойск процесса syslog
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux9-6.png)

 >* htop с добавлением выводом hostname, clock и uptime
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux9-8.png)

 ## Part 10. Использование утилиты fdisk

 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux10-1.png)

 ## Part 11. Использование утилиты df

 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux11-1.png)

 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux11-2.png)

 ## Part 12. Использование утилиты du
 >* du:
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux12-1.png)

 >* /home
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux12-2.png)

 >* /var
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux12-3.png)

 >*/var/log
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux12-4.png)

 ## Part 13. Установка и использование утилиты ncdu

 >* /home
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux13-1.png)

 >* /var
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux13-2.png)

 >* /var/log
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux13-3.png)

 ## Part 14. Работа с системными журналами

 >* Последняя авторизация
 ![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux14-1.png)

## Part 15. Использование планировщика заданий CRON

>* Создание задачи в cron
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux15-2.png))

>* uptime каждые 2 минуты
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux15-1.png)

>* удаление всех задач
![Image alt](https://repos.21-school.ru/students/D01_Linux.ID_356272/kenyaqui_student.21_school.ru/D01_Linux-1/-/blob/develop/src/images/linux15-3.png)
