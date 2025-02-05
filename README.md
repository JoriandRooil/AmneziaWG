# AmneziaWG

Этот проект представляет собой bash-скрипт, цель которого — максимально просто настроить VPN [AmneziaWG](https://docs.amnezia.org/ru/documentation/amnezia-wg/) на Linux-сервере

## Требования к установке

Поддерживаемые дистрибутивы:
- AlmaLinux 9 и выше  
- Debian 11 и выше  
- Rocky Linux 9 и выше  
- Ubuntu 22.04 и выше

Требуется 2 Гб свободного места для временных файлов

## Установка

1.Перед установкой настоятельно рекомендуется обновить вашу систему до <br> последней доступной версии и выполнить перезагрузку после этого

2.Используйте один из предложенных ниже вариантов:
```bash  
curl -O https://raw.githubusercontent.com/JoricJim/AmneziaWG/refs/heads/main/install.sh
```  
```bash  
wget https://raw.githubusercontent.com/JoricJim/AmneziaWG/refs/heads/main/install.sh
```  

3.Установите права на выполнение:  
```bash  
chmod +x install.sh  
```  

4.Запустите скрипт:  
```bash  
./install.sh  
```

5.Отвечайте на вопросы, задаваемые скриптом. Он установит AmneziaWG на сервер и настроит его
