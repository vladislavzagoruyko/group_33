# ADB
---------------------------
# Homework 1

|№|Exercise|Command|
|---|---|---|
| 1 | Отобразить подключенный девайс в консолия | .\adb devices |
| 2 | Вывести адрес приложения todolist в системе Android | .\adb shell 'pm list packages -f' | findstr todolist |
| 3 | Установить .apk файл приложения todolist на телефон с компьютера через  ADB | .\adb install E:\QAKsendzov_30\group_33\ADB\TodoList.apk |
| 4 | Сделать скриншот запущенного приложения todolist и сразу скопировать на компьютер в одной команде | .\adb shell screencap -p /storage/emulated/0/DCIM/scrn.png | .\adb pull /storage/emulated/0/DCIM/scrn.png |
| 5 | Вывести в консоль логи приложения todolist | .\adb logcat -d | findstr com.android.todolist |
| 6 | Скопировать логи приложения todolist на компьютер | .\adb logcat -d | findstr com.android.todolist > logs.log |
| 7 | Удалить приложение todolist с телефона через ADB | .\adb uninstall com.android.todolist |
