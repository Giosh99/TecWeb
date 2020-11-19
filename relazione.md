## Analisi codice HTML  
  Per controllare se il sito avesse un HTML valido, si e' deciso di utilizzare lo strumento Total Validator, il quale dopo una scansione di tutte le pagine, ha dato i seguenti risultati:   
  1 Pagina **Home**: valida  
  2 Pagina **Azienda**: valida  
  3 Pagina **Preventivatore**: valida     
  4 Pagina **Contatti**: valida     

  Si e' poi passati ad un controllo manuale per la verifica semantica dei tag HTML, tramite la lettura resa possibile dallo strumento sviluppatore di google chrome. E' risultato che le web pages sono state composte in maniera corretta, in linea generale, tuttavia sono sorte alcune criticita':  
##### HOME
1. Immagine inserita non come sfondo ma con un tag HTML, inoltre e' stato inserito un alt completamente inutile.  
2. Le due immagini nel footer sono state inserite con un tag HTML  
##### AZIENDA  
  1. L'immagine della macchina con a fianco i dipendenti non porta alcuna informazione ad un possibile non vedente/ipo vedente, sarebbe stato piu' corretto inserirla come immagine di background, senza percio' un alt.  
#### PREVENTIVATORE  
1. Il possibile utilizzatore di uno screenreader non fatica nella sezione Data-nascita e Data-decesso a capire il formato della data da inserire, sarebbe stato piu' agevole al possibile utente l'utilizzo di un attributo input type="date" 
#### MENU  
1. I tab index sono posti tutti a 0, qualsiasi sia il link.  

#### COMMENTO 
1. I tre link per muoversi nella pagina sono utili per i non vedenti ( apputno da completare )    
### Errori sviluppo CSS  
### Pagine il cui CSS e' valido:  
  1 HOME  
  2 AZIENDA  
  3 PREVENTIVATORE   
  4 CONTATTI    
#### HOME  
1. Per schermi piccoli i link visitati non si differenziano da quelli visitati, e il contrasto non e' ottimale 
2. I link della visualiazzione presenti nel menu da telefono non sono visibili/ sono poco visibili per daltonici del tipo:  
  - Tritanopia  
  - Deuteranomaly  
