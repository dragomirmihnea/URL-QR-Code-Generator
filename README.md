# QR Code Generator)

Acesta este un mic proiect pe care l-am facut in Node.js ca sa invat cum lucrez cu pachete externe (NPM) si cum sa gestionez fisierele pe calculator.

### Ce face aplicatia:
- Te intreaba in terminal ce link vrei sa transformi.
- Iti genereaza automat o imagine .png cu codul QR.
- Salveaza link-ul tau intr-un fisier numit URL.txt ca sa ai un istoric.

### Ce am folosit:
- Inquirer: pentru intrebarile din terminal.
- qr-image: pentru generarea imaginii propriu-zise.
- fs (File System): modulul nativ din Node ca sa scriu fisierele pe disk.

### Cum il pornesti:
1. Descarci fisierele.
2. Dai un "npm install" in terminal ca sa se instaleze bibliotecile.
3. Scrii "node index.js" si urmezi instructiunile.

Am invatat aici cum sa folosesc async/await ca sa astept raspunsul de la user si cum sa fac importuri de module moderne (ESM).
