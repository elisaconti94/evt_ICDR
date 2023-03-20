<h1>Edizione EVT dell'opera I capricci d'un Re</h1>
<h2>Commedia in cinque atti di Stefano Pulvirenti.</h2>

<h3>Come nasce il progetto</h3>
<p>L’edizione digitale de I Capricci d’un Re nasce nel contesto del Master Infotext dell’Università degli studi di Siena e si propone di divulgare la commedia I Capricci d'un Re, tramite un contatto diretto con quanto scritto da Stefano Pulvirenti, grazie agli strumenti che oggi l’Informatica Umanistica riesce a fornire.
L’idea è nata grazie alla progettazione di una Biblioteca digitale dedicata al medesimo autore e creata sempre nel contesto del Master Infotext nell’edizione del 2022. Si tratta di un lavoro che ha comportato la raccolta del materiale di Pulvirenti e uno sguardo approfondito alla storia delle sue opere. Da qui nasce l’idea di un’edizione digitale de I Capricci d’un Re nella sua versione manoscritta.</p>

<h3>La visualizzazione e il proposito</h3>
<p>Lo strumento di visualizzazione impiegato è il software [EVT1](http://evt.labcd.unipi.it/) (Edition Visualization Technology) che permette al lettore di analizzare contemporaneamente il manoscritto digitalizzato e la sua trascrizione. In questo modo il fruitore dell’edizione potrà osservare egli stesso la grafia dell’autore, la fattura del quaderno, gli errori del testo. Nonostante si perda l’esperienza tattile dello sfogliare il manoscritto, o non si sia direttamente esposti dell’aura di cui parla Walter Benjamin,1 grazie ad una visualizzazione di questo tipo è possibile vivere un’esperienza maggiormente autentica rispetto alla sola lettura di una trascrizione del testo.</p>
<p>Il proposito è dunque quello di andare oltre la semplice lettura ma proporre uno strumento filologico che porti il lettore dentro il testo e sulla sua superficie materiale intrisa di un inchiostro che può egli stesso osservare.</p>


<h3>La codifica</h3>

<p>Codifica del testo. La codifica impiegata è XML-TEI. Non è stato utilizzato uno schema TEI specifico. La scelta è stata quella di privilegiare la codifica relativa alla formattazione del testo teatrale, lasciando spazio anche alla codifica di frammenti poetici in altre lingue.</p>
<ol>
<li>I marcatori del testo drammatico: sono stati utilizzati tag specifici per la lista dei personaggi `<castList>`,`<castItem>`,`<castGroup>` con il tag `<roleDesc>` per il ruolo dei personaggi. Ogni personaggio ha un xml:id che è servito nella fase di attribuzione delle battute. Alcuni personaggi sono stati inseriti da noi nella lista principale tramite delle note in cui viene segnalato il nostro intervento.
Per quanto riguarda le battute, è stato utilizzato il marcatore `<sp>` con gli altri due tag richiesti `<speaker>` e `<p>`. All’interno di `<sp>` è stato utilizzato l’attributo @who che ci permesso di inserire il rimando all’xml:id del personaggio. Per questo motivo la lista dei personaggi da noi trascritta presenta degli elementi aggiuntivi segnalati nelle note. Infatti l’autore ha inserito nuovi personaggi solo in un secondo momento, senza apportare modifiche alla lista iniziale dei personaggi. Proprio per dare omogeneità alla codifica abbiamo preferito inserirli ed esplicitare il nostro intervento negli appositi luoghi.
Per le entrate, le uscite dei personaggi, le attività sul palco e il modo di parlare è stato impiegato il tag `<stage>`. Grazie alla varietà di attributi (@entrance, @exit, @business, @delivery, @mixed, @modifier) è stato possibile distinguere le attività dei personaggi utilizzando un solo marcatore.</li>
<li>Tag di formattazione e di elementi linguistici: il testo è stato diviso in sezioni tramite `<div>`, nello specifico `<div1>` per gli atti e `<div2>` per le scene. È stato attribuito un xml:id per ogni `<div>` in modo da poter avere un riferimento univoco per ogni sezione. Per indicare l'inizio di una pagina nuova abbiamo utilizzato il tag `<pb>` (page beginning), seguendo una nostra numerazione che comprendesse tutte le pagine del manoscritto.
Abbiamo marcato anche le parole di lingua diversa e i termini evidenziati dallo stesso autore. Infatti oltre all’italiano sono presenti parole in francese, siciliano o parole evidenziate nel manoscritto per mezzo una sottolineatura. Nei casi delle parole in lingua straniera, abbiamo evidenziato questi casi con il tag `<foreign>` con attributi @rend e @xml:lang. Per i termini evidenziati dall’autore abbiamo impiegato il marcatore `<hi>` con l’attributo @rend.</li>
<li>Marcatori del testo poetico: sono stati marcati anche i versi presenti nel testo, utilizzando i tag `<lg>` e `<l>`. Nel caso dei versi in lingua spagnola o in dialetto siciliano, sono state inserite da noi delle note con la relativa traduzione. Anche in questi casi abbiamo segnalato chiaramente il nostro intervento.</li>
</ol>

<p>Errori di battitura, forme ortograficamente scorrette e accenti sono stati normalizzati. In particolare, per quanto riguarda gli accenti, Pulvirenti utilizza solo l'accento grave (perchè, poichè, tuttochè). Queste forme state corrette da noi con accento acuto.</p>

<h3>Diritti</h3>
<p>Il progetto è realizzato per la libera consultazione. Tutti i contenuti sono riproducibili a patto che se ne indichi la fonte. Le immagini sono state riprodotte con il permesso dei detentori dei diritti di ©, ovvero la famiglia Pulvirenti.</p>
