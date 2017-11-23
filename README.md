# hackathon_neuro

(1) В папке с проектом выполнить `mkfifo fifo`

(2) Сначала запускаем скрипт чтения из буфера `hackathon_R.py`

(3) Далее, запускаем основной скрипт записи данных с ЭЭГ `hackathon_W_three chanel.py` (`hackathon_W_one chanel.py` - старый режим с одним каналом

(4) Результат можно видеть на графике: http://neuro-console-ws-client.eu-gb.mybluemix.net/
В качестве websocket-сервера указываем `ws://node-ws-server-neuro.eu-gb.mybluemix.net/`
