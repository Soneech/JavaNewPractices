# MireaJavaPractice4Term

## [Practice 1](https://github.com/Soneech/MireaJavaPractice4Term/tree/master/Practices1-8/src/main/java/org/soneech/practice1)
Имплементировать интерфейс Comparator, сравнивающий две строки по сумме всех чисел, представленных в строке.

## [Practice 2](https://github.com/Soneech/MireaJavaPractice4Term/tree/master/Practices1-8/src/main/java/org/soneech/practice2)
В ходе выполнения практической работы должно быть реализовано:
- класс Human (int age, String firstName, String lastName, LocalDate birthDate, int weight);
- приложение, которое создает список из объектов класса Human, а затем производит действия в соответствии с вариантом индивидуального задания (список после каждого этапа должен выводиться в консоль).

Все действия должны производиться только с использованием Stream API.
Задание варианта: Сортировка по возрасту в обратном порядке, фильтрация по имени «начинается с А», сортировка по дате рождения, расчет среднего веса.

## [Practice 3](https://github.com/Soneech/MireaJavaPractice4Term/tree/master/Practices1-8/src/main/java/org/soneech/practice3)
Создать свои потокобезопасные имплементации интерфейсов в соответствии с вариантом индивидуального задания.
Задание варианта: Set с использованием Semaphore, List с использованием ключевого слова synchronized.

## [Practice 4](https://github.com/Soneech/MireaJavaPractice4Term/tree/master/Practices1-8/src/main/java/org/soneech/practice4)
Реализовать собственную имплементацию ExecutorService с единственным параметром конструктора – количеством потоков.

## [Practice 5](https://github.com/Soneech/MireaJavaPractice4Term/tree/master/Practices1-8/src/main/java/org/soneech/practice5)
Реализовать паттерн Singleton как минимум 3-мя способами.

## [Practice 6](https://github.com/Soneech/MireaJavaPractice4Term/tree/master/Practices1-8/src/main/java/org/soneech/practice6)
Написать реализацию паттернов «Фабричный метод», «Абстрактная фабрика», «Строитель», «Прототип».

## [Practice 7](https://github.com/Soneech/MireaJavaPractice4Term/tree/master/Practices1-8/src/main/java/org/soneech/practice7)
Написать реализацию паттерна в соответствии с вариантом индивидуального задания:  Фасад, Легковес.

## [Practice 8](https://github.com/Soneech/MireaJavaPractice4Term/tree/master/Practices1-8/src/main/java/org/soneech/practice8)
Написать реализацию паттерна в соответствии с вариантом индивидуального задания: Снимок, Наблюдатель.

## [Practice 9](https://github.com/Soneech/MireaJavaPractice4Term/tree/master/Practice9)
Создать приложение, которое выводит какое-то сообщение в консоль. Создать Gradle Task, который создает jar-файл приложения, переносит его в отдельную папку, в которой хранится Dockerfile для jar, а затем создает Docker контейнер из данного jar-файла и запускает его.

## [Practice 10](https://github.com/Soneech/MireaJavaPractice4Term/tree/master/Practice10)
Создать приложение, в котором создается ApplicationContext и из него берётся бин с названием, переданным в качестве аргумента к приложению, и вызывается метод интерфейса, который он имплементирует. Нужно создать по одному бину для каждого класса, определить им название. Проверить, что вызывается при вводе названия каждого из бинов. Классы и интерфейс определяются в соответствии с вариантом индивидуального задания. 

Задание варианта: Интерфейс Musician с методом doMusic(), его имплементации: Drummer, Guitarist, Trombonist.

## [Practice 11](https://github.com/Soneech/MireaJavaPractice4Term/tree/master/Practice11)
Создать приложение с использованием Spring Boot Starter Initializr (https://start.spring.io/) с такими зависимостями:
– Spring Web;
– Lombok;
– Validation;
– Spring boot Actuator.

Запустить приложение и удостовериться, что не появилось никаких ошибок. Добавить все эндпоинты в Actuator, сделать HTTP-запрос на проверку состояния приложения. Собрать jar-файл приложения, запустить и проверить состояние при помощи REST-запроса.

## [Practice 12](https://github.com/Soneech/MireaJavaPractice4Term/tree/master/Practice12)
Создать приложение, которое при запуске берет данные из одного файла, хеширует, а при остановке приложения удаляет исходный файл, оставляя только файл с захешированными данными. Названия первого и второго файла передаются в качестве аргументов при запуске (я сделаль немношк по-другому, ибо почему бы и нет). При отсутствии первого файла создает второй файл и записывает в него строку null. Реализовать с использованием аннотаций PostConstruct, PreDestroy.
