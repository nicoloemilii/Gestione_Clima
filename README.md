# 🌡️ Controllo di Temperatura e Umidità via App con DHT11 e HC-06

## 🧠 Descrizione del progetto
Questo progetto permette di:
- Misurare temperatura e umidità ambientale tramite sensore **DHT11**
- Trasmettere i dati a una **app Android via Bluetooth** usando il modulo **HC-06**
- **Accendere o spegnere** un termosifone e un deumidificatore simulati tramite LED, sia da app che dal monitor seriale

L'app è stata realizzata tramite **MIT App Inventor**, mentre lo schema elettrico è stato disegnato con **Proteus 8 Professional**.

## 🧩 Componenti utilizzati
- Arduino UNO  
- Modulo Bluetooth HC-06  
- Sensore temperatura/umidità DHT11  
- Breadboard  
- 2 LED  
- 2 resistori da 220Ω  

## 🖥️ Funzionamento
- Il **DHT11** misura temperatura e umidità.
- Arduino riceve i dati e li invia via Bluetooth all'app e al monitor seriale.
- Dalla **app Android**, realizzata con blocchi grafici, è possibile:
  - Leggere i valori misurati
  - Inviare comandi per simulare l'accensione/spegnimento di dispositivi tramite LED

## 📲 Applicazione
- Realizzata con MIT App Inventor  
- Comunicazione tramite Bluetooth (HC-06)  
- Controllo diretto dei LED (termosifone e deumidificatore)

## ⚙️ Connessioni principali
- **DHT11** → pin 8 di Arduino  
- **HC-06** → comunicazione seriale  
- **LED** → simulano attuatori accesi/spenti  

## 👨‍💻 Autore

Nicolò Emilii

---

