# Risoluzione conflitti

Un conflitto nel `merge` di un `branch` avviene quando il sistema non e' in grado di scegliere tra due versioni alternative
dei contenuti.

Ad esempio, nell'aggiungere i vostri nomi alla lista siamo partiti tutti da

``` md
- DrBenghi - Claudio Benghi
```

E ciascuno ha aggiunto un nuovo nome:

```md
- DrBenghi - Claudio Benghi
- NuovoNomeA - Nome A
```


```md
- DrBenghi - Claudio Benghi
- NuovoNomeB - Nome B
```

Il sistema non sa se le nuove voci vanno aggiunte o sostituite una con l'atra e notifica di un problema di merge.
I sistemi per correggere questo conflitto sono molti, ma il sito offre una funzionalita' integrata:

![image](https://user-images.githubusercontent.com/101411317/157959786-395c7ff4-78c7-44c2-9f75-5e6bbfb54169.png)

Premendo `resolve conflicts` si ottiene una interfaccia che mostra le linee incriminate:

![image](https://user-images.githubusercontent.com/101411317/157960522-280fcc43-48a3-40ae-89a4-332160317a2a.png)

Una volta corretto il file e confermato il salvataggio con `mark as resolved`. Potremo completare il merge.
