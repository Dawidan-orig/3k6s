По сути, это событие.
Эта команда принимает сигнал.

Работает с [[Состояния процесса]] - прерываемые процессы работают именно с сигналами.

Проблема: Их надо постоянно слушать.

Входит сюда ещё:
sigaction -- установка гибких настроек.
SIGSTOP -- этот формат сигнала переводит процесс в STOPPED
SIGCONT -- Формат переводит из STOPPED куда-то ещё.
SIGKILL -- Убивает процесс в зомби
И так далее про логику сигнала.