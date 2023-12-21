# mk_23_kr

## Курсовая работа по дисциплине "Микроконтроллеры мехатронных устройств"

### Автор: Гапчич К.

### Тема: "Модуль одометрии на основе датчика Холла для робота-ассистента"

### Используемые интерфейсы
1. RS485 --- интерфейс для связи с ПК;
2. SWD --- интерфейс для подключения программатора МК;
3. SPI --- интерфейс для связи с другими модулями мехатронного комплекса.

### Внешние устройства МК
1. Датчик Холла - подключается к любому цифровому порту и АЦП, данные передаются от датчика к МК;
2. Программатор МК - подключается к МК через интерфейс SWD;
3. Внешний кварцевый резонатор МК - подключается к портам внешнего тактирования МК;
4. ПК - подключается к МК через интерфейс RS485;
5. Другие модули мехатронного комплекса - подключаются к МК через интерфейс SPI.

### Используемое ПО
1. arm-none-eabi-g++ --- кросс-компилятор;
2. make --- система сборки проекта;
3. cmake --- система управления проектом;
4. git --- система контроля версий.
