PiCalculator
Описание
PiCalculator — это интерактивный Python-скрипт, который вычисляет число π с заданной пользователем точностью с использованием библиотеки mpmath. Пользователь может ввести количество знаков после запятой, до которого требуется вычислить π. Эта программа полезна для демонстрации чисел с высокой точностью и изучения работы библиотек для вычислений с плавающей точкой.

Функциональные возможности
Интерактивный ввод для задания количества знаков после запятой.
Поддержка вычислений с использованием библиотеки mpmath для высокой точности.
Возможность выхода из программы, введя 0.
Установка
Для работы скрипта необходимо иметь установленный Python 3 и библиотеку mpmath. Вы можете установить библиотеку, выполнив следующую команду в терминале:


pip install mpmath
Если у вас установлено несколько версий Python, используйте:


pip3 install mpmath
Использование
Скачайте или клонируйте репозиторий на ваш локальный компьютер.
Откройте терминал и перейдите в директорию проекта.


python pi_calculator.py
Ввод данных
После запуска скрипта, программа будет запрашивать у вас количество знаков после запятой для числа π:

Введите положительное целое число для получения π с заданной точностью.
Введите 0, чтобы выйти из программы.
Программа будет обрабатывать неверный ввод и предлагать повторный ввод.