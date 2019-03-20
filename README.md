# hunspell-ru-surnames

Словарь создан для использования с модулем hunspell в elasticsearch. 

https://www.elastic.co/guide/en/elasticsearch/reference/master/analysis-hunspell-tokenfilter.html

Создавался, как временное решение при отказе от модуля русской морфологии. 

https://github.com/imotov/elasticsearch-analysis-morphology

Базовый файл аффиксов Александра Клюквина https://code.google.com/archive/p/hunspell-ru/ (поэтому такая лицензия)

Правила склонения фамилий:
* http://gramatik.ru/sklonenie-familij-i-imyon/
* http://www.oshibok-net.ru/for-all/sklonenie-famili/
* http://gramota.ru/class/istiny/istiny_8_familii/
* http://new.gramota.ru/spravka/letters/71-rubric-482

Из доступного мне набора в 2,6 млн фамилий получилось больше 160 тысяч уникальных фамилий. Были удалены фамилии встречающиеся только один раз (кроме тех что мне обязательно нужны :) ) и несклоняемые фамилии. Осталось около 100500 штук. Порядок оставил по частоте встречаемости.
