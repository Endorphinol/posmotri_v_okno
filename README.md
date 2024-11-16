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