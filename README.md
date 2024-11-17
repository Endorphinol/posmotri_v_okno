# Посмотри в Окно  
[Ссылка на репозиторий](https://github.com/Endorphinol/posmotri_v_okno "Ссылка на репозиторий")   
## Произведена стилизация проекта с помощью CSS по заговленному ранее коду:  
1. Не произведено *не единой* манипуляции с HTML.
2. Поочередно добавлялись файлы стилей в обход (DOM) для простоты восприятия по инструкции.
3. Осуществлена **стилизация** в соответствии с шаблоном.

### Ревьюеру: Спасибо заранее ваш разбор и указание на точки роста, надеюсь у меня все получиться, и я не наделал много ошибок. Делал самостоятельно, подсказки с чата старался не брать. Хорошего вам дня или вечера, надеюсь разбор для вас не будет утомительным.

# Исправление 1  

## Было исправлено:  
1. Скорректированы блоки на оснований Pixel Perfect.
2. Максимально расставлены наследования для шрифтов. 
3. Поставлен CurrentColor в необходимых местах. 
4. Приняты ко вниманию принципы "Каскада".
5. Расставлены запасные шрифты "sans-serif" в случае отстутствия загрузки основного с сервера.
6. Установлены обрезания для текста не вместившегося в блок с многоточием (text-overflow).
7. Установлен перманентныый стиль для селектора content__card-link_current.
8. Установлены интерактивные элементы focus / focus-visible / active для селектора .content__card-link.
9. Удалены дубликаты селекторов, проведена дополнительная проверка.  

# Исправление 2  

## Было исправлено:  
1. Добавлено активное состояние для всех ссылок с карточками.
2. Убрано ограничение по высоте для блока с поиском, установлена минимальная высота (min-height), вместо фиксированной.
3. Установлен шрифт Oswald для блока с карточками.
4. Исправлено отображение через Pixel Perfect. Не была установлена минимальная высота и ширифа в селекторе .content для установления размеров для обоих вариантов экранов (при ошибке поиске карточки, и в стандартом режиме).

# Исправление 3  

## Было исправлено:
1. Убран параметр высоты в блоке навигации.
2. Добавлена опция подчеркивания для блока карточек по наведению мыши. 
3. Скорректированы более точно размеры через Pixel Perfect.

# Исправление 4 

## Было исправлено:  
1. Удалено применение фона при наведений курсора мыши на блок с карточками.
