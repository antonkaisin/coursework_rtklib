# RTKlib coursework  
## `coursework.ipynb`
## Описание задачи
Даны rinex-файлы наблюдений gps-спутника за 2007-2012 год (около 365 файлов за каждый год).

Необходимо обработать файлы наблюдений (переведенные в формат rinex) с помощью `rtklib` в автоматическом режиме. Посмотреть, как отличаются координаты, определить параметры тектонического движения и сезонную составляющую по высоте по полученным файлым `javd.pos`

## Описание данных:

* `javd_год_дата.o` или `javd_год_дата.n` – уже переведенные из формата rinex навигационные файлы и файлы наблюдений 
* `.clk_30` – 30-секундные часовые файлы орбит с сайта `cddis.nasa.gov` 
* `.sp3` – файлы орбит (эфемерид) с сайта `cddis.nasa.gov`
* `RTKLIB-master` и `rtklib_2.4.2_bin` - файлы для работы программы RTKLIB


## В репозитории прикреплены уже готовые файлы `javd.pos`, так как 30-секундные, sp3, и навигационные файлы весят слишком много (за 5 лет)
