Progetto discusso al NeaPolis Innovatio 2019 
Workshop "MICROCONTROLLERS AND ARTIFICIAL INTELLIGENCE"

Il file ZIP "STM32F769I_ML_Atollic_Keras_ver0.0.5.zip" è il progetto che gira sulla STM32F769I-DISCO e può essere importato in Atollic e compilato. Il file "DISCOVERY_PRJ_Atollic_Validate.7z" è il progetto che uso per importare il modello in Keras e per generare i file di network/weights.

Dopo la generazione del codice, tutti i file sotto la directory "Middlewares\ST\AI" li copio nella corrispondente directory del progetto "STM32F769I_ML_Atollic_Keras_ver0.0.5.zip".

I passi di sviluppo quindi vanno dal progetto notebook che mi genera il modello Keras, l'import e la conversione/generazione del codice e poi la copia dei file di netork/weights nel progetto finale.

I file notebook sono all'nterno dei progetti.
