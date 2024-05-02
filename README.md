## Лабораторные работы по дисциплине Биостатистика и анализ систем 

1) lab1.ipynb
   
Целью лабораторной работы является построение эмпирической функции дожития, условной функции дожития (при условии дожития до момента t, где t возможно задать в качестве параметра), гистограммы по экспериментальным данным, а также аппроксимации эмпирической функции дожития кривой дожития Гомперца. Оценку параметров кривой Гомперца при аппроксимации можно производить любым методом (методом максимального правдоподобия, методом наименьших квадратов). В качестве экспериментальных данных берется выборка моментов гибели (измеряется в днях) лабораторных животных при различных биологических экспериментах - life_expectancy.txt

 Результатом лабораторной работы № 1 является компьютерная программа,которая выводит в графическом режиме эмпирическую функцию дожития, условную функцию дожития (на произвольно заданный момент) и гистограмму по предложенным экспериментальным данным, а также оценивает параметры аппроксимирующей кривой Гомперца и строит данную кривую.

Нелинейная минимизация метода наименьших квадратов и подбор кривых для Python:
 https://lmfit.github.io/lmfit-py/
 Установка pip install lmfit 

#### lifelines 
Installation: pip install lifelines
or
conda install -c conda-forge lifelines

https://lifelines.readthedocs.io/en/latest/jupyter_notebooks/Piecewise%20Exponential%20Models%20and%20Creating%20Custom%20Models.html#The-Exponential-model

Introduction to survival analysis
https://lifelines.readthedocs.io/en/latest/Survival%20Analysis%20intro.html

https://kpfu.ru/portal/docs/F_1675497345/lekciya.9.pdf


Условная функция дожития (conditional_after, lifelines)
 https://lifelines.readthedocs.io/en/latest/Survival%20Regression.html


 2) lab2.ipynb

Целью работы является применение критериев Стьюдента и Фишера для проверки гипотез о статистической значимости различий между группами наблюдаемых индивидуумов. 

В первой части работы необходимо с помощью критерия Стьюдента проверить гипотезу о равенстве средних значений (случайности различий) двух нормально распределенных совокупностей. В качестве экспериментальных данных берутся две выборки моментов гибели (измеряется в днях) лабораторных животных при различных биологических экспериментах. 

Во второй части работы необходимо с помощью критерия Фишера проверить гипотезу о равенстве дисперсий (случайности различий) четырех нормально распределенных совокупностей. В качестве экспериментальных данных берутся четыре  выборки моментов гибели (измеряется в днях) лабораторных животных при различных биологических экспериментах. 
Уровень значимости критериев в обоих случаях взять α=0.05. 

Результатом лабораторной работы № 2 является компьютерная программа, написанная на языке программирования высокого уровня (или в статистическом пакете) или таблицы, сформированные в Exel, которые содержат исходные данные и этапы проверки гипотез (промежуточные расчеты, критические значения соответствующих распределений), а также приводят конечные результаты (основная гипотеза верна или нет).

3) lab3.ipynb

Целью работы является применение непараметрических критериев - критерия знаков и критерия Вилкоксона - для проверки гипотез о статистической значимости различий между группами наблюдаемых индивидуумов. 

В первой части работы необходимо с помощью критерия знаков проверить гипотезу о статистической значимости различий двух совокупностей. В качестве экспериментальных данных берутся две выборки моментов гибели (измеряется в днях) лабораторных животных при различных биологических экспериментах. Так как для применения критерия знаков необходимо чтобы обе выборки были одинакового объема, то из каждого файла берутся М значений, где М – минимальное количество элементов в двух файлах. 

Во второй части работы необходимо применить ранговый критерий Вилкоксона для проверки гипотезы о статистической значимости различий двух совокупностей. В качестве экспериментальных данных берутся две  выборки моментов гибели (измеряется в днях) лабораторных животных при различных биологических экспериментах. 
Уровень значимости критериев во всех случаях взять α=0.05. 

Результатом лабораторной работы №3 является компьютерная программа, написанная на языке программирования высокого уровня (или в статистическом пакете) или таблицы, сформированные в Exel, которые содержат исходные данные и этапы проверки гипотез (промежуточные расчеты, критические значения соответствующих распределений), а также приводят конечные результаты (основная гипотеза верна или нет).


