<b>Фикс фризов и "заикания" FPS.</b>
<hr>
В этом гайде вы сможете подробно ознакомиться со всеми тонкостями настройки CS:GO, а конкретно файлов AutoExec.cfg и Video.txt.

<b>Вступление</b>
<hr>
Начну с того, что этот гайд для тех, у кого компьютер не выше процессора 5 поколения и оперативной памяти порядка 4 ГБ ОЗУ, ибо у кого больше, то у них и так все нормально и вам тут просто делать нечего. Собственно углубленное изучение настроек CS:GO я начал около полугода назад, как только начал играть. Уже пытался делать гайд для повышения ФПС, но в силу еженедельных обновлений он просто потерял свою актуальность, но на то время он работал идеально (ссылку на старый гайд вы сможете найти в моем профиле). Так вот, спустя многое время, долгих изучения настроек игры я сделал некий итог. И этим итогом стали 2 файла, отвечающие за настройки игры - Autoexec.cfg и Video.txt, и конечно же параметры запуска игры, которые играют немалую роль. Собственно о них и пойдем речь в этом гайде.
<br>
<br>
<b>Установка</b>
<hr>
Чтобы минимально упростить гайд, я просто добавлю сюда ссылки на файлы.<br>
Autoexec.cfg: https://github.com/mysubcult/cs-go/blob/master/autoexec.cfg<br>
Video.txt: https://github.com/mysubcult/cs-go/blob/master/video.txt<br>
Эти файлы вы должны добавить и заменить в директории: '..\Steam\SteamApps\common\Counter-Strike Global Offensive\csgo\cfg'
<br>
<br>
<b>Параметры запуска</b>
<hr>
Огромную роль при всем при этом играют параметры запуска, ниже я приведу пример параметров запуска, которые стоят у меня:
-processheap -novid -nojoy -high -threads 4 -nod3d9ex -noaafonts +mat_dxlevel 90 +mat_queue_mode 2 +mat_vignette_enable 0
<br>
<br>
<b>Необходимые параметры:</b>
<hr>
<b>-processheap -high -threads 4 -nod3d9ex -noaafonts +mat_dxlevel 90 +mat_queue_mode 2 +mat_vignette_enable 0</b>
<br></b>
<br>
P.S.
Разрешение в игре вы можете менять на любое, которое вам удобно, но советую не менять уровень теней и сглаживания. Autoexec.cfg советую тоже не трогать, всю информацию, которую вы там можете менять я вывел в начало списка, чтобы вам было удобнее.
Рейты в Autoexec.cfg выставлены под сервера с 128 тикрейтом, но они автоматически конвертируются в 64 тикрейт на официальных серверах, что не долнжо вызвать проблем. 
Raw Input или "прямой" ввод мыши: исходя из моих личных наблюдений советую оставить значение m_rawinput равное нулю, т.е. "m_rawinput 0". Подробнее об этом вы можете прочитать тут: http://www.reddit.com/r/GlobalOffensive/comments/1f8km4/csgo_raw_input_faulty/
Так же советую еще установить фикс для мышки по ссылке: http://donewmouseaccel.blogspot.com/2010/03/markc-windows-7-mouse-acceleration-fix.html
<br>
<br>
<b>Заключение</b>
<hr>
В заключении хочу сказать, что данный гайд писался на скорую руку, основной его идеей является довести до вас необходимую информацию, которая действительно работает и помогает. Данный гайд будет пополняться и модернизироваться, так же приветствуются люди, которые помогут с поиском грамматических ошибок в гайде и переводом на другие языки, либо с новыми идеями для модификации.
</b>Нужен ли видео гайд?</b>
<hr>
В комментариях напишите, нужна ли видеоинструкция по установке этого гайда?
