# Небольшая шпаргалка для работы с GitHub

## С чего начать?
Дорогой друг, мне, как и тебе сейчас, тоже поначалу казалось, что работать с GitHub сложно, но после прохождения [бесплатного курса от Яндекс Практикум](https://practicum.yandex.ru/git-basics/) по освоению GitHub, этот мир мне стал абсолютно понятен. Несмотря на то, что мне еще многому нужно научиться, этот курс дал мне то, что так необходимо в начале пути - ясность.<br>
Помимо этого, ниже я опишу основные моменты, к которым ты, да и я, скорее всего, еще не раз вернешься, пока не набьешь руку.

## Супер-основы
```
pwd     # (от англ. print working directory) — показать рабочую папку
cd      # (от англ. change directory) — сменить директорию
cd ~    # перейти в домашнюю директорию (обычно это путь Диск/юзеры/твой юзер)
cd ..   # перейти на уровень выше
ls      # показать файлы, которые есть в текущей директории
```

## Работа с файлами
```
mkdir new-rep     	# создание директории (папки)
touch readme.md   	# создание файла readme.md 
cp readme.md new-rep/	# копирование файла readme.md в директорию (папку) new-rep
mv table.csv new-rep	# перемещение (move) файл table.csv в директорию (папку) new-rep
cat readme.md 		# распечатывание содержимого файла readme.md
rm readme.md 		# удаление файла readme.md из текущей директории (папки) 
rmdir new-rep 		# удаление папки new-rep из текущей директории, 
               		# если папка new-rep пуста 
rm -r images 		# удаление папки new-rep со всем её содержимым из текущей директории
```
## На этом у меня все, удачи в начинаниях, друг!