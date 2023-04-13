``` shell
artur@artur-VirtualBox:~$ cd Kennel/
artur@artur-VirtualBox:~/Kennel$ cat home_animals
cat: home_animals: Нет такого файла или каталога
artur@artur-VirtualBox:~/Kennel$ cat > home_animals
Кошка
собака
хамяяк
лошадь
осел
artur@artur-VirtualBox:~/Kennel$ cat
artur@artur-VirtualBox:~/Kennel$ cat home_animals
Кошка
собака
хамяяк
лошадь
осел 
artur@artur-VirtualBox:~/Kennel$
artur@artur-VirtualBox:~/Kennel$ cat home_animals
Кошка
собака
хамяяк
лошадь
осел вер�
�artur@artur-VirtualBox:~/Kennel$ nano home_animals
artur@artur-VirtualBox:~/Kennel$ cat home_animals
Кошка
собака
хамяяк
лошадь
осел
Верблюд
artur@artur-VirtualBox:~/Kennel$ ll
итого 12
drwxrwxr-x  2 artur artur 4096 апр 13 23:14 ./
drwxr-x--- 23 artur artur 4096 апр 13 23:12 ../
-rw-rw-r--  1 artur artur   76 апр 13 23:14 home_animals
artur@artur-VirtualBox:~/Kennel$ cat > home_animals
Кошки
Собаки
Хомяки
Кошки: команда не найдена
Собаки: команда не найдена
Хомяки: команда не найдена
artur@artur-VirtualBox:~/Kennel$ cat > home_animals
Кошки
Собаки
Хомяки
Кошки: команда не найдена
Собаки: команда не найдена
Хомяки: команда не найдена
artur@artur-VirtualBox:~/Kennel$ cat > home_animals
кошки
собаки
хомякиartur@artur-VirtualBox:~/Kennel$ cat > home_animals
кошки
собаки
хомякиartur@artur-VirtualBox:~/Kennel$ cat home_animals
кошки
собаки
хомякиartur@artur-VirtualBox:~/Kennel$ cat > home_animals
Кошки
собаки
хомяки
artur@artur-VirtualBox:~/Kennel$ cat home_animals
Кошки
с�обаки
хомя�ки
artur@artur-VirtualBox:~/Kennel$ cat > pack_animals
Лошади
Ослы
Верблюды
artur@artur-VirtualBox:~/Kennel$ cat  pack_animals
Лошади
Ослы
Верблюды
artur@artur-VirtualBox:~/Kennel$ ды
ды: команда не найдена
artur@artur-VirtualBox:~/Kennel$ LS
LS: команда не найдена
artur@artur-VirtualBox:~/Kennel$ ;s
-bash: синтаксическая ошибка рядом с неожиданным маркером «;»
artur@artur-VirtualBox:~/Kennel$ ls
home_animals  pack_animals
artur@artur-VirtualBox:~/Kennel$ cat home_animals pack_animals > animals
artur@artur-VirtualBox:~/Kennel$ cat animals
Кошки
с�обаки
хомя�ки
Лошади
Ослы
Верблюды
artur@artur-VirtualBox:~/Kennel$  mv animals mans_friends
artur@artur-VirtualBox:~/Kennel$ ls -ali
итого 20
1228831 drwxrwxr-x  2 artur artur 4096 апр 13 23:23 .
1189347 drwxr-x--- 23 artur artur 4096 апр 13 23:21 ..
1188947 -rw-rw-r--  1 artur artur   40 апр 13 23:19 home_animals
1217924 -rw-rw-r--  1 artur artur   79 апр 13 23:22 mans_friends
1188948 -rw-rw-r--  1 artur artur   39 апр 13 23:20 pack_animals
artur@artur-VirtualBox:~/Kennel$ cd ..
artur@artur-VirtualBox:~$ mkdir Kennel_system
artur@artur-VirtualBox:~$ cd Kennel
artur@artur-VirtualBox:~/Kennel$ ll
итого 20
drwxrwxr-x  2 artur artur 4096 апр 13 23:23 ./
drwxr-x--- 24 artur artur 4096 апр 13 23:25 ../
-rw-rw-r--  1 artur artur   40 апр 13 23:19 home_animals
-rw-rw-r--  1 artur artur   79 апр 13 23:22 mans_friends
-rw-rw-r--  1 artur artur   39 апр 13 23:20 pack_animals
artur@artur-VirtualBox:~/Kennel$ mv animals mans_friends
mv: не удалось выполнить stat для 'animals': Нет такого файла или каталога
artur@artur-VirtualBox:~/Kennel$ mv mans_friends ../Kennel_system
artur@artur-VirtualBox:~/Kennel$ cd ../Kennel_system
artur@artur-VirtualBox:~/Kennel_system$ ll
итого 12
drwxrwxr-x  2 artur artur 4096 апр 13 23:27 ./
drwxr-x--- 24 artur artur 4096 апр 13 23:27 ../
-rw-rw-r--  1 artur artur   79 апр 13 23:22 mans_friends
artur@artur-VirtualBox:~/Kennel_system$ cd /home/artur
artur@artur-VirtualBox:~$ sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb
[sudo] пароль для artur:
--2023-04-13 23:28:14--  https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb
Распознаётся dev.mysql.com (dev.mysql.com)… 184.85.150.139, 2001:2030:21:19e::2e31, 2001:2030:21:1a9::2e31
Подключение к dev.mysql.com (dev.mysql.com)|184.85.150.139|:443... соединение установлено.
HTTP-запрос отправлен. Ожидание ответа… 302 Moved Temporarily
Адрес: https://repo.mysql.com//mysql-apt-config_0.8.23-1_all.deb [переход]
--2023-04-13 23:28:16--  https://repo.mysql.com//mysql-apt-config_0.8.23-1_all.deb
Распознаётся repo.mysql.com (repo.mysql.com)… 104.76.200.230
Подключение к repo.mysql.com (repo.mysql.com)|104.76.200.230|:443... соединение установлено.
HTTP-запрос отправлен. Ожидание ответа… 200 OK
Длина: 18028 (18K) [application/x-debian-package]
Сохранение в: ‘mysql-apt-config_0.8.23-1_all.deb’

mysql-apt-config_0.8.23-1_all.deb       100%[============================================================================>]  17,61K  --.-KB/s    за 0,001s

2023-04-13 23:28:17 (24,2 MB/s) - ‘mysql-apt-config_0.8.23-1_all.deb’ сохранён [18028/18028]

artur@artur-VirtualBox:~$ sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb
Выбор ранее не выбранного пакета mysql-apt-config.
(Чтение базы данных … на данный момент установлено 215850 файлов и каталогов.)
Подготовка к распаковке mysql-apt-config_0.8.23-1_all.deb …
Распаковывается mysql-apt-config (0.8.23-1) …
Настраивается пакет mysql-apt-config (0.8.23-1) …
Warning: apt-key should not be used in scripts (called from postinst maintainerscript of the package mysql-apt-config)
Warning: apt-key is deprecated. Manage keyring files in trusted.gpg.d instead (see apt-key(8)).
OK
artur@artur-VirtualBox:~$ sudo apt update
Сущ:1 http://ru.archive.ubuntu.com/ubuntu jammy InRelease
Пол:2 http://ru.archive.ubuntu.com/ubuntu jammy-updates InRelease [119 kB]
Пол:3 http://security.ubuntu.com/ubuntu jammy-security InRelease [110 kB]
Пол:4 http://ru.archive.ubuntu.com/ubuntu jammy-backports InRelease [108 kB]
Сущ:5 https://download.docker.com/linux/ubuntu focal InRelease
Пол:6 http://ru.archive.ubuntu.com/ubuntu jammy-updates/main i386 Packages [469 kB]
Сущ:7 https://download.docker.com/linux/ubuntu jammy InRelease
Сущ:8 http://nginx.org/packages/mainline/ubuntu jammy InRelease
Пол:9 http://ru.archive.ubuntu.com/ubuntu jammy-updates/main amd64 Packages [993 kB]
Пол:10 http://ru.archive.ubuntu.com/ubuntu jammy-updates/main amd64 DEP-11 Metadata [101 kB]
Пол:11 http://ru.archive.ubuntu.com/ubuntu jammy-updates/universe amd64 DEP-11 Metadata [269 kB]
Пол:12 http://ru.archive.ubuntu.com/ubuntu jammy-updates/universe amd64 c-n-f Metadata [18,6 kB]
Пол:13 http://ru.archive.ubuntu.com/ubuntu jammy-updates/multiverse amd64 DEP-11 Metadata [940 B]
Пол:14 http://ru.archive.ubuntu.com/ubuntu jammy-backports/main amd64 DEP-11 Metadata [7980 B]
Пол:15 http://ru.archive.ubuntu.com/ubuntu jammy-backports/universe amd64 DEP-11 Metadata [12,5 kB]
Пол:16 http://security.ubuntu.com/ubuntu jammy-security/main amd64 DEP-11 Metadata [41,5 kB]
Пол:17 http://repo.mysql.com/apt/ubuntu jammy InRelease [15,2 kB]
Пол:18 http://security.ubuntu.com/ubuntu jammy-security/universe amd64 DEP-11 Metadata [18,5 kB]
Пол:19 http://repo.mysql.com/apt/ubuntu jammy/mysql-8.0 Sources [966 B]
Пол:20 http://repo.mysql.com/apt/ubuntu jammy/mysql-apt-config amd64 Packages [565 B]
Пол:21 http://repo.mysql.com/apt/ubuntu jammy/mysql-apt-config i386 Packages [565 B]
Пол:22 http://repo.mysql.com/apt/ubuntu jammy/mysql-8.0 amd64 Packages [8555 B]
Пол:23 http://repo.mysql.com/apt/ubuntu jammy/mysql-tools amd64 Packages [7905 B]
Пол:24 http://repo.mysql.com/apt/ubuntu jammy/mysql-tools i386 Packages [455 B]
Получено 2304 kB за 4с (520 kB/s)
Чтение списков пакетов… Готово
Построение дерева зависимостей… Готово
Чтение информации о состоянии… Готово
Может быть обновлено 33 пакета. Запустите «apt list --upgradable» для их показа.
W: https://download.docker.com/linux/ubuntu/dists/focal/InRelease: Key is stored in legacy trusted.gpg keyring (/etc/apt/trusted.gpg), see the DEPRECATION section in apt-key(8) for details.
N: Пропускается получение настроенного файла «nginx/binary-i386/Packages», так как репозиторий «http://nginx.org/packages/mainline/ubuntu jammy InRelease» не поддерживает архитектуру «i386»
W: http://repo.mysql.com/apt/ubuntu/dists/jammy/InRelease: Key is stored in legacy trusted.gpg keyring (/etc/apt/trusted.gpg), see the DEPRECATION section in apt-key(8) for details.
artur@artur-VirtualBox:~$ sudo apt-get install mysql-server
Чтение списков пакетов… Готово
Построение дерева зависимостей… Готово
Чтение информации о состоянии… Готово
Следующий пакет устанавливался автоматически и больше не требуется:
docker-scan-plugin
Для его удаления используйте «sudo apt autoremove».
Будут установлены следующие дополнительные пакеты:
libmecab2 mecab-ipadic mecab-ipadic-utf8 mecab-utils mysql-client mysql-common mysql-community-client mysql-community-client-core
mysql-community-client-plugins mysql-community-server mysql-community-server-core
Следующие НОВЫЕ пакеты будут установлены:
libmecab2 mecab-ipadic mecab-ipadic-utf8 mecab-utils mysql-client mysql-common mysql-community-client mysql-community-client-core
mysql-community-client-plugins mysql-community-server mysql-community-server-core mysql-server
Обновлено 0 пакетов, установлено 12 новых пакетов, для удаления отмечено 0 пакетов, и 33 пакетов не обновлено.
Необходимо скачать 38,2 MB архивов.
После данной операции объём занятого дискового пространства возрастёт на 273 MB.
Хотите продолжить? [Д/н] y
Пол:1 http://ru.archive.ubuntu.com/ubuntu jammy/main amd64 libmecab2 amd64 0.996-14build9 [199 kB]
Пол:2 http://repo.mysql.com/apt/ubuntu jammy/mysql-8.0 amd64 mysql-common amd64 8.0.32-1ubuntu22.04 [68,6 kB]
Пол:3 http://ru.archive.ubuntu.com/ubuntu jammy/main amd64 mecab-utils amd64 0.996-14build9 [4850 B]
Пол:4 http://ru.archive.ubuntu.com/ubuntu jammy/main amd64 mecab-ipadic all 2.7.0-20070801+main-3 [6718 kB]
Пол:5 http://repo.mysql.com/apt/ubuntu jammy/mysql-8.0 amd64 mysql-community-client-plugins amd64 8.0.32-1ubuntu22.04 [1437 kB]
Пол:6 http://repo.mysql.com/apt/ubuntu jammy/mysql-8.0 amd64 mysql-community-client-core amd64 8.0.32-1ubuntu22.04 [2184 kB]
Пол:7 http://repo.mysql.com/apt/ubuntu jammy/mysql-8.0 amd64 mysql-community-client amd64 8.0.32-1ubuntu22.04 [2458 kB]
Пол:8 http://ru.archive.ubuntu.com/ubuntu jammy/main amd64 mecab-ipadic-utf8 all 2.7.0-20070801+main-3 [4384 B]
Пол:9 http://repo.mysql.com/apt/ubuntu jammy/mysql-8.0 amd64 mysql-client amd64 8.0.32-1ubuntu22.04 [67,3 kB]
Пол:10 http://repo.mysql.com/apt/ubuntu jammy/mysql-8.0 amd64 mysql-community-server-core amd64 8.0.32-1ubuntu22.04 [25,0 MB]
Пол:11 http://repo.mysql.com/apt/ubuntu jammy/mysql-8.0 amd64 mysql-community-server amd64 8.0.32-1ubuntu22.04 [79,1 kB]
Пол:12 http://repo.mysql.com/apt/ubuntu jammy/mysql-8.0 amd64 mysql-server amd64 8.0.32-1ubuntu22.04 [67,3 kB]
Получено 38,2 MB за 5с (8247 kB/s)
Предварительная настройка пакетов …
Выбор ранее не выбранного пакета mysql-common.
(Чтение базы данных … на данный момент установлено 215855 файлов и каталогов.)
Подготовка к распаковке …/00-mysql-common_8.0.32-1ubuntu22.04_amd64.deb …
Распаковывается mysql-common (8.0.32-1ubuntu22.04) …
Выбор ранее не выбранного пакета mysql-community-client-plugins.
Подготовка к распаковке …/01-mysql-community-client-plugins_8.0.32-1ubuntu22.04_amd64.deb …
Распаковывается mysql-community-client-plugins (8.0.32-1ubuntu22.04) …
Выбор ранее не выбранного пакета mysql-community-client-core.
Подготовка к распаковке …/02-mysql-community-client-core_8.0.32-1ubuntu22.04_amd64.deb …
Распаковывается mysql-community-client-core (8.0.32-1ubuntu22.04) …
Выбор ранее не выбранного пакета mysql-community-client.
Подготовка к распаковке …/03-mysql-community-client_8.0.32-1ubuntu22.04_amd64.deb …
Распаковывается mysql-community-client (8.0.32-1ubuntu22.04) …
Выбор ранее не выбранного пакета mysql-client.
Подготовка к распаковке …/04-mysql-client_8.0.32-1ubuntu22.04_amd64.deb …
Распаковывается mysql-client (8.0.32-1ubuntu22.04) …
Выбор ранее не выбранного пакета libmecab2:amd64.
Подготовка к распаковке …/05-libmecab2_0.996-14build9_amd64.deb …
Распаковывается libmecab2:amd64 (0.996-14build9) …
Выбор ранее не выбранного пакета mysql-community-server-core.
Подготовка к распаковке …/06-mysql-community-server-core_8.0.32-1ubuntu22.04_amd64.deb …
Распаковывается mysql-community-server-core (8.0.32-1ubuntu22.04) …
Выбор ранее не выбранного пакета mysql-community-server.
Подготовка к распаковке …/07-mysql-community-server_8.0.32-1ubuntu22.04_amd64.deb …
Распаковывается mysql-community-server (8.0.32-1ubuntu22.04) …
Выбор ранее не выбранного пакета mecab-utils.
Подготовка к распаковке …/08-mecab-utils_0.996-14build9_amd64.deb …
Распаковывается mecab-utils (0.996-14build9) …
Выбор ранее не выбранного пакета mecab-ipadic.
Подготовка к распаковке …/09-mecab-ipadic_2.7.0-20070801+main-3_all.deb …
Распаковывается mecab-ipadic (2.7.0-20070801+main-3) …
Выбор ранее не выбранного пакета mecab-ipadic-utf8.
Подготовка к распаковке …/10-mecab-ipadic-utf8_2.7.0-20070801+main-3_all.deb …
Распаковывается mecab-ipadic-utf8 (2.7.0-20070801+main-3) …
Выбор ранее не выбранного пакета mysql-server.
Подготовка к распаковке …/11-mysql-server_8.0.32-1ubuntu22.04_amd64.deb …
Распаковывается mysql-server (8.0.32-1ubuntu22.04) …
Настраивается пакет libmecab2:amd64 (0.996-14build9) …
Настраивается пакет mysql-common (8.0.32-1ubuntu22.04) …
update-alternatives: используется /etc/mysql/my.cnf.fallback для предоставления /etc/mysql/my.cnf (my.cnf) в автоматическом режиме
Настраивается пакет mysql-community-server-core (8.0.32-1ubuntu22.04) …
Настраивается пакет mecab-utils (0.996-14build9) …
Настраивается пакет mysql-community-client-plugins (8.0.32-1ubuntu22.04) …
Настраивается пакет mecab-ipadic (2.7.0-20070801+main-3) …
Compiling IPA dictionary for Mecab.  This takes long time...
reading /usr/share/mecab/dic/ipadic/unk.def ... 40
emitting double-array: 100% |###########################################|
/usr/share/mecab/dic/ipadic/model.def is not found. skipped.
reading /usr/share/mecab/dic/ipadic/Noun.name.csv ... 34202
reading /usr/share/mecab/dic/ipadic/Filler.csv ... 19
reading /usr/share/mecab/dic/ipadic/Conjunction.csv ... 171
reading /usr/share/mecab/dic/ipadic/Noun.nai.csv ... 42
reading /usr/share/mecab/dic/ipadic/Auxil.csv ... 199
reading /usr/share/mecab/dic/ipadic/Noun.adjv.csv ... 3328
reading /usr/share/mecab/dic/ipadic/Noun.verbal.csv ... 12146
reading /usr/share/mecab/dic/ipadic/Noun.others.csv ... 151
reading /usr/share/mecab/dic/ipadic/Noun.csv ... 60477
reading /usr/share/mecab/dic/ipadic/Noun.number.csv ... 42
reading /usr/share/mecab/dic/ipadic/Prefix.csv ... 221
reading /usr/share/mecab/dic/ipadic/Suffix.csv ... 1393
reading /usr/share/mecab/dic/ipadic/Noun.adverbal.csv ... 795
reading /usr/share/mecab/dic/ipadic/Others.csv ... 2
reading /usr/share/mecab/dic/ipadic/Adverb.csv ... 3032
reading /usr/share/mecab/dic/ipadic/Interjection.csv ... 252
reading /usr/share/mecab/dic/ipadic/Noun.demonst.csv ... 120
reading /usr/share/mecab/dic/ipadic/Postp.csv ... 146
reading /usr/share/mecab/dic/ipadic/Postp-col.csv ... 91
reading /usr/share/mecab/dic/ipadic/Noun.org.csv ... 16668
reading /usr/share/mecab/dic/ipadic/Verb.csv ... 130750
reading /usr/share/mecab/dic/ipadic/Noun.proper.csv ... 27328
reading /usr/share/mecab/dic/ipadic/Adnominal.csv ... 135
reading /usr/share/mecab/dic/ipadic/Adj.csv ... 27210
reading /usr/share/mecab/dic/ipadic/Noun.place.csv ... 72999
reading /usr/share/mecab/dic/ipadic/Symbol.csv ... 208
emitting double-array: 100% |###########################################|
reading /usr/share/mecab/dic/ipadic/matrix.def ... 1316x1316
emitting matrix      : 100% |###########################################|

done!
update-alternatives: используется /var/lib/mecab/dic/ipadic для предоставления /var/lib/mecab/dic/debian (mecab-dictionary) в автоматическом режиме
Настраивается пакет mysql-community-client-core (8.0.32-1ubuntu22.04) …
Настраивается пакет mecab-ipadic-utf8 (2.7.0-20070801+main-3) …
Compiling IPA dictionary for Mecab.  This takes long time...
reading /usr/share/mecab/dic/ipadic/unk.def ... 40
emitting double-array: 100% |###########################################|
/usr/share/mecab/dic/ipadic/model.def is not found. skipped.
reading /usr/share/mecab/dic/ipadic/Noun.name.csv ... 34202
reading /usr/share/mecab/dic/ipadic/Filler.csv ... 19
reading /usr/share/mecab/dic/ipadic/Conjunction.csv ... 171
reading /usr/share/mecab/dic/ipadic/Noun.nai.csv ... 42
reading /usr/share/mecab/dic/ipadic/Auxil.csv ... 199
reading /usr/share/mecab/dic/ipadic/Noun.adjv.csv ... 3328
reading /usr/share/mecab/dic/ipadic/Noun.verbal.csv ... 12146
reading /usr/share/mecab/dic/ipadic/Noun.others.csv ... 151
reading /usr/share/mecab/dic/ipadic/Noun.csv ... 60477
reading /usr/share/mecab/dic/ipadic/Noun.number.csv ... 42
reading /usr/share/mecab/dic/ipadic/Prefix.csv ... 221
reading /usr/share/mecab/dic/ipadic/Suffix.csv ... 1393
reading /usr/share/mecab/dic/ipadic/Noun.adverbal.csv ... 795
reading /usr/share/mecab/dic/ipadic/Others.csv ... 2
reading /usr/share/mecab/dic/ipadic/Adverb.csv ... 3032
reading /usr/share/mecab/dic/ipadic/Interjection.csv ... 252
reading /usr/share/mecab/dic/ipadic/Noun.demonst.csv ... 120
reading /usr/share/mecab/dic/ipadic/Postp.csv ... 146
reading /usr/share/mecab/dic/ipadic/Postp-col.csv ... 91
reading /usr/share/mecab/dic/ipadic/Noun.org.csv ... 16668
reading /usr/share/mecab/dic/ipadic/Verb.csv ... 130750
reading /usr/share/mecab/dic/ipadic/Noun.proper.csv ... 27328
reading /usr/share/mecab/dic/ipadic/Adnominal.csv ... 135
reading /usr/share/mecab/dic/ipadic/Adj.csv ... 27210
reading /usr/share/mecab/dic/ipadic/Noun.place.csv ... 72999
reading /usr/share/mecab/dic/ipadic/Symbol.csv ... 208
emitting double-array: 100% |###########################################|
reading /usr/share/mecab/dic/ipadic/matrix.def ... 1316x1316
emitting matrix      : 100% |###########################################|

done!
update-alternatives: используется /var/lib/mecab/dic/ipadic-utf8 для предоставления /var/lib/mecab/dic/debian (mecab-dictionary) в автоматическом режиме
Настраивается пакет mysql-community-client (8.0.32-1ubuntu22.04) …
Настраивается пакет mysql-client (8.0.32-1ubuntu22.04) …
Настраивается пакет mysql-community-server (8.0.32-1ubuntu22.04) …
update-alternatives: используется /etc/mysql/mysql.cnf для предоставления /etc/mysql/my.cnf (my.cnf) в автоматическом режиме
Created symlink /etc/systemd/system/multi-user.target.wants/mysql.service → /lib/systemd/system/mysql.service.
Настраивается пакет mysql-server (8.0.32-1ubuntu22.04) …
Обрабатываются триггеры для man-db (2.10.2-1) …
Обрабатываются триггеры для libc-bin (2.35-0ubuntu3.1) …
artur@artur-VirtualBox:~$ sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb
--2023-04-13 23:32:29--  https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb
Распознаётся download.docker.com (download.docker.com)… 13.32.121.35, 13.32.121.78, 13.32.121.111, ...
Подключение к download.docker.com (download.docker.com)|13.32.121.35|:443... соединение установлено.
HTTP-запрос отправлен. Ожидание ответа… 200 OK
Длина: 40955778 (39M) [binary/octet-stream]
Сохранение в: ‘docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb’

docker-ce-cli_20.10.13~3-0~ubuntu-jammy 100%[============================================================================>]  39,06M  7,18MB/s    за 4,6s

2023-04-13 23:32:34 (8,53 MB/s) - ‘docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb’ сохранён [40955778/40955778]

artur@artur-VirtualBox:~$ sudo dpkg -i docker-ce-cli_20.10.133-0ubuntu-jammy_amd64.deb
dpkg: ошибка: нет доступа к архиву «docker-ce-cli_20.10.133-0ubuntu-jammy_amd64.deb»: Нет такого файла или каталога
artur@artur-VirtualBox:~$ sudo dpkg -i docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb
dpkg: предупреждение: снижение версии docker-ce-cli с 5:23.0.3-1~ubuntu.22.04~jammy до 5:20.10.13~3-0~ubuntu-jammy
dpkg: проблемы с зависимостями не позволяют удалить пакет docker-ce-cli:
docker-ce зависит от docker-ce-cli.

dpkg: ошибка при обработке пакета docker-ce-cli (--remove):
проблемы с зависимостями — не удаляется
При обработке следующих пакетов произошли ошибки:
docker-ce-cli
artur@artur-VirtualBox:~$ sudo apt remove docker-ce-cli
Чтение списков пакетов… Готово
Построение дерева зависимостей… Готово
Чтение информации о состоянии… Готово
Следующие пакеты устанавливались автоматически и больше не требуются:
docker-ce-rootless-extras docker-scan-plugin libslirp0 pigz slirp4netns
Для их удаления используйте «sudo apt autoremove».
Следующие пакеты будут УДАЛЕНЫ:
docker-ce docker-ce-cli
Обновлено 0 пакетов, установлено 0 новых пакетов, для удаления отмечено 2 пакетов, и 33 пакетов не обновлено.
После данной операции объём занятого дискового пространства уменьшится на 264 MB.
Хотите продолжить? [Д/н] y
Прервано.
artur@artur-VirtualBox:~$ sudo apt remove docker-ce-cli
Чтение списков пакетов… Готово
Построение дерева зависимостей… Готово
Чтение информации о состоянии… Готово
Следующие пакеты устанавливались автоматически и больше не требуются:
docker-ce-rootless-extras docker-scan-plugin libslirp0 pigz slirp4netns
Для их удаления используйте «sudo apt autoremove».
Следующие пакеты будут УДАЛЕНЫ:
docker-ce docker-ce-cli
Обновлено 0 пакетов, установлено 0 новых пакетов, для удаления отмечено 2 пакетов, и 33 пакетов не обновлено.
После данной операции объём занятого дискового пространства уменьшится на 264 MB.
Хотите продолжить? [Д/н] y
(Чтение базы данных … на данный момент установлено 216198 файлов и каталогов.)
Удаляется docker-ce (5:23.0.3-1~ubuntu.22.04~jammy) …
Warning: Stopping docker.service, but it can still be activated by:
docker.socket
Удаляется docker-ce-cli (5:20.10.13~3-0~ubuntu-jammy) …
Обрабатываются триггеры для man-db (2.10.2-1) …
artur@artur-VirtualBox:~$ sudo dpkg -r docker-ce-cli
dpkg: предупреждение: игнорируется запрос на удаление неустановленного пакета docker-ce-cli
artur@artur-VirtualBox:~$ sudo dpkg -i docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb
Выбор ранее не выбранного пакета docker-ce-cli.
(Чтение базы данных … на данный момент установлено 215995 файлов и каталогов.)
Подготовка к распаковке docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb …
Распаковывается docker-ce-cli (5:20.10.13~3-0~ubuntu-jammy) …
Заменено файлами из установленного пакета docker-buildx-plugin (0.10.4-1~ubuntu.22.04~jammy) …
Настраивается пакет docker-ce-cli (5:20.10.13~3-0~ubuntu-jammy) …
Обрабатываются триггеры для man-db (2.10.2-1) …
artur@artur-VirtualBox:~$ sudo dpkg -r docker-ce-cli
(Чтение базы данных … на данный момент установлено 216190 файлов и каталогов.)
Удаляется docker-ce-cli (5:20.10.13~3-0~ubuntu-jammy) …
Обрабатываются триггеры для man-db (2.10.2-1) …
artur@artur-VirtualBox:~$
``` 