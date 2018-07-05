# VolumeOptimization
Element+Greedy.cs - описывает класс и метод поиска жадного алгоритма 

Implict_Enum.cs - описывает класс, наследуюмый от класса Elment из прошлого задания и описывает функцию создания списка из Nodes, который строится полным перебором с отсечениями (по заданию так)

main.cs - там где вводятся данные(тесты есть в файле test.txt) и сам редакш, то есть бинпоиск, который ищет ответ

Lagrange.cs - ищет аппербаунд, но пока что не ищет, а дает просто сумму по р

Local_Search.cs - это жадный алгоритм + со вторым шагом, то есть лучше 

Вообще, проект стоило бы полностью переписать на нормальном языке программирования, а не на С#


------------------Previous C++ codes------------------

class_greed.cpp - описывает класс, в котором реализована функция Greedy(так как указано в задании)

full.cpp - полный перебор за 2^N, использовал чтобы чуть-чуть потестировать

class.cpp - описывает класс, в котором реализовано динамическое программирование 

До меня только дошло, что задача NP-полная из-за этих запрещенных пар.
Искать ответ жадно или ДП неправильно, потому что он не дает наилучшего ответа, а полный перебор работает долго

Есть идея как оптимизировать ДП, чтобы оно искало наилучший выбор, но будет работать неплохо только если у нас мало запрещенных пар(до 20). Могу написать код или описать смысл решение, если хотите. А пока есть то, что требовалось в задании.
