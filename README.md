# Сгенерируйте конфиг Cloudflare WARP для AmneziaWG
Этот bash скрипт сгенерирует конфиг Cloudflare WARP для AmneziaWG.

Не стоит выполнять его локально, так как РКН заблокировал запросы для получения конфига. Вместо этого лучше выполнять на удалённых серверах.

1. Заходим на https://terminator.aeza.net/en/
2. Выбираем **Debian**
3. Вставляем команду:
```bash
bash <(wget -qO- https://raw.githubusercontent.com/lap-does-things/bash-warp-generator/main/warp_generator.sh)
```
Эта вилка была сделана <br />
а) для redundancy от оригинального источника на случай приколов РКН <br />
б) для поигрулек с самим скриптом, когда-нибудь я обязательно допилю что-нибудь кайфовое <br />
