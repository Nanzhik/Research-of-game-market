# Прогноз продаж компьютерных игр

[ipynb](https://github.com/Nanzhik/Research-of-game-market/blob/main/Research-of-game-market.ipynb)

## Описание проекта

**Заказчик:** интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры.

**Исходные данные:** из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation).

**Задача:** выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

## Навыки и инструменты

* **python**
* **pandas**
* **numpy**
* **seaborn**
* **matplotlib**
* scipy.**stats**

## Вывод

В ходе исследования определили зависимости, влияющие на количество проданных копий игр и получили следующие результаты:
* посчитали, что в среднем платформа существует около 8 лет;
* определили самые популярные жанры в разрезе суммарных продаж среди всех пользователей: для Северной Америки это **Shooter**, для Европы - **Action**, для Японии - **Role-Playing**;
* выяснили, что на продажи игр оценки критиков влияют, а оценки пользователей - нет;
* определили на играх каких платформ стоит делать акцент при прогнозе продаж на 2017 год - **PS4**, **XOne**, **3DS**;
* определили самые популярные платформы и жанры по разным регионам. Тем самым составили портрет пользователя каждого региона;
* вяснили, что самые продаваемые игры в категории возрастный ограничений с рейтингом ESRB - **E** (для взрослых), а также игры **без рейтинга**;
* проверили гипотезы, что пользовательские оценки платформ Xbox One и PC совпадают, а в жанрах Action и Sports - отличаются.

**Рекомендации интернет-магазину по продаже компьютерных игр:**  
* при прогнозе продаж на 2017 год необходимо учитывать игры только актуальных платформ и делать акцент на более новых платформах;
* учитывать, что рынок Японии значительно отличается от Европейского и Североамериканского;
* стоит учесть, что даже у самых перспективных платформ продажи с каждым годом становятся все меньше и меньше, что говорит об общем падении рынка игровой индустрии.
