[https\://github.com/lucasjoberg/Tricell-Encryption-Algorithm-2.0/tree/main](https://github.com/lucasjoberg/Tricell-Encryption-Algorithm-2.0/tree/main)

README.md

\# Tricell Encryption Algorithm 2.0

Välkommen till repositoryt för \*\*Tricell Encryption Algorithm 2.0\*\*.

\#\# Om projektet  
Detta projekt innehåller en krypteringsalgoritm baserad på ett nummerbaserat substitutionschiffer kombinerat med ett ojämnt salt (7 siffror i början och 8 siffror i slutet). Målet har varit att skapa hög säkerhet mot obehöriga samtidig som behöriga mottagare enkelt kan dekryptera meddelandet med hjälp av våra instruktioner.

\#\# Repositoryns innehåll  
I detta repository hittar du följande filer:  
\* \`README.md\` – Denna översiktsfil.  
\* \`flodesschema.mmd\` – Källkoden för algoritmens flödesschema i Mermaid-format.  
\* \`alfabetsnyckel.txt\` – Den genererade nyckeltabellen för A–Z.

\#\# Projektmedlemmar  
\* McLovin  
\* Flambae  
\* Lucifer

flodesschema.mmd

graph TD  
    A\[Krypterad siffersträng\] \--\> B\[Ta bort salt\]  
    B \--\> C\[Dela upp i sifferpar\]  
    C \--\> D\[Översätt med infogat alfabet \]  
    D \--\> E\[Lägg till mellanslag i meddelande t\]

alfabetsnyckel.txt

ALFABETSNYCKEL

A \= 73  
B \= 15  
C \= 94  
D \= 38  
E \= 62  
F \= 29  
G \= 81  
H \= 46  
I \= 10  
J \= 53  
K \= 88  
L \= 24  
M \= 67  
N \= 31  
O \= 90  
P \= 55  
Q \= 18  
R \= 76  
S \= 42  
T \= 89  
U \= 21  
V \= 64  
W \= 97  
X \= 35  
Y \= 50  
Z \= 83  
