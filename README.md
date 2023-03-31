## Descrição do problema :
-Testei 4 algoritmos de ordenação diferentes para um array de 1 milhão de elementos e vamos tentar otimizar a solução utilizando python numba .
## Estratégia de paralelização :
-Irei utilizar a biblioteca NUMBA ,espeficamente , jit com o argumento nopython .
## Versão sequencial e paralela :
-Foi abordada no notebook , não existe um trecho em si , utilizamos o @jit na função toda.
## Análise da escalabilidade 
-Como esses algoritmos tem bastante loops , então torna o algoritmo interessante .
## Discussão sobre a eficiência :
-Antes de realizar a paralelização eu acreditava que seria possível encontrar uma solução ótima para o algoritmo quadrático do selection sort , infelizmente , não foi possível . Porém satisfatoriamente obti resultados muito interessantes para o merge sort .
## Conclusão 
- Utilizando essa biblioteca , já percebe-se uma melhora significativa para um algoritmo que é muito importante em aplicações reais , logo , está evidente que muitos sistemas reais poderiam ser otimizados usando essas técnicas .