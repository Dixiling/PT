## Итоговая контрольная работа по блоку специализация

### Информация о проекте
Необходимо организовать систему учета для питомника в котором живут домашние и Pack animals

### Операционные системы и виртуализация (Linux)

1. Используя команду cat в терминале операционной системы Linux, создать два файла Домашние животные 
(заполнив файл собаками, кошками, хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и ослами, а затем объединить их.
Просмотреть содержимое созданного файла. Переименовать файл, дав ему новое имя (Друзья человека).
![Quest1.JPG](image/Quest1.JPG)

2. Создать директорию, переместить файл туда.
![Quest2.JPG](image/Quest2.JPG)

3. Подключить дополнительный репозиторий MySQL. Установить любой пакет
из этого репозитория.
![Quest3.JPG](image/Quest3.JPG)

4. Установить и удалить deb-пакет с помощью dpkg.
![Quest4.JPG](image/Quest4.JPG)

5. Выложить историю команд в терминале ubuntu
![bash_history.JPG](image/Quest5.JPG)

6. Нарисовать диаграмму, в которой есть класс родительский класс, домашние
животные и вьючные животные, в составы которых в случае домашних
животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные
войдут: Лошади, верблюды и ослы.
![animal.drawio.png](animal.drawio.png)

7. В подключенном MySQL репозитории создать базу данных “Друзья человека”.
![Quest7.JPG](image/Quest7.PNG)

8. Создать таблицы с иерархией из диаграммы в БД.

9. Заполнить низкоуровневые таблицы именами(животных), командами которые они выполняют и датами рождения.
![Quest8,9.JPG](image/Quest8,9.PNG)

10. Удалив из таблицы верблюдов, т.к. верблюдов решили перевезти в другой питомник на зимовку.
Объединить таблицы лошади, и ослы в одну таблицу.
![Quest10.JPG](image/Quest10.PNG)

11. Создать новую таблицу “молодые животные” в которую попадут все животные старше 1 года, 
но младше 3 лет и в отдельном столбце с точностью до месяца подсчитать возраст животных в новой таблице.
![Quest11.JPG](image/Quest11.PNG)

12. Объединить все таблицы в одну, при этом сохраняя поля, указывающие на прошлую принадлежность к старым таблицам.
![Quest12.JPG](image/Quest12.PNG)

13. Создать класс с Инкапсуляцией методов и наследованием по диаграмме.

14. Написать программу, имитирующую работу реестра домашних животных. В программе должен быть реализован следующий функционал:
+ Завести новое животное
+ Определять животное в правильный класс
+ Увидеть список команд, которое выполняет животное
+ Обучить животное новым командам
+ Реализовать навигацию по меню 
+ Создайте класс Счетчик, у которого есть метод add(), увеличивающий значение внутренней int переменной на 1 при нажатие “Завести новое животное” 
Сделайте так, чтобы с объектом такого типа можно было работать в блоке try-with-resources.
Нужно бросить исключение, если работа с объектом типа счетчик была не в ресурсном try и/или ресурс остался открыт.
Значение считать в ресурсе try, если при заведения животного заполнены все поля.