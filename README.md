![Header](https://github.com/5eafear/celestial_server/blob/main/img/Group%201.png)

![Header](https://github.com/5eafear/celestial_server/blob/main/img/Group%202.png)
# Тутор по настройке
## Как  запустить сервер?
## Скачиваем все содержимое этого репозитория, распоковываем и открываем файл run.bat и тада локальный сервер готов 127.0.0.1:25565
### server.properties
```properties
server-port=25565
# Порт который будет после локального ip 127.0.0.1:XXXXX
```
```properties
online-mode=false
# значение true - Вход только для лицензирванных игроков
# значение false - Вход для всех
```
```properties
view-distance=10
# Если у вас включенно 32 чанка, а видете только 5-10, тосмело можете ставить значение больше
# ВАЖНО! СЕРВЕР МОЖЕТ ЛАГАТЬ!
```
```properties
spawn-protection=0
# Делает приват на точке возрождения
```



## CustomF3Brand
### config.json
```js
{
  "_comment1": "You can set your brand message. This can be an array of made of a single string to make it static or can be a list of",
  "_comment2": "strings to create an animation or make it change with a specified period.",
  "_comment3": "These strings can contain Chat color codes (Hexadecimal values are not supported) and can contain tags that will be replaced",
  "_comment4": "automatically by the plugin; these tags are:",
  "_comment5": "{name} - replaced with the player's name",
  "_comment6": "{displayname} - replaced with te player's display name",
  "_comment7": "{server} - replaced with the name of player's the server (ONLY BUNGEECORD)",
  "_comment8": "{spigot} - replaced with the spigot one (ONLY BUNGEECORD)",
  "_comment9": "Any placeholder by PlaceholderAPI (ONLY SPIGOT)",
  "f3_brand": [
    "&6Мое Ядро", # Указанное названия ядра
  ],
  "update_period": 50
# Частота обновления в тиках
}
```

## AutoMessage
### config.yml
```yml
timer: 2300 # Оюновления в секундах
Random: false 
UseTellRawMessages: false
Messages:
- '&eКонч инатофф используй ! чтобы написать в глобал чат'
TellRawMessages:
- '{"text":"[Get more info on TellRaws here: minecraft.tools/en/tellraw.php ]","color":"dark_purple"}'
- '{"text":"[This is a test message!] ","color":"aqua"}'
- '["",{"text":"Click me to open URL!","color":"red","bold":true,"underlined":false,"clickEvent":{"action":"open_url","value":"https://www.google.com"}}]'
- '{"text":"Hover over me for help text!","color":"yellow","bold":true,"hoverEvent":{"action":"show_text","value":{"text":"","extra":[{"text":"I
  am a hint!","color":"yellow","bold":true}]}}}'
- '{"text":"Click me to run help command!","color":"yellow","bold":true,"clickEvent":{"action":"run_command","value":"/help"}}'
```
## MOTD
### config.yml
```yml
# This is the server motd.
Server-MOTD:
  Line-1: '&b&l                Celestial'
  Line-2: '&e&lНаш сайт &fmc-celestial.teafear.by'

# The motd of the player when they join in.
JoinGame-MOTD:
  Enabled: true
  # Check forum for placeholders.
  # Supported for PlaceholderAPI placeholders.
  Messages:
  - '&eДобро пожаловать на сервер.'

# Server icon.
Custom-Server-Icon:
  # Set to true will load image from motd folder.
  Enabled: false
  # Make sure it's 64 x 64 pixels with png format.
  Image: server-icon.png

# The maximum players of the server.
Server-Maximum-Players:
  Modify: true
  Maximum-Players: 228
```
## TAB
### config.yml
```yml
header-footer:
  enabled: true
  header:
  - <#f0f8ff>&m                                                </#FFFF00> # Ввеху черта грандиент зависит от цвета (html цвет)
  - '&b&lCelestian'
  - '&7Игроков: &f%online%👥'
# Можно дополнить или написать что то свое
  - ''
  footer:
  - '&7Пинг:&2 %ping% &7Тпс:&2 %tps%'  // пинг тпс
  - ''
  - <#f0f8ff>&m                                                </#FFFF00> # Снизучерта грандиент зависит от цвета (html цвет)
```
## server.properties
```properties
online-mode=false # значение true - вход только для лицензий
spawn-protection=0 # защита спавна( поставил на 0 потому что а нахуй надо
```
### Написал 5eafear 03.12.2023 / 3.00
### Последние измененеие 11.12.2023 / 3.42

