# DSIS_summer_work

## Введение

### Кратко про датасет

Датасет "Cyber Security Indexes" включает в себя четыре показателя, которые иллюстрируют текущую ситуацию с кибербезопасностью во всем мире. Данные представлены по 193 странам и территориям, сгруппированным по пяти географическим регионам - Африке, Северной Америке, Южной Америке, Европе и Азиатско-Тихоокеанскому региону.

Индекс подверженности кибербезопасности (CEI) определяет уровень подверженности киберпреступности в разбивке по странам от 0 до 1; чем выше оценка, тем выше степень подверженности (предоставлено 10guard). Последний раз показатель обновлялся в 2020 году.

Глобальный индекс кибербезопасности (GCI) – это надежный справочник, который измеряет приверженность стран кибербезопасности на глобальном уровне - для повышения осведомленности о важности и различных аспектах кибербезопасности.

Национальный индекс кибербезопасности (NCSI) измеряет готовность страны противостоять киберугрозам и управлять киберинцидентами. Он состоит из категорий, возможностей и показателей (предоставленных NCSI). Последний раз показатель обновлялся в январе 2023 года.

Уровень цифрового развития (DDL) определяет средний процент, полученный страной от максимального значения обоих индексов (предоставленного NCSI). Последний раз показатель обновлялся в январе 2023 года.

(Добавленный индекс) Индекс сетевой готовности Всемирного экономического форума (NRI) измеряет склонность стран использовать возможности, предоставляемые информационно-коммуникационными технологиями (ИКТ).

## Ход работы

В ходе работы были применены библиотеки pandas, matplotlib и ploty. Была проанализирована выборка "Cyber Security Indexes" в трёх этапах: 1) Анализ выборки. 2) Сравнение показателей. 3) Карты. В первом этапе была проанализирована выборка и её отсутствующие значения. Во втором этапе были сравнения предоставленных данных и ранее полученных графиков. В заключетельном этапе были продемонстрированы карты для наглядности показателей. Также карты были визуализированы в виде png так как, к сожалению, ни github ни nbviewer не поддерживают карты choropleth.

## Заключение

В ходе работы была исследована выборка "Cyber Security Indexes". Были получены и изучены данные об участии регионов в глобальных исследованиях. Также я сравнил различные исследования и, в заключительном этапе, визуализировал данные из самых показательных исследований.
