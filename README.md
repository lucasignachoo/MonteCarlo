# MonteCarlo
Se pueden elegir la cantidad de datos a usare solo cambiando el n1estrellas, de igual manera están los alpha correspondiente a la IMF de kroupa, de igual manera está la masa minima y maxima como M_min y M_max 
los m1,m2,etc nos hacen la distribución de masas homogeneas en nuestra simulación 
Luego los Histogramas de distribución de masas 
definimos nuestra función de Kroupa como kroupa_imf(m)
Ahora usando esa distribución re distribuimos nuestras masas con la funcion sample_masses_kroupa, los cuales ahora nos entregará  muestras_masas
graficamos la IMF de Kroupa para ver como se distribuye 
vemos la distribución del nacimiento de las estrellas de manera uniforme para así tener una SFR uniforme como se requeria
graficamos histogramas de las edades
calculamos nuestro tiempo de las estrellas en la Main Sequence con las muestras_masas como tsp1, tsp2, etc.
definimos cuales son remanentes con nuestra desigualdad
definimos cuales de las estrellas remanentes son correspondientes a Agujeros negros, Estrella de neeutrones y cuales a enana blanca.
definimos función para que nos haga un print de cuantas estrellas remanentes de cada tipo hay 
Se plotea un histograma para visualizar mejor la distribución de estrella en la MS
Separamos nuestras enanas blancas de las remanentes, en la lista llamada white_dwarf_masses, luego se usa la función correspondiente para calcular la masa final de este tipo de remanente, en este caso enana blanca.
lo mismo para estrella de neutrones y agujeros negros
Luego de obtenidos las masa finales, sepuede realizar un gráfico que nos exprese de buena manera como se relacionan la masa inicial con lamasa remanente.
