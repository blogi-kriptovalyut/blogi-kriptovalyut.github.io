---
layout: single
title: Скачать Phoenix Miner 4.5b AMD/NVIDIA Ethereum [Июль 2019]
categories: programmy
tags: [Майнинг, PhoenixMiner]
h1: Скачать Phoenix Miner 4.5b
---
*Вышла версия 4.5b Phoenix Miner. Скачать и настроить программу поможет эта статья*
![PhoenixMiner](/assets/images/programmy/phoenixminer/PhoenixMiner-4.5b.png)

## Скачать версию 4.5b

> [Скачать с Официального сайта](https://phoenix-miner.github.io)
{: .notice--info}

> [Скачать с Mega](https://mega.nz/#!rXZymQAL!nTcvj-tnALygEkq1QzD-yxUZvAOw_ho5-u5VfXe_L3A)
{: .notice--warning}

>[Скачать с Яндекс Диска](https://yadi.sk/d/yHnpOZ3sj0alzg)
{: .notice--success}

## Что нового в версии 4.5b

4.5b
<ul>
  <li><p>Изменения в ядрах Nvidia для более стабильной работы и лучшего использования видеокарт</p></li>
  <li><p>Также реализован майнинг ProgPOW BCI для карт Nvidia. Под Windows вы должны скачать и распаковать файл PhoenixMiner_NVRTC_Windows.zip в той же папке, что и PhoenixMiner.exe, чтобы добывать BCI с картами Nvidia.</p></li>
  <li><p>Добавлена ​​поддержка всех новых драйверов AMD для Windows до последней версии 19.7.2</p></li>
  <li><p>Добавлена ​​поддержка всех новых драйверов AMD Linux до последней версии 19.30-838629</p></li>
  <li><p>Добавлен аппаратный контроль и мониторинг (разгон, напряжение, вентиляторы и т. д.) Для карт Nvidia под Windows. Обратите внимание, что вы должны указать разгон для карт Nvidia относительно значений по умолчанию (например, <code>-mclock +400</code> вместо <code>-mclock 4400</code>)</p></li>
  <li><p>Добавлен аппаратный контроль и мониторинг (разгон, напряжение, вентиляторы и т. д.) Для карт Radeon VII (только для Windows)</p></li>
  <li><p>Добавлен расширенный мониторинг оборудования (укажите <code>-hstats 2</code> для его активации). Он покажет вам частоту ядра и памяти видеокарт, напряжения и P-состояния (если поддерживается)</p></li>
  <li><p>Добавлено энергопотребление видеокарт, если драйвер сообщает об энергопотреблении. Вы также можете указать мощность холостого хода (<code>-pidle</code>), эффективность блока питания / видеокарт (<code>-ppf</code>) и стоимость электроэнергии (<code>-prate</code>) и рассчитать для вас ежедневные затраты на электроэнергию. Если вы используете стороннее программное обеспечение для майнинга, которое не ожидает данных о потребляемой мощности в журнале майнера, вы можете отключить его, указав <code>-hstats 0</code></p></li>
  <li><p>Добавлен новый параметр <code>-mt</code> для установки таймингов памяти на картах AMD. <code>-mt 0</code> является значением по умолчанию, которое использует тайминги памяти VBIOS. <code>-mt 1</code> и <code>-mt 2</code> используют предопределенные тайминги памяти, которые не зависят от таймингов VBIOS. Эта опция полезна для майнинга с картами RX580 / 570/560/480/470/460 без прошивки Биоса. Это работает только на Windows и с относительно недавними драйверами (за последние 6-8 месяцев)</p></li>
  <li><p>Стендовый режим теперь работает для дуал майнинга и ProgPOW. Алгоритм определяется параметрами <code>-coin</code> и <code>-dcoin</code>. Например. <code>-bench 10</code> <code>-coin bci</code> будет тестировать BCI ProgPOW, а <code>-bench 10</code> <code>-dcoin blake2s</code> будет тестировать дуал майнинг</p></li>
  <li><p>Увеличена максимальная поддерживаемая DAG эпоха до 450. Обратите внимание, что драйверы AMD не допускают буферов размером более 4 ГБ, поэтому максимально возможная DAG эпоха с текущими драйверами AMD составляет 378.</p></li>
  <li><p>Добавлена ​​возможность прочитать <code>«FriendlyName»</code> из реестра Windows и использовать его (если доступно) вместо общего имени карты из драйвера.</p></li>
  <li><p>Исправлены пулы devfee для некоторых альтернативных монет, таких как PIRL и других, в которых многие пулы либо исчезли, либо используют старые версии pre-fork клиентов и добывают не на той цепочке блоков.</p></li>
  <li><p>Другие небольшие улучшения и исправления.</p></li>
</ul>



## Настройка батника

Просто замените <code>0x360d6f9efea21c82d341504366fd1c2eeea8fa9d</code> на свой кошелек
{: .notice--ya}


```
PhoenixMiner.exe -pool eth-eu2.nanopool.org:9999 -wal 0x360d6f9efea21c82d341504366fd1c2eeea8fa9d -worker Phoenix -epsw x -mode 1 -Rmode 1 -log 0 -mport 0 -etha 0 -retrydelay 1 -tt 79 -tstop 89 -tstart 79 -fanmin 30 -coin eth
```
## Батник

<a href="/assets/images/programmy/phoenixminer/PhoenixMiner-4.5b-nastroyka.png" class="gray lightbox-image current">
![файлы claymore](/assets/images/programmy/phoenixminer/PhoenixMiner-4.5b-nastroyka.png)<span class="img-tit nev">Настроенные файлы программы</span>
</a>

## Загрузка

> [Скачать с Официального сайта](https://phoenix-miner.github.io)
{: .notice--info}

> [Скачать с Mega](https://mega.nz/#!rXZymQAL!nTcvj-tnALygEkq1QzD-yxUZvAOw_ho5-u5VfXe_L3A)
{: .notice--warning}

>[Скачать с Яндекс Диска](https://yadi.sk/d/yHnpOZ3sj0alzg)
{: .notice--success}
