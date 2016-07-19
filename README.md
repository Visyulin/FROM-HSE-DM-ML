# Программа "Машинное обучение и майнинг данных"
Программа помогает получить базовые компетенции аналитика данных, среди которых адекватный выбор метода для решения конкретной задачи анализа данных, предобработка данных, настройка параметров метода анализа и интерпретация полученных результатов.  В ходе обучения слушатели также знакомятся с программными продуктами Weka, Orange и библиотекой scikit-learn. Содержание программы охватывает основные устоявшиеся разделы современного машинного обучения (Machine Learning) и майнинга данных (Data Mining).
Теоретический материал подкрепляется большим количеством практических занятий. 
Итоговая аттестация проводится в форме защиты проекта по анализу реальных данных.

## Основные темы программы
- Введение в машинное обучение и разработку данных
- Свободно-распространяемые системы машинного обучения и разработки данных
- Методы классификации
- Методы регрессии
- Отбор признаков и снижение размерности
- Работа с выбросами и пропущенными значениями
- Методы кластеризации
- Поиск признаковых зависимостей и частых множеств
- Масштабируемое машинное обучение и анализ больших наборов данных с Apache Spark

## Преподаватели
#### Юрий Кашницкий
Преподаватель факультета компьютерных наук НИУ ВШЭ, научный сотрудник  Международной научно-учебной лаборатории интеллектуальных систем и структурного анализа.  Имеет публикации, представленные на семинарах топовых конференций по искусственному интеллекту (IJCAI и ECAI) и машинному обучению (ECML/PKDD). Преподаватель языка Python и машинного обучения в MLClass. В прошлом — разработчик Hadoop, бизнес-аналитик и Java-программист РДТЕХ.

#### Дмитрий Игнатов
Кандидат технических наук, преподаватель факультета компьютерных наук НИУ ВШЭ, доцент Департамента анализа данных и искусственного интеллекта, научный сотрудник Международной научно-учебной лаборатории интеллектуальных систем и структурного анализа.  Проходил обучение по PhD программе в Техническом университете Дрездена (Германия) в рамках гранта DAAD.

# Инструкция по установке виртуальной машины
В курсе используется сборка библиотек Anaconda, тетрадки Jupyter, Apache Spark и некоторые другие библиотеки.
Все это можно разом установить на виртуальной машине (требования - около 4 Гб места на диске, 4 Гб RAM) по следующией инструкции:
- Установите [VirtualBox](https://www.virtualbox.org/wiki/Download_Old_Builds_4_3) версии 4.3
- Установите [Vagrant](https://www.vagrantup.com/downloads.html)
- Скачайте материалы текущего репозитория (как архив либо командой git clone)
- Перейдите в терминале (в случае Windows открывайте терминал как администратор - Shift + правая кнопка) в скачанный каталог ML_DM_HSE (cd <путь к ML_DM_HSE>)
- Выполните команду sudo vagrant up (в случае Windows просто vagrant up). Ее выполнение займет примерно полчаса
- Выполните команду sudo vagrant reload
- Перейдите в браузере по адресу localhost:4545
- По окочании работы с виртуальной машиной выполните sudo vagrant halt
