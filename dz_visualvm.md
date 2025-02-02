# Коментарии к задаче: "Исследование JVM через VisualVM"

21:06:05: Executing ':ru.netology.JvmExperience.main()'...  // Запуск программы, загрузка класса JvmExperience и других необходимых классов с помощью загрузчика классов, помещение в Metaspace метаинформации загруженных классов.

> Task :compileJava UP-TO-DATE

> Task :processResources NO-SOURCE

> Task :classes UP-TO-DATE

> Task :ru.netology.JvmExperience.main() // создание фрейма в стеке для метода main()

Please open 'ru.netology.JvmExperience' in VisualVm

21:06:35.438434300: loading io.vertx

21:06:35.643620900: loaded 529 classes // загрузка 529 новых классов и метаинформации об этих классах в Metaspace

21:06:38.645655300: loading io.netty

21:06:39.043016: loaded 2117 classes // загрузка 2117 новых классов и метаинформации об этих классах в Metaspace

21:06:42.044012900: loading org.springframework

21:06:42.182138400: loaded 869 classes // загрузка 869 новых классов и метаинформации об этих классах в Metaspace

21:06:45.184020900: now see heap

21:06:45.184020900: creating 5000000 objects // создание 5000000 новых объектов в куче

21:06:45.312136900: created

21:06:48.313057300: creating 5000000 objects // создание 5000000 новых объектов в куче

21:06:48.400136600: created

21:06:51.426998400: creating 5000000 objects // создание 5000000 новых объектов в куче

21:06:51.555114500: created

BUILD SUCCESSFUL in 49s

2 actionable tasks: 1 executed, 1 up-to-date

21:06:55: Execution finished ':ru.netology.JvmExperience.main()'.

## Скриншоты VisualVM с комментариями

Metaspace:
![Metaspace](<QIP Shot - Screen 1673.png>)

Heap:
![Heap](<QIP Shot - Screen 1674.png>)

Classes
![Classes](<QIP Shot - Screen 16741.png>)