# hunspell-ru-surnames

Словарь создан для использования с модулем hunspell в elasticsearch. 

Создавался, как временное решение при отказе от модуля https://github.com/imotov/elasticsearch-analysis-morphology

Базовый файл аффиксов Александра Клюквина https://code.google.com/archive/p/hunspell-ru/ (поэтому такая лицензия)

Правила склонения фамилий:
* http://gramatik.ru/sklonenie-familij-i-imyon/
* http://www.oshibok-net.ru/for-all/sklonenie-famili/
* http://gramota.ru/class/istiny/istiny_8_familii/
* http://new.gramota.ru/spravka/letters/71-rubric-482

Из доступного мне набора в 2,6 млн фамилий получилось чуть больше 160 тысяч уникальных фамилий. Были удалены фамилии встречающиеся только один раз (кроме тех что мне обязательно нужны :) ) и не склоняемые фамилии. Осталось чуть более 100 тысяч. Порядок оставил по частоте встречаемости.
