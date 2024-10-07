# Учебное пособие по Java Core

Серия учебных пособий по основам Java, примеры для изучения и закрепления основных технологий Java, лучшая практика для начинающих и укрепления основных технологий.
Включает базовый синтаксис, ООП, строки, коллекции, ввод-вывод, рефлексию, потоки, сеть и т.д.
Незавершенные модули: руководство Alibaba Java, java8, аннотации, fork/join, шифрование/дешифрование и т.д.

## "Руководство по разработке Java"

-   «Серия уроков по руководству Java: Почему обязательно разные имена переменных для подклассов и родительских классов?»
-   «Размышления о руководстве по разработке Java»
-   "Продвинутый Java"

## "Java Collections"

-   «Java Containers & Generics: 1. Знакомство с контейнерами»
-   «Java Containers & Generics: 2. Сравнение ArrayList, LinkedList и Vector»
-   «Java Containers & Generics: 3. Сравнение HashSet, TreeSet и LinkedHashSet»
-   «Java Containers & Generics: 4. Алгоритмы Collections.sort и Arrays.sort»
-   «Java Containers & Generics: 5. Откровения HashMap и TreeMap»
-   «Java Containers & Generics: 6. Почему контейнеры используют обобщения»
-   "Java IO"

## «Java I/O: Битовые операции»

-   «Иллюстрированный Java IO: 1. Исходный код File»
-   «Иллюстрированный Java IO: 2. Исходный код FilenameFilter»
-   «Java IO: Исходный код InputStream»
-   «Java IO: Исходный код OutputStream»
-   «Java IO: Анализ исходного кода FileInputStream & FileOutputStream»
-   «Итоговая схема Java IO»

## Структура проекта

-   Директория src
-   Код для изучения основных технологий Java и тестовые примеры
-   Директория test (имена пакетов тестов соответствуют директории src)
-   Подробные тестовые примеры для соответствующих учебных пакетов кода

## Структура пакетов:

    ├── org.rpc // Простая реализация RPC на основе Java Dynamic Proxy & Socket
    =================Красивая разделительная линия=================
    ├── org.javacore.base // Основы Java
    ├── org.javacore.collection // Java Collections
    ├── org.javacore.collection.list // Java Collections List
    ├── org.javacore.collection.map // Java Collections Map
    ├── org.javacore.collection.queue // Java Collections Queue
    ├── org.javacore.collection.set // Java Collections Set
    ├── org.javacore.collection.util // Утилиты Java Collections
    ├── org.javacore.initAndCleanup // Инициализация и очистка в Java
    ├── org.javacore.io // Java IO
    ├── org.javacore.io.byteoper // Java IO операции с байтами
    ├── org.javacore.io.zip // Java IO ZIP сжатие/распаковка
    ├── org.javacore.nio // Java NIO
    ├── org.javacore.reflection // Java Reflection
    ├── org.javacore.rtti // Java RTTI
    ├── org.javacore.thread // Java Threads
    =================Практика JAVA 8=================
    ├── org.javacore.lambda // Лямбда-выражения
    ├── org.javacore.stream // Stream API для потоковых операций с коллекциями
    │

Подробное содержание:

    ├── README.md // Единственный подробный документ проекта
    ├── org.javacore.base // Основы Java
    ├── CopyT.java // Глубокое и поверхностное копирование
    ├── org.javacore.base.inter // Java интерфейсы
    ├── ApplyClass.java // Пример интерфейса без использования интерфейса
    ├── ApplyInter.java // Пример интерфейса с использованием интерфейса
    ├── org.javacore.collection // Java Collections
    ├── PerBtwnAllCollectionsT.java // Сравнение производительности методов добавления для разных коллекций
    ├── org.javacore.collection.list // Java Collections List
    ├── ArrayListT.java // Использование ArrayList
    ├── PerBtwnArlAndLklT.java // Сравнение производительности ArrayList и LinkedList
    ├── org.javacore.collection.map // Java Collections Map
    ├── HashMapObjT.java // Определяющие факторы для работы HashMap с объектами: hashCode и equals
    ├── HaspMapT.java // Метод Add в HashMap
    ├── TreeMapT.java // Использование TreeMap
    ├── org.javacore.collection.queue // Java Collections Queue
    ├── PriorityQueueT.java // Использование PriorityQueue
    ├── org.javacore.collection.set // Java Collections Set
    ├── HashSetObjT.java // Определяющие факторы для работы HashSet с объектами: hashCode и equals
    ├── HashSetsCopyT.java // Преобразование и использование HashSet и его подклассов
    ├── HashSetT.java // Метод Add в HashSet
    ├── SetContainT.java // Метод Contains в Set
    ├── TreeSetT.java // Работа TreeSet с объектами, реализующими интерфейс Comparable
    ├── org.javacore.collection.util // Утилиты Java Collections
    ├── CollectionsT.java // Использование Collections
    ├── IterAndListIterT.java // Различия между Iterator и ListIterator
    ├── PerBtwnEmptyMapAndHashMapT.java // Сравнение производительности Collections.EMPTY_MAP и new HashMap
    ├── org.javacore.initAndCleanup // Инициализация и очистка в Java
    ├── SimpleConstructor.java // Демонстрация простого конструктора
    ├── SimpleConstructor2.java // Демонстрация простого конструктора с параметрами
    ├── VoidConstructor.java // Различия между конструктором по умолчанию и методом
    ├── org.javacore.io // Java IO
    ├── BufferedInputFileT.java // Буферизованный ввод файла
    ├── CopyFileT.java // Копирование файлов
    ├── Directory.java // Утилиты для работы с директориями
    ├── DirListT.java // Список директорий с сортировкой
    ├── FileIOStreamT.java // Примеры использования FileInputStream и FileOutputStream
    ├── FileMethodsT.java // Подробное использование методов File
    ├── FilenameFilterT.java // Использование фильтра имен файлов
    ├── FileT.java // Использование класса File
    ├── FormatteMemoryInput.java // Форматированный ввод из памяти
    ├── JavaFileListT.java // Использование FilenameFilter для фильтрации файлов
    ├── MemoryInputT.java // Ввод из памяти
    ├── PipeStreamT.java // Использование потоков PipedInputStream и PipedOutputStream
    ├── RandomAccessFileT.java // Использование RandomAccessFile
    ├── StoringAndRecoveringData.java // Примеры использования DataOutputStream и DataInputStream
    ├── SystemStreamT.java // Использование IO в System.out и System.err
    ├── UsingRandomAccessFile.java // Пример использования RandomAccessFile
    ├── org.javacore.io.byteoper // Java IO операции с байтами
    ├── IntegerConvertT.java // Преобразование между Integer и массивом байтов
    ├── IntegerOperT.java // Преобразование систем счисления в классе Integer
    ├── LongConvertT.java // Преобразование между Long и массивом байтов
    ├── StringConvertT.java // Преобразование String в массив байтов
    ├── org.javacore.io.zip // Java IO ZIP сжатие/распаковка
    ├── GZIPcompress.java // Простое использование GZIP
    ├── ZipCompress.java // Использование Zip для сохранения нескольких файлов
    ├── org.javacore.nio // Java NIO
    ├── AvailableCharSets.java // Вывод доступных CharSet
    ├── BufferToText.java // Примеры преобразования между ByteBuffer и char
    ├── ChannelCopy.java // Пример копирования файлов с использованием FileChannel
    ├── Endians.java // Порядок хранения байтов в ByteBuffer
    ├── FileChannelT.java // Пример чтения и записи файлов с использованием FileChannel
    ├── FileChannelTransferTo.java // Примеры использования transferTo/transferFrom в FileChannel
    ├── FileLocking.java // Блокировка файлов
    ├── GetChannel.java // Примеры получения FileChannel из потоков
    ├── GetData.java // Примеры работы с данными разных типов в ByteBuffer
    ├── IntBufferDemo.java // Работа с данными типа int в ByteBuffer через IntBuffer
    ├── LargeMappedFiles.java // Использование отображения файлов в память
    ├── MappedIO.java // Сравнение производительности MappedByteBuffer и Old IO
    ├── UsingBuffers.java // Использование буферов для обмена соседних символов
    ├── ViewBuffers.java // Буферы с разными представлениями
    ├── org.javacore.reflection // Java Reflection
    ├── ArrayCopy.java // Расширение массива объектов с помощью рефлексии
    ├── EmployeeClass.java // Пример использования рефлексии в наследовании
    ├── ObjectAnalyzer.java // Инструмент анализа объектов с помощью рефлексии
    ├── ReflectionTest.java // Рефлексия конструкторов, методов и полей объектов
    ├── User.java // Bean для использования в примере рефлексии конструкторов
    ├── UserConstructorReflect.java // Создание экземпляра с помощью рефлексии конструктора
    ├── org.javacore.rtti // Java RTTI
    ├── ClassInitialization.java // Пример инициализации Class
    ├── ShowMethods.java // Пример получения методов Class
    ├── org.javacore.thread // Java Threads
    ├── BasicThreads.java // Простое использование потоков
    ├── CachedThreadPool.java // Простое использование пула потоков CachedThreadPool
    ├── CallableDemo.java // Использование интерфейса Callable --- реализация задач с возвращаемым значением
    ├── DaemonFromFactory.java // Использование фабрики фоновых потоков
    ├── DaemonThreadFactory.java // Класс фабрики потоков
    ├── DaemonsDontRunFinally.java // Фоновые потоки и блок Finally
    ├── FixedThreadPool.java // Простое использование пула потоков FixedThreadPool
    ├── LiftOff.java // Реализация интерфейса Runnable - класс LiftOff
    ├── MoreBasicThreads.java // Простое использование потоков - запуск нескольких потоков
    ├── MyRunnable.java // Простое использование интерфейса Runnable
    ├── MyThread.java // Простое использование Thread
    ├── SimpleDaemons.java // Простое использование фоновых потоков Daemon
    ├── SimplePriorities.java // Использование приоритетов потоков
    ├── SingleThreadExecutor.java // Использование SingleThreadExecutor
    ├── SleepingTask.java // Использование sleep для приостановки потока

## Метод обучения

Изучайте материал блок за блоком, следуя структуре пакетов. Затем для каждого класса смотрите соответствующий пакет test или примеры тестов непосредственно в src для изучения.
