# Internal & external storage & camera

https://developer.android.com/training/data-storage/files.html
https://developer.android.com/training/camera
https://github.com/Yalantis/uCrop

### Задания и codelabs

https://codelabs.developers.google.com/codelabs/android-storage-permissions/#0
* Работаем на основании приложения с прошлой недели:
* Добавляем возможность просмотреть экран с галереей из собственных фотографий
* Необходимо завести отдельную папку на телефоне, куда ваше приложение будет сохранять фотографии сделанные пользователем
* Когда пользователь попадает на этот экран нужно отображать фотографии в списке подобно тому как мы это делаем на остальных экранах
* Если пользователь будет свайпать фотографию на этом экране то в таком случае мы удаляем фотографию
* После того как пользователь сделает фотографию предлагаем ее обработать с помощью библиотеки uCrop
* После обработки сохраняем полученный результат и отображаем как новый элемент списка
* Так же добавляем возможность скачать фотографию на файловую систему при просмотре фулл скрин фоточки из фликера - отображать ее будем в том же списке что и другие фотографии на файловой системе
* Фотографии сделанные из приложения с камеры пользователя сохранять в приватное хранилище, фотографии из фликера загружать в какую-то папку в общем хранилище
