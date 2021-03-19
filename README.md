# База данных автомобилей JSON, CSV
**cars.json** - бесплатная база данных марок и моделей легковых автомобилей с https://auto.ru/cars/all/  
**cars.csv** - версия в формате таблицы |Марка|Модель|  
[Демо базы](https://blanzh.github.io/carsBase/)

_База обновляется_
## База 1. Расширенная база CSV, JSON
Полная база автомобилей с auto.ru Марка -> Модель
Коммерческий и мото транспорт с обновлением   
для получения свяжитесь со мной в телеграме https://t.me/gulpsun или по почте gulpsun@gmail.com  
с пометкой "Коммерческий и мото транспорт"

### Обновление от 19.03.2021
|#|name|id|group|
|---|---|---|---|
|1|[Легковой](https://auto.ru/cars/all/) (278)|`cars`|`cars`|
|2|[Сельскохозяйственный](https://auto.ru/agricultural/all/) (180)|`agricultural`|`commercial`|
|3|[Седельный тягач](https://auto.ru/artic/all/) (58)|`artic`|`commercial`|
|4|[Автопогрузчик](https://auto.ru/autoloader/all/) (219)|`autoloader`|`commercial`|
|5|[Бульдозер](https://auto.ru/bulldozers/all/) (43)|`bulldozers`|`commercial`|
|6|[Автобус](https://auto.ru/bus/all/) (105)|`bus`|`commercial`|
|7|[Строительная](https://auto.ru/construction/all/) (262)|`construction`|`commercial`|
|8|[Автокран](https://auto.ru/crane/all/) (63)|`crane`|`commercial`|
|9|[Экскаватор](https://auto.ru/dredge/all/) (127)|`dredge`|`commercial`|
|10|[Легкий коммерческий](https://auto.ru/lcv/all/) (87)|`lcv`|`commercial`|
|11|[Коммунальная](https://auto.ru/municipal/all/) (135)|`municipal`|`commercial`|
|12|[Съемный кузов](https://auto.ru/swap_body/all/) (14)|`swap_body`|`commercial`|
|13|[Прицеп](https://auto.ru/trailer/all/) (718)|`trailer`|`commercial`|
|14|[Грузовик](https://auto.ru/truck/all/) (102)|`truck`|`commercial`|
|15|[Мотовездеход](https://auto.ru/atv/all/) (231)|`atv`|`moto`|
|16|[Мотоцикл](https://auto.ru/motorcycle/all/) (284)|`motorcycle`|`moto`|
|17|[Скутер](https://auto.ru/scooters/all/) (130)|`scooters`|`moto`|
|18|[Снегоход](https://auto.ru/snowmobile/all/) (54)|`snowmobile`|`moto`|

Всего марок: **3090**  
Всего моделей: **16482**


[Демо полной базы](https://blanzh.github.io/carsBase/demo_private.zip)  
_В этой базе данные представлены для ознакомления со структурой_

## База 2. Расширенная база легковых автомобилей CSV, XLSX
Также имеется база автомобилей (https://auto.ru/catalog/cars/)  
Марка -> Модель -> Название поколения и/или годы выпуска -> Кузов -> Модификация (Объем дв., коробка передач, мощность, топливо, название комплектации, id)

где id соответствует фотографии автомобиля (Например: **30822185a.jpg**) 1280x852px. Архив с фотографиями ~1.5Гб

Отрывок таблицы:

|mark|model|generation-name|generation-years|body|specification-type|specification-power|fuel|equipment|id|
|---|---|---|---|---|---|---|---|---|---|
|BMW|2000 C/CS|I|1965 – 1970|Купе|2.0 MT|101 л.c.|бензин|-|6150861af|
|BMW|2000 C/CS|I|1965 – 1970|Купе|2.0 MT|122 л.c.|бензин|-|6150861af|
|BMW|3 серии|VII (G2x)|2018 – н.в.|Седан|2.0 AT|156 л.c.|бензин|318i SE|343b7122e|
|BMW|3 серии|VII (G2x)|2018 – н.в.|Седан|2.0 AT|184 л.c.|бензин|320i|343b7122e|
|BMW|3 серии|VII (G2x)|2018 – н.в.|Седан|2.0 AT|184 л.c. 4x4|бензин|320i xDrive|343b7122e|
|BMW|3 серии|VII (G2x)|2018 – н.в.|Седан|2.0 AT|184 л.c.|бензин|320i Sport Line|343b7122e|
|BMW|3 серии|VII (G2x)|2018 – н.в.|Седан|2.0 AT|184 л.c. 4x4|бензин|320i xDrive M Sport Pure|343b7122e|
|BMW|3 серии|VII (G2x)|2018 – н.в.|Седан|2.0 AT|184 л.c. 4x4|бензин|320i xDrive M Sport Pro|343b7122e|
|BMW|3 серии|VII (G2x)|2018 – н.в.|Седан|2.0 AT|258 л.c.|бензин|330i Dark Shadow SE|343b7122e|

Всего модификаций: **72106**  
Всего фотографий: **9903**

![Автомобильная база скачать CSV](https://blanzh.github.io/carsBase/cars.jpg)

Для получения свяжитесь со мной в телеграме https://t.me/gulpsun или по почте gulpsun@gmail.com  
с пометкой "Расширенная база легковых автомобилей"
