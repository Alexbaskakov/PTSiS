# ПТСиС
____________________________________
## Lab2
К лабораторной #2 для теста скорости можно использовать утилиту Bandwidth test
[ссылка на статью с использованием утилиты](https://www.mikc.ru/document/statii/izmerenie_propusknoy_sposobnosti_s_pomoshchyu_bandwidth_test/)
Саму утилиту можно скачать на сайте [mikrotik.com](mikrotik.com) в разделе software

Добавить клиента L2TP в Windows по аналогии с первой лабораторной, подключиться к настроенному серверу.

Проверку скорости проводить на неподключенном VPN, с подключением SSTP и с подключением L2TP, в итоге должно получиться 3 параметра скоростей передачи данных.


Вопросы к отчету лаб2:
 - Назовите основные различия протоколов туннелирования PPTP и SSTP (алгоритмы шифрования, скорость передачи данных и т.д.)
 - Приведите описание кадра L2TP, его основных полей
 - Приведите пример процесса установления соединения L2TP (какие сообщения отправляются, что требуется для установления соединения)
 - Почему в предыдущей лабораторной работе требовалось вручную импортировать сертификат в Windows, в чем опасность самоподписанных сертификатов?
 - Какой адрес выдается клиенту при подключении к VPN серверу?
 - Назовите основные сферы применения VPN соединений, для какого типа подойтет соединение SSTP, L2TP?
______________________________________
## Lab3
К лабораторной #3

- Включить в отчет конфигурацию клиента (аналогично как в лабораторной №2)
- Проанализировать таблицу снижения скорости передачи данных с использованием VPN ([ссылка](https://mikrotik.wiki/wiki/VPN:%D0%A2%D0%B5%D1%81%D1%82_%D1%81%D0%BA%D0%BE%D1%80%D0%BE%D1%81%D1%82%D0%B8_%D0%BF%D0%B5%D1%80%D0%B5%D0%B4%D0%B0%D1%87%D0%B8_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85_%D0%BF%D1%80%D0%B8_VPN))
- Почему разные протоколы имеют разную скорость передачи данных, от чего она зависит?
- В чем основное отличие настройки клиентов VPN для лабораторных #2 и #3? 
- Что дает подход установления частного защищенного соединения именно между маршрутизаторами?
- С какой целью в лабораторной производится настройка межсетевого экрана?

______________________________________
## Темы докладов:

2023:
 - 1 Промышленные протоколы связи, применение, достоинства и недостатки, стандарты промышленных сетей связи. Проводные решения сетей связи в области Интернета Вещей.
 - 2 Технологии и протоколы мобильной связи. Первое и второе поколение мобильной связи. Устройство сети оператора. Основные технологические решения второго поколения сети связи, элементы ядра сети и их функции.
 - 3 Третье поколение мобильных сетей связи (см. п. 2)
 - 4 Четвертое поколение мобильных сетей связи (см. п. 2)
 - 5 Пятое поколение мобильных сетей связи (см. п. 2)
 - 6 Протоколы и технологии SDN. Коммутаторы P4, Openflow. Алгоритмы работы SDN
 - 7 Основы передачи голоса по пакетным сетям связи. Сигнализация SIP. Промышленные решения (SIP, VoIP и т.д.). Структура IP АТС (программная, free switch, turn\coturn составляющая и другие)
 - 8 Технологии беспроводной передачи данных в Интернете Вещей, SigFox, LoraWAN, Lora, маквил, zigbee и др.
 - 9 Структуированные кабельные сети
 - 10 Multicast routing
 - 11 QoS

______________________________________

- 1.Протоколы маршрутизации BGP, eBGP
- 2.Протокол маршрутизации OSPF
- 3.Технологий EnIP
- 4.Технология наложенных сетей VxLAN
- 5.Технология EVPN
- 6.**Протокол QUIC**
- 7.Протокол VPLS
- 8.Особенности построения сетей ЦОД
- 9.Технология SD-WAN
- 10.Технологии повышения пропускной способности в 4/5G
- 11.Цепочки NAT в ядре Linux (Mikrotik)
- 12.Адресное пространство IPv6
- 13.**Протокол Yggdrasil, I2P**
- 14.Сети CDN
- 15.Технология EoIP
- 16.Сегментация сетей: DMZ, APP, BD
- 17.**WPA2/3, Radius**
- 18.Сети ZigBee
- 19.Наложенные сети TRILL, FabricPath
- 20.Наложенные сети OTV, LISP
- Mikrotik RouterOS ВМ: https://disk.yandex.ru/d/OriUM7JZPjxnNw
