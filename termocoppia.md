# termocoppia
\documentclass[12pt,letterpaper]{article}
\usepackage[utf8]{inputenc}

\title{Relazione termocoppia}
\author{Bianchi Fabio, Morri Marco}
\date{\today}

\begin{document}

\maketitle

\section*{Riassunto}

L'esperimento è consistito nello stimare i parametri A e B della retta di
regressione lineare (y=A+Bx), utilizzata per la regolazione della termocoppia, che sono
stati stimati come A=(?? \pm ??)$unità di misura$ e B=(?? \pm ??)$unità di
misura$ confrontandoli con quelli ottenuti dai fogli di calcolo.
In particolare, i valori stimati sono: A=(?? \pm ??)$unità di misura$ e
B=(?? \pm ??)$unità di misura$, quelli attesi sono A=(?? \pm ??)$unità di
misura$ e B=(?? \pm ??)$unità di misura$.
Dopo  aver ricavato tali parametri si è proceduto con la stima della
temperatura del giunto freddo e del parametro k della legge di raffreddamento
dell'acqua; le loro stime sono rispettivamente Tf=(?? \pm ??)$unità di
misura$ e k=(?? \pm ??)$unità di misura$.

\section*{Introduzione}

Lo scopo dell'esperimento è quello di stimare: la temperatura del giunto freddo della termocoppia e il valore della costante k della legge di raffreddamento dell'acqua; per fare ciò si è proceduto acquisendo il valore dalla d.d.p. a intervalli di temperatura regolare al fine di ottenere la retta di calibrazione della termocoppia, per fare ciò si è prima fatta una stima della retta di regressione lineare per il riscaldamento dell'acqua, poi si è proceduto analogamente per il raffreddamento, così da confrontare le due stime tra loro; si è inoltre confrontato il valore di  B con  quello atteso $40\cdot10^-6\frac{V}{C}$ al fine di verificare la corretta calibrazione della termocoppia. 
Infine, tramite la formula di Newton, .... si è ottenuta la seguente stima del valore di k e della temperatura del giunto freddo.

\section{Metodo sperimentale}

\subsection{Apparato sperimentale}

Per l'espermento sono stati utilizzati: una termocoppia (un sensore
di temperatura basato sull'effetto Seebeck, cioè sul fatto che due 
giunzioni bimetalliche a temperature differenti generino una
differenza di potenziale), un termistore di riferimento, un
multimetro di Elvis con un'incertezza stimata di (), un becker, una
resistenza (utilizzata per portare l'acqua a temperatura di 
ebollizione), un barometro, acqua distillata (per velocizzare la fusione del ghiaccio) e ghiaccio (per portare la temperatuara iniziale del giunto caldo a 0°C).

\subsection{Svolgimento}

Si è iniziato l'esperimento rilevando la temperatura e la pressione 
del laboratorio; si è proceduto con la calibrazione della termocoppia, per fare ciò si immerso il termistore all'interno di un 
becker contenente del ghiaccio e si è registrato il valore della 
d.d.p a 0°C, si è poi proceduto a registrare i valori della d.d.p. a
intervalli di circa 10°C fino al raggiungimento della temperatura di
ebollizione, ciò è stato possibile tramite l'utilizzo dell'acqua
distillata (per accellerare il processo di fusione del ghiaccio)
prima, e di una resistenza (per portare il ghiaccio ormai fuso a
temperatura di ebolizione) poi, si è inoltre continuato ha registrare
tali valori negli stessi intervalli anche durante il raffreddamento; 
tramite queste due serie di misura è stato possibile stimare e 
confrontare tra loro due rette di regressione lineare, la prima di
riscaldamento e la seconda di raffreddamento, e confrontare il
parametro B ricavato tramite la formula:
\[B= \frac{N\sum_{i=1}^{N}{x_{i}y_{i}}-\sum_{i=1}^{N}{x_{i}}\sum_{i=1}^{N}{x_{i}}}{\Delta}\ con\ \Delta=N\sum_{i=1}^{N}{x_{1}^2}-(\sum_{i=1}^{N}{x_{i}})^{2}\]
(dove: B è il parametro della retta di regressione ddp=A+BT, N è il numero di misurazioni della temperatura T) con il valore atteso $()$.
Contemporaneamente alle misurazioni per la retta di regressione del raffreddamento si è proceduto a registrare i valori della temperatura a intervalli di tempo costanti, fatto ciò si è proceduto a stimare il parametro k della formula per il raffreddamento dell'acqua e della temperatura del giunto freddo, ripettivamente:
\[T(t)-T_{amb}=(T_{iniz}-T_{amb})e^{-kt}\ e\ T_{f}=\frac{-A}{B}\ con\ A= \frac{N\sum_{i=1}^{N}{x^2_{i}\sum_{i=1}^{N}y_{i}}-\sum_{i=1}^{N}{x_{i}}\sum_{i=1}^{N}{x_{i}y_{i}}}{\Delta}\]
dove $T_{amb}$ indica la tempeatura ambiente, N il numero di misurazioni, A e B sono i parametri della retta di regressione percedentemente descritti, $T_{iniz}$ è la temperatura iniziale, $T_{f}$ è la temperatura finale, t indica il tempo e T(t) è la temperatura al tempo t .
