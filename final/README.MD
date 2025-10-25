# Курс Специализация Data Science Дипломный проект. Бриф учебного кейса 
## «Модель прогнозирования стоимости жилья для агентства недвижимости»

<img src="foto.png" alt="alt text" width="200"/>
## Оглавление
[1. Описание проекта](https://github.com/dushaelena1319/data_science/blob/main/final/README.md#Описание-проекта)

[2. Краткая информация о данных](https://github.com/dushaelena1319/data_science/blob/main/final/README.md#Краткая-информация-о-данных)

[3. Этапы работы над проектом](https://github.com/dushaelena1319/data_science/blob/main/final/README.md#Этапы-работы-над-проектом)

[4. Результаты](https://github.com/dushaelena1319/data_science/blob/main/final/README.md#Результаты)

[5. Выводы](https://github.com/dushaelena1319/data_science/blob/main/final/README.md#Выводы)  

### Описание проекта
Cоздать модель, которая позволит предсказывать стоимость жилья по характеристикам.

### Краткая информация о данных

## Описание данных:
* 'status' — статус продажи;
* 'private pool' и 'PrivatePool' — наличие собственного бассейна;
* 'propertyType' — тип объекта недвижимости;
* 'street' — адрес объекта;
* 'baths' — количество ванных комнат;
* 'homeFacts' — сведения о строительстве объекта (содержит несколько
типов сведений, влияющих на оценку объекта);
* 'fireplace' — наличие камина;
* 'city' — город;
* 'schools' — сведения о школах в районе;
* 'sqft' — площадь в футах;
* 'zipcode' — почтовый индекс;
* 'beds' — количество спален;
* 'state' — штат;
* 'stories' — количество этажей;
* 'mls-id' и 'MlsId' — идентификатор MLS (Multiple Listing Service, система
мультилистинга);
* target' — цена объекта недвижимости (целевой признак, который
необходимо спрогнозировать).

Набор данных - ***data.csv***, набор данных (размер более 100mb - разместила на гугл диск) https://drive.google.com/file/d/1qv5WIlhX3Jov9OO4QGgziAy7h-SIZNMA/view?usp=sharing

промежуточные датасеты: cleaned_data https://drive.google.com/file/d/1BLR4-ECcTtyMSNSOBG9Ny6MnuMhExFzT/view?usp=sharing
финальный датасет: data_model https://drive.google.com/file/d/1E5MVKlRcAbJebIwQFS4Tp_c6EAGrLD2u/view?usp=sharing

### Этапы работы над проектом
- Ознакомление с описанием задачи;
- Знакомство с данными;
- Импортирование необходимых библиотек;
- Обработка данных;
- Написание функций, тестирование модедей;
- Проверка соответствия написанного кода стандарту PEP8;
- Оформление проекта;
- Загрузка проекта на GitHub.

### Результаты:

Проект c корректным выполнением кейса (https://github.com/dushaelena1319/data_science/blob/main/final/Diplom1.ipynb)
(https://github.com/dushaelena1319/data_science/blob/main/final/Diplom2.ipynb)
(https://github.com/dushaelena1319/data_science/blob/main/final/Diplom3.ipynb)
(https://github.com/dushaelena1319/data_science/blob/main/final/Diplom4.ipynb)

### Выводы
Датасет очищен от мусора, дубликатов, пропущенных значений и выбросов
Созданы новые переменные
Произведен отбор признаков различными методами
Обработаны и отнормированы признаки
Применены разные модели, выбрана оптимальная
Подгружена обученная модель CatBoostRegressor
Проведен тест на воспроизводимость
Написана функция для предсказания стоимости квартиры по входным параметрам
Расписана инструкция по созданию и запуску контейнера

:arrow_up:[к оглавлению](https://github.com/dushaelena1319/data_science/blob/main/final/README.md#Оглавление)