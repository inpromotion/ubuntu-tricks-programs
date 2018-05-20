# СКРИНШОТЫ И СКРИНКАСТЫ (ЗАХВАТ ФОТО, АУДИО, ВИДЕО)

## 1.1. Kazam

Установка:
```
sudo apt-get install kazam
```

## 1.2. Shutter

Установка:
```
sudo add-apt-repository ppa:shutter/ppa
sudo apt-get update
sudo apt-get install shutter
```

## 1.3. OBS Studio

Установка:
```
sudo add-apt-repository ppa:obsproject/obs-studio
sudo apt-get update
sudo apt-get install obs-studio
```

## 1.4. OBS Linux Browser Plugin

Установка:
```
wget https://github.com/bazukas/obs-linuxbrowser/releases/download/0.3.1/linuxbrowser0.3.1-obs20.0.1-64bit.tgz
mkdir -p $HOME/.config/obs-studio/plugins
tar xfvz linuxbrowser0.3.1-obs20.0.1-64bit.tgz -C $HOME/.config/obs-studio/plugins/
```

## 1.5. SimpleScreenRecorder

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
