NumPy è una libreria Python che consente di creare array multidimensionali. 
Le dimensioni dell'array vengono chiamate assi (dove un asse è un insieme di elementi) e il numero degli assi indica il rank dell'array.   
ES: [[1,2,3]] un asse e rank 1      -      [[1,2,3], [4,5,6]] 2 assi e rank 2

Le funzioni più importanti sono: **ndarray.ndim** (numero di assi dell'array), **ndarray.shape** (restituisce una tupla di interi che indica la grandezza dell'array di ogni dimensione), **ndarray.size** (numero totale degli elementi dell'array), **ndarray.dtype** (restituisce un oggetto che descrive il tipo di elementi dell'array), **ndarray.itemsize** (grandezza in bytes di ogni elemento dell'array), **ndarray.data** (restituisce un buffer con gli elementi attuali dell'array).  

Per creare un array si usa **np.array**  
ES: a = np.array([2,3,4]) di rank 1,  oppure b = np.array([(1.5,2,3), (4,5,6)]) di rank 2.  

Gli operatori aritmetici vengono applicati a tutti gli elementi dell'array; viene creato un nuovo array e riempito con i risultati:    
ES: a = np.array( [20,30,40,50] ) a<35 >>> array([ True, True, False, False], dtype=bool)
