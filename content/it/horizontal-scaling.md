---
title: Horizontal Scaling
status: Completed
category: Concetto
tags: ["infrastruttura", "", ""]
---

## Cos'è

Lo scaling orizzontale è una tecnica in cui la capacità di un sistema viene aumentata aggiungendo altri [nodi](it/nodes/) 
e non aggiungendo più risorse di calcolo ai singoli nodi (quest'ultima tecnica è nota come [scaling verticale] o vertical scaling(it/vertical-scaling/)). 
Supponiamo di avere un sistema con 4 GB di RAM e di volerne aumentare la capacità a 16 GB di RAM, 
scalare orizzontalmente significa farlo aggiungendo 4 x 4GB di RAM piuttosto che passare a un sistema da 16GB di RAM.

Questo approccio migliora le prestazioni di un'applicazione aggiungendo nuove istanze, o [nodi] (it/nodes/), 
per distribuire meglio il carico di lavoro. 
In altre parole, mira a diminuire il carico del server 
e non a espandere la capacità del singolo server.

## Quali problematiche affronta

Quando la domanda di un'applicazione cresce oltre la capacità contingente di quell'istanza, 
è necessario trovare un modo per rendere [scalabile](it/scalability/) il sistema (e quindi aumentarne la capacità).
Possiamo aggiungere altri nodi (scalabilità orizzontale) 
o più risorse di calcolo ai nodi esistenti (scalabilità verticale).

## In che modo aiuta

La scalabilità orizzontale consente alle applicazioni di essere scalabili entro i limiti previsti dal cluster sottostante. 
Aggiungendo altre istanze al sistema, l'applicazione può elaborare un numero maggiore di richieste. 
Se un singolo nodo può gestire 1.000 richieste al secondo, 
ogni nodo aggiuntivo dovrebbe aumentare il numero totale di richieste di circa 1.000 richieste al secondo. 
Questo permette all'applicazione di svolgere più lavoro in contemporanea 
senza che la capacità di un nodo in particolare debba essere aumentata.


## Termini correlati

* [Scaling Verticale](it/vertical-scaling/)
* [Auto Scaling](it/auto-scaling/)



