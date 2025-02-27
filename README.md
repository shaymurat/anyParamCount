Самостоятельная работа по уроку "Произвольное число параметров".

Цель: закрепить знание использования параметров *args/ **kwargs на практике.

Задача "Однокоренные":

Напишите функцию single_root_words, которая принимает одно обязательное
слово в параметр root_word, а далее неограниченную последовательность в
параметр *other_words.
Функция должна составить новый список same_words только из тех слов
списка other_words, которые содержат root_word или наоборот
root_word содержит одно из этих слов. После вернуть список same_words в
качестве результата своей работы.

Пункты задачи:
1. Объявите функцию single_root_words и напишите в ней параметры
   root_word и *other_words.
2. Создайте внутри функции пустой список same_words, который
   пополнится нужными словами.
3. При помощи цикла for переберите предполагаемо подходящие слова.
4. Пропишите корректное относительно задачи условие, при котором
   добавляются слова в результирующий список same_words.
5. После цикла верните образованный функцией список same_words.
6. Вызовите функцию single_root_words и выведете на экран(консоль)
   возвращённое ей значение.

Пример результата выполнения программы:

Исходный код:
```
result1 = single_root_words('rich', 'richiest', 'orichalcum', 'cheers',
'richies')
result2 = single_root_words('Disablement', 'Able', 'Mable', 'Disable',
'Bagel')
print(result1)
print(result2)
```

Вывод на консоль:
```
['richiest', 'orichalcum', 'richies']
['Able', 'Disable']
```

Примечания:
> 1. При проверке наличия одного слова в составе другого стоит учесть,
   что регистр символов не должен влиять ни на что. ('Disablement' -
   'Able') ('Able', 'able', 'AbLe' - все подходят)
> 2. В этой задаче вам могут понадобиться следующие методы строк/ключевые слова:
>    а) Оператор in или count()
>    b) lower()/upper().

Файл module_3_4.py и загрузите его на ваш GitHub репозиторий. В решении
пришлите ссылку на него.

Успехов!
