# Come preparare una lista puntata:

## Lista puntata semplice

In markdown iniziare una riga con un numero, un punto, uno spazio ed il testo. 
Lo stesso per le righe successive.

Ad esempio il seguente testo

```
1. Prima
2. Seconda
3. Terza
```

viene reso cosi':

1. Prima
2. Seconda
3. Terza

## Numerazione automatica

Dei numeri scritti, solo il primo viene preso per iniziare il valore della lista, quelli successivi crescono automaticamente, percui

```
3. La lista inizia con tre
2. dopo il tre viene il quattro
1. e via a crescere
```

viene reso cosi':

3. La lista inizia con tre
2. dopo il tre viene il quattro
1. e via a crescere


## Paragrafi all'interno della lista

Una lista puo' contenere paragrafi indentati sotto una delle voci:    
1. Blu  
Il blu e' un colore primario
5. Giallo  
Il giallo non e' un colore primario 
9. Rosso  
Il rosso e' un colore primario

Questo si ottiene finendo le linee mumerate con due spazi seguite da semplice a-capo, ma senza un doppio acapo, come segue:

```
1. Le liste numerate come questa finiscono con due spazi prima dell'acapo  
Il blu e' un colore primario
5. Anche questa ha due spazi alla destra di questa freccia ->  
Il giallo non e' un colore primario 
9. Rosso (seguito da due spazi)  
Il rosso e' un colore primario
```
