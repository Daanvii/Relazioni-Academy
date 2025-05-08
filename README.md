# Relazioni-Academy

#
#
## COS'E' UN FILE SH?
L'estensione . sh vuol dire SHell ed è un file con estensione .sh. E' un file di script di shell utilizzato nei sistemi operativi Unix e Linux.

# Com'è strutturato?
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
