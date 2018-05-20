# СКРИНШОТЫ И СКРИНКАСТЫ (ЗАХВАТ ФОТО, АУДИО, ВИДЕО)

## 1.1. Kazam

Kazam Screencaster - это небольшое, но очень удобное приложение для создания скринкастов, а говоря более простым языком - записи видео с рабочего стола.

Установка:
```
sudo apt-get install kazam
```

## 1.2. Shutter

Shutter - это один из лучших скришотеров для Linux, но и его приходится допиливать. Например, из него нельзя настроить горячие клавиши для создания скриншотов.

Установка:
```
sudo add-apt-repository ppa:shutter/ppa
sudo apt-get update
sudo apt-get install shutter
```

## 1.3. OBS Studio

OBS Studio – свободное программное обеспечение, предназначенное для записи экрана и ведения трансляций.

Установка:
```
sudo add-apt-repository ppa:obsproject/obs-studio
sudo apt-get update
sudo apt-get install obs-studio
```

## 1.4. OBS Linux Browser Plugin

OBS Linux Browser Plugin - это Linux-плагин для добавляения в источники браузера для OBS Studio. Разработан на основе встроенной базы Chromium.

Установка:
```
wget https://github.com/bazukas/obs-linuxbrowser/releases/download/0.3.1/linuxbrowser0.3.1-obs20.0.1-64bit.tgz
mkdir -p $HOME/.config/obs-studio/plugins
tar xfvz linuxbrowser0.3.1-obs20.0.1-64bit.tgz -C $HOME/.config/obs-studio/plugins/
```

## 1.5. SimpleScreenRecorder

SimpleScreenRecorder – это инструмент для записи работы игр или программ на рабочем столе Linux, разработанный автором Maarten Baert, целью которого было разработать программу, в которой есть все, что нужно приложению для записи с рабочего стола.

Установка:
```
sudo add-apt-repository ppa:maarten-baert/simplescreenrecorder
sudo apt-get update
sudo apt-get install simplescreenrecorder
```


## 1.6. Joxi (установка вызывает удаление OBS Studio и наоборот)

Joxi - бесплатная программа для создания скриншотов

Установка:
```
wget http://dl.joxi.ru/linux/joxi-amd64.deb
sudo dpkg -i joxi*.deb
```
