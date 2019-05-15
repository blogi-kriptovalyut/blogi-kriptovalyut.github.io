---
layout: mining-post-item
title: Как Майнить Akroma (AKA) с помощью видеокарт [2019]
categories: Mining
tags: [крипта]

---
*Акрома - это новая криптовалюта, основанная на эфириуме (алгоритм Даггера Хасимото).*
![майнинг akroma](/images/mining/coins/akroma/akroma.jpeg)


## Немного о проекте acroma.
Акрома - это новая криптовалюта, основанная на эфириуме (алгоритм Даггера Хасимото).

Проект Akroma использует эти мастер-узлы для поддержки функций разработчика. 

***Таким образом, в основной протокол Akroma встроена система стимулирования, которая вознаграждает тех, кто размещает серверы мастер-класса, с помощью AKA.***

 Также в будущем разработчики планируют добавить концепцию Oracles. Оракулы - это системы, которые предоставляют данные для смарт контрактов. Целью сети Oracle является разработка функции, которой разработчики смарт контрактов могут доверять настолько, чтобы получить доступ к результатам предоставленных им данных, поскольку это часто будет катализатором для перемещения токенов.
 
Akroma основана на алгоритме Dagger и может использоваться для майнинга на вашем оборудовании на базе видеокарт от Nvidia или AMD.

Теперь мы рассмотрим шаги, которые необходимо предпринять, чтобы получить монеты Akroma с помощью программы Claymore Dual GPU miner.

### Шаг 1 - создать кошелек Akroma
Сначала нужно создать кошелек Akroma. Для этого нам нужно зайти на сайт 
[https://w.akroma.io](https://w.akroma.io/){:target="_blank"}{:rel="nofollow"}

<a href="/images/mining/coins/akroma/akroma-wallet.jpeg" class="gray lightbox-image current">
![майнинг akroma](/images/mining/coins/akroma/akroma-wallet.jpeg)
</a>


Вам необходимо ввести пароль для будущего кошелька (пароль должен быть длиной 9 символов, и вы можете щелкнуть на глазик, чтобы просмотреть точный пароль, не забудьте сохранить его!).

Теперь нам нужно сохранить файл хранилища ключей (этот файл содержит ВСЕ ваши данные для адреса вашего кошелька и о них нужно заботиться. Не теряйте его! Его невозможно восстановить, если вы его потеряете.).

После сохранения файла вы можете перейти на следующую страницу. Просто нажмите «Я понимаю. Продолжить.».

<a href="/images/mining/coins/akroma/akroma-wallet2.jpeg" class="gray lightbox-image current">
![майнинг akroma](/images/mining/coins/akroma/akroma-wallet2.jpeg)
</a>

На следующей странице вы сможете увидеть свой закрытый ключ, это очень важная информация для вас и вашего кошелька. Я бы порекомендовал сохранить ключ на бумаге, как советуют создатели кошелька, и сохранить эту бумагу в очень безопасном месте. 

***Закрытый ключ - это альтернатива вашему файлу Keystore для входа и доступа к вашей учетной записи.***
<a href="/images/mining/coins/akroma/akroma-wallet3.jpeg" class="gray lightbox-image current">
![майнинг akroma](/images/mining/coins/akroma/akroma-wallet3.jpeg)
</a>
После того как вы все сделали, вы можете наконец получить доступ к своему кошельку.

Вы нажимаете «Сохранить свой адрес».
<a href="/images/mining/coins/akroma/akroma-wallet4.jpeg" class="gray lightbox-image current">
![майнинг akroma](/images/mining/coins/akroma/akroma-wallet4.jpeg)
</a>
Теперь мы можем разблокировать наш кошелек. Используйте «закрытый ключ». Введите наш ключ и нажмите «Разблокировать»

<a href="/images/mining/coins/akroma/akroma-wallet5.jpeg" class="gray lightbox-image current">
![майнинг akroma](/images/mining/coins/akroma/akroma-wallet5.jpeg)
</a>

Наконец мы видим наш кошелек. Мы сохраняем адрес кошелька, он нам понадобится для настройки майнинга.

## Шаг 2. Загрузите Claymore Dual Miner 

Перейдите на официальный сайт Claymore и скачайте последнюю версию майнера.



> [Скачать Claymore's Dual Ethereum AMD+NVIDIA GPU Miner v14.1 (Windows/Linux) с официального сайта Claymore](https://claymore-dual.github.io/ru){:target="_blank"}{:rel="nofollow"}
 
>  [Скачать с Mega - пароль claymore](https://mega.nz/#!rXJSTILb!4V1YhoqrLq_svkZbX9cBVczcH-NVhCyYVDZHwU0ZSb4){:target="_blank"}{:rel="nofollow"}
 
>  [Скачать с Яндекс Диска - пароль claymore](https://yadi.sk/d/N_OHRswOuCISug){:target="_blank"}{:rel="nofollow"}

 
Пока Claymore загружается, мы выберем пул, на котором мы получим монету. Я использую [http://akroma.minerpool.net](http://akroma.minerpool.net){:target="_blank"}{:rel="nofollow"} надежный и стабильный пул для майнинга Акрома. 

Вы всегда можете найти другой пул, используя поиск Google. Но мне нравится этот пул
.
После загрузки распакуйте майнер в рабочую папку и найдите в нем файл Akroma-minerpool.bat», щелкните по нему правой кнопкой мыши и нажмите «Изменить».

<a href="/images/mining/coins/akroma/akroma-claymore.jpeg" class="gray lightbox-image current">
![майнинг akroma](/images/mining/coins/akroma/akroma-claymore.jpeg)
</a>

## Шаг 3. Вписать свой кошелек

 В файле Akroma-minerpool.bat вам необходимо указать свой кошелек и пул, на которым вы будете получать монеты. Пример строки для настройки Claymore's Dual Miner указан в середине главной страницы пула.
 
``` 
EthDcrMiner64.exe -epool eu.akroma.eu:8001 -ewal 0xba7e38d976a03d844ad77a01e0988269267a3237 -eworker Claymore -epsw x -dbg -1 -retrydelay 1 -ftime 55 -tt 79 -ttli 77 -tstop 89 -tstart 85 -fanmin 30 -r 0 -erate 1 -allcoins 1 -allcoins 1
pause
```

Так что я просто покажу свои настройки в файле Akroma-minerpool.bat

```
setx GPU_FORCE_64BIT_PTR 0
setx GPU_MAX_HEAP_SIZE 100
setx GPU_USE_SYNC_OBJECTS 1
setx GPU_MAX_ALLOC_PERCENT 100
setx GPU_SINGLE_ALLOC_PERCENT 100
EthDcrMiner64.exe -epool eu.akroma.eu:8001 -ewal 0xba7e38d976a03d844ad77a01e0988269267a3237 -eworker Claymore -epsw x -dbg -1 -retrydelay 1 -ftime 55 -tt 79 -ttli 77 -tstop 89 -tstart 85 -fanmin 30 -r 0 -erate 1 -allcoins 1 -allcoins 1
pause
```

После внесения изменений в настройках сохраните файл и запустите его. Через несколько секунд вы должны увидеть эту картинку.

<a href="/images/mining/coins/akroma/akroma-claymore-miner.jpeg" class="gray lightbox-image current">
![майнинг akroma](/images/mining/coins/akroma/akroma-claymore-miner.jpeg)
</a>

Теперь через некоторое время на вашем кошельке появятся монеты. Кроме того, вы всегда можете контролировать процесс добычи монет на странице статистики пула.
Приятного вам майнинга.