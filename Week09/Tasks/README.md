# Задачи за сортировки

## Задача 1:

Прочетете **n** на брой силволни низа от стандартния вход. Всеки низ трябва да представлява число между 1 и 10<sup>6</sup>. Всяко число трябва да е положително.

Сортирайте масива от символни низове и след това принтирайте елементите му на стандартния изход.

Примерен вход:

```
5
4315
2
42
51346
7
```

Примерен изход:

```
2
5
7
42
4315
51346
```

## Задача 2:

В практиката, често се налага компютринте да сортират информация. Примерно, хората често искат да видят файловете си подредени възходящо по размера на всеки файл. Сортирането на елементи е един от най-простите проблеми в програмирането, който има множество решения.

Ще се запознаем с **Insertion Sort**, лесен и интуитивен алгоритъм, като разгледаме следната задача:

Имате масив с **n** елемента, като първите **n - 1** са сортирани, а последния елемент(този най-вдясно) не е на мястото си. Задачата ви е да раместите елементите на масива така, че най-крайното число да отиде на мястото си. Принтирайте състоянието на масива преди всяко едно разместване(swap-ване) на елементи в масива, така че в последствие да можем да проследим как са се разместили елементите.

Нужни данни:

```
size - брой елементи в масива
arr - някакъв масив съдържащ size - 1 на брой сортирани целочислени стойности и една несортирана стойност най-вдясно в масива
```

Примерен вход:

```
5
2 4 6 8 3
```

Примерен изход:

```
2 4 6 8 8
2 4 6 6 8
2 4 4 6 8
2 3 4 6 8
```