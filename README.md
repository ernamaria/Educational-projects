
Задание 1. A/B–тестирование

В ходе тестирования одной гипотезы целевой группе была предложена новая механика оплаты услуг на сайте, у контрольной группы оставалась базовая механика. Необходимо проанализировать итоги эксперимента и сделать вывод, стоит ли запускать новую механику оплаты на всех пользователей.

В качестве входных данных Вы имеете 4 csv-файла:    
•	groups.csv - файл с информацией о принадлежности пользователя к контрольной или экспериментальной группе (А – контроль, B – целевая группа)     
•	groups_add.csv - дополнительный файл с пользователями, который вам прислали спустя 2 дня после передачи данных    
•	active_studs.csv - файл с информацией о пользователях, которые зашли на платформу в дни проведения эксперимента.     
•	checks.csv - файл с информацией об оплатах пользователей в дни проведения эксперимента. 

Задание 2. Python

•	Реализуйте функцию, которая будет автоматически подгружать информацию из дополнительного файла groups_add.csv (заголовки могут отличаться) и на основании дополнительных параметров пересчитывать метрики.    
•	Реализуйте функцию, которая будет строить графики по получаемым метрикам.

Задание 3. SQL
Анализ для образовательной платформы. 

Образовательные курсы состоят из различных уроков, каждый из которых состоит из нескольких маленьких заданий. Необходимо написать запрос, который даст информацию о количестве очень усердных студентов* Под усердным студентом мы понимаем студента, который правильно решил 20 задач за текущий месяц.    
Также необходимо в одном запросе выгрузить следующую информацию о группах пользователей:

•	ARPU     
•	ARPAU     
•	CR в покупку     
•	СR активного пользователя в покупку     
•	CR пользователя из активности по математике (subject = ’math’) в покупку курса по математике  

ARPU считается относительно всех пользователей, попавших в группы.    
Активным считается пользователь, за все время решивший больше 10 задач правильно в любых дисциплинах.    
Активным по математике считается пользователь, за все время решивший 2 или больше задач правильно по математике.

