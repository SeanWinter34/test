		# Anomaly detection - Yolov4

## README

De demonstrator is een fysieke opstelling met een GUI en het herkennen van producten. De bedoeling van de demonstrator
is om het tellen van producten zo efficiënt mogelijk te laten zien. Voor het installeren van de backend + frontend 
van shape detection en object detection staat meer informatie bij het kopje "INSTALL". Shape detection is doormiddel
van de juiste installaties en docker klaar om te gebruiken. Het is belangrijk om te zorgen dat de demonstrator in een
ruimte staat die niet te fel belicht is, dit kan anders zorgen voor problemen met het detecteren van producten.

De fysieke opstelling bestaat uit een lopendeband met hierboven op een cabine, deze kan op de desbetreffende 'inhammen'
geplaats worden. Vervolgens is het belangrijk dat er volle batterijen in de ledlampjes zitten voor het beste licht te 
geven. De camera die schuin in de cabine geplaatst is kan met een kabel aan een computer of laptop geconnect worden.

Voor meer informatie over de demonstrator en hoe het tot stand is gekomen kan het extended abstract en de poster-
presentie geraadpleegd worden.


INSTALL
De instructies voor het installeren worden in twee verschillende onderdelen opgedeeld, OpenCV en Yolov4.

OpenCV - instructies


### Yolov4 - instructies

**Gemaakt met:**
* YOLOv4
* Python
* Javascript

### Prerequisites 

1. Er is een camera verbonden met de PC

2. Google drive

### Setup plan:

1. Plaats de aangeleverde map "images" en "YOLOv4" in google drive.

2. Navigeer naar [Google colab](https://colab.research.google.com/)

3. Navigeer naar het "Uploaden" tabblad.

4. Sleep het aangeleverde bestand "YoloV4 Screw v2.0.ipynb" in het venster.

5. Navigeer in de navigatiebalk naar Bewerken -> Notebookinstellingen

6. Selecteer GPU in hardwareversnelling.

7. Navigeer in de navigatiebalk naar Runtime -> Alles uitvoeren

8. Link de google drive door middel van de gegeven link onder het kopje "Het verbinden en kopiÃ«ren van de drive naar colab".

9. Plak de gegeven code in colab.

### Gewichten trainen

1. Voer de eerste code cel onder het kopje "AFK training script voor in de chrome console" uit.

### Prerecorded image

1. Plaats de gemaakte afbeelding in de "images" folder in google drive.

2. Plaats de naam van de geuploade image op de plek van /mydrive/images/[IMAGE NAME HERE]

3. Voer de cel uit

### Live image

1. Voer de eerste cel onder het kopje "Custom detector voor live afbeelding" uit.

2. Voer de tweede cel onder het kopje "Custom detector voor live afbeelding" uit.

3. Druk op de "capture" knop wanneer het gewenste frame in de preview zit.

### Live video

1. Voer de eerste cel onder het kopje "Custom detector voor live video" uit.

2. Voer de tweede cel onder het kopje "Custom detector voor live video" uit.






