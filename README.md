# Relazioni-Academy

#
#
# COS'E' UN FILE SH?
I file con estensione .sh sono una componente fondamentale dell'ambiente Unix e Linux, utilizzati per scrivere script di shell. Questi script consentono agli utenti di automatizzare una serie di comandi e operazioni, rendendo più efficienti le attività quotidiane e semplificando la gestione del sistema. 
invece di digitare ogni comando manualmente, si può racchiudere tutto in un file .sh e farlo eseguire in un colpo solo.

### Com'è strutturato?
Un file .sh inizia tipicamente con una "shebang" che indica quale interprete utilizzare per eseguire lo script. Ad esempio:
#
              !/bin/bash
Dopo la shebang, puoi inserire i comandi che desideri eseguire:
#
              echo "Ciao, mondo!"
# 
Per eseguire un file .sh, dobbiamo assicurarci che sia eseguibile e possiamo farlo con il comando chmod
#
              chmod +x script.sh
#
Si possono utilizzare variabili all'interno di uno script .sh. Ad esempio:
#
              #!/bin/bash
              nome="Mario"
              echo "Ciao, $nome!"
#
Si possono aggiungere commenti nello script utilizzando il simbolo #. I commenti non vengono eseguiti e servono per documentare il codice:
#
              # Questo è un commento
              echo "Questo verrà eseguito"
#
I file .sh possono essere utilizzati per una vasta gamma di applicazioni, dalla gestione di file e directory all'automazione di processi complessi.
