# Prendere contributi pubblicati da altri

Nella giornata di oggi abbiamo osservato come produrre un PR (Pull request) per consigliare
ad altri utenti di prelevare del matariale prodotto da noi. 
Ed abbiamo visto come accettare la richiesta includendo il materiale.

Questo tutorial mostra come prendere materiale da atri branch senza passare da una `pull request`.

Considerate questa situazione:

![image](https://user-images.githubusercontent.com/101411317/157965661-1aad83c5-cae4-41bd-b8ff-9f56a80e0656.png)

L'utente @enricodeangelis ha modificato un file e pubblicato sul sito, ma senza creare un PR.

Cliccando sul particolare commit nel grafico di rete si vedono i contenuti modificati:

![image](https://user-images.githubusercontent.com/101411317/157968146-c9ef8758-0a04-40b6-adde-d278666ff30f.png)

Potete osservare il contenuto proposto online alla pagina: https://github.com/enricodeangelis/IlCorso/commit/3b15d44388c393272efddbe0cc574119984a496e
dove il codice `3b15d44388c393272efddbe0cc574119984a496e` e' l'identificativo di quel particolare commit, che appartiene al branch `main`.

Volendo prelevare il codice in questo caso possiamo usare la linea di comando 

```shell
git remote add enrico https://github.com/enricodeangelis/IlCorso
git merge enrico/main
```

Il che ha il seguente aspetto nella console di comando:

![image](https://user-images.githubusercontent.com/101411317/157973973-9b461fb3-ed7b-4ec2-af1c-dee03f832314.png)

Alla fine di questa operazione, come si vede le modifiche remote sono state incluse ed la rete ha il seguente aspetto:

![image](https://user-images.githubusercontent.com/101411317/157974362-6a19cd9c-c2d5-4a03-9583-1c2cd8a06565.png)

La medesima cosa si potrebbe fare con il contributo di @alberto2archetti, ma nell'occasione aspettero' che venga creata una PR.
