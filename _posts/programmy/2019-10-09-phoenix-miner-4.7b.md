---
layout: single
title: Скачать PhoenixMiner 4.7b AMD/NVIDIA Ethereum [2019]
categories: programmy
tags: [Майнинг, PhoenixMiner]
h1: Скачать и настроить Phoenix Miner 4.7b [2019]
---
*PhoenixMiner 4.7b выпущен как версия, решающая ошибки 4 ГБ видеокарт в Windows 10. Скачать и настроить программу поможет эта статья*
![PhoenixMiner](/assets/images/programmy/phoenixminer/PhoenixMiner-4.7b.png)


## Скачать версию 4.7b

> [Скачать с Официального сайта](https://phoenix-miner.github.io)
{: .notice--info}

> [Скачать с Mega](https://mega.nz/#!TaokVIjS!uOFolEkzVSvB5cdABSwvvinTqYNfvlt_XbjgS7-AaHk)
{: .notice--warning}

>[Скачать с Яндекс Диска](https://yadi.sk/d/RhzT4M5c-u8g_g)
{: .notice--success}

## Что нового в версии 4.7b

<ul>
  <li>Новые ядра для Navi (RX5700) с лучшей стабильностью. Нужно решить проблему зависания и перезагрузок, которые некоторые майнеры испытывают с картами Navi.</li>
  <li>Сокращение использования VRAM для карт AMD и Nvidia в Windows и Linux</li>
  <li>Добавлена опция командной строки <code>-config</code> для загрузки файла config.txt. Это позволяет комбинировать параметры командной строки и файл config.txt.</li>
  <li>Добавлена поддержка майнинга QuarkChain (QKC) без переключения DAG на devfee (используйте <code>-coin qkc</code>)</li>
  <li>Добавлена поддержка новейших драйверов AMD для Windows 19.9.3</li>
  <li>Другие небольшие улучшения и исправления. </li>
</ul>
<p>При использовании новой опции <code>-config</code> обратите внимание на следующее:</p>
<ol>
  <li>Важен порядок вариантов. Например, если у нас есть файл config.txt, который содержит <code>-cclock 1000</code>, и мы указываем в командной строке <code>-cclock 1100 -config config.txt</code>, то опция из файла config.txt будет иметь приоритет, а результирующий <code>-cclock</code> будет равен 1000. Если порядок обратный (<code>-config config.txt -cclock 1100</code>), то вторая опция имеет приоритет, и в результате <code>-cclock</code> будет 1100.</li>
  <li>Допускается только одна опция <code>-config</code></li>
  <li>Если вы перезагрузите файл конфигурации клавишей 'c' или с помощью удаленного интерфейса, его параметры будут иметь приоритет над тем, что вы указали в командной строке.</li>
</ol>



## Настройка версии 4.7b

Просто замените <code>0x360d6f9efea21c82d341504366fd1c2eeea8fa9d</code> на свой кошелек
{: .notice--ya}

```
PhoenixMiner.exe -pool eth-ru2.dwarfpool.com:8008 -wal 0x360d6f9efea21c82d341504366fd1c2eeea8fa9d.Phoenix -mode 1 -Rmode 1 -log 0 -mport 0 -etha 0 -tt 79 -tstop 89 -fanmin 30 -coin eth
```
## Батник версии 4.7b

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

> [Скачать с Mega](https://mega.nz/#!TaokVIjS!uOFolEkzVSvB5cdABSwvvinTqYNfvlt_XbjgS7-AaHk)
{: .notice--warning}

>[Скачать с Яндекс Диска](https://yadi.sk/d/RhzT4M5c-u8g_g)
{: .notice--success}
