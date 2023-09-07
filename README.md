Итоговая контрольная работа по основному блоку Урок 1. Контрольная работа Данная работа необходима для проверки ваших знаний и навыков по итогу прохождения первого блока обучения на программе Разработчик. Мы должны убедится, что базовое знакомство с IT прошло успешно.

Задача алгоритмически не самая сложная, однако для полноценного выполнения проверочной работы необходимо:

Создать репозиторий на GitHub
Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)
Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
Написать программу, решающую поставленную задачу
Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)
Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры: [“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”] [“1234”, “1567”, “-2”, “computer science”] → [“-2”] [“Russia”, “Denmark”, “Kazan”] → []

Создание репозитория в GitHub.

Создание проэкта

В терминале VSC командой был создан проект на C#.

В терминале VSC командой был создан локальный репозиторий проекта.

Cоздание блок-схемы решения задачи Kontr

Написание кода на C#

После каждого шага выполнялась отправка промежуточных коммитов в удаленный репозиторий командами

2.git add 3.git commit 3.git push

5.Описана функция CreateArray() для создания исходного массива с получением данных от пользователя. 6.Описана функция ShowArray() для вывода массива в консоль. 7.Описана функция ResultArray() по блок-схеме, которая непосредственно выполняет поставленную задачу. 8.Описание вызова функций. 7.Тестирование на премерах и дополнительных данных.
