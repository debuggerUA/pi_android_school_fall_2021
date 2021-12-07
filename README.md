# Fragments & System communication


* https://developer.android.com/guide/components/fragments всю секцию
* https://guides.codepath.com/android/Fragment-Navigation-Drawer
* https://guides.codepath.com/android/ViewPager-with-FragmentPagerAdapter
* https://developer.android.com/guide/components/broadcasts
* https://developer.android.com/training/basics/fragments/fragment-ui.html

### Задания и codelabs

* https://codelabs.developers.google.com/codelabs/android-training-broadcast-receivers/index.html?index=..%2F..android-training#0
* https://codelabs.developers.google.com/codelabs/advanced-android-training-fragments/index.html?index=..%2F..advanced-android-training#0
* https://codelabs.developers.google.com/codelabs/advanced-android-training-fragment-communication/index.html?index=..%2F..advanced-android-training#0

* Переделываем наше приложение на master\detail flow  (пример в есть водной из кодлаб)
* Добавляем Navigation Drawer, в котором будут находится секции Maps, Favorites, etc.
* Экраны переводим на фрагменты для того что бы при выборе секции динамически менять контент на главном экране
* Оставляем только одну главную  Activity
* Если на телефоне меняется заряд батареи, то на каком бы фрагменте мы не находились показываем  snackbar сообщение с текущим зарядом
* Лочим ориентацию приложения только на портретный режим
