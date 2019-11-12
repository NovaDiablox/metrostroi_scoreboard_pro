# Metrostroi Scoreboard Pro

**Created by:** Alexell

**Website:** https://alexell.ru/
 
![Metrostroi Scoreboard Pro](http://metrostroi.alexell.ru/images/metrostroi_scoreboard_pro.jpg)

**Описание:**

Продвинутая таблица с игроками, разработанная специально для серверов Метростроя. Scoreboard написан с нуля, но из SUI Scoreboard v2.6 (PolarWolf Edit) были позаимствованы некоторые части кода и внешний вид строк игроков.

**Возможности:**
* Локализация (RU, EN)
* Поддержка мониторов шириной от 1280px
* Кастомизация цветов
* Отображается общее число игроков и вагонов на сервере
* Отображается время клиента и время сервера
* Отображаются номера маршрута для всех существующих составов, включая 81-717.6
* Отображается кол-во вагонов игроков
* Отображается тип состава
* Отображается путь, текущая станция или перегон (с указанием предыдущей и следующей станции) для каждого состава
* Для отображения часов в аддон встроен Utime

**Необходимые аддоны:**

* Metrostroi
* ULib

**Установка на сервер:**
* Удалить из коллекции сервера [этот](https://steamcommunity.com/sharedfiles/filedetails/?id=1835844389) или любой другой Scoreboard, который есть в коллекции
* Удалить с сервера **utime**, если имеется
* Добавить в коллекцию сервера [Metrostroi Scoreboard Pro](https://steamcommunity.com/sharedfiles/filedetails/?id=1910844812)

## Примечания
Для определения местоположения составов используются системы Метростроя. Для правильного отображения путей и станций требуются корректные **треки** на картах, а также правильно расставленные **gmod_track_platform**. Если на какой-либо карте у вас неверно отображаются пути или станции, попробуйте найти причину, проверив треки и gmod_track_platform на карте. Затем, либо исправьте сами, либо напишите автору карты, укажите на ошибки и попросите исправить.

На станциях всегда отображается путь и название станции. В перегонах между станциями всегда отображается путь, название предыдущей станции и название слудующей станции.
В случае, когда нужная информация из треков и платформ не получена, для определения местоположения состава используются точки из **Metrostroi.StationConfigurations**. В случаях, когда местопложение не найдено всеми способами, отображается **N/A**.

**N/A** всегда будет отображаться на парковых путях, в перегоне из депо на главные пути, при движении из тупика на стацию. Это нормально.
