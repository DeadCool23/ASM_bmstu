# Задание на лабораторную работу №7

Написать программу на Си/Си++, которая вызывает 2 подпрограммы на ассемблере:

1. Принимает 1 параметр - указатель на строку, определяет длину строки и выполнена в виде ассемблерной вставки
2. Копирует строку с адреса, заданного одним указателем, по адресу, заданному другим указателем, и реализована в отдельном asm-файле. Функция должна принимать 3 параметра: два указателя и длину строки. Про расположение указателей в памяти и расстояние между ними заранее ничего не известно (первая строка может начинаться раньше второй или наоборот; строки могут перекрываться)

Подпрограммы должны соответствовать соглашению о вызовах языка Си и использовать команды обработки строк с префиксом повторения
