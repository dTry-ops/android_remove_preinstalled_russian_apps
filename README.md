### Удаление предустановленного российского программного обеспечения 

#### Что случилось?

С 1 апреля 2021 года вступил в силу закон обязующий продавать телефоны с предустанавлинным российским программным обеспечением.
В этот список ПО входит:

* Яндекс.Браузер
* Поисковая система «Яндекс»
* Яндекс.Карты
* Яндекс.Диск
* Почта Mail.ru
* ICQ
* Голосовой помощник «Маруся».
* Новости Mail.ru
* Приложение для пользовательских онлайн-трансляций OK Live
* ВКонтакте
* Одноклассники
* Госуслуги
* Приложение для работы с документами «МойОфис Документы»
* Applist.ru — программа для доступа к списку российских сервисов
* Mir Pay
* Антивирус Kaspersky Internet Security

#### Как это исправить? 

+ Для того чтобы удалить ненужные приложения в android, необходимо включить режим разработчика на телефоне
[Подробнее](https://remontka.pro/developer-mode-android/)

+ Далее установить adb
[Подробнее](https://developer.android.com/studio/releases/platform-tools)

+ Через adb подключиться к телефону
[Подбробнее](https://developer.android.com/studio/command-line/adb)

+ После внутри директории проекта выполнить `cat remove_preinstalled_app.adb | adb shell`

+ В конце в меню разработчика режим разработчика можно отключить
