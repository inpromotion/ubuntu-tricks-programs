# 1. Установка MessengerForDesktop

Информация по установке из репозитория
```
sudo apt-key adv --keyserver pool.sks-keyservers.net --recv 6DDA23616E3FE905FFDA152AE61DA9241537994D
echo "deb https://dl.bintray.com/aluxian/deb <channel> main" | sudo tee -a /etc/apt/sources.list.d/aluxian.list
sudo apt-get update
sudo apt-get install messengerfordesktop
```

# 2. Решение проблем

При возникновении ошибки "JavaScript error in the main process" необходимо отключить следующее:
```
App > Check for Update Automatically
```
