Скрипт переименовывает видеофайл(ы) - добавляет к названию файла его продолжительность.
Передаваемые параметры:
-d Переносит все файлы из вложенных папок в текущую директорию (откуда запустили скрипт)
-c Конвертирует название файла в вид: Первая буква заклавная, остальные строчныне
-f 'file1' 'file2' Обрабатывает не все файлы в текущем каталоге, а только указанные после ключа '-f'

Для запуска из скрипта из любой директории:

1. Файл должен быть в одной из директорий, указанной в $PATH
$ echo $PATH

2. Файл должен быть исполняемым
$ chmod +x rn.py

3. Файл должен содержать корректную shebang строку на самом верху, например:
#!/home/user/anaconda3/bin/python3
Чтобы найти путь к вашему интерпретатору python на вашем компьютере, вы можете запустить команду:
which python
