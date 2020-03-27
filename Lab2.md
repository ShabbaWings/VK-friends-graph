# Lab 2

Для использования в программе был выбран Kamada & Kawai layout algorithm. 

В его основе лежит физический подход к представлению графа. Каждые две вершины, соединенные ребром, как бы соединяются пружиной, после чего на основе этой системы считается потенциальная энергия для каждой отдельной пружины и системы в целом. Более подробно этот алгоритм описан в вступлении статьи L. Pospisil, M. Hasal, J. Nowakova, and J. Platos, "Computation of
Kamada-Kawai Algorithm Using Barzilai-Borwein Method," in
Intelligent Networking and Collaborative Systems (INCOS), 2015
International Conference on, 2015, pp. 327-333: IEEE.

Реализация алгоритма находится в функции kamada_kawai_layout_alg в файле Graph.ipynb. Далее идут три примера графа, построенных с помощью этой функции.

Три новых получившихся отображения графов (помимо того, который был в предыдущей лабораторной):
![alt text](Graph1.png)
![alt text](Graph2.png)
![alt text](Graph3.png)
