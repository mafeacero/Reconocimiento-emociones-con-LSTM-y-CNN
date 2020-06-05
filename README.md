# Reconocimiento emociones con Redes Neuronales

**Integrantes**: Wendy Garcia y Maria Acero

El proyecto tendrá como objetivo la clasificación de las emociones. Este análisis se hará con la base de datos de [RAVDESS](https://zenodo.org/record/1188976#.XoEvLYhKhPa). La cual tiene dos tipos de archivos:
- Audio: Habla y canto
- Video: Habla y canto

Cada uno de estos tiene varios identificadores, los cuales son los siguientes: 

1. Modalidad (01 = full-AV, 02 = video-only, 03 = audio-only).
2. Canal de audio (01 = speech, 02 = song).
3. Emoción (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).
4. Intensidad Emocional (01 = normal, 02 = strong). NOTE: There is no strong intensity for the 'neutral' emotion.
5. Declaración (01 = "Kids are talking by the door", 02 = "Dogs are sitting by the door").
6. Repetición (01 = 1st repetition, 02 = 2nd repetition).
7. Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).

La lectura de los audios fue realizada por medio de lo que se encuentra en el documento: 
1. [Proyecto audios](https://github.com/mafeacero/Reconocimiento-emociones-con-Redes-Neuronales/blob/master/Proyecto.ipynb) 

Para esto se realizará un modelo para los videos y para los audios. Para los audios se evaluarán las siguientes posibilidades:
1. [Modelo de una red neuronal sobre los audios.](https://github.com/mafeacero/Reconocimiento-emociones-con-Redes-Neuronales/blob/master/NN_Audio_An%C3%A1lsis_de_sentimientos.ipynb) 
2. Modelo de una red neuronal sobre los espectogramas. 
3. Modelo de una ResNet sobre los espectogramas. 

