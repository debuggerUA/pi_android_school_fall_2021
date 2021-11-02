# Списки, сохранение данных на диске

### Списки
https://www.youtube.com/watch?v=G35pcPv_tEA
https://developer.android.com/guide/topics/ui/layout/recyclerview
https://developer.android.com/reference/androidx/recyclerview/widget/RecyclerView.html
https://developer.android.com/reference/androidx/recyclerview/widget/ItemTouchHelper
https://github.com/bumptech/glide


### Хранение данных
https://developer.android.com/guide/topics/data/data-storage
https://developer.android.com/training/data-storage/shared-preferences
https://developer.android.com/training/data-storage/sqlite.html
https://developer.android.com/training/data-storage/room
https://youtu.be/A-P6EDw5z_s
http://facebook.github.io/stetho/ Для работы с БД в живую на девайсе
https://developer.android.com/studio/inspect/database Встроенный в студию инспектор для БД


### Задания и codelabs
https://codelabs.developers.google.com/codelabs/android-training-livedata-viewmodel/index.html?index=..%2F..android-training#0
https://codelabs.developers.google.com/codelabs/android-training-room-delete-data/index.html?index=..%2F..android-training#0
https://codelabs.developers.google.com/codelabs/android-training-create-recycler-view/index.html?index=..%2F..android-training#0

Работаем на основе приложения с прошлой недели:
* Применяем RecyclerView для отображения результатов поиска
* Отобразить результаты в карточке (CardView)
* На каждой карточке должна отображаться картинка и запрос по которому картинка получена
* Пользователь должен иметь возможность свайпнуть её в сторону (удалить из списка)
* Организовать локальную БД для хранения необходимых данных
* Сделать экран входа (формальный без пароля) и сохранять все данные на каждого отдельно взятого пользователя:
    * При выходе из приложения сохраняем текст введённый в поисковую строку и восстанавливаем при запуске
    * На экране просмотра фотографии нужно выводить текст поискового запроса, по которому была найдена фотография
    * На экране просмотра фотографии нужно добавить функцию - сохранение/удаление в Избранные, реализовать одним View
* Добавить возможность на главном экране перейти на экран Избранные. В нём отображаем избранные фотографии с группировкой по поисковым запросам: запрос по которому лайкались фотки - отдельный элемент списка, после которого идут все фотографии которые ему соответствуют (пример https://www.b4x.com/android/forum/attachments/android_listview_header_section-523x1024-png.64031/)
* Если на экране Избранные пользователь свайпает фотографию - её необходимо удалить из списка Избранные и в базе данных
* На экране Избранные на каждой карточке отобразить кнопку, которая позволит убрать фотографию из списка (помимо свайпа)
* Создать экран с историей запросов
* Дополнительное задание: на главном экране необходимо реализовать бесконечный список с догрузкой (в случае наличия данных на API)

