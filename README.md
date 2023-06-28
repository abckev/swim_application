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

# Schermata Login
![1](https://github.com/abckev/swim_application/assets/49757916/362a61c0-86d5-4643-a627-60134a5336eb)

# Schermata Home
![2](https://github.com/abckev/swim_application/assets/49757916/359e163a-8b1b-46ae-89d9-df45a084e19b)

# Schermata Todo
![3](https://github.com/abckev/swim_application/assets/49757916/20d0d5b6-dc76-47d4-8521-6a4b9cae0342)

# Schermata Todo Completed
![5](https://github.com/abckev/swim_application/assets/49757916/6fb37a09-efd8-4306-8b2e-71f9ba6c5cac)

# Schermata Logout
![6](https://github.com/abckev/swim_application/assets/49757916/ae46f7b6-627d-466e-9aa8-f72eb7d96e3d)

# Schermata tablet layout
![7](https://github.com/abckev/swim_application/assets/49757916/14b1d70e-7bfd-4124-8e3b-523fb05a5c6b)

# Schermata desktop layout
![8](https://github.com/abckev/swim_application/assets/49757916/6aa64f0e-9c0f-4080-8079-44ca76e91a0f)




# Strumenti utilizzati

Gli strumenti utilizzati sono stati:
-	Per la creazione degli allenamenti i dati sono stati memorizzati in variabili di tipo List
-	L’interfaccia risulta adattabile ai vari display dei dispositivi (mobile, tablet, desktop).
-	Sono stati utilizzati provider per permettere di accedere e propagare lo stato più facilmente.
-	L’autenticazione e la persistenza dei dati sono stati effettuati tramite l’utilizzo della piattaforma Firebase.
  ![9](https://github.com/abckev/swim_application/assets/49757916/2f645a82-c7af-435a-8f74-6fd3af320732)
  ![10](https://github.com/abckev/swim_application/assets/49757916/b7fe58e0-18e9-4a70-8d56-d7e34aec6ccc)
-	Il progetto è stato strutturato separando per quanto possibile la parte grafica dalla parte logica, creando cartelle differenti contenenti i widget, funzioni, stati e modelli.

# Test

I test sono stati effettuati principalmente su browser(Chrome) e su un telefono Android.



