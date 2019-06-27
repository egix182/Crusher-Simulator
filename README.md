# Crusher-Simulator

Il tool Crusher Simulator, in accordo alla logica del framework CRUSHER, è in grado di fornire il 
migliore algoritmo di compressione lossless possibile, dato un set di dati; infatti, tramite una 
ricerca esaustiva, è in grado di identificare delle componenti algoritmiche predeterminate 
all’interno di uno spazio di ricerca e le concatena, dando in output l'algoritmo migliore. 
Lo spazio di ricerca viene determinato a partire da algoritmi di compressioni esistenti, i quali 
vengono  rotti nelle loro parti costitutive e  generalizzate. 

Le componenti ottenute vengono implementate utilizzando un'interfaccia comune, in modo che 
ogni componente possa ricevere un blocco di dati come input, che lo trasforma in un blocco di 
output di dati. In questo modo si possono combinare le componenti in qualsiasi modo, formando 
quindi una catena, consentendo la generazione di un numero elevato di candidati all'algoritmo di 
compressione da un piccolo insieme di componenti.  

## Vedi Tesina crusher_simulator per maggiori informazioni
