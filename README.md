# общая информация
Remap Controller

Xinput
* поддержка C Z M1 M2 M3 M4 (можно назначить абсолютно всё, никаких ограничений)
* поддержка вибрации (изменение силы вибрации обоих или каждого мотора отдельно, можно на лету через трей)
* поддержка любых аналогов xbox геймпадов
* надо делать скрытие устройства от системы, чтобы игра подхватывала именно программу, а не физический геймпад

Direct Input
* поддержка любых кнопок C Z M1 M2 M3 M4 HOME PLUS MINUS
* поддержка гироскопа
* можно добавить поддержку абсолютно любого геймпада и множества кнопок

вся настройка сводится к выбору условия и выполнения действия

условия:
* нажатие кнопки
* состояние триггера (можно выбрать диапазон нажатия, множество действий для разных состояний)
* состояние стика (можно выбрать из 8 направлений и любой диапазон наклона, множество действий для разных состояний)
* гироскоп - наклон контроллера (можно выбрать направление и диапазон угла наклона, любое кол-во условий)

действия:
* нажатие кнопки / кнопок (+ переключение состояния вкл выкл)
* турбо нажатие кнопки / множества кнопок (+ переключение вкл выкл)
* турбо с задержкой - если кнопка удерживается менее указанного времени, то она работает как обычная кнопка (делает удержание, если удерживается), но если удерживается дольше - становится турбо
* нажатие триггера на любое значение
* наклон и вращение стиков в любом направлении (360 градусов) на любое значение
* макросы - управление кнопками, триггерами, стиками (любое кол-во, любая длина)
* гироскоп управляет стиками - 2 оси, 2 режима для каждой оси (как прицеливание для шутера или как вращение руля для гонок), настраивается индивидуально каждая ось, режим, чувствительность
* нажатие кнопки клавиатуры и мыши (одиночное нажатие, очередь, удержание)
* запуск программ, файлов

про макросы подробнее:
* команды: нажать кнопку, отжать кнопку, сделать турбо, убрать из турбо, добавить значение к триггеру, добавить значение к стику (оси X, Y, наклон, вращение), сделать вибрацию
* дополнительный макрос после отпускания кнопки
* поочерёдный запуск макросов, если удерживается условие
* цикличный макрос - повторять, пока удерживается условие
* множество цикличных макросов на одном условии, в зависимости от времени удержания
* мульти-макрос - на одну кнопку можно назначить множество макросов, выбор зависит от времени удержания кнопки (время и кол-во любое)
* смена макроса на следующий после нажатия
(так что да, кнопки могут управлять стиками, а стики нажимать кнопки, тригерры управлять триггерами на любое значение)

смена профиля:
каждый профиль - новые действия для выбранных условий, любое кол-во профилей
* применить
* применить при удерживании
* временно применить до первого действия (т.е. смена обратно происходит автоматически)
