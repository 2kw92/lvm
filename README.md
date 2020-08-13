Инструкции

Так как домашнее задание предусматривает 2 перезагрузки системы, прикладываю
6 файлов утилиты script (3 с протоколом работы lvm(1-3) и 3 с отметками времени timeline(1-3)). 

Соотвественно для прогонки всего сценария необхрдимо сначала запустить:
scriptreplay ~timeline1 ~lvm1
Затем сделать shutdown -r now
После этого scriptreplay ~timeline2 ~lvm2
Снова shutdown -r now
И вызов scriptreplay ~timeline3 ~lvm3