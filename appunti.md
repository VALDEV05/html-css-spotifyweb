Costruzione layout, seguo ragionamento svolto con figma, ho costruito due blocchi, il primo "quello centrale", il secondo il "footer". Le proporzioni che sto usando sono l'85% per il main e il 15 per il footer
la side_bar, fa parte del container_main , è di dimensioni del 20% della viewport
la sidebar e l'header_main, verrà posizionata in modo fisso
allo stesso modo ho aggiunto anche le altre sezioni, passo ai contenuti
Ho pensato che anche il footer va posizionato con fixed
ridimensionata la sidebar
Complete content sidebar

Aggiunto bottone header main "btn_head"
Creato footer

content_main aggiunto il menu centrale di navigazione, 
aggiunta anche la sezione delle canzoni recenti con relativo effetto

Completata tutta la creazione delle card_song 

    border-left: 5px solid greenyellow


Effetti esercizi Spotify 
    Sidebar	
        - [x] Hover su menu sidebar, laterale 5px solid #ADFF2F con scritta che da grigia diventa bianca
        - [x] Sezione playlist, al passaggio ogni cosa diventa bianca
    Content_main
        - [x] Menu_header passaggio diventano bianche e bordino sotto tranne in evidenza
        - [x] Bottone scale1.5
    Footer	
        Da sx a dx
        - [x] Nome con underline
        - [x] play_centrale scale1.8
        - [ ] Barre diventano #ADFF2F
    
Sistemare sezione 




8
Ora abbiamo visto che il layout funziona, passo a lavorare con le media query.

La prima media query da costruire con valori fino a 882px

La sidecar rimane identica,
Leader main con il bottone anche,
Il menu del content va a capo,
Le immagini stessa grandezza vanno a capo
Foooter si restringe, forse barra scorrimento musica si restringe leggermente.



La seconda media query da costruire con valori fino a 643px

La sidecar rimane identica,
L'header main con il bottone anche,
Il menu del content va a capo sei formano due righe con 3 elementi ognuna,
Le immagini stessa grandezza vanno a capo, due per riga.
Foooter si restringe, ancora le icone si incolonnano,
Sicuramente la barra dello scorrimento si rimpicciolerà notevolmente.

La terza media query da costruire con valori fino a 556px

La sidecar rimangono solo le icone di sinistra,
L'header main con il bottone anche,
Il menu del content medesimo della media query 1 Le immagini uguali alla media quei 1
Foooter si restringe, ancora più piccolo.


Per l'altezza, per far uscire la scrollbar laterale sulla playlist, bisogna impostare a Hidden a aside e a playlist, a ul impostiamo height 100%
E overflow-y:auto