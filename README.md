# позиционирование
-по умолчанию все блоки в позиции static
-relative -обычно используют для ограничения перемещения блока absolute 
даже при смещении блока relative брядом стоящие эллементы "считают" что блок не смещался
-absolute -при включении свойства ,рядом стоящие блоки теряют элемент из вида и стремятся занять его место
если элемт не ограничен другим ( relative)то он позиционируется по окну браузера,  иначе по блоку ограничителю
-fixed- фиксирует блок,в указаных координатах, left и right, смещают блок по окну браузера
-sticky- пока не указана смещение top или bottom блок ведёт себя как обычный static
