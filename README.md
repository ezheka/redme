# Документация Jungle: Dangerous Romance
Мобильная игра Jungle: Dangerous Romance разработана на игровом движке [Unity 2019.4](https://unity.com) с использованием расширения [Naninovel](https://naninovel.com). Это расширение представляет из себя инструмент, облегчающий создание и разработку игр в жанре интерактивных историй.

## Начало работы
Перед началом работы нужно установить Unity 2019.4 через Unity Hub и загрузить сам проект с GitHub

## Сценарии
Инструкции по основным командам для сценариев - [тут](https://naninovel.com/ru/guide/naninovel-scripts.html#%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D0%B8%D0%B8-naninovel)

Для сценариев было использовано расширение Spreadsheet. Инструкция по его использованию - [тут](https://naninovel.com/ru/guide/spreadsheet.html#usage)     
Все таблицы храняться в [Assets->Resources->Spreadsheet](https://github.com/senomegames/Jungle-2022-naninovel/tree/main/Assets/Resources/Spreadsheet)     

Для редактирования сценария нужно открыть интересующую главу в программе Excel, внести правки и сохранить таблицу. После чего произвести импорт, как указано в инструкции.

## Персонажи
Персонажи выполнены с помощью [послойных персонажей от Nani](https://naninovel.com/ru/guide/characters.html#%D0%BF%D0%BE%D1%81n%D0%BE%D0%B9%D0%BD%D1%8B%D0%B5-%D0%BF%D0%B5%D1%80%D1%81%D0%BE%D0%BD%D0%B0%D0%B6%D0%B8)

Персонажи храняться в [Assets->Characters](https://github.com/senomegames/Jungle-2022-naninovel/tree/main/Assets/Characters)   

Инструкцию по их насройке и испольщаванию можно найти по [ссылке](https://naninovel.com/ru/guide/characters.html#%D0%BF%D0%BE%D1%81n%D0%BE%D0%B9%D0%BD%D1%8B%D0%B5-%D0%BF%D0%B5%D1%80%D1%81%D0%BE%D0%BD%D0%B0%D0%B6%D0%B8)

## Фоны
В проекте используется два вида фонов:
- [Cпрайтовые](https://naninovel.com/ru/guide/backgrounds.html#%D1%81%D0%BF%D1%80%D0%B0%D0%B9%D1%82%D0%BE%D0%B2%D1%8B%D0%B5-%D1%84%D0%BE%D0%BD%D1%8B)
- [Видео-фоны](https://naninovel.com/ru/guide/backgrounds.html#%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%84%D0%BE%D0%BD%D1%8B)

Подробную инструкцию можно найти по [ссылке](https://naninovel.com/ru/guide/backgrounds.html#%D1%84%D0%BE%D0%BD%D1%8B)

Фона храняться в [Assets->Sprites->Backgrounds](https://github.com/senomegames/Jungle-2022-naninovel/tree/main/Assets/Sprites/Backgrounds) и [Assets->Videos](https://github.com/senomegames/Jungle-2022-naninovel/tree/main/Assets/Videos)

## Аудио и Озвучивание
Для вставки аудио и озвучки были также использваны стандарнтые команды от Nani. Инструкция по [Аудио](https://naninovel.com/ru/guide/audio.html#%D0%B0%D1%83%D0%B4%D0%B8%D0%BE) и по [Озвучивание](https://naninovel.com/ru/guide/voicing.html#%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B5-%D0%BE%D0%B7%D0%B2%D1%83%D1%87%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)

Аудио храняться в [Assets->Audio](https://github.com/senomegames/Jungle-2022-naninovel/tree/main/Assets/Audio)  
Озвучка храниться в [Assets->Resources->Naninovel->Voice](https://github.com/senomegames/Jungle-2022-naninovel/tree/main/Assets/Resources/Naninovel/Voice)

## Пользовательский интерфейс
Для пользовательского интерфейса было использоваано решение [пользовательского UI от Naninovel](https://naninovel.com/ru/guide/user-interface.html#%D0%BA%D0%B0%D1%81%D1%82%D0%BE%D0%BC%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F-ui)

Префабы UI храняться в [Assets->Prefabs->UI](https://github.com/senomegames/Jungle-2022-naninovel/tree/main/Assets/Prefabs/UI)     
Спрайты для UI в [Assets->Sprites](https://github.com/senomegames/Jungle-2022-naninovel/tree/main/Assets/Sprites)

Инструкция по настройке интерфейса по [ссылке](https://naninovel.com/ru/guide/user-interface.html#%D0%BA%D0%B0%D1%81%D1%82%D0%BE%D0%BC%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F-ui)

## Локализация
Локализация для сценариев хранится в таблице со сценарием. Локализация для мини-игр и меню храница в [Assets->Resources->Naninovel->Text](https://github.com/senomegames/Jungle-2022-naninovel/tree/main/Assets/Resources/Naninovel/Text)

Инструкция по [ссылке](https://naninovel.com/ru/guide/localization.html#%D0%BB%D0%BE%D0%BA%D0%B0n%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F)

## Архитектруа
Архитектура проекта строится на Naninovel. [Подробнее](https://naninovel.com/ru/guide/localization.html#%D0%BB%D0%BE%D0%BA%D0%B0n%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F)
