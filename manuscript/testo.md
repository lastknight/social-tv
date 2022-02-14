# Perché questo libro

> "Qualsiasi sciocco può fare qualcosa di complesso; ci vuole un genio per fare qualcosa di semplice." *(Pete Seeger)*  

Questo non doveva essere un e-book. È nato come un post, ma si è allungato oltre le aspettative iniziali, non tanto per la complessità di rispondere alla domanda implicita - in realtà molto semplice - quanto per la difficoltà di spiegare in parole semplici una serie di concetti che sono, comunque li si guardi, complessi.  
  
La domanda da cui origina questo libro è un quesito che ci siamo posti tutti, benché a volte gli stessi addetti ai lavori abbiano timore di chiederselo ad alta voce: **“Come mai le analisi della SocialTV fatte da soggetti differenti non danno mai gli stessi risultati?”**.  
  
Il dubbio è lecito e la domanda molto, molto semplice: tuttavia, la risposta è complessa e tutt'altro che immediata, perché comporta il prendere in considerazione fattori molteplici: come vengono raccolti i dati, da che fonti provengono, in che modo vengono analizzati, quali filtri si impongono.   
  
Nella prima parte di questo volume mi sono impegnato a tentare di spiegare quali ragioni portano a risultati apparentemente discordanti tra vari soggetti che osservano lo stesso programma, al fine di sollevare un po’ il velo di mistero che attornia le analisi e mostrare come in realtà ogni analisi è replicabile, e il fatto di arrivare a conclusioni differenti non deriva da strane magie alchemiche ma molto più semplicemente da configurazioni differenti.  
  
Nella seconda parte del volume ho cercato, invece, di offrire un quadro riassuntivo delle metriche usate per misurare i fenomeni di SocialTV. Anche in questo caso, sebbene la domanda di partenza sia di per sé semplice (**"Come faccio a misurare le performance della SocialTV?"**), la risposta non è immediata, non tanto per la peculiarità delle metriche in sé, quanto perché la scelta della metrica adeguata dipende dal punto di osservazione adottato e da quali sono nella mia visione gli aspetti specifici che misurano il successo aziendale - comunque esso venga definito.  
  
Un volume breve che vuole offrire spunti di riflessione e, perché no, di discussione sullo stato dell’arte del settore, frutto dell’esperienza maturata in quattro anni di lavori sulla SocialTV con [The Fool][1001], la **Digital Reputation Company** che ho fondato e che anche di questo si occupa giorno per giorno. Non già, forse, un compendio di “best practice” quanto invece un catalogo delle problematiche e delle soluzioni che negli anni sono state adottate e definite per cercare di dare al mercato i migliori dati possibili.  
  
Matteo G.P. Flora (@lastknight)  

# L'importanza dei dati e le metriche

Chi di voi segue il fenomeno online della SocialTV si sarà spesso trovato di fronte a quello che accade anche a noi, operatori del settore che seguono una o più emittenti.  
  
Come probabilmente chi mi legge sa già, in [The Fool][1001] analizziamo i dati che provengono dagli account social di varie reti televisive, tra cui uno dei maggiori player televisivi italiani della televisione di intrattenimento; altri nostri competitor affrontano le medesime problematiche e i medesimi argomenti in un settore dominato da pochi soggetti che, nel bene e nel male, si confrontano sulle medesime tematiche.  
  
Da qualche mese è arrivato anche in Italia un nuovo “elephant in the room” (colosso mondiale) che ha proposto i prodotti legati all'accesso a metriche peculiari derivate da una partnership esclusiva con Twitter, alimentando, nel tentativo di definire uno standard de facto per la SocialTV, la competizione tra le differenti realtà già operanti nel settore.  
  
In questo panorama sempre più affollato di fonti e di dati, ci si accorge ben presto di qualcosa che prima non era così evidente: **i numeri non tornano**. O meglio, i numeri diffusi dopo un evento variano sensibilmente a seconda della fonte. Nelle prossime pagine cercherò di spiegare le ragioni di queste discordanze, aiutandovi a comprendere meglio i dati che vengono forniti, a conoscere quali sono le metriche e identificare quelle a cui prestare attenzione.  
  
Seguendo le Best Practices di The Fool, affronterò nell’ordine i seguenti argomenti:
						
* in **Come vengono selezionati i dati?** vedremo come possono variare le logiche di analisi delle fonti e la scelta dell’orizzonte dei dati da prendere in considerazione;
* in **Da dove provengono i dati?** analizzeremo le differenti fonti dati disponibili e le peculiarità di ciascuna di queste;	
* In **Come vengono misurate le performance?** analizzeremo invece le diverse misure che vengono proposte, considerando le peculiarità di ciascuna;
* In **Quali tipologie di metriche?** analizzeremo infine le macro tipologie di metriche che possiamo utilizzare per valutare il successo o l'insuccesso di un fenomeno.

# Come vengono selezionati i dati
  
Nella pratica di analisi dei contenuti sui Social Media, il processo, di per sé complesso, si può riassumere in modo sintetico in questa successione di operazioni:  

* si osserva un flusso di dati per un certo periodo di tempo (ad esempio Twitter da 3 ore prima dell'inizio a 3 ore dopo la fine di un programma);
* si controlla la presenza di alcune parole chiave che abbiamo identificato come rilevanti rispetto al fenomeno che vogliamo monitorare (ad esempio gli *hashtag* ufficiali, il nome del programma e i nomi dei presentatori);
* si recuperano i contenuti e li si depura dello “sporco” (ad esempio eventi in altre parti del mondo con medesimo *hashtag* o spam) eventualmente rilevato. 

Ogni variazione marginale in ciascuna di queste fasi può influenzare in modo anche sostanziale i risultati dell’analisi; è quindi indispensabile comprendere ogni singola componente in modo molto, molto approfondito.

## L'Orizzonte dell'Analisi

Quali social stiamo controllando quando diamo i "numeri" dell'evento? Siamo limitati al solo Twitter, dimenticandoci ogni altro Social (come alcune realtà vorrebbero fare, in una visione estremamente limitativa del fenomeno) o stiamo guardando il mercato nella sua interezza? Se paragoniamo un’analisi *Twitter* con una più articolata basata sulla combinazione *Twitter + Facebook + Instagram* è ovvio che la seconda avrà decisamente più contenuti della prima, anche sotto il punto di vista meramente numerico. E, ricordiamoci, dire che la SocialTV in Italia è **solo Twittter** è un’affermazione assolutamente pericolosa e scarsamente attinente alla realtà, come è facile constatare dal numero di messaggi che transitano ogni anno da Facebook vs Twittter[^solotwitter].  
  
[^solotwitter]: Sembra che anche AdWeek sia daccordo con me nel ritenere questo approccio estremamente limitativo, visto cosa dice in un recente articolo: http://www.adweek.com/lostremote/thanks-nielsen-for-that-twitter-study-but-its-time-we-total-it-up-with-you/50907

E la cosa non si ferma qui: anche se diciamo quali sono le fonti, è necessario specificare attentamente cosa viene preso in esame: ad esempio se analizziamo Facebook, quelle che conteggiamo sono le menzioni (ad esempio) degli *hashtag* da parte di tutti gli utenti o stiamo semplicemente calcolando il numero di messaggi e commenti che vengono scritti in un arco di tempo della trasmissione da qualunque utente sulla pagina del programma? Ovviamente i due dati potrebbero variare anche significativamente.  

I> Quindi: per paragonare due analisi controlla attentamente quali sono le fonti che prendono in esame e in che estensione.

## L'Intervallo Temporale preso in esame

Ogni indagine definisce a "tavolino" un orizzonte temporale utile per l'analisi stessa. Raramente è quello "da inizio a fine della trasmissione" e, se ci pensate, è una scelta intelligente: un approccio così restrittivo non farebbe altro che escludere dall'analisi il pre-programma e la coda di post-programma, che fanno assolutamente parte dell'effetto di coinvolgimento del programma stesso, ed escluderli sarebbe prima di tutto errato ed in secondo luogo poco utile ai fini della ricerca.  
  
D’altronde di quanto "prolungare" prima o dopo la soglia di analisi è un tema scottante e che può offrire risultati molto contrastanti. La "regola non scritta" dice di osservare una finestra magica di **tre ore prima dell'inizio e tre ore post fine**, ma bisogna essere consci che tale impostazione è tutt'altro che imperativa, soprattutto per i programmi di prima o seconda serata, i cui strascichi di commenti (si pensi ad esempio ad una puntata de *Le Iene*) saranno sicuramente discussi per almeno tutto il giorno a venire se la puntata affronta temi particolarmente controversi.  
  
La scelta di ampliare o ridurre l’arco temporale di analisi non solo consente di analizzare numeri più grandi o più piccoli, ma spesso si rivela essere l’unica maniera possibile per determinare fedelmente l’entità di un fenomeno preso in esame. La regola applicata nel nostro contesto aziendale è, salvo che il cliente ci chieda altrimenti, quella di attendere la china delle risultanze fino ad un livello di "rumore di fondo", che ci porta ad essere ragionevolmente sicuri di aver recuperato la buona parte del fenomeno.   

I> Quindi: per paragonare due analisi controlla attentamente quale ambito temporale prende in analisi.

## Le Parole Chiave dell'Analisi

Quasi qualunque analisi sui SocialMedia si basa sulla rilevazione della presenza di taluni termini che possiamo "associare" al programma e che, quindi, ci rendono ragionevolmente sicuri che proprio di quell'argomento si stia parlando. Quasi mai si tratta del solo *hashtag* di riferimento, poiché non tutti gli utenti usano l'*hashtag* che proponiamo, ma spesso li stravolgono, creano, abbreviano, modificano *(ad esempio #grandefratello15 o #grandefratello o #gf2015 o #gf)*, e talora non li citano affatto pur parlando della trasmissione. A volte citano l'account ufficiale, a volte non lo fanno. A volte scrivono con i nomi dei personaggi, a volte con nomignoli storpiati, a volte citano uno degli attori, a volte ancora una certa situazione (es. #tugurio) senza aggiungere altra connotazione alla trasmissione. Ovviamente, in tutti questi casi stanno parlando del programma ed è necessario che una buona analisi conteggi tutto questo chiacchierio online a prescindere dal fatto se usi o meno le chiavi che abbiamo proposto per intavolare la discussione.    
  
"Dimenticarsi" qualcuna di queste parole potrebbe alterare anche sensibilmente i risultati, spesso sotto-stimandoli e non dando quindi una vera indicazione del fenomeno di commenti che si è svolto, solo per errata creazione di un perimetro di analisi completo. Per venire incontro a queste problematiche, uno staff di esperti esamina e propone parole chiave per ogni singola puntata, in un documento (che chiamiamo spesso *ontologia semantica*) che può avere fino ad un paio di centinaia di parole chiave non solamente in aggiunta a quelle ufficiali ma anche e soprattutto in sottrazione, per eliminare alcuni termini che sappiamo già non avere attinenza con l'argomento e che possono facilmente inquinare i risultati finali dell'analisi.  
  
Non credo sia necessario spiegare come un’analisi fatta con centinaia di parole chiave riporterà un numero tendenzialmente, ma non necessariamente, molto superiore di contenuti rispetto ad una completata con il semplice *hashtag* “ufficiale”. Questa unica considerazione basta a spiegare perché  tale analisi sia anche di molto differente da una "fatta in casa" che riporta un numero di tweet contenenti il solo *hashtag* *(ad esempio cercando con strumenti come Topsy)* e nel contempo come sia impossibile mettere a confronto due diverse analisi se non si hanno in mano le medesime parole chiave. Oltretutto è anche abbastanza palese come l'unica realtà che veramente conosce a priori gli argomenti che verranno trattati è l'emittente televisiva (o al massimo il produttore) e che quindi la cooperazione con questa  risulta necessaria per ottenere un dato affidabile.  

I> Quindi: per mettere a confronto due analisi controlla attentamente le parole chiave che sono state usate, o per lo meno gli ambiti di ricerca (solo *hashtag* o *hashtag* e personaggi ecc.).

## Gli ambiti linguistici e territoriali presi in esame

Un altro fattore  peculiare da prendere in considerazione nella nostra indagine è la ampiezza territoriale *(definita su base geografica e/o linguistica)* dell'analisi che stiamo effettuando, il cui raggio d’azione porta inevitabilmente a risultati molto differenti. Anche se, di primo acchito, potrebbe sembrare che la soluzione sia semplice *(è SocialTV italiana, quindi cerco in Italia in italiano)* nella pratica di tutti i giorni potrebbe non essere così. Questo perché moltissimi utenti sono ancora identificati *(soprattutto se Twittatori della "prima ora")* come inglesi *(me compreso)*, o perché semplicemente non hanno dichiarato correttamente la lingua o, ancora, non hanno dichiarato l'appartenenza geografica o ancora perché sono in Italia e discutono del programma anche se non sono originari del paese.  
  
Limitare quindi geograficamente una ricerca può essere fortemente controproducente e può arrivare ad essere estremamente limitativa, sottostimando anche grandemente i risultati di performance tralasciando alcuni dei contenuti sul programma.  
Diversamente, invece, ampliare a tutto il mondo rischia di lasciarci in balia di molto "sporco" che può compromettere la bontà della ricerca: se stiamo analizzando la partita trasmessa dall'emittente nazionale, lasciare aperto il bocchettone di analisi al nome del giocatore, ad esempio, potrebbe essere pericoloso, perché si rischia di deviare dal focus dell’oggetto su cui si sta investigando (magari con notizie riguardanti il calciomercato e non il match in onda). Così come nella pesca a strascico confluiscono indistintamente tutti pesci che si trovano sullo stesso tragitto della rete, allo stesso modo potrebbe accadere che all’interno della nostra ricerca possano finire tutti i commenti degli utenti  di un'altra nazione, che stanno partecipando alle conversazioni di un programma di una differente emittente nazionale.  
La stessa situazione si verifica, ovviamente, quando si troviamo di fronte a manifestazioni che potrebbero essere in onda contemporaneamente in più stati al mondo e di cui, magari, ci interessa solamente l'edizione italiana (es. il Grande Fratello potrebbe andare in onda contemporaneamente in Brasile e Italia, sempre com medesimo *hashtag* #GF).  

I> Quindi: per mettere a confronto due analisi controlla attentamente quale combinazione di stati/lingue è stata scelta.

## La seconda analisi di integrazione

Non sempre la prima analisi viene "col buco", nel senso che non sempre la prima analisi, per quanto bene impostata, è in grado di recuperare tutte le informazioni che ci servono e di eliminare efficacemente lo "sporco" pescato con i risultati. Spesso alcuni *hashtag* nascono *durante* il programma e non possono essere preventivamente analizzati, semplicemente perché non vi è modo di recuperarli a priori. Ovviamente stiamo parlando di *hashtag* che vengono utilizzati *in alternativa* rispetto agli *hashtag* principali o ufficiali, altrimenti non abbiamo necessità di preoccuparci, perché i relativi contenuti ricadrebbero comunque nel perimetro dell'analisi che stiamo effettuando: se infatti l'utente utilizza contemporaneamente i tag #gf e #docciasexy sappiamo ovviamente che ritroveremo nell'analisi i contenuti grazie al primo *hashtag* che abbiamo messo in monitoraggio, ma se utilizza solamente l'*hashtag* #docciasexy senza indicazioni non abbiamo modo se non a posteriori di aggiungere questo tag al perimetro di analisi.  
  
In questo caso le piattaforme e i servizi cambiano notevolmente: alcune piattaforme non consentono, una volta lanciata l'analisi, di fare alcun tipo di modifica sino alla fine della registrazione, altre consentono di modificare *in fieri* alcune o tutte le parole chiave prese in esame. Il nostro approccio è sempre stato quello di effettuare due analisi distinte: una prima analisi per rilevare gli *hashtag* e le parole chiave più utilizzate nel singolo evento, ed una seconda analisi di dettaglio per poter recuperare - tramite le parole chiave create nel corso dell'evento -  anche i contenuti che non sono stati rilevati con la prima ricerca.  
  
Ovviamente quest'ultima tipologia di analisi è molto più laboriosa e dispendiosa delle precedenti, sia perché a tutti gli effetti si tratta di due attività differenti ancorché complementari, sia perché necessita dell'accesso *"storico*" ai dati dei Social Network *(l'accesso quindi a posteriori e non in sincrono)*, che è una opzione mediamente di ordini di magnitudo più costosa rispetto alla mera analisi in tempo reale.  

I> Quindi: per mettere a confronto due analisi controlla attentamente come viene effettuata la cernita delle parole chiave e se a posteriori viene effettuata una post-analisi rilevando i dati pertinenti eventualmente non ricompresi nella prima.

## L'eliminazione dei contenuti non rilevanti

Un passo importante rispetto alle analisi è poi quello di eliminare il contenuto spurio che potrebbe essere entrato nell'ambito di analisi. Questo tipo di contenuto rientra, normalmente, in due differenti tipologie: spam e tailgating da un lato e contenuti classificati in modo non corretto dall'altro.  
  
Il contenuto classificato “in modo non corretto” è facilmente intuibile come sia rappresentato da quei contenuti che sono "entrati" nell'analisi a seguito della scelta di parole chiave errate, o di un perimetro errato. Possono essere *hashtag* che non ci eravamo accorti essere usati altrove per altri scopi o il personaggio omonimo di una star del sud-est asiatico o ancora contenuti per nulla attinenti ma aventi medesimi *hashtag* per uno scherzo del destino (ci è capitato con manifestazioni aventi lo stesso *hashtag* di un programma televisivo ma facenti capo ad un congresso di odontoiatri). Questi contenuti devono ovviamente essere estromessi per non falsare i dati quantitativi dell'analisi, spesso anche in percentuale consistente.  
  
Un po' più complessa la tematica dello spam e della pratica comunemente detta tailgating: si tratta della abitudine ormai discretamente consolidata di inviare messaggi pubblicitari/politici/sociali utilizzando gli *hashtag* degli argomenti di punta, facendo sì in questo modo che chi sta seguendo una ricerca per *hashtag* si imbatta direttamente in questi contenuti, prevalentemente creati a scopo pubblicitario. Come gestire questi contenuti è un tema dibattuto, perché una parte consistente degli analisti tende a reputarli come facenti comunque parte del fenomeno e a conteggiarli. In [The Fool][1001] vengono classificati da analisti e dalla piattaforma come spam e vengono estromessi dalle analisi: siamo infatti dell'opinione che tali contenuti nulla aggiungano, nel bene e nel male, alla conversazione e che non debbano quindi, in quanto episodi sporadici, essere calcolati all'interno dell'analisi quali-quantitativa.  
  
Sebbene alcune di queste rilevazioni di contenuti "spuri" o "erronei" possano essere elaborate matematicamente, ancora nessun algoritmo è in grado di battere l'affidabilità di un analista umano ed un servizio di analisi condotto  da analisti esperti dimostra, anche in questo ambito, tutta la propria superiorità rispetto a qualunque processo meramente tecnologico.  

I> Quindi: per mettere a confronto due analisi controlla attentamente come vengono riconosciuti ed eventualmente estromessi i fenomeni di spam e di tailgating o gli errori di classificazione.
  
# Da dove provengono i dati    

Per elaborare le analisi non sempre si dispone della stessa fonte dati: esistono infatti differenti modalità per poter usufruire dei dati e differenti costi nell'accedere a ciascuna di queste, che sebbene non costituiscano un problema per un utilizzo non professionale (o anche aziendale ad uso consuntivo) delle analisi, devono però essere attentamente vagliati per un utilizzo professionale degli stessi.  
  
Le differenze sono importanti, soprattutto da un punto di vista del bilanciamento tra completezza del dato offerto e costo di accesso alla modalità di analisi: sebbene infatti sia possibile ottenere anche gratuitamente i dati da Twitter/Facebook, la quantità degli stessi è limitata ad una frazione del totale dei contenuti disponibili, non è disponibile come dato storico ma solamente in tempo reale e, soprattutto e principalmente, nessuna garanzia è data sulla completezza del dato, come anche corretto per un servizio erogato gratuitamente. "I servizi a pagamento, d'altro canto, garantiscono l'accesso *(a volte anche in differita)* al dato con una certezza di completezza, ovviamente a fronte di un esborso economico spesso proibitivo per le singole realtà.  
  
Volendo riassumere per sommi capi le differenti tipologie di contenuti è possibile suddividere in:  

* Provider diretto con accesso alla base dati storica
* Provider diretto senza accesso alla base dati storica
* Provider indiretto con accesso al dato storico
* Provider indiretto senza accesso al dato storico
* Provider diretto a best-effort

## Provider diretto con accesso alla base dati storica

È la versione indubbiamente più costosa di recupero dei dati e offre non solo  l'accesso completo al firehose *(così vengono chiamati i flussi dati dei social network)* dei dati per poter mettere in tempo reale in ascolto su qualunque combinazione di parole chiave i contenuti postati sulle piattaforme, ma anche la possibilità di accedere al contenuto storico a posteriori per eseguire nuovamente eventuali analisi che si ritenessero necessarie, anche trascorso l'evento. È la tipologia di accesso utilizzata in [The Fool][1001].

I> Quindi: se avere un panorama il più possibile completo del dato è una vostra priorità e pensate che sia necessario avere la possibilità a posteriori di svolgere analisi su eventi passati, questa è la tipologia di dato di cui avete necessità.

## Provider diretto senza accesso alla base dati storica

È la versione più utilizzata da quasi tutti i servizi a pagamento disponibili e consente, previa corretta impostazione delle analisi in prima battuta, di catalogare i contenuti trovati in tempo reale sulla base delle parole chiave impostate. Tuttavia non permette in alcun modo di correggere a posteriori le analisi, qualora alcune parole chiave non fossero state impostate e non consente analisi a posteriori su eventi trascorsi.  

I> Quindi: se avere un panorama il più possibile completo del dato è una vostra priorità ma vi è sufficiente pre-impostare parole chiave per eventi futuri senza necessità di svolgere analisi su eventi passati, questa è la tipologia di dato che cercate.

## Provider indiretto con accesso al dato storico

È la versione normalmente in forze a buona parte delle Agenzie Web, con l'utilizzo di sistemi di secondo livello che classificano i contenuti dei vari social network e li indicizzano. La loro copertura differisce di norma di circa il 15/20% rispetto ai provider ad accesso diretto. L'accesso storico ai dati non ha quasi mai la garanzia del 100% della copertura, ma si limita in genere alla copertura di quei soli contenuti che uno degli utenti della piattaforma aveva in osservazione. Chiedere informazioni approfondite al provider di dati rivela spesso molte sorprese inaspettate.    

I> Quindi: se vi basta avere un’idea di massima del dato sia in futuro che, eventualmente, su eventi passati e non avete necessità di dati completi al 100% questa è la modalità consigliata.

## Provider indiretto senza accesso al dato storico

È la versione economicamente più vantaggiosa rispetto alla precedente soluzione e la normale fornitura dei prodotti di costo minore (meno di 500 euro/mese) consente l'analisi senza alcuna garanzia di completezza del dato e senza accesso "storico", permettendo di  rilevare contenuti facenti capo alle parole chiave inserite dal momento del loro inserimento in avanti.  

I> Quindi: se vi è sufficiente avere un’dea di massima del dato senza necessità di una copertura al 100% e non avete necessità di accedere a eventi passati, questa modalità è la più vantaggiosa.

## Provider diretto a best-effort
È la versione più utilizzata, per ragioni economiche, per test e per tutte quelle realtà che non necessitano di completezza del dato. È anche la versione data a disposizione gratuitamente da Twitter via API, limitata solo dalla quantità di contenuto che può essere rinvenuto attraverso questa metodologia, dove Twitter stesso non restituisce un valore preciso ma si limita a dire che si tratta di "un campione dei dati". Ovviamente basare su questa fonte dati le analisi rappresenta un’impossibilità pratica.

I> Quindi se vi serve, a mero scopo di intrattenimento o informazione sommaria, soltanto un campione delle conversazioni su un argomento, questa è sicuramente l'opzione da contemplare!

# Come vengono misurate le performance

Altro annoso problema, una volta recuperati i dati, è ovviamente quello di analizzarli ed estrarre da questi degli indicatori che possano servire per comprendere al meglio i fenomeni. Vige, in tutto l'ambiente, una certo utilizzo ambiguo di terminologie che non aiuta nella condivisione delle valutazioni: ad esempio si sente parlare spesso di ROI *(Return On Investment)*, una metrica prettamente finanziaria, al posto del termine più corretto di KPI *(Key Performance Indicator)* o di Metrica.  
Per disambiguare una volta per tutte queste problematiche, prima di procedere nelle analisi, è utile ricapitolare, senza troppa documentazione accademica, i significati che diamo a una serie di termini:  

* **Metrica**: una metrica è un indicatore numerico che ci aiuta a comprendere un fenomeno *(quanti fan ha la mia pagina?)*;
* **KPI**: è una metrica riferita ad un contesto e un obiettivo *(voglio ottenere un +23% di fan nel trimestre, ad oggi sono ad un +5%)*;
* **ROI**: è un particolare indicatore di valutazione finanziaria per il calcolo a posteriori della profittabilità di un progetto *(quanto ho venduto con una spesa di 1 euro in Adv su Facebook?)*;

In questa ottica è necessario conoscere le differenti **metriche**, poiché per valutare il nostro (o altrui) operato abbiamo bisogno di utilizzarle per stabilire degli obiettivi che vogliamo raggiungere e quindi costruire dei corretti **KPI** per valutare il raggiungimento (o meno) di tali obiettivi. Su questi obiettivi possiamo anche decidere di investire un budget e tracciare i risultati finanziari per poter eventualmente calcolare un **ROI** dell'azione che abbiamo intrapreso.  
  
Per portare concetti astratti nel concreto, possiamo decidere che vogliamo controllare come **metrica** il numero di tweet per singola trasmissione, poiché tra i tanti abbiamo valutato o deciso che è quello che meglio rappresenta la misurazione del successo di un’iniziativa.  
Stabiliamo come **obiettivo** una crescita del 30% dei tweet rispetto alla stagione precedente: i nostri **KPI** saranno il delta di percentuale tra i tweet della puntata attuale e i tweet dell'omologa puntata nella stagione precedente *(es. +5%)*, oltre al delta totale della stagione precedente rispetto a quella attuale, che ci aiutano a comprendere come, nel tempo, stiamo avanzando e quanto siamo distanti dall'obiettivo finale.  
Se abbiamo disponibilità di tracciare una metrica finanziaria *(es. redemption di un coupon twittato)*, possiamo definire un budget per sponsorizzare i tweet in cui annunciamo i buoni, aggiungere i costi di gestione dell'iniziativa, misurare quanti buoni vengono riscossi ed ottenere una indicazione anche del **ROI** dell'iniziativa.  
  
Se la scelta dei KPI passa necessariamente dagli obiettivi che mi pongo (e non fa quindi parte delle analisi che vediamo pubblicate online) la base fondante di ogni KPI che vado a creare non è nient'altro che una combinazione di metriche singole, metriche che assolvono ciascuna ad un compito differente e che, sebbene spesso fortemente correlate, danno ciascuna un punto di vista differente su di un fenomeno e solo conoscendo le peculiarità di ciascuna posso essere in grado di scegliere quelle migliori per il mio caso specifico.  

# Quali tipologie di metriche?

Non tutte le metriche nascono uguali e non tutte hanno le medesime finalità: se vogliamo comprendere approfonditamente il tema delle metriche è probabilmente necessario effettuare qualche distinzione importante.  
  
In primo luogo è necessario differenziare le **Vanity Metrics** dalle **Actionable Metrics**: le prime non hanno utilità pratica e servono semplicemente per "vantarmi" con i competitor relativamente alla mia supposta superiorità rispetto a loro, mentre le seconde mi consentono di creare una misurazione utile per impostare strategie. Tra le Vanity Metrics per eccellenza abbiamo il numero di Fan di Facebook e il numero di Follower Twitter, ambedue proprio perché Vanity hanno visto crearsi un copioso mercato "nero" o "grigio" di compravendita di Fan e Follower a poco prezzo, per poter ottenere una metrica socialmente presentabile e destinata (nell'immaginario dei non addetti ai lavori) a suscitare stima o invidia.  
  
Altra importante distinzione è quella tra **Metriche Pubbliche** e **Metriche Private**: le prime sono disponibili a chiunque e possono quindi costituire un metodo per paragonare tra loro differenti competitor ad armi pari, le seconde invece sono disponibili solamente agli amministratori dei vari profili e non disponibili al mondo esterno. Ovviamente l'unico modo di confrontare sullo stesso piano differenti eventi o realtà è solamente quello di utilizzare delle Metriche Pubbliche, dove chiunque dispone delle adeguate conoscenze e piattaforme può analizzare i dati ed ottenere, nei limiti degli errori di misurazione, i medesimi risultati. Sono esempi di Metriche Pubbliche il numero di tweet, il numero di Follower, il numero di messaggi e like sui post della pagina Facebook ed esempi di Metriche Private il Reach delle Pagine Facebook e le Organic Impression dell'account di Twitter.  
  
Ulteriore riflessione merita la differenza tra **Metriche Aperte** e **Metriche Chiuse**: le prime sono disponibili a molteplici (o tutti) gli operatori di settore e consentono anche in modo competitivo di usare differenti fornitori per paragonare (e controllare) i dati a vicenda, mentre le seconde sono date direttamente dalle piattaforme ad una realtà monopolista. Non essendo possibile esternamente controllare la veridicità delle informazioni date tramite **Metriche Chiuse**, e non essendo possibile controllare eventuali errori (anche in buona fede), non esiste **alcuna possibilità che tali metriche, per quanto certificate, possano essere proficuamente utilizzate per costituire una "currency"**.
  
# Una panoramica delle Metriche  

Nelle prossime pagine analizzeremo le principali metriche, in un elenco sicuramente non onnicomprensivo ma auspicabilmente abbastanza esaustivo, cercando di spiegarne (in breve) l'utilità ed i limiti.  

Saranno presentate diverse tipologie di metriche legate a differenti ambiti di analisi, tutte altrettanto importanti per comprendere i fenomeni in analisi, ma dedicate ciascuna all’indagine di un ambito specifico. Volendo distinguere le varie tipologie di metriche potremmo utilizzare la seguente tassonomia:

* **Metriche di Diffusione**: Quantificano numericamente un fenomeno e le caratteristiche che hanno portato alla sua diffusione;
* **Metriche di Contenuto**: Analizzano quantitativamente e qualitativamente i contenuti del fenomeno, cercando di interpretarne il senso;
* **Metriche di Influenza**: Analizzano quantitativamente gli utenti che hanno partecipato alle conversazioni cercando di stabilirne l'efficacia di comunicazione.

Ciascuna metrica verrà analizzata singolarmente anche se, ovviamente, quasi tutte interagiscono tra di loro per la valutazione complessiva di un fenomeno e non possono che essere prese in esame nella loro interezza.  
  
## Il numero di Tweet

Una delle metriche principali, quella peraltro più roboante anche a livello mediatico, è sicuramente il numero di tweet. È semplice da leggere, è la metrica, insieme alle Impression, più di impatto e la superiore come cardinalità.  
È anche una metrica importante per notare l'andamento di un fenomeno e, quindi, una di quelle su cui si basa massivamente il paragone tra i differenti programmi.  
  
Al contrario di altre metriche è molto più sensibile sia alla scelta oculata delle parole chiave dell'analisi, sia alla scelta del limite temporale e spesso variazioni anche minime di questi due fattori possono determinare scostamenti anche importanti tra due differenti analisi.  
  
I limiti di questo tipo di metrica sono evidenti: basta un ristretto gruppo di utenti determinati per manipolare anche significativamente la cardinalità finale, e questo comportamento è peraltro abbastanza standard in fenomeni come il tailgating *(l'utilizzo di hashtag di trasmissioni a fine di spam)* o il tweetting compulsivo in occasioni di cyberstrike *(utenti associati per creare "disturbo" ad un particolare hashtag)* o hashjacking *(utenti che utilizzano in modo differente ed antagonista l'hashtag proposto)*.  
  
Una misura meramente quantitativa dei tweet è sicuramente una misura efficace nel valutare l'entità di un fenomeno ma, stante l'attuale configurazione dei servizi come Twitter, rischia nel tempo di divenire una vanity metric, una di quelle metriche cioè che contano come solo fine quello di attribuire una "medaglietta" al possessore della metrica più alta senza alcun effetto reale di impatto sul business.  
  
È una metrica "pubblica", ed è quindi ottenibile anche senza i privilegi di amministrazione sugli account social, il che ne determina un’ottima utilizzabilità per il paragone tra differenti Brand ed un’ottima affidabilità, con la possibilità per plurimi soggetti di controllarla anche separatamente.  
  
Nonostante queste limitazioni, impostare dei KPI per eventi simili o per una serie di eventi basandosi sulla differenza del numero dei tweet è comunque una strategia efficace nel misurare, soprattutto per esigenze interne, le proprie performance.

## Il numero di Fan di una FanPage

Se, agli esordi di Facebook, un ampio numero di fan di una pagina offriva un’enorme possibilità di raggiungere il proprio uditorio mentre il fenomeno della compravendita di Fan rappresentava un problema marginale, l’avvento di nuove regole di visibilità, che riducono ad una frazione la visibilità dei post di pagina e che rendono l'acquisto di utenti disponibile a chiunque, ha severamente limitato le capacità di questa metrica di rappresentare poco più che una Vanity Metric.  
  
Come però scontato, il numero di Fan della pagina rimane, più a torto che a ragione, un metro di paragone tra differenti Brand, spesso (forse *troppo* spesso) utilizzato nelle varie classifiche che ordinano proprio per questa metrica il successo o l'insuccesso di un marchio, prodotto, personaggio, ed è quindi una metrica da cui è impossibile prescindere all'interno di una realtà in cui "si viene giudicati" anche per questo fattore, per quanto poco utile ai fini pratici.  
  
È una misura "pubblica", ed è quindi ottenibile anche senza i privilegi di amministrazione sugli account social, il che ne determina un’ottima utilizzabilità per il paragone tra differenti Brand e un’ottima affidabilità con la possibilità per plurimi soggetti di controllarla anche separatamente.  
  
Essendo impossibile omettere questa misurazione, merita sicuramente di essere relegata non già a componente principale nella formulazione dei KPI, anche perché fortemente correlata ad altre dinamiche di puro Engagement *(maggiore è il coinvolgimento che riesco a generare, maggiore sarà il numero di utenti che seguirà la mia pagina)*, ma a presentarsi meramente come una misura consequenziale ad altre azioni intraprese. 

## Il numero di Utenti Unici

Forse una in assoluto delle migliori metriche per valutare l'efficacia di una azione Social in genere e soprattutto di un evento commentato su SocialTV è il numero di utenti unici che sono stati attivati in una azione su Twitter o Facebook. Le azioni che, normalmente, vengono prese in esame sono i Tweet ed i Retweet, mentre su Facebook si prendono in considerazione gli utenti che hanno commentato o fatto like su Post e Commenti. Il numero degli utenti complessivi rappresenta il metro della mia capacità di "attivare" il Social.  
  
La metrica è tutt'altro che perfetta, non tenendo infatti conto degli utenti coinvolti "passivamente" e per problemi di API anche degli utenti che fanno "share" su Facebook o "preferito" su Twitter, ma rappresenta comunque forse la migliore metrica disponibile via accesso programmatico e quindi ottenibile per paragoni tra differenti eventi o Brand. Anche in questo caso si tratta, infatti, di una misura "esterna", ed è quindi ottenibile anche senza i privilegi di amministrazione sugli account social, il che ne determina una ottima utilizzabilità per il paragone tra differenti Brand e una ottima affidabilità con la possibilità per plurimi soggetti di controllarla anche separatamente.  

Impostare un KPI sulla base delle aspettative di Utenti Unici è un ottimo modo per confrontarsi con criteri di reale engagement *(partecipazione)* e non meramente a delle metriche di rappresentanza.  

## Il numero di Utenti Attivi/Passivi  
  
Altra metrica fortemente utile e "pubblica", quindi affidabile e controllabile anche dai non amministratori, è la misurazione degli utenti "attivi" e degli utenti "passivi", normalmente definiti su Twitter come quelli che inviano tweet (“attivi” o “conversatori espliciti”) e che si limitano al mero retweet (“passivi” o “conversatori impliciti”) e su Facebook come gli utenti che commentano (“attivi” o “conversatori espliciti”) contro quelli che meramente impostano un "like" (“passivi” o “conversatori impliciti”)[^espliciti].

[^espliciti]: Nella realtà non è formalmente corretto parlare degli utenti che si limitano a like e retweet come utenti “passivi”, perché rappresentano comunque una volontà di selezione dei contenuti e di “content curation”. Per questo la suddivisione che mi sento di suggerire è classificare comuque gli utenti come “conversatori” espliciti o impliciti.  
  
Il metro del rapporto tra utenti unici attivi e passivi ci può dare informazioni interessanti sul livello di coinvolgimento che siamo riusciti a creare, magari in occasione di eventi da commentare *(ad esempio un voto online)* o a comprendere se qualche parte della rete sociale attivata ha contribuito in modo determinante al successo della disseminazione di informazioni creando un alto numero, ad esempio, di retweet.  
  
Come nel caso dei generici Utenti unici, anche nel caso degli utenti attivi/passivi impostare un KPI sulla base delle aspettative queste tipologie di utenti è un ottimo modo per cimentarsi con dei criteri di reale engagement, molto lontani delle metriche di rappresentanza.  

## L'Accelerazione (o contents-per-time)

Una misura importante per definire un fenomeno è sicuramente quella dell'Accelerazione, la capacità cioè di generare una moltitudine di contenuti in un ristretto periodo di tempo. L'Accelerazione, e non il numero grezzo di tweet anche se le due metriche sono spesso strettamente correlate, è anche uno dei fattori principali per la comparsa su Twitter degli *hashtag* in Trendig Topic.  
  
Analizzare l'Accelerazione consente ovviamente di individuare i picchi di attenzione (e coinvolgimento) degli utenti e ad intuire i momenti che hanno suscitato più attenzione. Una analisi precisa dei momenti di forte Accelerazione è fondamentale, un po' come l'analisi dei picchi di ascolto durante la trasmissione nelle analisi "tradizionali". Anche l'attenzione alle strategie per ottenere una forte Accelerazione (ad esempio proponendo domande o votazioni via Social) è un fenomeno da tenere in grandissima considerazione, sia per aumentare, come ovvio, il numero complessivo di contenuti creati dagli utenti, sia per aumentare il numero di utenti unici, ma soprattutto per cercare di ottenere un forte incremento dei contenuti nell'unità di tempo che ci può consentire di "scalare le classifiche" degli argomenti "caldi" sulle piattaforme e beneficiare quindi della spinta "indotta" dalla piattaforma stessa che propone regolarmente agli utenti i topic più caldi.

## Le Impression ed il Reach di Facebook

Un paragrafo a parte meritano le metriche "private", quindi non disponibili a tutti (specialmente ai Competitor), di Reach e di Impression, soprattutto perché spesso si prestano ad interpretazioni "fantasiose" e lontane dalla verità. Le due metriche sono rappresentazioni del medesimo fenomeno: si tratta infatti della misurazione della esposizione che i contenuti che noi pubblichiamo sulle nostre pagine riescono ad ottenere da parte degli utenti di Facebook, semplicemente dividendo in "occasioni" ed "utenti unici".  
  
Il Reach è rappresentato dal numero di individui unici (o forse sarebbe meglio dire "account unici") che sono stati esposti al contenuto analizzato e che hanno quindi avuto la possibilità di visualizzarlo. Non significa che l'utente lo abbia effettivamente letto, ma semplicemente che all'interno del suo "wall" ha effettivamente visualizzato quel contenuto. Se lo stesso contenuto è presentato più volte, magari perché condiviso da più amici contemporaneamente, o se è visualizzato su più piattaforme la metrica del Reach mi restituirà comunque un solo valore per ogni utente unico. Un aumento di Reach è un traguardo importante, poiché significa che si è riusciti a coinvolgere una più ampia rete sociale all'interno della sfera di distribuzione dei propri contenuti.   
  
Il valore di Impression rappresenta, invece, il numero di volte che un contenuto ha avuto la possibilità di essere visto all'interno della piattaforma, senza tenere conte della duplicazione degli utenti: ogni utente ha infatti la possibilità di essere esposto al contenuto molteplici volte da più dispositivi e da condivisioni multiple di altri utenti della piattaforma. Si tratta a tutti gli effetti non già di una metrica reale ma di una misura di impatto potenziale che ci fornisce un dato importante per valutare la diffusione che il mio contenuto ha ottenuto. Un aumento delle Impression è una metrica importante da analizzare, poiché significa anche a parità di Reach che gli utenti che sono stati coinvolti hanno avuto più possibilità di essere esposti ai miei contenuti e, quindi, di notarli o di interagirvi.   
  
Se voglio quindi ottenere una misurazione della esposizione effettiva di audience che sono riuscito a generare posso ricorrere al Reach, mentre se voglio avere una indicazione della esposizione del messaggio che ho ottenuto, in gergo OTS (Opportunity To See), la misura che sto cercando è quella delle Impression.  

## Le Impression di Twitter

La misurazione delle Impression su Twitter segue la medesima logica di impatto "potenziale" di visualizzazione in una metrica "pubblica". Il valore di Impression rappresenta, infatti, il numero di volte che un contenuto ha avuto la possibilità di essere visto all'interno della piattaforma, senza tenere conte della duplicazione degli utenti. Questo è anche il motivo per cui con 35 milioni di italiani attivi online i valori di Impression forniti nelle analisi possono essere anche dei centinaia di milioni di unità: non si tratta di un errore, ma semplicemente della molteplice possibilità di un singolo utente di essere esposto al singolo tweet.  
  
Normalmente il numero di Impression viene calcolato moltiplicando i tweet su un particolare topic o *hashtag* in analisi per il numero dei follower dell'account che li ha effettuati e sommando i valori. Questo significa che se un account con 10.000 follower twitta due volte, il numero di Impression sarà di 20.000.  
  
Alcuni player di mercato hanno introdotto anche una metrica leggermente modificata di Unique Impressions, rappresentata dal conteggio unitario dei follower del singolo account (nel caso precedente quindi avremo un valore di 10.000).  
  
La misura delle Impression, a parte una spettacolarizzazione del fenomeno, segue le stesse logiche delle Impression di Facebook: ancora una volta si tratta non già di una metrica reale ma della misura di un effetto di impatto potenziale, per valutare la diffusione del mio contenuto. Un aumento delle Impression è, ancora una volta, una metrica importante da analizzare, mostrando che gli utenti che sono stati coinvolti hanno avuto più possibilità di essere esposti ai miei contenuti e, quindi, di notarli o di interagire con essi. 
  
Una nota particolare merita la definizione di Impression data da Twitter stesso all'interno della sua piattaforma (nei pannelli di Analytics e nella applicazione): non si tratta infatti di una misura di Impression secondo gli standard del mercato qui espressi, ma della misura Privata di Organic Impression, il numero cioè reale di volte in cui gli utenti sono stati esposti al messaggio e non già una misura potenziale delle OTS (Opportunities To See). La differenza è notevole: le Impression misurano in potenza la massima portata che posso attendermi dal mio messaggio basata sul numero di follower degli account che lo comunica, mentre le Organic Impression rappresentano il numero reale di volte in cui il mio messaggio ha raggiunto l'audience.  

Si tratta di una misura che Twitter non rilascia se non per gli account di mia proprietà e che non è disponibile Pubblicamente: inadatta quindi a confronti tra fenomeni ma molto utile nelle analisi interne dell'andamento dei miei Account.  
  
## La Unique Audience di Twitter (o True Reach)

La collaborazione tra Twitter e Nielsen ha portato all’introduzione nel mercato della SocialTV di una nuova metrica denominata Unique Audience, che riprende l'omonimo termine di Nielsen nell'analisi delle performance online.  
  
La metrica rappresenta il totale degli utenti unici che hanno visualizzato almeno uno dei tweet presenti nel perimetro di indagine, in una quantificazione simile a quella del Reach ma limitata non già ad un account, ma ad un perimetro di analisi. Le differenze con le metriche di Reach all'interno del pannello di analytics di Twitter sono quindi due: innanzitutto si tratta di utenti che hanno partecipato all'evento non solamente interagendo con i contenuti creati dall'account che si gestisce, ma anche di quelli che hanno citato *hashtag*, parole chiave, personaggi dell'evento all'interno della finestra temporale oggetto di analisi. La seconda differenza sostanziale è la possibilità per Nielsen di accedere a questi dati per la totalità degli account e degli eventi presenti su Twitter, possibilità che consente di effettuare paragoni tra programmi impossibili per il singolo account.

Benché questa metrica rappresenti probabilmente una delle migliori presenti sul mercato, è affetta da una serie di problemi strutturali non indifferenti: per prima cosa coinvolge solamente il mondo di Twitter, estremamente riduttivo nella comprensione dei fenomeni, e in secondo luogo rappresenta una metrica chiusa, i cui dettagli non sono disponibili per un controllo di terze parti, non fornendo Twitter i medesimi dati agli sviluppatori per creare analisi similari. Questo approccio fa si che anche in presenza di problematiche evidenti non si sia in grado di contestare una metrica chiusa: nessuna metrica standard di analisi può in alcun modo appoggiarsi a dei valori che non siano pubblici e verificabili da terzi.  

## Like, Favourite e Applause Metrics	

Una categoria a parte nella valutazione delle metriche è costituita da quelle che vengono comunemente definite Applause Metrics e cioè quelle metriche che rappresentano un indice di gradimento da parte del pubblico di un particolare contenuto, espresso su Twitter con un Favorite e su Facebook con un Like.  
  
Benché questa metrica porti un limitato effetto di amplificazione dei contenuti (solo alcune piattaforme mi propongono i contenuti apprezzati dalla mia rete sociale), la metrica di apprezzamento è invece fondamentale per comprendere appieno quali tipologie di contenuti sono i più apprezzati dalla mia rete sociale e quali, per contrasto, non riescono a suscitare interesse ed empatia.  
  
Un’analisi nel tempo delle metriche di Applause può dare un riscontro estremamente veloce ed intuitivo per la valutazione della modifica dell'apprezzamento dei miei contenuti all'interno della mia audience potenziale, aiutandomi a selezionare quelle tipologie di contenuti maggiormente in linea con i gusti dei miei target.  

## Retweet, Share e Amplification Metrics	

Una categorie di metriche estremamente importanti, per non dire vitali, per la disseminazione dei miei contenuti è rappresentata dalle Amplification Metrics che comprendono lo Share di Facebook e il Retweet di Twitter.  
  
Chiaramente fondamentali per la condivisione dei contenuti, per la diffusione e ovviamente per l'impatto che questo può avere in termini di variazione di tutte le altre metriche, divengono ancora più fondamentali in un ecosistema dove, come è noto al settore, sempre più contenuti vengono usufruiti non tanto per la loro visualizzazione all'interno di pagine e account ufficiali, quanto per la loro visualizzazione all'interno degli account degli utenti che condividono i contenuti.  
  
Un’analisi nel tempo delle metriche di Amplification consente un riscontro immediato ed intuitivo per la valutazione non solamente di quei contenuti che gli utenti si sentono inclini a condividere all'interno della loro rete sociale, ma anche una valutazione di opportunità nella selezione di quei contenuti che, maggiormente in linea con la volontà di condivisione, posso creare per ottimizzare il raggiungimento di una massa sempre più ampia di utenti. 

## La Total Audience

Non tutte le metriche sono una "soluzione" in cui basta una definizione per comprendere il problema: il grande mistero della analisi degli eventi Social rimane quello della Total Audience, il totale delle persone uniche che hanno partecipato ad un evento indipendentemente dal Social utilizzato.  
  
Cercare infatti di limitare l'audience e le metriche ad un solo Social (sia esso Facebook o Twitter indifferentemente) è infatti come voler calcolare il numero dei turisti di una città volendo contare solamente quelli vestiti di rosso. Non solamente si rischia di sottostimare grandemente il numero complessivo, ma come il turista può cambiare vestito più volte al giorno, un singolo utente può usufruire un evento su più piattaforme contemporaneamente o con diversi Social in differenti momenti.  
  
Nell'impossibilità per ora di tracciare gli utenti **in modo univoco** attraverso differenti Social, l'approccio sicuramente più utile e più razionale è impostare dei KPI che prendano in considerazione per lo meno gli utenti unici delle varie piattaforme: limitarsi a valutare i fenomeni su una sola, anche se la più popolosa, rimane sicuramente una approccio limitativo e di sicura sottostima.  

## Le principali Parole Chiave

Non sempre gli utenti esprimono concetti, anche polarizzati, utilizzando gli *hashtag*. Analizzare quindi semplicemente gli *hashtag* non permette di  ottenere un disegno completo di cosa sta accadendo (o è accaduto) all'interno del perimetro dell'evento, ed è così necessario riuscire ad ottenere anche un elenco delle parole chiave che gli utenti hanno utilizzato.  
  
Tale elenco deve ovviamente escludere, per evitare il rumore di fondo, quelle parti di frase comunemente definite "stopwords": rappresentano le parole "vuote" e senza significato implicito come pronomi, articoli, preposizioni ed altre parole, che non aggiungono concetti ma creano ampio rumore.  
  
Tracciare le parole chiave più utilizzate porta agli stessi vantaggi del monitoraggio degli *hashtag*, anche in questo caso fornendo spunti importantissimi per selezionare in modo efficace le parole chiave da aggiungere nella selezione delle parole chiave per il monitoraggio.  

## Gli utenti più Attivi

Vengono definiti utenti più attivi quelli che all'interno del perimetro di riferimento hanno prodotto la quantità maggiore di contenuti relativamente all'ambito di indagine. Non è assolutamente detto che siano i più influenti o i più popolari, ma semplicemente hanno deciso di essere estremamente attivi nella creazione di contenuti che sono ricaduti all'interno dell'analisi.  
  
L'analisi degli utenti più attivi diviene utilissima per individuare velocemente quegli utenti che si impegnano in azioni di spam o in tailgating (la creazione di contenuti con *hashtag* di trasmissioni per fine pubblicitario) oltre che per individuare, in caso di concorsi o questionari, le più evidenti anomalie.  

Se il contenuto creato è pertinente, invece, siamo semplicemente di fronte ad utenti particolarmente affezionati che potremmo decidere a qualche titolo di ingaggiare.

## Gli utenti più Popolari

La misura degli utenti più popolari è effettuata normalmente calcolando quegli utenti all'interno del perimetro di analisi che sono stati più citati da altri utenti, con mention, con messaggi o con retweet. Rappresentano uno specchio importante in cui andare ad individuare gli utenti che sono stati maggiormente al centro dell'interesse da parte del pubblico Social.  
  
Sono da distinguere in due differenti categorie: utenti attivi che sono stati molto condivisi con retweet o mention, che sono da tenere in grandissima considerazione per via della loro palese capacità di diffondere un messaggio e generare conversazioni, e utenti che non sono stati attivi ma che vengono comunque citati, in genere personaggi dello spettacolo presenti in trasmissione o citati.  
  
La misura degli utenti più popolari è un’ottima metrica per individuare macroscopicamente nell'arena dei commentatori dell'evento quei soggetti che hanno manifestato più influenza tramite la capacità sviluppare azioni da parte di altri utenti.  

## Gli utenti con più Impression  
  
La metrica delle Impression, che abbiamo analizzato in precedenza, è calcolata all'interno del perimetro di analisi moltiplicando il numero dei tweet effettuati dal singolo utente per il numero dei suoi follower e creando una sommatoria di tutto l'evento.  
Come è facile intuire, lo spaccato delle Impression generate dal singolo utente ci offre uno strumento piuttosto utile per l'analisi di quali utenti hanno maggiormente contribuito alla diffusione delle opportunità di visualizzare il nostro contenuto.  
  
È da notare come spesso la classifica degli utenti che hanno generato maggiori impression coincida con quella degli utenti con un maggior numero di follower. Un attento paragone tra queste due misurazioni consente frequentemente di trarre spunti interessanti su come coinvolgere gli utenti particolarmente abili nel generare potenziali visualizzazioni.

## Gli utenti con più Follower

Vanity Metric per eccellenza, il numero dei Follower è la misura tra tutte con minore affidabilità, vista la notevole semplicità che il mercato ha sviluppato negli anni di acquistare follower a bassi prezzi ed ancora più bassa utilità e possibilità di ingaggio.

Ingaggiare una TwitStar con un numero ampissimo di Follower di cui la maggior parte risulta inattiva è una perdita di tempo e denaro se non si è assolutamente sicuri della onestà e liceità della sua base di Follower.  
  
È comunque possibile valutare in modo abbastanza agevole la plausibilità che i follower siano genuini andando ad analizzarne un campione e prendendo nota di fattori come nazionalità, lingua, ultima azione effettuata: queste misurazioni ci consentono di avere un buon metro di giudizio per l'ingaggio o meno di utenti con "reali" follower.

## Gli utenti con maggiore Score di Influenza

Utili, quando se ne comprendono i limiti più che i pregi, sono anche i servizi che offrono una misurazione indiretta della Influenza dei singoli utenti della rete: svariate metriche sono attive e forniscono normalmente valori numerici da 1 a 100 generalizzati sull'utente o suddivisi all'interno di categorie di influenza (motori, tv, sport...).  
  
Se l'utilizzo di tali metriche diviene estremamente utile per riconoscere velocemente, all'interno di un vasto elenco di utenti che hanno partecipato alla conversazione, quelli che macroscopicamente possiedono una misurazione di Influenza maggiore (le TwitStar), non è sempre detto che orientarsi su queste tipologie di dati o sulle piattaforme che offrono classifiche per argomento possa essere utile: tali piattaforme offrono infatti una visione di insieme difficilmente legata al mio programma ed alla mia nicchia verticale, oltre a mancare totalmente della parte di valutazione sulla vicinanza (o sul disprezzo!) del mio Brand con l'utente.  
  
Il consiglio migliore è quello di non affidarsi a misure esterne e generali relativamente agli influencer, ma valutarli singolarmente per la mia trasmissione o il mio evento sulla base di una analisi interna all'evento stesso, giudicando quali utenti si sono contraddistinti, mediante multiple metriche, e hanno portato a risultati reali e misurabili di coinvolgimento.  


## Il paragone audience tradizionale e social

Un ultimo tipo di analisi non propriamente legato ad una metrica ma all'applicazione delle metriche di cui sopra è sicuramente quella del paragone, per i network che dispongono di questo dato, tra i tracciati degli ascolti auditel delle trasmissioni e quelli derivati dall'ascolto dei social.  
  
Questo paragone rivelerà con estrema probabilità, nella maggior parte dei casi, un andamento quasi parallelo delle linee dell'audience nei vari media, ma ogni difformità sostanziale è sicuramente da evidenziare: vi sono infatti dati estremamente interessanti da recuperare anche da questa semplice comparazione.  
  
In primo luogo qualunque difformità nei picchi "di attenzione" rivela molto velocemente quali sketch, quali momenti o quali parti della trasmissione hanno raccolto maggiore apprezzamento dai differenti tipi di pubblico, quello "tradizionale" e quello social.  
Andando ad analizzare intervalli di tempi più elevati, ad esempio una settimana, è anche possibile vedere quali utenti hanno usufruito dei contenuti in modo lineare e quali, invece, ne hanno usufruito e commentato attraverso piattaforme di replay-tv.  
È anche possibile osservare quali argomenti della trasmissione hanno suscitato a posteriori particolari ed importanti discussioni, fornendo una importante quantità di dati per meglio pianificare anche le occasioni di creazione di contenuti social all'interno della trasmissione.  
  
Questa piccola ed in apparenza banale analisi, quindi, offre con dispendio di tempo analisi veramente ridotto una serie di indicatori preziosi per megli comprendere discrasie e diversi pattern di usufruizione tra utenti tradizionali e social.  

# Ringraziamenti

Un libercolo come questo si presta a problemi di interpretazione e soprattutto potrebbe risentire fortemente delle limitazioni dell'autore (soprattutto visto l'autore...). Ma per creare un contenuto che possa essere utile alla maggior parte delle persone è necessario che si ottenga la maggiore precisione possibile.  
Per fare questo ho deciso di contare su una squadra di eccellenti professionisti che revisionassero con me il testo, per fare sì che le menti di molti andassero a colmare le imprecisioni mie. Potete ringraziare loro per molti spunti intelligenti, mentre per ogni problematica residua sono da considerare l'unico responsabile.  
  
Eccoli in ordine rigorosamente sparso (in reltà alfabetico per cognome):  
  
* Raffaele Cumani *(@raffaelecumani)*
* Emanuele Callioni *(@emacall)*
* Mafe De Baggis *(@mafedebaggis)*
* Oscar di Montigny *(@oscardimontigny)*
* Alessandra Farabegoli *(@alebegoli)*
* Carlo Frinolli Puzilli *(@carl0s_)*
* Claudio Gagliardini *(@cla_gagliardini)*
* Filippo Giotto *(@filippog8)*
* Emanuela Goldoni *(@emanuelagoldoni)*
* Francesco Lanza *(@bedrosian)*
* Irene Lasta *(@irenelasta)*
* Giuseppe Mayer *(@giuseppemayer)*
* Giovanni Scrofani *(@jovanz74)*
* Piero Tagliapietra *(@pierotaglia)*
* Diego Valente *(@dvalente10)*
* Stefano Ventura *(@ventura_stefano)*
* Emanuela Zaccone *(@zatomas)*

Questo libro non sarebbe stato possibile senza l'esperienza fatta in The Fool nell'analisi della Reputazione Online e della SocialTV, e principalmente senza le chiacchierate (spesso molto animate) con il team di persone fantastiche che la compone. Credo che tutti abbiano avuto la loro parte, ma nel gruppo ringrazio Barbara Bianchi, Andrea Mostosi, Emanuele Manni, Giulia Garofalo, Giorgio Omati, Lucia Celi, Gianluca Gilardi, Mirko Bruni, Piero Tagliapietra, Jacopo Bravin, Diana Cavarretta, Saveria Gualtieri, Nicholas Wieland, Amit Moravchick, Alessandro Fornaro, Federico Bianco, Mauro Banfi, Manuela Pretis, Michela Borsa, Cibele Mariza Dardi Da Silva e l'immancabile Federica Capelli.  
  
Grazie a tutti di cuore!

I> Marchi e loghi utilizzati in questo volume sono di titolarità dei rispettivi proprietari ed usati solo a scopo descrittivo. Il loro uso non implica avallo o condivisione dei contenuti da parte dei rispettivi titolari.  

# L’Autore

![](images/foto_matteo.jpg)

> "Vestito da buffone naif, fuori da ogni forma o apparenza (..) il Matto rappresenta la forza primigenia senza preconcetti che è alla base del creare."  

Matteo G.P. Flora, Esperto in Digital Reputation e Computer Forensics, è CEO di [The Fool][1001], la Digital Reputation Company italiana dedicata al Monitoraggio, Analisi, Moderazione, Gestione e Tutela Legale della Reputazione e degli Asset Digitali.  
Ha portato [The Fool][1001] ad essere pioniere dell'analisi della SocialTV in Italia, sviluppando i sistemi di controllo e monitoraggio delle performance dei programmi TV oggi utilizzati da uno dei più grandi Broadcaster italiani e le piattaforme di SocialCRM che gestiscono oltre 100 realtà attinenti al mondo dello spettacolo, dell'entertainment e del costume e società.  
Nel 2013 è stato ospite del Dipartimento di Stato Americano nell’ambito del progetto di cooperazione IVLP (International Visitors Leadership Program) che seleziona personaggi nel mondo che possono portare maggiore consapevolezza e cooperazione tra gli Stati Uniti e l’Italia.  
Dirige la Holding Tecnologica Samadhi, è advisor dell’Incubatore LUISS ENLABS, socio co-fondatore del [Centro Studi Hermes per la Trasparenza e Diritti Umani Digitali][1002] e membro del Comitato Scientifico dell’Osservatorio Italiano Privacy e Sicurezza IT oltre che Professore a Contratto in “Open Source Intelligence” nell’ambito del Master di II livello in “Intelligence Economico Finanziaria” dell’Università degli Studi di Roma “Tor Vergata”.  
Scrive su diverse testate, principalmente sui temi di Reputazione Digitale, SocialTV, Privacy e Sicurezza IT, Innovazione e Proprietà Intellettuale.  
Online sono attivi anche il suo blog ([http://mgpf.it][1003]) ed il profilo Twitter ([@lastknight][1004]).  
  
**Per contatti:** mf@thefool.it, twitter @lastknight

[1001]: http://thefool.it
[1002]: http://hermescenter.org
[1003]: http://mgpf.it
[1004]: http://twitter.com/lastknight


# The Fool srl

[The Fool][1001] è la Digital Reputation Company italiana che dal 2008 si occupa di Monitoraggio, Analisi, Moderazione, Gestione e Tutela Legale della Reputazione e degli Asset Digitali. È riconosciuta Leader nella Tutela della Reputazione e del Diritto all’Oblio con strategie e tecnologie per monitoraggio ed analisi. Definita “una della più importanti realtà europee per la protezione della Proprietà Intellettuale online”, fornisce servizi e piattaforme di Misura ed analisi di Sentiment, Brand Reputation, percezione della Reputazione del Brand, di Prodotti e Personal Reputation per clienti Bancari, Assicurativi, Editori, Corporate, Privati ed Enti Governativi con tecnologia proprietaria.  
  
È stata pioniera nell'analisi della SocialTV in Italia, sviluppando i sistemi di controllo e monitoraggio delle performance dei programmi TV oggi utilizzati da uno dei più grandi Broadcaster italiani e le piattaforme di SocialCRM che gestiscono oltre 100 realtà attinenti al mondo dello spettacolo, dell'entertainment e del costume e società.  
  
Offre consulenza, piattaforme proprietarie e personale specializzato per la gestione, in un’unica interfaccia, dell’intero ciclo di vita delle informazioni su tutti i Social Network ed i siti e concorsi aziendali con soluzioni per la Gestione Social, i Servizi di Moderazione, piattaforme di SocialCaring sino all’affiancamento o gestione autonoma dei processi di SocialCRM ed escalation e, tramite consulenza strategica, metodologie e strumenti è in grado di Gestire e Creare una Reputazione Digitale di Brand, Personaggi, Prodotti, Enti ed Iniziative in modo efficace grazie alla applicazione di metodologie di consolidata esperienza.  
  
**Per contatti:** info@thefool.it, +39.02.00618826 - http://thefool.it

## Changelog

* 10 Aprile 2015 - v.1.0 - Messa a disposizione Online tramite il sito


[1]: http://thefool.it
[2]: http://web.social.mediaset.it/*hashtag*