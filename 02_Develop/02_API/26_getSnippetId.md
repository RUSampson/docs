###Возвращает идентификатор текущего сниппета, в котором происходит вызов

*Замечание: Эта функция не работает при вызове из подключенного файла (include, include_once, require, require_once).*

int getSnippetId();

***

####Пример

	$txt = $modx-> getSnippetId();
	//Вернет идентификатор текущего сниппета.