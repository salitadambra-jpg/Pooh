# Pareggia sequenze

Pagina web per pareggiare il volume delle sequenze (basi) usate dal vivo, **senza compressione**.

Trascini l'export della scaletta (WAV, MP3, AIFF, FLAC): la pagina trova i brani dalle pause di silenzio, misura la loudness di ciascuno (EBU R128, LUFS) e indica di quanti dB alzarlo o abbassarlo. Le correzioni si applicano poi nella DAW, per esempio con l'automazione del volume sull'uscita stereo.

L'audio viene elaborato solo nel browser: nessun file viene caricato online.

## Uso
1. Esporta l'intera scaletta dalla DAW in un unico file.
2. Apri la pagina e trascina il file.
3. Applica le correzioni indicate per ogni brano.

## Opzioni
- **Livello di arrivo**: automatico (più alto possibile senza clip), solo abbassare, o valore fisso in LUFS.
- **Silenzio minimo** tra un brano e l'altro.
- **Inizi dei brani a mano**, se due brani non sono separati da una pausa.
