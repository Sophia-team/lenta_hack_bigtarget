# BIGTARGE хакато о Лент и Microsoft
https://bigtarget.online/  
Разработана модель машинного обучения на облачной платформе Microsoft Azure для наиболее точного таргетинга предложений в «Ленте».
1) Модель построена только с использованием присланных данных.
2) Модель эффективно ранжирует клиентов для SMS-рассылки, проставляя каждому клиенту ранжирующий скор, по которому можно выбрать сет для коммуникации.
3) Решение базируется на Python и реализовано на облачной платформе Microsoft Azure
4) Решение обладает хорошей масштабируемостью (может быть использовано для моделирования по другим рассылкам).

Техническая реализация:  
Выделены 4 типа клиентов  
Up-lift моделирование  
Классификатор на основе MS LightGBM  
Оптимизация MS HyperDrive  
Общий uplift ~ 5.5%  

Результат: победа в номинации "Лучшее решение, с использованием Micrisoft Azure"
