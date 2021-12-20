
# Week 10

# Уведомления

* https://developer.android.com/training/best-background
* https://developer.android.com/topic/libraries/architecture/workmanager
* https://developer.android.com/guide/topics/ui/notifiers/notifications
* https://developer.android.com/reference/android/app/Service

### Задания и codelabs

* https://codelabs.developers.google.com/codelabs/notification-channels-java/index.html?index=..%2F..index#0
* https://codelabs.developers.google.com/codelabs/android-workmanager/index.html?index=..%2F..index#0

* Добавляем экран настроек, выполненый в стиле системных настроек Android
* На этом экране добавляем возможность включать/отключать запросы приложения на обновление фото в фоне
* Если пользователь разрешает такие обновления - разрешаем выбрать периодичность (15 минут, 30 минут, 1 час, 6 часов, сутки)
* Приложение, работая в фоне, должно будет с указанной периодичностью ходить на сервер и получать новые фотографии
* После успешного обновления сохранять их в отдельную таблицу в базе, добавить возможность просмотра этих фотографий на отдельном экране (фрагменте)
* После успешного обновления показывать уведомление, содержищее preview одной из полученых фотографий
* В уведомлении отображать количество полученных фотографий
* При нажатии на уведомление переходить на экран просмотра скаченных фотографий
