# job_placement

(Challenge Settembre 2021 corso IA Università degli Studi di Roma Tre)

**Contesto**
Il dataset consiste in dati di collocamento nel mondo del lavoro da parte di studenti in un campus.
Include dati sull'istruzione superiore, come specializzazione e punteggi. Include anche dati sull'esperienza lavorativa e sulle offerte attese al primo impiego.

**Obiettivo**
Tirate fuori un classificatore che, dato un candidato, preveda il piazzamento o meno. In altre parole, individuate i fattori che contribuiscono al collocamento nel mondo del lavoro.

**Dataset**
Il dataset contiene le caratteristiche (feature) di ~170 studenti. La più importante è 'status', che assume solo valori 'Placed'/'Not Placed' ossia se lo studente abbia trovato collocazione nel suo primo anno.



Produrre 2 notebook, 1 di preparazione dati ed 1 di training.

Il notebook di training, fa tutto quello che vi immaginate: apre il dato di test/train, fa l'analisi, fa la trasformazione dei dati, addestra il classificatore ed emette l'accuracy.

Il notebook di preparazione, a partire dal file di dati che vi verrà passato, crea e scrive su disco 2 file CSV con nome fisso, train.csv e test.csv, che dovranno contenere i rispettivi dati di train e test. Nel notebook di training dovrete aprire ed usare quei due file. Non c'è quindi bisogno di salvare modelli da un notebook all'altro poichè tutto avviene in quello di training. Questo notebook non fa calcoli, nè pulizia, nè altro. Fa solo split.
