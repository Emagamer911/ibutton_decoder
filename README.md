# iButton Decoder

**iButton Decoder** è un'applicazione per leggere e decodificare i dati memorizzati su chiavi iButton Dallas DS1971.  
Permette anche la conversione inversa per generare i byte corrispondenti a un importo in euro.

## ⚠️ ATTENZIONE!
Questo programma funziona **soltanto** con gli algoritmi e sistemi **che usano il credito nei 4 byte della prima riga**.

## ✨ Funzioni principali
- Lettura e decodifica immediata del credito memorizzato
- Conversione inversa (da importo in € a bytes)
- Interfaccia semplice e intuitiva

## 📚 Guida rapida
Per decodificare il credito:
1. Leggi la memoria completa dell’iButton con un lettore supportante DS1971 o con un Flipper Zero.
2. Serviranno solo **i primi 4 byte** (formato esadecimale) della prima riga di memoria.  
   Esempio: `AA BB CC DD`
3. Inseriscili nel programma e avvia la decodifica.

Per la conversione inversa:
- Inserisci l'importo in euro e il programma mostrerà i 4 byte corrispondenti.

## 📥 Download
Scarica l'ultima versione qui:  
[ Windows (.exe)](https://github.com/Emagamer911/ibutton_decoder/releases/tag/Windows)  
[ macOS (.dmg)](https://github.com/Emagamer911/ibutton_decoder/releases/tag/macOS)

## 📄 Licenza
Questo software è rilasciato sotto **Creative Commons Attribuzione-NonCommerciale 4.0 Internazionale (CC BY-NC 4.0)**.  
Puoi copiarlo, modificarlo e condividerlo **solo per scopi non commerciali**, fornendo attribuzione all'autore.  

Consulta il file [`LICENSE`](LICENSE) per ulteriori dettagli  
oppure visita: [https://creativecommons.org/licenses/by-nc/4.0/deed.it](https://creativecommons.org/licenses/by-nc/4.0/deed.it)
