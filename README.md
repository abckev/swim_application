# SWIM APP

# Informazioni progetto:

Nome: Kevin Berberolli

Matricola: 321060

Titolo: Swim APP

# Breve introduzione

Swim APP è un’applicazione mobile sviluppata per le piattaforme Android e Web utilizzando il framework Flutter.
L’applicazione consiste nel pianificare i propri allenamenti di nuoto ed è composta da diverse schermate. All'avvio l'applicazione richiederà un login (unico) per poi poter utilizzare l’applicazione effettiva dando la possibilità di accedere a 4 schermate diverse:

-	Home: mostra una semplice schermata con una breve descrizione motivazionale di ciò che si può fare nell’applicazione e un’immagine.
-	Todos: schermata principale che mostra la lista degli allenamenti da fare.
-	Todos completed: schermata che mostra gli allenamenti segnati come completati.
-	Logout: schermata che mostra il nome utente con cui abbiamo fatto il login e dà la possibilità di effettuare il logout.

# Casi d’uso

L’utente all’avvio dell’applicazione dovrà effettuare un login con la combinazione e-mail/password con le seguenti credenziali: e-mail: prova@gmail.com , password: password.
Una volta inserite correttamente le credenziali l’applicazione si presenta con una pagina introduttiva e si potrà navigare nell’applicazione cambiando le schermate tramite la barra di navigazione nella parte bassa dello schermo del dispositivo che si sta utilizzando.
Quando l’utente aprirà la seconda schermata dalla barra di navigazione potrà cominciare ad utilizzare l’applicazione vera e propria, cominciando ad aggiungere gli allenamenti che vorrà eseguire, modificarli o eliminarli scrollando verso destra o sinistra il riquadro dell’allenamento che si vuole modificare o eliminare. Se l’utente deciderà di modificare un allenamento si aprirà una nuova schermata con le caratteristiche già inserite precedentemente pronte per essere sostituite.
Gli allenamenti che invece si riterranno come completati si potranno contrassegnare come “completati” spuntando la check box del rispettivo allenamento, e quel terminato allenamento completato lo si potrà ritrovare nella terza schermata, sempre raggiungibile dalla barra di navigazione sottostante.
Infine, quando l’utente vorrà chiudere l’applicazione potrà eseguire il logout nell’ultima schermata, dove potrà controllare anche con quale e-mail ha eseguito il login inizialmente.

# Esperienza Utente

L’esperienza per l’utente (UX) è molto chiara ed intuitiva. È stata aggiunto un BottomNavigationBar per semplificarne la navigazione tra le varie schermate. 

Per l’interfaccia utente (UI) sono stati utilizzati dei colori che potessero rispecchiare i colori della piscina e per essere di facile intuito dell’utente su quale pagina si stesse trovando in un determinato momento.

# 1
![1](https://github.com/abckev/swim_application/assets/49757916/362a61c0-86d5-4643-a627-60134a5336eb)




# Strumenti utilizzati

Gli strumenti utilizzati sono stati:
-	Per la creazione degli allenamenti i dati sono stati memorizzati in variabili di tipo List
-	L’interfaccia risulta adattabile ai vari display dei dispositivi (mobile, tablet, desktop).
-	Sono stati utilizzati provider per permettere di accedere e propagare lo stato più facilmente.
-	L’autenticazione e la persistenza dei dati sono stati effettuati tramite l’utilizzo della piattaforma Firebase.
-	Il progetto è stato strutturato separando per quanto possibile la parte grafica dalla parte logica, creando cartelle differenti contenenti i widget, funzioni, stati e modelli.

# Test

I test sono stati effettuati principalmente su browser(Chrome) e su un telefono Android.



