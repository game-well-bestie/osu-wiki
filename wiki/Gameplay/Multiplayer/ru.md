# Мульти

Мульти (сокращение от *мультиплеер*) был добавлен в публичную версию osu! b335 и является игровым режимом для онлайн игры с другими игроками, число которых может доходить до 16 человек.

Это тема также освещена в [шестом выпуске](https://www.youtube.com/watch?v=cyYRl-a5xII) [osu!academy](/wiki/Community/Video_series/osu!academy) наравне со [списком игроков в сети](/wiki/Client/Interface/Chat_console#расширенное-окно-чата).

## Как начать

### Минимальные требования

![](/wiki/shared/Beatmaps_peppy.jpg "Как распаковать карту \(наглядно\).")

- Стабильное подключение к интернету;
- Произведенный вход в osu! (вход производится клиентом автоматически во время запуска);
- Знание того, [как скачивать карты, не выходя из лобби](/wiki/Beatmap).

### Как зайти

В главном меню выберите Play, а затем Multi. Это можно сделать и с клавиатуры, нажав кнопки `P` и `M`.

Если подключение к серверу произошло успешно, то вы окажетесь в **мультиплеере**, на странице выбора комнаты для игры в мульти.

### Примечания

- Не забывайте, что скачивание карт может длиться от нескольких секунд до пары часов, в зависимости от вашей скорости интернета.
- При потере соединения с сервером игрок будет перенаправлен в главное меню.
  - Если это произошло во время игры, то напротив ника игрока появится надпись "Quit", как у вышедшего из игры.
  - Чтобы перезайти в мультиплеер, подождите, пока соединение с сервером не установится снова, и нажмите `Multi` еще раз.
    - Если проблема с подключением не решилась, перезагрузите роутер. Если это не помогло, напишите в техподдержку osu!.
- Если вы находитесь на ветке обновлений **cutting edge**, то для входа в мультиплеер вам нужен [саппорт](/wiki/osu!supporter).
- Чтобы открыть настройки в мультиплеере, нажмите `Ctrl`+`O`.

## Мультиплеер

![](img/Multi_lobby.jpg "Пример типичного дня в лобби Мультиплеера")

В мультиплеере показываются все доступные на данный момент комнаты.

Слева вверху находятся фильтры для комнат, а справа вверху — проигрыватель музыки.

Список фильтров приведен ниже:

| Название | Описание |
| :-: | :-- |
| `Все`/`osu!`/`osu!taiko`/`osu!catch`/`osu!mania` | Показать только комнаты с **соответствующим режимом**. |
| `Карты, которые есть у меня` | Показать только комнаты с картами, **которые у вас скачаны**. |
| `Показать полные комнаты` | Показать комнаты **без свободных мест**. |
| `Поиск` | Поиск по имени игрока, названию песни или комнаты. При использовании поиска будут проигнорированы все фильтры, кроме `Показывать игры в процессе`(единственный доступный во время поиска фильтр). |
| `Комнаты с моими друзьями` | Показать только **комнаты с вашими друзьями**. Данный фильтр имеет приоритет над всеми остальными фильтрами. |
| `Показывать закрытые комнаты` | Показать комнаты, **в которые нельзя войти без пароля**. |
| `Показывать игры в процессе` | Показать комнаты, в которых **игра уже началась**. Если комната имеет свободные места, вы можете зайти в нее и подождать, пока остальные доиграют. Комнаты с игрой в процессе будут выделены серым цветом и в названии будет надпись `(идёт игра)`. |

---

В центре экрана находятся комнаты, подходящие под выбранные фильтры.

Каждая комната имеет свое описание:

- Слева находятся значок игрового режима и его название с (командным режимом) в скобках, количество игроков/количество открытых слотов, а также диапазон между самым высоким и низким ранком игроков в комнате.
- Справа находятся аватарка хоста и остальных игроков, название комнаты и название мапсета с \[названием сложности\] в квадратных скобках. Квадрат под каждой аватаркой имеет свой цвет:
  - Красный: слот занят игроком;
  - Зелёный: свободный слот;
  - Серый: закрытый слот.

Чтобы зайти в комнату, нажмите на её название.

![](img/Multi_lobby_locked.jpg "Закрытая комната")

**Примечание**: Если нажать на значок игрового режима с замком, вам предложат ввести пароль для входа в комнату. Если у вас нет пароля, попросите его у хоста. Так же вы можете попросить приглашение у хоста, что бы обойти защиту паролем.

---

В мультиплеере игрок может использовать три кнопки над чатом (слева направо):

| Название | Описание |
| :-: | :-- |
| `Назад в меню` | **Покинуть мультиплеер и вернуться в главное меню**. |
| `Новая комната` | **Открыть меню настроек новой комнаты.** |
| `Быстрое подключение` | Перейти в случайно выбранную комнату, основываясь на текущем **диапазоне рангов**. |

По умолчанию в [основном окне чата](/wiki/Client/Interface/Chat_console) откроется `#lobby`, и чат будет открыт все время.

## Новая комната

![](img/Multi_new_game.jpg "Настройки новой комнаты")

| Название | Описание |
| :-: | :-- |
| **Game Name** | **Название новой комнаты.** По умолчанию ставится как `{имя_игрока}`'s game. Для того что бы сделать комнату закрытой отметьте галочку `Require password to join`. |
| **Password** | **Пароль для комнаты**. Ввод пароля доступен только при отмеченной галочке “Require password to join”. Закрытая комната будет показываться с замком в значке режима и будет требовать пароль при входе. |
| **Max players** | **Максимальное количество игроков в комнате.** По умолчанию — 8 и может изменяться с 2 до 16, включая игрока-хоста. Вы сможете изменить это позже в самой комнате открывая/закрывая слоты. |

Нажмите кнопку `1. Start Game`, чтобы **создать комнату** с указанными настройками и песней, которая у вас **играет в данный момент**.

## Настройка игры

<!-- One/Two image here? Subsections of the images later like what was done in Interface of the old osu! wiki for Song Selection? -->

![](img/Multi_roomhost.jpg "Пример комнаты от лица хоста")

![](img/Multi_roomplayer.jpg "Пример комнаты от лица игрока (со свободными модами)")

Наверху экрана отображается ваша роль в комнате (хост или обыкновенный игрок), ваш ранг и кнопка паузы.

---

Снизу экрана находится [основное окно чата](/wiki/Client/Interface/Chat_console). При входе в комнату в чате автоматически открывается новая вкладка `#multiplayer`, в которую [BanchoBot](/wiki/BanchoBot) отправит ссылку на историю матча с подписью `(Match history available here)`. История матча открывается по ссылке вида `https://osu.ppy.sh/community/matches/x` (где "x" — это идентификатор матча в виде цифр).

После игры будет показано ваше место в другой вкладке `#userlog` (только для Head to Head режима) в формате `Место в мультиплеере: #{место} из {всего}, карта: {мапсет} [сложность] <игровой режим>.`

---

Центр экрана разделен на две части: слева находится список игроков, а справа — настройки игры.

### Список игроков

С левой стороны показано количество игроков и свободных слотов в данной комнате.

Игроки могут менять свое положение в списке или поменять команду на синюю или красную, если они не готовы к игре. Если навести курсор на игрока, вам будут показаны его уровень, страна и точность.

Хост, в свою очередь, может передавать права хоста другим игрокам, выгонять их из комнаты или закрывать и открывать слоты.

Статус игроков можно узнать по их цвету:

| Цвет (Статус) | Описание |
| :-- | :-- |
| **Красный (Нет карты)** | **У игрока нет карты.** Рядом с ником игрока будет надпись `[нет карты]`, пока игрок не скачает и не распакует карту. При смене хостом карты в зависимости от ее наличия у всех игроков меняется цвет либо на красный (нет карты), либо на белый (не готов). |
| **Белый (не готов)** | **Игрок имеет карту, но еще не готов играть.** Игрок может менять моды в этом состоянии, пока не нажмет кнопку готовности. Каждый игрок при смене хостом карты примет либо этот статус, либо Красный (нет карты). |
| **Зеленый (Готов)** | **Игрок готов к игре.** Игровые моды не могут быть изменены в данном состоянии. Игрок может нажать кнопку `Мне нужно подготовиться`, чтобы вернуться к белому состоянию, но у хоста обычно отсутствует такая возможность, так как вместо этой кнопки будет кнопка Принудительный старт (если только он не один в комнате). |
| **Светло голубой (в игре)** | **Игрок находится в игре.** К нику будет добавлена надпись \[в игре\] до конца игры. |

### Опции комнаты

С правой стороны находятся, собственно, опции комнаты. Менять их может только хост, кроме игровых модов при свободных модах, в этом случае игроки могут выбрать их сами.

#### Название комнаты и смена пароля

Сверху находится название комнаты, которое хост может изменить в любой момент. Также хост может создать/поменять пароль, нажав на кнопку `Сменить пароль`.

#### Карта

![](img/Multi_host_song_change.jpg "Во время смены карты будет отображаться эта плашка.")

![](img/Multi_SS.jpg "Пример того, как выглядит выбор карты для хоста.")

В середине находится секция карты. В данной секции показываются изображение, символ режима игры, название, автор карты, исполнитель и сложность текущей карты. Также, если навести курсор на нее, будут показаны BPM, длительность и свойства карты.

![](img/Multi_beatmapinfo.jpg "Информация о карте при наведении курсора")

Если у игрока отсутствует карта, он увидит один из нижеприведенных вариантов:

| Статус карты | Описание |
| :-- | :-- |
| Нажмите, чтобы скачать карту | При нажатии будет открыта страница карты в браузере по умолчанию. Если у игрока есть osu!direct, карта будет скачана автоматически |
| Not uploaded or not up-to-date | Игрок не сможет открыть карту при нажатии. Хосту следует дать ссылку на карту вручную. |
| Cannot update the beatmap | Скорее всего, у хоста [модифицированная версия карты.](https://osu.ppy.sh/community/forums/topics/135726 "ppy's reply on a bug report.") |

#### Моды

![](img/Multi_mods_host.jpg "Настройки модов \(osu!\) у хоста")

![](img/Multi_mods_player.jpg "Настройки модов \(osu!\) у игрока \(при свободных модах\)")

Ниже находится меню игровых модов. Тут будут показаны выбранные [игровые моды](/wiki/Game_modifier). Хост может установить `Cвободные моды`, чтобы остальные игроки могли выбирать свои моды, *кроме* [Double Time (DT)](/wiki/Game_modifier/Double_Time)/[Nightcore (NC)](/wiki/Game_modifier/Nightcore) или [Half Time (HT)](/wiki/Game_modifier/Half_Time). При этом выбранные хостом моды (кроме модов на скорость) не будут включены для остальных игроков.

#### Командный режим, условие победы, цвет комбо в Tag Coop

Нижняя правая секция показывает режим игры (командный) и условие победы в матче.

##### Командный режим

Всего существует четыре командных режима, в которые можно играть:-

| Командный режим | Описание |
| :-- | :-- |
| Head to Head | Соревнуйтесь друг с другом за первое место. |
| Team Vs | Соревнуйтесь командами (красной/синей) за победу. |
| Tag Coop \[только osu!, UNRANKED\] | Режим, в котором каждый по очереди играет по одному комбо. |
| Tag Team Vs \[только osu!, UNRANKED\] | Тот же Tag Coop, только игроки поделены на команды. |

**Примечание:** Аватарка победителя в матче будет показана на странице результатов только для режима Head to Head.

##### Условие победы

Всего есть четыре варианта того, как будет определяться победа в матче:-

| Название | Описание |
| :-: | :-- |
| Score | Игрок с наибольшим числом очков выиграет. |
| Accuracy | Игрок с наибольшей точностью выиграет. Если два игрока имеют стопроцентную точность, то победитель решается по наибольшему числу очков от спиннеров. Если же в карте не спиннеров, то победитель остается неопределенным. |
| Combo | Игрок с наибольшим комбо выиграет. Если у игроков комбо совпадает, то выигрывает игрок с наибольшим числом очков. Максимальное комбо не учитывается. |
| Score v2 | Победит игрок с наибольшим числом очков в новой системе. |

##### Цвет комбо в Tag Coop (только для Tag Coop/Tag Team Vs)

![](img/Multi_tag_colour.jpg "Доступные цвета для комбо игрока")

Если был выбран режим *Tag Coop/Tag Team Vs*, будет также показано меню **Tag Colour:** `(цвет комбо)` для выбора цвета вашего комбо. По умолчанию будут использованы цвета комбо карты.

### Кнопки комнаты

Слева находится оранжевая кнопка `Покинуть комнату` и синяя кнопка `Можно начинать`/`Мне надо подготовиться`/`Начать игру`/`Принудительно начать` справа.

Название кнопки `Покинуть комнату` как бы намекает на ее назначение: покинуть комнату и вернуться в мультиплеер.

А вот текст и действие синей кнопки могут меняться в зависимости от предыдущих действий и от того, является ли игрок хостом:

| Название | Описание |
| :-: | :-- |
| `Можно начинать` | Нажмите, чтобы **приготовиться (зеленый цвет)**. Кнопка изменится на `Мне надо подготовиться` для игроков и на `Начать игру`/`Принудительно начать` для хоста, если есть другие игроки, в противном случае изменится на `Мне надо подготовиться`. |
| `Мне надо подготовиться` | Нажмите, чтобы **отменить готовность (белого цвета)**. Кнопка изменится на `Можно начинать`. |
| `Начать игру` | Показывается только у хоста при готовности всех игроков; начинает матч. Если хотя бы один игрок не будет готов, то кнопка сменится на `Принудительно начать`. |
| `Принудительно начать (x/y)` | Показывается только у хоста; принудительно начинает матч, даже если остались не приготовившиеся игроки. Появляется, если хост нажал на кнопку готовности, но не все игроки готовы (`х` в этом случае — число готовых игроков, а `у` — число всех игроков в комнате). |

### История матча

**Примечание**: При входе в комнату во вкладке `#multiplayer` в первой же строке появляется ссылка на историю матча, которая откроется в браузере по умолчанию.

![](img/multi-mh.jpg "Пример истории матча.")

## Командный режим

### Общие сведения

#### Клавиша Esc

Нажатие клавиши `Esc` (Escape) на клавиатуре *не ставит матч на паузу*; вместо этого снизу справа появится предупреждение о том, что для выхода из комнаты нужно нажать клавишу `Esc` еще раз. Чтобы выйти из комнаты и вернуться в мультиплеер, нажмите `Esc` *снова*.

#### Визуальные настройки

Перед началом матча во время загрузки карты внизу экрана в визуальных настройках можно отключить сториборд/видео/хитсаунды и настроить затемнение. Если используются `Свободные моды`, используемые моды будут влиять на игровой процесс игрока, и подсчет числа очков будет производиться с учетом модификаторов модов. Интерфейс у игроков во время игры может отличаться.

#### Полоска здоровья

Когда полоска здоровья игрока полностью истощается, рекорд считается проигранным. Если игрок проиграл хотя бы раз, то его очки и точность не будут учитываться в общей статистике. Однако, проигравший игрок может продолжать играть и восстановиться при достижении полного здоровья.

Если включен [Sudden Death (SD)](/wiki/Game_modifier/Sudden_Death) либо [Perfect (PF)](/wiki/Game_modifier/Perfect), то восстановиться не получится.

#### Результаты, ретрай и реплей

Несмотря на отсутствие онлайн-статистики внизу экрана с результатами, не проигранный рекорд будет учитываться так же, как и в одиночной игре. Результаты игры не будут показываться в локальном топе. Сделанный в мультиплеере рекорд возможно увидеть только в онлайн-рейтинге (если поставленный в мультиплеере рекорд выше других рекордов игрока на этой карте).

**Переигрывать в мульти нельзя**, но реплей можно сохранить нажатием на `F2` (не будет показывать игровые элементы мультиплеера и не будет сохраняться на сервере osu!) Имейте в виду, что это не относится к Tag Coop и Tag Team Vs (так как оба режима не считаются ранкнутыми), где рекорд не будет записан и реплей нельзя сохранить.

#### Топ в мульти

В списке показываются участники матча в реальном времени, в зависимости от условия победы:

**Head to Head / Team Vs:*

- Если Score/Score v2: Счет, очки за нажатия и комбо показываются в реальном времени.
- Если Accuracy: Точность, очки за нажатия и комбо будут показываться в реальном времени.
- Если Combo: Комбо показывается в реальном времени. Максимум комбо не показывается.

**Tag Coop / Tag Team Vs:*

- Если Score/Score v2: Счет команды и очки за нажатия показываются в реальном времени.
- Если Accuracy: Точность команды и очки за нажатия показываются в реальном времени.
- Если Combo: Текущее комбо команды, счет и очки за нажатия показываются в реальном времени.
- Если *Failed*: Матч заканчивается и при \[Tag Coop\] игроки возвращаются в комнату, а при \[Tag Team Vs\] выжившая команда автоматически выигрывает.
  - Проигравшие игроки не будут учитываться в общем счете команды пока не восстановятся, достигнув полной полоски здоровья.
- Если *Quit*: [Auto](/wiki/Game_modifier/Auto) будет играть за ушедшего игрока.
  - Если все игроки одной команды покинут матч, то другая команда будет объявлена победителем.

Проигравшие или покинувшие игроки будут находиться внизу турнирной таблицы отдельно от остальных игроков, хотя все равно могут менять соревноваться друг с другом.

#### Цвет игрока

<!-- A player box reference here? Old images in img/Playerbox -->

<!-- Special player box note: Skipped (has its own special callout), Failed (red text), and Quit (red text with [Quit] appended) -->

| Статус/Цвет | Описание |
| :-: | :-- |
| **Нормальный/Синий** | **У игрока *больше* половины здоровья**, обычно полное. Цвет будет ярче, если у игрока высокое здоровье, и покраснеет, если здоровье упадет ниже половины. |
| **Опасность/Красный** | **Игрок имеет *менее* половины здоровья**. Красный будет всё насыщеннее при уменьшении здоровья и сменится синим при увеличении здоровья выше половины. |
| **Failed/Серый** | **Полоска здоровья опустела.** Игрок может продолжить играть и, если не были использованы [Sudden Death (SD)](/wiki/Game_modifier/Sudden_Death)/[Perfect (PF)](/wiki/Game_modifier/Perfect), восполнение здоровья полностью вернет игрока к нормальному состоянию. Также в этом состоянии счет игрока не будет учитываться в общем счете команды. Ник игрока поменяет цвет с белого на красный. |
| **Tag/Зеленый** | *Только для Tag Coop и Tag Team Vs*. **Это постоянный цвет для каждого игрока на весь матч и не зависит от состояния полоски здоровья.** На текущего игрока будет указывать зеленая стрелка. |
| **Skipped/Белый** | **Игрок попросил пропустить начало песни, если таковое имеется.**. Игроки, нажавшие кнопку `Skip` справа снизу экрана, будут отмечены желтой отметкой с надписью `Skipped`. **Чтобы пропустить, Skip должны нажать все игроки**. |
| **Quit/Различается** | **Игрок покинул матч**. Существует два способа войти в это состояние: (1) нажать `Esc` дважды, или (2) отсоединиться от Bancho. Цвет текста изменится с белого на красный, и появится надпись `[Quit]` в конце. Цвет будет тем же, что был у игрока перед выходом из игры. |

### Head to Head

#### Интерфейс

![](img/Multi_HTH.jpg "Интерфейс Head to Head")

Head to Head — это режим, где игроки соревнуются друг с другом за первое место. Это режим по умолчанию и не имеет каких-либо особенностей во время игры, просто соревнуйтесь за первое место.

#### Результаты

![](img/Multi_grade.jpg "Результаты Head to Head")

В конце матча будет показана аватарка победившего игрока.

Итоги матча будут показаны на фоне изображения оценки. Результаты других игроков можно увидеть, нажав на них в турнирной таблице.

Каждый игрок получает персонализированный итог матча во вкладке `#userlog` после завершения карты.

### Team Vs

#### Интерфейс

![](img/Multi_team_vs.jpg "Интерфейс Team Vs")

В режиме Team Vs соревнуются две команды (Blue/Red) в одном из условий победы. Постарайтесь выиграть по условию победы, чтобы достигнуть первого места в команде и соревнуйтесь с другой командой по общему счету команды.

Игроки синей команды расположены с левой стороны, а игроки красной команды — справа, а корона посередине показывает текущее превосходство какой-либо из команд. Корона будет двигаться тем ближе в сторону выигрывающей команды, чем больше ее преимущество над другой.

При выборе данного режима все игроки присоединяются к красной либо синей команде и получают соответствующий флаг. Игроки могут нажать на него, чтобы сменить команду на другую.

Размеры команд не играют роли и никаких преимуществ у команды с меньшим количеством игроков нет; возможно даже начать игру вообще без второй команды. Расположение игроков перед матчем не играет роли, после начала матча синяя команда будет расположены слева, а красная — справа. В команде нет ролей (вроде лидера или капитана); просто соревнуйтесь за первое место в команде и побейте общий счет другой команды.

Игрок команды с наиболее высоким счетом будет показан на первом месте, при условии, что он выжил. Проигравшие игроки будут расположены внизу командной таблицы и не будут учитываться в общем счете команды.

#### Результаты

![](img/Multi_team_grade.jpg "Результаты Team Vs")

Победившая команда будет определена на основе общего счёта команды, на экране результатов по центру будет надпись цвета той команды, которая победила. Общее число очков синей команды будет слева, а общее число очков красной — справа.

**Учитываются в общем счете команды только результаты не проигравших игроков**; вполне может случиться такое, что победителем объявят красную команду при явном преимуществе синей, *только потому*, что обеспечивающий команде преимущество игрок проиграл под конец, либо во время игры проиграли все игроки синей команды.

Вкладка `Total` будет показывать общее количество попаданий (300, 100 и т.д.), сделанное всей командой, и среднюю точность команды. Комбо не будет учитываться в командной вкладке `Total`. Оценка будет показываться не во вкладке `Total`, а фоном на окне результатов (если пройдено).

### Tag Coop / Tag Team Vs

#### Интерфейс

*Доступно только в режиме osu!. **UNRANKED***

![](img/Multi_tag_co-op.jpg "Интерфейс Tag Coop")

![](img/Multi_tag_team_vs.jpg "Интерфейс Tag Team Vs")

В режиме Tag Coop все игроки в комнате вместе проходят карту по одной комбо-секции по очереди. Tag Team Vs — это просто состязание красной и синей команды в Tag Coop.

Обратите внимание, что этот командный режим доступен **только для osu!** и *не учитывается в рейтинге*.

В этом режиме расположение игроков в комнате играет роль, так как это определит очередность хода игроков.

Во время матча текущий игрок будет отмечен зеленой стрелкой. Имя игрока будет указано в правом нижнем углу экрана. Перед тем, как наступит очередь игрока, перед ним замигают предупредительные стрелки и комбо будет **окрашено в выбранный ранее цвет**, пока ход игрока не закончится. Игрок может поменять цвет комбо на один из цветов в **Tag Colour** перед началом матча.

**Все игроки должны крутить спиннер**. Если же кто-то не докрутит спиннер до конца, текущее комбо будет сброшено.

Если игрок покидает игру во время матча, за него будет играть [Auto](/wiki/Game_modifier/Auto).

В режиме Tag Coop у игроков одна полоска здоровья на всех. Если полоска здоровья опустошается полностью, матч заканчивается, и все игроки сразу возвращаются в комнату без показа экрана результатов.

В режиме Tag Team Vs у каждой команды есть своя полоска здоровья, которая видна только членам этой команды. Если полоска здоровья одной из команд опустошается полностью, матч заканчивается преждевременно, и победа присуждается другой команде. Если был включен [Easy (EZ)](/wiki/Game_modifier/Easy) мод, полоска здоровья будет, как обычно, дважды восполняться, но сразу после этого опустошится полностью и карта будет проиграна. Игроки, использующие [Sudden Death (SD)](/wiki/Game_modifier/Sudden_Death)/[Perfect (PF)](/wiki/Game_modifier/Perfect), будут иметь немного отличающийся интерфейс, особенно в плане эффектов. Если игрок **с выключенным** модом делает ошибку, карта будет продолжаться как обычно, но у игроков со включённым полоска здоровья опустеет и не будет подниматься, однако никакого влияния **на игровой процесс** это не окажет (то есть будет только визуальный эффект). Если же ошибку сделает игрок, *использующий* мод, игроки проиграют незамедлительно.

Если вы играете в оконном режиме, обратите внимания, что курсор **не** ограничен границами окна во время перерыва или не во время очереди игрока.

#### Результаты

![](img/Multi_co-op_grade.jpg "Результаты Team Co-Op")

![](img/Multi_tag_team_grade.jpg "Результаты Tag Team Vs")

Как было отмечено выше, счет не будет учитываться в рейтинговых очках и очках производительности, потому что этот режим *анранкнутый*.

В режиме Tag Coop результаты показаны в виде общего счета, количества попаданий и точности команды. Индивидуальные результаты не будут показаны и могут быть доступны только в истории матчей. Экран с результатами появится только при успешном прохождении карты.

В режиме Tag Team Vs экран с результатами аналогичен такому же, как и в Team Vs.

## Разное

### История

![](img/Multi_Mania_unpatched.jpg "Скриншот osu! без обновления, когда впервые появилась osu!mania \(8 октября 2012\)")

- Раньше в комнате могло находиться максимум 8 игроков.
- osu!mania режим у не обновившихся игроков в Мультиплеере показывался как `3`.
- No Video был *единственным* модом, который разрешалось использовать в мульти, однако это перенесли в визуальные настройки.