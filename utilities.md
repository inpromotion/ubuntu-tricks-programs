# УТИЛИТЫ

## 1.1. TLP

TLP - это продвинутая, консольная утилита для управления питанием, которая автоматически применяет нужные настройки для конкретного аппаратного оборудования и знает про разные дистрибутивы линукс и их возможности.

Установка и запуск:
```
sudo apt install tlp tlp-rdw
sudo tlp start
```

## 1.2. Htop

Htop - это продвинутый монитор процессов в системе Linux. Его используют тогда, когда информации, которая выводится при помощи стандартной утилиты top, недостаточно.

Установка и запуск:
```
sudo apt-get install htop
sudo htop
```

## 1.3. ScreenFetch

ScreenFetch - простая терминальная утилита для вывода информации о системе, драйвере и ОЗУ в Linux.

Установка:
```
sudo apt-get install screenfetch
sudo screenfetch
```

## 1.4. Wget

Wget - это программа для "вытягивания" файлов из Internet при помощи протоколов HTTP или FTP.

Установка: 
```
sudo apt-get install wget
```

## 1.5. Pkg-Config

В пакете pkg-config находится инструментарий, предназначенный для передачи пути include и/или путей к библиотекам в скрипты сборки пакета, работающие во время выполнения команд configure и make.

Установка:
```
sudo apt-get install pkg-config
```

## 1.6. Make

Make — утилита, автоматизирующая процесс преобразования файлов из одной формы в другую. Чаще всего это компиляция исходного кода в объектные файлы и последующая компоновка в исполняемые файлы или библиотеки.

Установка:
```
sudo apt-get install make
```

## 1.7. Nasm

Nasm — это ассемблер для семейства Unix-овых операционных систем.

Установка:
```
sudo apt-get install nasm
```

## 1.8. Libtool

Libtool - это такой набор скриптов, входящих в состав GNU toolchain, которые, по идее, должны облегчить процесс сборки и использования динамических библиотек (.so) на разных ОС.

Установка:
```
sudo apt-get install libtool
```

## 1.9. Automake

Automake — это утилита для автоматической генерации файлов Makefile.in из файлов Makefile.am

Установка:
```
sudo apt-get install automake
```

## 1.9. Autoconf

Autoconf — утилита для создания конфигурационных скриптов (configure), которые автоматически настраивают пакеты с исходным кодом для работы в Unix-подобных операционных системах.

Установка:
```
sudo apt-get install autoconf
```

## 1.10. GCC

GNU Compiler Collection (обычно используется сокращение GCC) — набор компиляторов для различных языков программирования, разработанный в рамках проекта GNU.

Установка:
```
sudo apt-get install gcc
```

## 1.11. G++

g++ — традиционное обозначение GNU C++, свободно распространяемого компилятора языка C++. Является частью GCC — коллекции компиляторов GNU.

Установка:
```
sudo apt-get install g++
```

## 1.12. Qt

Qt — кроссплатформенный фреймворк для разработки программного обеспечения на языке программирования C++.

Установка:
```
sudo apt-get install qt5-default
```

## 1.13. QtCreator

Кроссплатформенная свободная IDE для разработки на С, С++ и QML. Поддерживаемые компиляторы: GCC, Clang, MinGW, MSVC, Linux ICC, GCCE, RVCT, WINSCW.

Установка:
```
sudo apt-get install qtcreator
```

## 1.14. Wipe

Wipe - утилита для безопасного полного стирания информации.

Установка:
```
sudo apt-get install wipe
```

## 1.15. Adobe Flash Player Plugin / Browser Plugin

Adobe Flash Player — это облегченный подключаемый модуль для браузера и среды выполнения расширенных веб-приложений (RIA), который обеспечивает комплексное и удобное взаимодействие, потрясающее воспроизведение аудио и видео, а также невероятное быстродействие веб-игр.

Установка Adobe Flash Player Plugin:
```
sudo apt-get install adobe-flashplugin
```

Установка Adobe Flash Browser Plugin:
```
sudo apt install browser-plugin-freshplayer-pepperflash
```

## 1.16. Java (JDK).

Java Development Kit (JDK) - бесплатно распространяемый компанией Oracle Corporation комплект разработчика приложений на языке Java, включающий в себя компилятор Java, стандартные библиотеки классов Java, примеры, документацию, различные утилиты и исполнительную систему Java.

Установка:
```
sudo apt-get install default-jdk
````

## 1.17. Java (JRE)

Java Runtime Environment (JRE) - Это всё, что вам нужно для запуска Java-приложений на своей системе.

Установка:
```
sudo apt-get install default-jre
```

## 1.18. Java (Icedtea plugin)	

Java Icetea plugin - плагин для поддержки в браузерах Java.

Установка:
```
sudo apt-get install icedtea-plugin
```

## 1.19. Python3

Python - это один из самых популярных языков программирования для Linux. На нем написано множество различных инструментов и библиотек.

Установка:
```
sudo apr-get install python3
```

## 1.20. Java 8

Java 8 — сильно типизированный объектно-ориентированный язык программирования, разработанный компанией Sun Microsystems (в последующем приобретённой компанией Oracle).

Установка:
```
sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update
sudo apt install oracle-java8-installer
```

## 1.21. Gdebi

Gdebi — это простой инструмент для установки файлов Debian, что позволяет устанавливать локальные пакеты .deb и устранять зависимости.

Установка:
```
sudo apt-get install gdebi
```

## 1.22. GParted

Gparted - hедактор дисковых разделов, являющийся графической оболочкой к GNU Parted. 

Установка:
```
sudo apt-get install gparted
```

## 1.23. TeamViewer

TeamViewer - пакет программного обеспечения для удалённого контроля компьютеров совместного использования, обмена файлами между управляющей и управляемой машинами, видеосвязи и веб-конференций.

Установка:
```
wget https://download.teamviewer.com/download/linux/teamviewer_amd64.deb
sudo dpkg -i teamviewer*_amd64.deb
```

## 1.24. Bleachbit

Установка:
```
wget https://www.bleachbit.org/download/file/t?file=bleachbit_2.0_all_ubuntu1710.deb
sudo dpkg -i bleachbit*.deb
```

## 1.25. Transmission

Установка:
```
sudo add-apt-repository ppa:transmissionbt/ppa
sudo apt-get update 
sudo apt-get install transmission-gtk
```


## 1.26. kTorrent

Установка:
```
sudo apt-get install ktorrent
```

## 1.27. qTorrent

Установка:
```
sudo apt-get install qbittorrent
```

## 1.28. KeePass2

Установка:
```
sudo apt-add-repository ppa:jtaylor/keepass
sudo apt-get update
sudo apt-get install keepass2
```

## 1.29. Python-GTK2

Python-ПЕЛ2 - набор Python-привязок для библиотеки графического интерфейса GTK+, является свободным ПО и распространяется на условиях GNU LGPL.

Установка:
```
sudo apt-get install python-gtk2
sudo apt-get --fix-broken install
```
