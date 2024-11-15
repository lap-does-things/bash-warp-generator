# Сгенерируйте конфиг Cloudflare WARP для AmneziaWG [![Codacy Badge](https://app.codacy.com/project/badge/Grade/9a8ec5c64ec445fb9fcd0ba7e04b7145)](https://app.codacy.com/gh/lap-does-things/bash-warp-generator/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
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
