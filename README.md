# hitchhikers-guide-to-my-repos

В основном пишу на языках низкого уровня типо ассемблера архитектур x86_64 и базово RISC-V; и C. Поэтому увлекаюсь вопросами встроенных системам и IoT. Среди проектов у меня в основном различные учебные проекты и модули устройств для ядра Linux:
1. Символьные, блочные, сетевые модули устройств для ядра Linux (работа проверялась в основном на Ubuntu 20.04-22.04) - https://github.com/Come1LLF00/device-drivers-development
2. Агломеративная иерархическая кластеризация на C (https://github.com/Come1LLF00/nuke), так что да я знаком с некоторыми методами машинного обучения
3. Многопоточное приложение с использованием Posix Threads (https://gitlab.se.ifmo.ru/system-software/ifmo-spring-2022/posix/come_ill_foo)
4. Аллокатор памяти с использованием системного вызова mmap (https://gitlab.se.ifmo.ru/come_ill_foo/assignment-memory-allocator)
5. Сепия фильтр с использованием ассемблерных SIMD инструкций на архитектуре x86_64 (https://gitlab.se.ifmo.ru/come_ill_foo/assignment-sepia-filter)
6. Базовые функции ввода-вывода на ассемблере x86_64 (https://gitlab.se.ifmo.ru/come_ill_foo/assignment-1-io-library)
7. Разворот картинки в формате BMP на C (https://gitlab.se.ifmo.ru/come_ill_foo/assignment-image-rotation)
8. Компилятор Pascal-подобного языка, строящий AST дерево и транслирующий его в трёхадресный код. Используются flex и bison (https://github.com/Come1LLF00/student-pc)
9. Знаком с форматами исполняемых файлов PE и ELF

Знаком с отладочной платой Xilinx Nexys 4 DDR и писал для нее прошивки на Verilog HDL в Vivado Design Suite (также знаком с Icarus Verilog):
1. Доработка однотактового RISC-V процессора своими инструкциями (https://github.com/Come1LLF00/schoolRISCV)
2. Модуль вычисляющий математическую функцию (использует семисегментный индикатор и переключатель для взаимодействия с пользователем) - https://github.com/Come1LLF00/rtl_math_acc

Также писал CRUD с использованием Java + Spring Boot + Vue.js + PostgreSQL + REST API:
1. Фронтенд (https://github.com/Come1LLF00/looking-glass)
2. Бэкенд (https://github.com/Come1LLF00/alicization)
3. Скрипты для создания модели в БД (https://github.com/Come1LLF00/alice_in_the_wonderland)

Пользовался различными инструментами тестирования и мониторинга и анализа бинарных файлов:
1. JUnit 5 (https://github.com/Come1LLF00/integration-test-functional-system)
2. Selenium IDE + Selenide (https://github.com/Come1LLF00/fishki-dnet-testing)
3. Apache JMeter (нагрузочное и стресс-тестирование университетских учебных стендов)
4. Анализ трафика различных протоколов с Wireshark
5. Binutils (readelf, objdump, nm)
6. Различные утилиты Linux (ps, top, pidstat, netstat, tcpdump, ...) - сборник питоновских оберток над стандартными утилитами для удобства сбора метрик во времени и сохранением их в графики https://github.com/Come1LLF00/cifostoolbox

Помимо просто утилит на Python 3 также по работе пользовался и такими популярными библиотеками, как Celery (брокер и бэкенд Redis в Docker-контейнере), Flask, Socket.IO, SQLAlchemy и JSON-RPC.

С Docker-ом знаком на уровне запуска готовых образов из docker hub и написании простеньких Dockerfile-ов для создания своих образов. Есть небольшой опыт настройки совсем простеньких CI/CD на gitlab (https://gitlab.se.ifmo.ru/come_ill_foo/assignment-sepia-filter) и на github (https://github.com/Come1LLF00/schoolRISCV/actions).

Есть простенькие проекты по шаблону для STM32F427:
1. Калькулятор с использованием клавиатуры и oLED-дисплея (https://github.com/Come1LLF00/SDK_Calculator)
2. Обработка прерываний с таймеров (https://github.com/Come1LLF00/SDK_cLab_interruptions)
Разрабатывались в STM32 Cube IDE.
