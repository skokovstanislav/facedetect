facedetect
==========
	Демон на питоне для увелечения энергосбережения ноутбука. Для работы требутеся веб-камера. 
	
	Протестировано в Linux Mint 17 - Mate. Скорее всего работать пока будет только на Mint. 
	
	Демон получает снимкм с камер и пытается найти на них лицо человека.
	
	Лицо найдено - человек за компьютером, все хорошо, можно не лочить систему.
	
	Если лицо человека не найдено в течении заданного периода времени(60 секунд по умолчанию,
	переопределить опцией -o<число_секнуд> при старте демона "python Main -c start -o<число>") - лочит
	систему.
	
	При появлении человека: разлочит монитор. 

	Запуск
	python Main.py -c start 

	Остановка:
	python Main.py -c stop

	Справка по дополнительным параметрам
	python Main.py -h
