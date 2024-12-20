#  LESSON 78
### voprosi

1. Шифрование защищает конфиденциальность данных, делая их недоступными без ключа. Кодирование преобразует данные для удобного хранения и передачи, не обеспечивая защиты.

2. Ключ в — это специальный параметр или набор символов, используемый для шифрования/дешифрации данных, аутентификации, доступа к ресурсам или идентификации объектов.

3. Наука, изучающая методы шифрования, называется криптографией.

4. Симметричный шифр - это метод шифрования, при котором обе стороны-участники обмена данными имеют одинаковые ключи для шифрования и расшифровки данных. Основная проблема при использовании симметричного шифра, когда участники переписки находятся в разных странах, связана с передачей этого общего ключа. Если ключ попадет в руки третьих лиц, вся переписка станет уязвимой для чтения.

5. Несимметричные шифры (асимметричная криптография) — это методы шифрования, использующие две пары ключей: публичный и приватный. Публичный ключ доступен всем и используется для шифрования сообщений, а приватный ключ известен только владельцу и служит для расшифровки. Надежность этих шифров основана на сложности математической задачи разложения больших чисел на простые множители или вычисления дискретных логарифмов, что делает практически невозможным взлом шифра без знания приватного ключа.

6. Криптостойкость алгоритма - это его способность противостоять криптоанализу. Алгоритм считается криптостойким, если успешная атака на него требует недостижимых объемов вычислительных ресурсов или значительного времени, что делает информацию устаревшей к моменту ее раскрытия. Криптостойкость зависит от сложности математической задачи, лежащей в основе алгоритма, такой как разложение числа на простые множители или вычисление дискретных логарифмов.

# LESSON 79
### voprosi

1. Хэширование — это процесс преобразования данных в строку фиксированной длины с помощью хэш-функции.

Хэш-функция — это математический алгоритм, который выполняет это преобразование.

Хэш-код — это результат работы хэш-функции, строка фиксированной длины, представляющая исходные данные.

2. Для поиска слова в словаре обычно используется хэш-функция, основанная на делении хэш-кода слова на размер хэш-таблицы.

3. Коллизии — это ситуация, когда две разные записи получают одно и то же значение хэш-кода. Чем больше коллизий, тем медленнее поиск и выше вероятность ошибок. Поэтому важно минимизировать число коллизий для эффективной работы хэш-таблиц.

4. Хэш-функции для хранения паролей должны соответствовать следующим требованиям:

 Односторонность: Невозможно восстановить пароль по хэш-коду.

 Устойчивость к коллизиям: Минимум совпадений хэш-кодов для разных паролей.

 Вычислительная сложность: Медленная работа функции для затруднения атак методом перебора.

 Добавление соли: Использование случайных значений для предотвращения атак по радужным таблицам.

Эти свойства обеспечивают надежную защиту хранимых паролей.

5. Вычислительно невозможно означает, что решение задачи потребует настолько большого количества времени и ресурсов, что на практике оно становится нереализуемым даже с использованием самых мощных современных компьютеров.

6. Да, если злоумышленник узнал хэш-код пароля администратора сервера, он может получить доступ к секретным данным на сервере. 

7. Надежность пароля зависит от нескольких ключевых свойств:

 Длина: Чем длиннее пароль, тем сложнее его подобрать.
   
 Разнообразие символов: Использование букв разного регистра, цифр и специальных символов увеличивает сложность взлома.

 Уникальность: Пароль не должен повторяться для разных сервисов или аккаунтов.

 Отсутствие очевидных последовательностей: Избегайте простых комбинаций вроде «123456» или «qwerty».

 Регулярная смена: Периодическая замена паролей снижает риск компрометации.

Эти факторы помогают создать надежный пароль, который будет устойчив к атакам методом перебора и другим видам взлома.

8. Длинный, разнообразный, уникальный, без очевидных комбинаций, использование менеджера паролей.

9. Наиболее часто используемые алгоритмы хэширования: SHA-256, SHA-3, Bcrypt, Argon2, Scrypt.
