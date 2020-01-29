---
layout: single
title: Скачать PhoenixMiner 4.9c AMD/NVIDIA Ethereum [2019]
categories: programmy
tags: [Майнинг, PhoenixMiner]
h1: Скачать и настроить Phoenix Miner 4.9c [2019]
---
*PhoenixMiner 4.9c выпущен как стабильная версия, решающая ошибки 4 ГБ видеокарт в Windows 10. Скачать и настроить программу поможет эта статья*
![PhoenixMiner](/assets/images/programmy/phoenixminer/PhoenixMiner-4.9c.png)


## Скачать версию 4.9c

> [Скачать с Официального сайта](https://phoenix-miner.github.io)
{: .notice--info}

> [Скачать с Mega](https://mega.nz/#!zKR2TAaA!Ol2LzPrnjKOrqdCJbm8KAL4KCIjfpYUupMJpIa-uiLA)
{: .notice--warning}

>[Скачать с Яндекс Диска](https://yadi.sk/d/Y39g2646ius_gg)
{: .notice--success}

## Что нового в версии 4.9c

<ul>
	<li>Добавлена опция <code>-rate 2</code> для использования имени команды <code>eth_submitHashRate</code> вместо <code>eth_submitHashrate</code> при соло майнинге</li>
	<li>Добавлена поддержка драйверов AMD Linux <code>19.50-967956</code></li>
	<li>Другие мелкие исправления и улучшения</li>
</ul>


## Настройка версии 4.9c

Просто замените <code>0x360d6f9efea21c82d341504366fd1c2eeea8fa9d</code> на свой кошелек
{: .notice--ya}

```
PhoenixMiner.exe -pool eth-ru2.dwarfpool.com:8008 -wal 0x360d6f9efea21c82d341504366fd1c2eeea8fa9d.Phoenix -mode 1 -Rmode 1 -log 0 -mport 0 -etha 0 -tt 79 -tstop 89 -fanmin 30 -coin eth
```
## Батник версии 4.9c

<a href="/assets/images/programmy/phoenixminer/PhoenixMiner-4.6b-nastroyka.png" class="gray lightbox-image current">
![файлы phoenixminer](/assets/images/programmy/phoenixminer/PhoenixMiner-4.5b-nastroyka.png)<span class="img-tit nev">Настроенные файлы программы</span>
</a>

## Настройка для Nicehash

```
PhoenixMiner.exe -pool stratum+tcp://daggerhashimoto.eu-new.nicehash.com:3353 -wal 16p3MvQB7Va2cAPBahvkBePxqQtwTd77sP -pass x -log 0 -tt 79 -tstop 89 -tstart 85 -fanmin 30 -Rmode 1 -proto 4 -stales 0 -fret 1 -rate 1
```
## Команда  reboot

"-r 1" - закрывает майнер и вызывает файл "reboot.bat" (для Линукс - "reboot.bash" или "reboot.sh") из каталога майнера (если он там есть) если что-то не то с какой-то из видеокарт. Таким образом, вы можете создать файл "reboot.bat" и предпринять какие-то действия, например, перезагрузить компьютер, поместив там строку: "shutdown /r /t 5 /f", где:
- r - перезагрузка;
- t 5 - таймаут завершения работы 5 секунд;
- f - принудительно завершить программы без предупреждения.

### Пример файла reboot.bat

shutdown /r /t 10 /f

```
rem Здесь:
rem - r - перезагрузить компьютер;
rem - t 10 - таймаут завершения работы 10 секунд;
rem - f - принудительно завершить программы без предупреждения.
```

## Загрузка

> [Скачать с Официального сайта](https://phoenix-miner.github.io)
{: .notice--info}

> [Скачать с Mega](https://mega.nz/#!zKR2TAaA!Ol2LzPrnjKOrqdCJbm8KAL4KCIjfpYUupMJpIa-uiLA)
{: .notice--warning}

>[Скачать с Яндекс Диска](https://yadi.sk/d/Y39g2646ius_gg)
{: .notice--success}


[Версия для Linux](https://yadi.sk/d/x2mxalgn2BBH8A)
{: .notice--ya}