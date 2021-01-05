## 0.Introducció

El següent projecte s'inclou dins l'assignatura 'Tipologia i cicle de vida de les dades' del programa del màster Ciència de Dades de la UOC.  

Integrants del projecte:
- Ana Marrodan Badell
- Mireia Solanich Ventura

## ON TROBAR:
 * El fitxer CSV amb les dades originals --> a la carpeta **data**
 * El fitxer CSV amb les dades finals analitzades. --> a la carpeta **data** (sufix CLEAN)
 * Una carpeta amb el codi generat per analitzar les dades.  --> a la carpeta **code**, format Rmd

## TAULA DE CONTRIBUCIONS

(s'ha hagut d'afegir al readme i a la versió Rmd del document, doncs la versió pdf presentabla problemes al renderitzar la taula)

| Contribució |Firma|
| ------------- |:-------------:| 
|Investigació prèvia|AM i MS|
|Redacció de les respostes|AM i MS|
|Desenvolupament codi|AM i MS|

## 1. Descripció del dataset. Perquè és important i quina pregunta/problema pretén respondre?

l'objecte del següent projecte cosisteix en predir quines de les següents bombes d'aigua són o no defectuoses.

A partir de les dades facilitades per Taarifa i el Ministeri d'Aigua de Tanzània, caldrà predir quines bombes són funcionals, quines necessiten algunes reparacions i quines no funcionen en absolut. Per a fer la classificació del funcionament dels pous caldrà fer-ne l'analisis a partir de les variables facilitades sobre quin tipus de bomba, quan es van instal·lar i com es gestiona.

El següent estudi permetrà coneixer i predir quins punts d'aigua fracassaran i permetrà millorar les operacions de manteniment i assegurar que l'aigua potable i neta estigui disponible per a les comunitats de Tanzània.


El projecte descrit forma part de la competició activa a a la plataforma "DrivenData.org" (DrivenData.org)

Per a realitzar els següent estudi es faciliten 4 fitxers 'csv':
- Submission format: El format per enviar les vostres prediccions
- Test set values: Les variables independents que necessiten prediccions
- Training set labels: La variable dependent (status_group) de cadascuna de les files dels valors del conjunt d'entrenament
- Training set values: Les variables independents del conjunt d'entrenament

Descripció dels camps:

Fitxers 'SubmissionFormat.csv' i 'training_set_lablels.csv' contenten els següents camps:
- **id**: Codi identificador de cada pou
- **status_group**: Estat del funcionament de cada pou

Fitxers 'test_set_values.csv' i 'training_set_lablels.csv' contenten els següents camps:
- **id**: Codi identificador de cada pou
- **amount_tsh**: Quantitat d'aigua disponible a cada pou (Total static head)
- **date_recorded**: Data en que s'ha creat el registre
- **funder**: Qui a financiat el pou
- **gps_height**:  altitud del pou GPS
- **installer**: Organitzacio que va instal·lar el pou
- **longitude**: Coordenada longitud GPS
- **latitude**: Coordenada latitud GPS
- **wpt_name**: Nom del punt d'aigua (si n'hi ha)
- **num_private**: Conca hidrogràfica
- **basin**: Localització conca hidrogràfica
- **subvillage**: Localització geogràfica
- **region**: Ubicació geogràfica de la regió
- **region_code**: Codi ubicació geogràfica de la regió
- **district_code**: Codi ubicació geogràfica del districte
- **lga**: Localització geogràfica
- **ward**: Localització geogràfica
- **population**: Població al voltant del pou
- **public_meeting**: cert / fals
- **recorded_by**: Grup que introdueix aquesta fila de dades
- **scheme_management**: Qui opera el punt d’aigua
- **scheme_name**: Qui opera el punt d’aigua
- **permit**: Si es permet el punt d'aigua
- **construction_year**: Any en què es va construir el punt d'aigua
- **extraction_type**: Tipus d’extracció que fa servir el punt d’aigua
- **extraction_type_group**: Tipus d’extracció que fa servir el punt d’aigua
- **extraction_type_class**: Tipus d’extracció que fa servir el punt d’aigua
- **management**: Com es gestiona el punt d’aigua
- **management_group**: Com es gestiona el punt d’aigua
- **payment**: Què costa l'aigua
- **payment_type**: El que costa l'aigua
- **water_quality**: Qualitat de l'aigua
- **quality_group**: Qualitat de l'aigua
- **quantity**: Quantitat d'aigua
- **quantity_group**: Quantitat d'aigua
- **source**: Font de l'aigua
- **source_type**: Font de l'aigua
- **source_class**: Font de l'aigua
- **waterpoint_type**: Tipus de punt d’aigua
- **waterpoint_type_group**: Tipus de punt d’aigua


