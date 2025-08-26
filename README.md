# iButton Decoder

**iButton Decoder** è un'applicazione per leggere e decodificare i dati memorizzati su chiavi iButton Dallas DS1971.  
Permette anche la conversione inversa per generare i byte corrispondenti a un importo in euro.

## [--->Sito Web<---](https://ibuttondecoder.my.canva.site/)


## ⚠️ ATTENZIONE!
Questo programma funziona **soltanto** con gli algoritmi e sistemi **che usano il credito in euro nei 4 byte della prima riga**.

## ✨ Funzioni principali
- Lettura e decodifica immediata del credito memorizzato
- Conversione inversa (da importo in € a bytes)
- Copia il risultato dal Popup!(Solo per Windows e MacOS)
- Extra: Funzionalità Extra solo sul Flipper Zero:
  - Decodifica File: Legge il file iButton (.ibtn) selezionato e decodifica il valore in euro.
  - Modifica File: Permette di scegliere un file da modificare, il credito voluto, e l'app modificherà il file con il credito in euro scelto!
- Interfaccia semplice e intuitiva

## 📚 Guida rapida
Per decodificare il credito:
1. Leggi la memoria completa dell’iButton con un lettore supportante DS1971 o con un Flipper Zero.
2. Serviranno solo **i primi 4 byte** (formato esadecimale) della prima riga di memoria.  
   Esempio: `AA BB CC DD`
3. Inseriscili nel programma e avvia la decodifica.

Per convertire un credito in byte:
- Inserisci l'importo in euro e il programma mostrerà i 4 byte corrispondenti.

## 📥 Download
Scarica l'ultima versione nella sezione Releases di questa Repository!
[Ultima RELEASE](https://github.com/Emagamer911/ibutton_decoder/releases/tag/1.0)

## 📄 Licenza
Questo software è rilasciato sotto **Creative Commons Attribuzione-NonCommerciale 4.0 Internazionale (CC BY-NC 4.0)**.  
Puoi copiarlo, modificarlo e condividerlo **solo per scopi non commerciali**, fornendo attribuzione all'autore.  

Consulta il file [`LICENSE`](LICENSE) per ulteriori dettagli  
oppure visita: [https://creativecommons.org/licenses/by-nc/4.0/deed.it](https://creativecommons.org/licenses/by-nc/4.0/deed.it)
