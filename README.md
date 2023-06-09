Виртуальные машины: виртуальные компьютеры на физических компьютерах

Виртуальная машина (часто сокращается до ВМ) мало чем отличается от физических компьютеров — ноутбука, смартфона или сервера. У нее есть ЦП, память, диски для хранения файлов и возможность подключения к Интернету. Компоненты вашего компьютера (аппаратная часть) материальны и осязаемы, тогда как виртуальные машины часто рассматриваются как виртуальные или программно-определяемые компьютеры в физических серверах, существующие только в виде кода.

Как работает виртуальная машина?

Виртуализация — это процесс создания программной, или "виртуальной" версии компьютера с выделенными ресурсами ЦП, памяти и хранилища, которые "заимствуются" у физического компьютера (например, персонального компьютера) и (или) удаленного сервера, например сервера в центре обработки данных поставщика облачных служб. Виртуальная машина — это компьютерный файл (обычно его называют образом), который действует как обычный компьютер. Она может работать в окне в качестве отдельной вычислительной среды (часто для запуска другой операционной системы) или даже как целая система, как это часто реализуется на рабочем компьютере, которым пользуются несколько человек. Виртуальная машина отделена от остальной части системы, то есть программное обеспечение виртуальной машины не может вмешиваться в работу операционной системы главного компьютера.

Для чего используются виртуальные машины?

Ниже приведено несколько примеров использования виртуальных машин:
- Создание и развертывание приложений в облаке.
- Тестирование новых операционных систем, в том числе бета-версий.
- Развертывание новой среды, чтобы упростить и ускорить выполнение сценариев разработки и тестирования для разработчиков.
- Резервное копирование существующей ОС.
- Доступ к зараженным вирусом данным или выполнение старого приложения путем установки старой версии ОС.
- Запуск программного обеспечения или приложений в операционных системах, для которых они изначально не предназначались.

Преимущества виртуальных машин

Хотя виртуальные машины работают как отдельные компьютеры с отдельными операционными системами и приложениями, главное их преимущество в том, что они совершенно не зависят друг от друга и от физического компьютера, на котором размещены. Специальный программный компонент, который называется гипервизором или диспетчером виртуальных машин, позволяет одновременно запускать разные операционные системы на разных виртуальных машинах. Благодаря этому можно запускать виртуальные машины Linux, например, в ОС Windows или запускать более раннюю версию Windows на более поздней.

А поскольку виртуальные машины не зависят от друг друга, они чрезвычайно портативны. Вы можете практически мгновенно перемещать виртуальные машины с одного гипервизора на другой гипервизор на другом компьютере.
Такая гибкость и портативность виртуальных машин предоставляет множество преимуществ. Вот некоторые из них:

- Экономия — благодаря запуску нескольких виртуальных сред с помощью одного компонента инфраструктуры вы можете существенно сократить размер физической инфраструктуры. А это в итоге увеличивает прибыль, так как сокращается число эксплуатируемых серверов и расходы на обслуживание и электроэнергию.
- Гибкость и скорость — запустить виртуальную машину быстрее и намного проще, чем выполнять подготовку новой среды для разработчиков. Виртуализация значительно ускоряет выполнение сценариев разработки и тестирования.
- Снижение времени простоев — виртуальные машины очень портативны и легко перемещаются с одного гипервизора в другой на другом компьютере. Это означает, что они отлично подходят для резервного копирования на тот случай, если узел внезапно прекратит работу.
- Масштабируемость — виртуальные машины позволяют упростить масштабирование приложений. Вам всего лишь нужно добавить дополнительные физические или виртуальные серверы для распределения рабочей нагрузки между несколькими виртуальными машинами. В результате это повышает доступность и производительность приложений.
- Преимущества безопасности — так как виртуальные машины работают в нескольких операционных системах, использование гостевой операционной системы на виртуальной машине позволяет запускать приложения с недостаточным уровнем безопасности и защитить операционную систему узла. Кроме того, виртуальные машины обеспечивают более качественную экспертизу безопасности и часто используются для безопасного изучения компьютерных вирусов (изолируя вирусы и не допуская заражения основного компьютера).






Что такое гипервизор?

монито́р виртуа́льных маши́н (в компьютерах), низкоуровневая оболочка

Гипервизор — это процесс (программа или апаратная схема), который отделяет операционную систему компьютера и приложения от базового физического оборудования. Обычно представляет собой программное обеспечение, хотя создаются и встроенные гипервизоры, например, для мобильных устройств.

Гипервизор является движущей силой концепции работы VPS и виртуализации, позволяя физическому хост-компьютеру управлять несколькими виртуальными машинами в качестве гостевых ОС, что в свою очередь помогает максимально эффективно использовать вычислительные ресурсы, такие как память, пропускная способность сети и количество циклов процессора.

Гипервизор сам по себе в некотором роде является минимальной операционной системой (микроядром или наноядром). Он предоставляет запущенным под его управлением операционным системам службу виртуальной машины, виртуализируя или эмулируя реальное (физическое) аппаратное обеспечение конкретной машины. И управляет этими виртуальными машинами выделением и освобождением ресурсов для них. Гипервизор позволяет независимое «включение», перезагрузку, «выключение» любой из виртуальных машин с той или иной ОС. При этом операционная система, работающая в виртуальной машине под управлением гипервизора, может, но не обязана «знать», что она выполняется в виртуальной машине, а не на реальном аппаратном обеспечении.

Вопросы:
1) Если устанавливать несколько ВМ, как распределяется мощность процессора?


DEBIAN
Debian — это одна из самых популярных и распространенных операционных систем Linux (GNU). Дистрибутив разработан по принципу свободного ПО с открытым исходным кодом. Debian является универсальной операционной системой, поскольку подходит как для повседневного использования, так и для специфической работы на серверах. Она оказала значительное влияние на развитие подобного типа ОС.





AppArmor
AppArmor — эффективная и простая в использовании система безопасности приложений Linux. AppArmor активно защищает операционную систему и приложения от внешних и внутренних угроз, даже атак нулевого дня, обеспечивая надлежащее поведение и предотвращая использование как известных, так и неизвестных уязвимостей приложений.
Так же, как и SELinux AppArmor является реализацией системы Mandatory Access Control (MAC), основанной на архитектуре Linux Security Modules (LSM). Модель безопасности Apparmor заключается в привязке атрибутов контроля доступа не к пользователям, а к программам. AppArmor обеспечивает изоляцию с помощью профилей, загружаемых в ядро, как правило, при загрузке.

AppArmor отличается от остальных реализаций MAC в Linux принципом действия на основе путей, еще он позволяет смешивать профили принудительного исполнения и режима предупреждений. Кроме того AppArmor использует вложенные файлы для облегчения разработки и имеет гораздо более пологий барьер для входа, чем тот же SELinux.

Система безопасности Mandatory Access Control (MAC) предполагает централизованный контроль над правилами политики доступа, при котором рядовые пользователи не имеют возможность вносить в них какие-либо изменения. Разработчик политики определяет, какие программы или процессы могут выполнять определенные действия с системными ресурсами. MAC фокусируется в большей степени на программах, нежели на пользователях и решает задачу разграничения доступа процессов к ресурсам ОС.
В сущности дизайн MAC старается копировать разграничение привилегий доступа к документации в физическом мире. Если некий сотрудник имеет права читать документы с грифом «совершенно секретно», то к стандартным конфиденциальным и внутренним документам он тоже имеет доступ. Обратное однако не верно. То же самое имеет место в контексте привилегий доступа процессов ОС в архитектуре MAC. Так, если программа может читать файл /etc/sudoers, то доступ к /etc/hosts у нее тоже имеется, но обратное также неверно.

В последних строках указаны режимы enforce и complain. Что вкратце из себя представляют эти режимы?

В режиме Enforce ядро гарантирует соблюдение правил, записанных в файле профиля. Нарушения не допускаются и соответствующая запись попадает в логи.
В режиме Complain AppArmor лишь регистрирует нарушения, не блокируя при этом сами действия.




SSH
Нередко на Debian приходится настраивать SSH-сервер. SSH (от англ. secure shell ― безопасная оболочка) ― это защищённый сетевой протокол для удалённого управления сервером через интернет.. Протокол работает по принципу взаимодействия двух сторон — клиента и сервера. Он требует аутентификации сторон одним из способов: по IP-адресу, по паролю или с помощью ключевой пары. Secure Shell по умолчанию проводит соединения по порту 22.

Существуют две версии протокола SSH. Первая (SSH-1) появилась в 1995 году — в то время широко использовались Telnet и FTP. Их главным недостатком была уязвимость соединения, поэтому SSH-подключение заинтересовало пользователей. Однако первая версия протокола SSH-1 имела много технических недоработок. Через год появилась, более безопасная вторая версия протокола — SSH-2. Именно она в 2006 году была признана стандартным протоколом в интернете.
SSH — это протокол прикладного уровня. SSH-сервер обычно прослушивает соединения на TCP-порту 22.
Протокол SSH предназначен для:

- передачи данных (почта, видео, изображения и другие файлы) через защищённое соединение,
- удалённого запуска программ и выполнения команд на сервере через командную строку,
- сжатия файлов для удобной передачи данных,
- переадресации портов и передачи шифрованного трафика между портами разных машин.

SSH-соединение состоит из 2-х компонентов: SSH-сервер и SSH-клиент. Что такое SSH-сервер? Это программа, которая устанавливает связь и производит аутентификацию с устройством пользователя. Он установлен на самом сервере. SSH-клиент используется для входа на удалённую машину и передачи ей команд. Он устанавливается на устройстве, с которого пользователь хочет подключиться к серверу. Бесплатный вариант клиента и сервера — OpenSSH. В операционных системах Unix клиент для OpenSSH установлен по умолчанию.

Подключение проходит в 3 этапа:

- Установка TCP-соединения. TCP — протокол управления передачей данных. С его помощью удалённый сервер и пользователь могут обмениваться данными.
- Открытие защищённого канала. Исходя из настроек соединения обе стороны обмениваются информацией о способе шифрования и сжатия данных.
- Аутентификация пользователя. Она происходит при помощи открытого ключа. У сервера и клиента есть публичный и частный ключ. Публичный ключ доступен любому. Частный известен только владельцу. Любой может зашифровать сообщение публичным ключом, но расшифровать его можно только частным. Клиент посылает имя пользователя и свой публичный ключ. У сервера есть список пользователей, которые могут подключаться к нему. Он проверяет полученный ключ по своему списку. Если клиент в списке, то сервер генерирует случайное число, шифрует клиента публичным ключом и отправляет его устройству. Клиент расшифровывает число и отправляет его обратно. Если всё расшифровано верно, то происходит успешная аутентификация.

После этих 3-х шагов устройство пользователя может передавать команды, получать или отправлять файлы.

Протокол SSH по умолчанию работает по порту 22. Несмотря на высокую защиту протокола, использование стандартного порта значительно повышает риск взлома сервера. Например, это можно сделать при помощи brute-force (атака полным перебором). Порт 22 — открытый, поэтому злоумышленнику нужно только подобрать логин и пароль к серверу. Это сложно, но возможно. Чтобы максимально ограничить доступ к серверу для злоумышленников, можно сменить SSH-порты.





Брандмауэр UFW
Правильно функционирующий брандмауэр является одним из наиболее важных аспектов общей безопасности системы Linux. По умолчанию дистрибутив Debian и Ubuntu поставляется с инструментом настройки брандмауэра под названием UFW (Uncomplicated Firewall), который является самым популярным и простым в использовании инструментом командной строки для настройки и управления брандмауэром в дистрибутивах Ubuntu и Debian.
Брандмауэр — это защитный экран между глобальным интернетом и локальной компьютерной сетью организации. Он выполняет функцию проверки и фильтрации данных, поступающих из интернета. В зависимости от настроек брандмауэр может пропустить их или заблокировать (например, если обнаружит «червей», вирусы и хакерскую атаку).

Нужно различать сетевой брандмауэр (или, по-другому, сетевой экран) и брандмауэр, встроенный в операционную систему Windows. В первом случае решение устанавливается на границе (физической или логической) компьютерной инфраструктуры организации и защищает все ПК, подключенные к локальной сети. Это может быть как программное, так и программно-аппаратное решение. Во втором случае это программа, работающая для защиты отдельно взятого компьютера пользователя.
Брандмауэр — это лишь одна из опций универсального шлюза безопасности, который включает в себя целый ряд функций.
Термин происходит от английского слова «firewall», что означает противопожарную стену, которая препятствует распространению огня и смягчает воздействие
на человека.
В сетевой безопасности файрвол — это система на основе программного или аппаратного обеспечения, которая является своеобразным посредником между безопасными и непроверенными сетями, а также их частями. Главная функция брандмауэра — фильтрация вредоносного и потенциально опасного контента и соединений.

Файрвол сетевого уровня выполняет функцию защиты внутренних систем, которые состоят из нескольких устройств или подсетей. Он работает
на сетевом аппаратном обеспечении и поэтому соответствует потребностям предприятий любого размера.
Файрвол на основе хоста запускается непосредственно на рабочих станциях пользователей и поэтому оказывает более персонализированные правила фильтрации.
Большинство операционных систем обеспечивают собственный файрвол
на основе хоста с базовыми функциональными возможностями.

Как работает брандмауэр?
Существует несколько типов брандмауэров с различными видами фильтрации трафика. Брандмауэр первого поколения работает как пакетный фильтр, сравнивая основную информацию, такую как оригинальный источник, назначение пакета, используемый порт или протокол, с определенным перечнем правил.
Второе поколение брандмауэра содержит еще один параметр для установки фильтра — состояние соединения. На основе этой информации технология может отслеживать данные о начале соединения и текущие соединения.
Брандмауэры третьего поколения построены для фильтрации информации с помощью всех уровней модели OSI, в частности и прикладного уровня. Они распознают программы и некоторые широко распространенные протоколы такие как FTP и HTTP. На основе этой информации брандмауэр может обнаруживать атаки, которые пытаются обойти его через разрешенный порт или несанкционированное использование протокола.
Новые файрволы все еще принадлежат к третьему поколению, однако их часто называют «следующим поколением» или NGFW. Данный вид объединяет все ранее использованные подходы с углубленным осмотром отфильтрованного контента и его сравнение с базой данных для выявления потенциально опасного трафика.

Установка UFW Firewall на Ubuntu и Debian
UFW (Uncomplicated Firewall) обычно установлен по умолчанию в Ubuntu и Debian, если нет, установите его с помощью диспетчера пакетов APT, используя следующую команду:
$ sudo apt install ufw

Проверка брандмауэра UFW
$ sudo ufw status verbose

При первой установке брандмауэр UFW отключен по умолчанию.

Включение брандмауэр UFW
$ sudo ufw enable

Чтобы отключить брандмауэр UFW, используйте следующую команду:
$ sudo ufw disable

Политика безопасности для UFW
По умолчанию брандмауэр UFW отклоняет все входящие соединения и разрешает только исходящие подключения к серверу. Это означает, что никто не может получить доступ к вашему серверу, если только вы специально не открываете порт, а все запущенные службы или приложения на вашем сервере могут иметь доступ к внешней сети.

Политики брандмауэра UFW находится в файле /etc/default/ufw и могут быть изменены с помощью следующей команды.

$ sudo ufw default deny incoming
$ sudo ufw default allow outgoing

как закрыть порты:
https://blog.sedicomm.com/2018/07/06/kak-nastroit-brandmauer-ufw-na-ubuntu-i-debian/

Проверка открытых портов 
lsof -nP -iTCP -sTCP:LISTEN

как удалить порты
https://www.cyberciti.biz/faq/how-to-delete-a-ufw-firewall-rule-on-ubuntu-debian-linux/


SUDO
sudo (англ. Substitute User and do, дословно «подменить пользователя и выполнить»)  — программа для системного администрирования UNIX-систем, позволяющая делегировать те или иные привилегированные ресурсы пользователям с ведением протокола работы. Основная идея — дать пользователям как можно меньше прав, при этом достаточных для решения поставленных задач. Программа поставляется для большинства UNIX и UNIX-подобных операционных систем.

Имя команды означает substitute user do или super user do. Утилита позволяет запускать программы от имени другого пользователя, но чаще всего от имени корневого. Утилита была разработана еще в 1980 году Бобом Когшелом и Клиффом Спенсером. За это время сменилось много разработчиков и было добавлено много функций.

Работает sudo благодаря флагу доступа SUID. Если этот флаг установлен для программы, то она выполняется не от имени того пользователя который ее запустил, а от имени владельца, учитывая что файл sudo принадлежит, то утилита выполняется от имени root. Затем она читает свои настройки, запрашивает пароль пользователя и решает можно ли ему разрешать выполнение команд от имени администратора. Если да, то выполняется переданная в параметре команда.

Команда sudo предоставляет возможность пользователям выполнять команды от имени суперпользователя root, либо других пользователей. Правила, используемые sudo для принятия решения о предоставлении доступа, находятся в файле /etc/sudoers (для редактирования файла можно использовать специальный редактор visudo, запускаемый из командной строки без параметров, в том числе без указания пути к файлу); язык их написания и примеры использования подробно изложены в man sudoers(5).

В большинстве случаев грамотная настройка sudo делает небезопасную работу от имени суперпользователя ненужной. Все действия оказываются выполнимы из-под аккаунта пользователя, которому разрешено использовать sudo без ограничений. Имеется возможность запрещать и разрешать определённым пользователям или группам выполнение конкретного набора программ, а также разрешить выполнение определённых программ без необходимости ввода своего пароля.

Простейший и самый распространённый вариант запуска команд с sudo:
sudo КОМАНДА

Краткая инструкция по настройке прав sudo для пользователей в ОС Debian GNU/Linux 11.

Для начала необходимо установить пакет sudo
apt install sudo

После этого добавляем пользователя в группу sudo
usermod -aG sudo username

Затем создадим файл с именем пользователя в каталоге /etc/sudoers.d/
touch /etc/sudoers.d/username

откроем его

и пропишем такую строку:
username ALL=(ALL) NOPASSWD:ALL

Это позволит пользователю выполнять запуск с правами суперпользователя root без ввода пароля.

Основные параметры в файле /etc/sudoers
Алиас Defaults позволяет задать стандартные параметры для работы утилиты, их мы и рассмотрим в этом разделе. Начинается такой алиас со слова Defaults, дальше идет имя флага. Если перед именем есть символ !, это значит, что флаг нужно включить, в обратном случае выключить:

Отключаем введение при первом использовании:
Defaults !lecture

Суперпользователь не может выполнять sudo:
Defaults !root_sudo

Изменять домашнюю директорию для целевого пользователя, по умолчанию остается папка текущего пользователя в качестве домашней директории:
Defaults set_home

Сохранять список групп текущего пользователя:
Defaults !preserve_groups

Запрашивать пароль суперпользователя вместо пароля пользователя:
Defaults rootpw

Дальше рассмотрим переменные, которым можно задать значения чтобы установить нужные настройки:
Задать количество попыток ввода пароля перед тем, как sudo прекратит работу, по умолчанию - 3:
Defaults passwd_tries=5

Количество минут, которое пройдет перед тем, как sudo будет спрашивать пароль снова, по умолчанию 5. Если установить значение в 0, то пароль будет спрашиваться всегда, независимо от того как давно вы использовали утилиту:
Defaults timestamp_timeout=10

Следующий параметр задает количество минут, пока sudo будет ожидать повторного ввода пароля при неправильном вводе:
Defaults passwd_timeout=10

Вы можете изменить сообщение, которое будет выводится при запросе пароля:
Defaults passprompt="Ваш пароль:"

Можно указать другого пользователя, не root, от которого будут выполняться все команды, для этого используйте:
Defaults runas_default="пользователь"

Вы можете записывать в лог все попытки подключения к sudo:
Defaults logfile=/var/log/sudo

Затем пробуем проверить работу лога:
sudo cat /var/log/sudo

https://losst.pro/nastrojka-sudo-v-linux

чтобы вывести ошибку на экран о неправильно введеном пароле 
Defauts badpass_message=""

Когда requirettyустановлено, sudoдолжно запускаться из сеанса терминала, вошедшего в систему (tty). Это предотвращает sudoиспользование демонами или другими отсоединенными процессами, такими как cronjobs или плагины веб-сервера. Это также означает, что вы не можете запустить его напрямую из sshвызова без настройки сеанса терминала.

Это может предотвратить определенные виды атак эскалации. Например, если у меня есть способ изменить crontab для пользователя с разрешениями NOPASSWD sudo, я мог бы использовать его, чтобы запустить задание от имени пользователя root. С requiretty, я не могу этого сделать...

...легко. Это ограничение не особенно сложно обойти, и, как правило, оно не так уж полезно по сравнению с действительными вариантами использования, которые оно нарушает. Red Hat использовала его, но удалила несколько лет назад.

https://www.geeksforgeeks.org/useful-sudoers-configurations-for-setting-sudo-in-linux/



TTY
Телетайп (англ. teletype, TTY) — электромеханическая печатная машина, используемая для передачи между двумя абонентами текстовых сообщений по простейшему электрическому каналу (обычно по паре проводов).
Наиболее совершенные телетайпы являются полностью электронными устройствами и используют дисплей вместо принтера.
Большинство телетайпов использовало 5-разрядный код Бодо (также известный как ITA2), что ограничивало количество используемых символов до 32. Но если ввести управляющие символы, информативность несложно увеличить; например, в СССР их было 79.

В Linux и других UNIX-подобных операционных системах (например, macOS), окно терминала и приложения по типу xterm и Konsole являются примерами виртуальных телетайпов, работа которых полностью эмулируется при помощи программного обеспечения. Из-за этой особенности терминалы получили название псевдо-телетайп (сокр. «PTS», от англ. «pseudo-teletypes»).

Команда tty
В Linux существует мультиплексор псевдо-телетайпов, который обрабатывает соединения со всех терминалов псевдо-телетайпов (PTS). Мультиплексор является ведущим устройством, а PTS — подчиненными. Мультиплексор общается с ядром через файл устройства, расположенный в /dev/ptmx.

Команда tty выводит имя специального файла устройства, который ваш ведомый псевдо-телетайп использует для взаимодействия с ведущим устройством. И это, по сути, номер вашего окна терминала.
(грубо говоря команда показывает сколько окон открыто)

tty
who






Настройка политики использования сильных паролей на Debian, Ubuntu, Linux Mint, Pop!_OS
Подключаемые модули аутентификации (PAM) установлены по умолчанию в системах на базе DEB.

Однако вам необходимо установить дополнительный модуль libpam-cracklib.

Для этого выполните следующую команду в Терминале:

$ sudo apt install libpam-cracklib
В системах на базе Debian политики паролей определяются в файле /etc/pam.d/common-password.

Прежде чем вносить в него какие-либо изменения, сделайте резервную копию этого файла.
sudo cp /etc/pam.d/common-password /etc/pam.d/common-password.bak

Теперь отредактируйте файл /etc/pam.d/common-password:

$ sudo nano /etc/pam.d/common-password
Найдите следующую строку и отредактируйте или измените ее, как показано ниже.

Если следующей строки не существует, просто добавьте ее.
password required pam_cracklib.so try_first_pass retry=3 minlen=12 lcredit=1 ucredit=1 dcredit=2 ocredit=1 difok=2 reject_username

Давайте разберем эту строку и посмотрим, что будет делать каждая опция.
try_first_pass retry=N – Максимальное количество повторных попыток смены пароля. N указывает на число. По умолчанию этот параметр равен 1.
minlen=N – Минимально допустимый размер нового пароля (плюс один, если кредиты не отключены, что является значением по умолчанию). В дополнение к количеству символов в новом пароле, за каждый символ (другой, верхний, нижний и цифру) дается кредит (+1 в длину). Значение по умолчанию равно 9.
lcredit=N – Определить максимальный кредит за содержание строчных букв в пароле. Значение по умолчанию равно 1.
ucredit=N – Определить максимальное количество заглавных букв в пароле. Значение по умолчанию равно 1.
dcredit=N – Определить максимальный кредит для содержания цифр в пароле. Значение по умолчанию равно 1.
ocredit=N – Определить максимальный кредит для содержания других символов в пароле. Значение по умолчанию равно 1.
ifok=N – Определить количество символов, которые должны отличаться от предыдущего пароля.
reject_username – Запретить пользователям использовать свое имя в качестве пароля.
Надеюсь, вы получили основное представление о вышеупомянутых параметрах.

Как определено в приведенном выше файле, пользователи теперь должны использовать пароль с показателем сложности пароля, равным 12. Один “кредит” будет даваться за 1 строчную букву, 1 кредит за 1 заглавную букву, 1 кредит за минимум 2 цифры и 1 кредит за 1 другой символ.

Однако вы можете отключить кредиты, присвоив им отрицательные значения, и заставить пользователя использовать комбинацию различных символов минимальной длины.

установка политики паролей для всех пользователей:
Нам понадобятся административные права для редактирования файла /etc/login.defs.
sudo vim /etc/login.defs
Установите значение PASS_MAX_DAYS на 30
PASS_MAX_DAYS Максимальное количество дней, в течение которых может использоваться пароль.
PASS_MIN_DAYS Минимальное количество дней между сменами пароля.
PASS_MIN_LEN Минимально допустимая длина пароля.
PASS_WARN_AGE Количество дней предупреждения до истечения срока действия пароля.


Чтобылитику паролей нужно открыть файл /etc/pam.d/common-password
В конце этой строчки можно через пробел перечислить правила проверки паролей:

retry=3 : количество попыток запроса ввода пароля;
minlen=12 : минимальная длина пароля;
difok=5 : минимальное количество изменённых символов относительно старого пароля;
maxrepeat=3 : разрешённое количество повторяющихся символов;
maxclassrepeat=5 : запрещает использование последовательностей с клавиатуры  длиной более пяти символов. Защита от паролей типа «QWERTY»,«12345», «!@#$%»;
ucredit=-1 : обязательное использование минимум одного символа в верхнем регистре;
lcredit=-2: обязательное использование минимум двух символов в нижнем регистре;
dcredit=-2 : обязательное использование минимум двух цифр;
ocredit=-2 : обязательное использование минимум двух специальных символов;
gecoscheck=1 : проверка на содержание в пароле имени пользователя.
После настройки сохраните файл и перезагрузите сервер для применения настроек.



CRON
cron — классический демон (компьютерная программа в системах класса UNIX), использующийся для периодического выполнения заданий в определённое время. Регулярные действия описываются инструкциями, помещенными в файлы crontab и в специальные каталоги.
Например, представим, что вам нужно делать ежедневный бэкап системы и базы данных. Каждый день запускать скрипт вручную не получится, к тому же не хочется днём нагружать систему ещё больше. Идеальный сценарий — запускать скрипт резервирования по ночам, при этом сохранять результаты в файл или уведомлять на служебную почту.
Для этого и подобных сценариев в Linux существует автоматизация задач, за которую отвечает специальный компонент-планировщик Cron. Пользователю достаточно только добавить нужный скрипт и указать регулярность выполнения. По умолчанию результаты отправляются на почту, но также их можно записывать в файл-журнал или вовсе никуда не выводить.
Установка cron
В большинстве Linux-дистрибутивов компонент Cron уже установлен по умолчанию. Но если в вашей системе это не так, это легко можно сделать вручную. Для этого сначала нужно обновить локальный индекс пакетов в системе, а затем установить непосредственно cron в Ubuntu.

sudo apt update
sudo apt install cron

Основная функция Cron — регулярное выполнение скриптов в фоновом режиме. Поэтому после установки нужно убедиться, что служба включена. Для этого воспользуемся диспетчером systemd.
sudo systemctl enable cron

Как работают скрипты
В Linux почти не используется расширение файла для опережения его типа на системном уровне. Это могут делать файловые менеджеры и то не всегда. Вместо этого, используются сигнатуры начала файла и специальные флаги. Система считает исполняемыми только те файлы, которым присвоен атрибут исполняемости.

Теперь о том, как работают скрипты. Это обычные файлы, которые содержат текст. Но если для них установлен атрибут исполняемости, то для их открытия используется специальная программа - интерпретатор, например, оболочка bash. А уже интерпретатор читает последовательно строку за строкой и выполняет все команды, которые содержатся в файле. У нас есть несколько способов выполнить запуск скрипта linux. Мы можем запустить его как любую другую программу через терминал или же запустить оболочку и сообщить ей какой файл нужно выполнять. В этом случае не нужно даже флага исполняемости.

чтобы скрипт запускался без указания путя нужно поместить его в директорию usr/local/bin

чтобы скрипт выводил на экран 
1) Архитектура вашей операционной системы и версия ее ядра.
uname -a
a - Отображает всю информацию, указанную с помощью флагов -m, -n, -r, -s и -v. Нельзя использовать с флагом -x или -SName. Если флаг -x указан с флагом -a, то флаг -x переопределяет его.

2) Количество физических процессоров.
cat /proc/cpuinfo | grep "physical id" | wc -l
grep -  поиск (фильтр)
wc - подсчет строк слов и байт
 -l  - отображение строк

3) Количество виртуальных процессоров.
cat /proc/cpuinfo | grep "processor" | wc -l

4) Текущая доступная оперативная память на вашем сервере и коэффициент ее использования в процентах.
free -m - отображение памяти в мегабайтах



