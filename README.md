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
  - <#f0f8ff>&m                                                </#FFFF00> # Снизу черта грандиент зависит от цвета (html цвет)
```

### Написал 5eafear 03.12.2023 / 3.00
### Последние измененеие 11.12.2023 / 3.42

