# os-1-msinstall
### Отчет
### Задание 1. Создание скрипта для автоматизации установки под Windows

### Архиватор **7-zip**
`7z1604-x64.msi /passive /norestart /le "C:\Users\Asya\ITMO\OS\7zip-log.txt" TARGETDIR="C:\Program Files\7-Zip"`  
*Параметры установки:*
  - /passive - Автоматический режим - только указатель хода выполнения
  - /norestart - Не перезапускать после завершения установки
  - /le "C:\Users\Asya\ITMO\OS\7zip-log.txt" вести журнал установки с отображением все сообщений об ошибках в файл 7zip-log.txt
  - TARGETDIR="C:\Program Files\7-Zip" - указание каталога для установки "C:\Program Files\7-Zip"
## Графический редактор **Paint.Net**
`paintnet_4.2.10.exe /auto TARGETDIR="C:\Program Files\Graphics\Paint" DESKTOPSHORTCUT=1`  
*Параметры установки:*
  - /auto - полностью автоматическая установка (в том числе и согласие с лицензией)
  - DESKTOPSHORTCUT=1 - на рабочий стол вывести ярлык для запуска приложения
  - TARGETDIR="C:\Program Files\Graphics\Paint" - указание каталога для установки  "C:\Program Files\Graphics\Paint"
## Векторный графический редактор **Inkscape**
`inkscape-0.92.4-x64.msi /qr /norestart /lw "C:\Users\Asya\ITMO\OS\inkscape-log.txt" TARGETDIR="C:\Program Files\Graphics\Inkscape"`  
*Параметры установки:*
  - /qr - Сокращенный интерфейс
  - /norestart - Не перезапускать после завершения установки
  - /lw "C:\Users\Asya\ITMO\OS\inkscape-log.txt" -вести журнал установки с отображением всех сообщений об устранимых ошибках в файл inkscape-log.txt
  - TARGETDIR="C:\Program Files\Graphics\Inkscape - указание каталога для установки "C:\Program Files\Graphics\Inkscape"
## Офисный редактор **LibreOffice**
`LibreOffice_6.4.2_Win_x86.msi /passive /norestart /le "C:\Users\Asya\ITMO\OS\libreoffice-install-log.txt"`
`LibreOffice_6.4.2_Win_x86_helppack_ru.msi /passive /forcerestart /le+ "C:\Users\Asya\ITMO\OS\libreoffice-install-log.txt"`   
*Параметры установки:*
  - /passive - Автоматический режим - только указатель хода выполнения
  - /norestart - Не перезапускать после завершения установки
  - /forcerestart - Всегда перезапускать компьютер после завершения установки
  - /le "C:\Users\Asya\ITMO\OS\libreoffice-install-log.txt" - вести журнал установки с отображением все сообщений об ошибках в файл libreoffice-install-log.txt
  - /le+ - добавление в существующий файл журнала
## Текстовый редактор **Notepad++**
`npp.7.8.5.Installer.exe /S`  
*Параметры установки:*
  - /S - полностью автоматическая установка
  
  ## Aвтоматическая установка **Java Runtime Environment**
  `jre-8u241-windows-x64.exe INSTALLCFG="C:\Users\Asya\ITMO\OS\config.txt" /L "C:\Users\Asya\ITMO\OS\jre-log.txt"`
  *Параметры установки:*
   -  INSTALLCFG="C:\Users\Asya\ITMO\OS\config.txt - с использованием конфигурационного файла "config.txt"
   -  /L "C:\Users\Asya\ITMO\OS\jre-log.txt" - создание лог-файла с результатами установки
