
# ОПРЕДЕЛЕНИЕ КРИТЕРИЕВ РАСПОЗНОВАНИЯ УСПЕШНОСТИ КОМПЬЮТЕРНЫХ ИГР

*Интернет-магазин продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы.*
**Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании**

## Данные подробно исследованы и проведена их подготовка.

## Проведен исследовательский анализ данных, по итогу которого были опеределены следующие особенности:

1.	С 1995 года пошел значительный рост в игровой индустрии.
2.	После 2009 года произошел спад по количеству выпускаемых игр в год, который вышел на плато в 2013 году, на момент анализа в среднем выпускается 278 игр в год.
3.	С течением времени игровые платформы устаревают и на смену им приходят новые, - средний срок жизни одной платформы составляет 7-9 лет. После своего появления продажи по каждой новой платформе стремительно растут, доходят до пика, и также стремительно падают, потому что появляется другая более современная платформа. **В связи с делением жизненного срока примерно поровну, актуальный период принят равным 3 года.**
4.	Анализ диаграмм размаха показал, что за последние годы **наиболее перспективными являются платформы PS4, XOne, WiiU, PC, 3DS**. На каждой из представленных платформ имеются «топовые» игры, которые бьют рекорды по продажам и создают длинный хвост для распределений. Средний объем продаж находится на уровне 200 тысяч копий.
5.	Отзывы пользователей практически не влияют на продажи игр (коэффициент корреляции в пределах от 0 до 0.1), отзывы критиков имеют слабое влияние (коэффициент корреляции около 0.4).
6.	По объему продаж лидируют игры следующих жанров: Action, Sports, Shooter, Misc, Role-Playing. Эти 5 жанров занимают практически **80** % рынка.
7.	Хуже всего продаются стратегии, пазлы и приключения.
8.	Взаимосвязь количества выпускаемых игр в жанре с объемом их продаж выше средней (коэффициент корреляции приблизительно равен **0.74**), это обусловлено особо высоким интересом геймеров к стрелялкам и спортивным играм, а также особо низким интересом к играм в жанрах приключения, пазлы и стратегии.

## Были составлены портреты пользователей каждого региона.
По итогу определения топовых характеристик для каждого региона можно сделать следующие описания:<br>
    
**Северная Америка**
    
Геймеры в Америке отдают предпочтение настольным приставкам, рынок между гигантами индустрии Sony и Microsoft разделился поровну - по 40 %. Несмотря на наличие новых версий приставок, старые все еще в ходу.
    
Больше всего в Америке любят играть в экшены, спортивные игры и стрелялки, также в топ-5 входят разнообразные игры и ролевые.


**Европа**
    
В Европе почти такая же ситуация по приставкам, первые три места разделили между собой PS4, PS3, XOne. На четвертом месте – X360, и в конце топа – карманная 3DS.
    
Любовь к жанрам в Европе проявляется также как в Америке.

Распределение объемов продаж по рейтингу в Европе аналогично распределению в Америке.
    
**Япония**
    
Ситуация по платформам разительно отличается в данном регионе. 2 из 5 в топ-5 – это карманные консоли (3DS, PSV), значит японцы предпочитают не быть прикованными к дивану и играть где им хочется. Оставшиеся платформы – это PS3, PS4 и WiiU. Продукция Microsoft в Японии в актуальном периоде не представлена.
    
36 % рынка Японии занимают ролевые игры, что обусловлено особой любовью этого региона к данному жанру, который даже носит название Японская ролевая игра. В остальном японцы также любят экшены, спортивные игры, разнообразные и платформенные.
    
В Японии очень много игр, которым не присвоен рейтинг, а также игры 18+ смещены у них на 3 место топа.

## Проверены гипотезы: 
- средние пользовательские рейтинги платформ Xbox One и PC одинаковые;  
- средние пользовательские рейтинги жанров Action и Sports разные. 

При анализе использовались критерий Стьюдента для независимых выборок.

## Библиотеки
* pandas
* matplotlib.pyplot
* scipy
* numpy
* seaborn
* plotly
