# Sistema de recomendación musical eHealth para mejorar la cognición y la motricidad en pacientes con Parkinson.

Código asociado al Trabajo Fin de Máster de Adrià Cortés Andrés para el Máster de Ciencia de Datos de la Universitat Oberta de Catalunya (UOC).

## Descripción del trabajo
Este TFM busca implementar un sistema de recomendación musical que pueda ser utilizado por pacientes de Parkinson. Con este objetivo se abordan diferentes algoritmos como los de filtrado colaborativo, basados en contenido y de aprendizaje profundo. 

Estas aproximaciones incluyen:
- enfoque simple **basado en la popularidad** de las canciones (modelo baseline)
- **filtrado colaborativo**
- **filtrado colaborativo neuronal**, basado en el aprendizaje profundo
- **filtrado basado en contenido con autoencoder** (tanto con cómo sin considerar los estados de ánimo)
- **filtrado basado en contenido utilizando TF-IDF** (Term Frequency Inverse Document Frequency)
- un recomendador que utiliza **Transformers**

## Librerías necesarias
Las librerías necesarias para ejecutar los archivos se detallan al inicio de cada notebook.

## Detalle de los notebooks
A continuación se incluye una breve descripción de los notebooks del repositorio:

*  _data_preprocessing_adding_extra_features_: preprocesamiento de datos e incorporación de características musicales y de metadato a las canciones.
*  _music_mood_classification_plus_features_: incorporación del estado anímico a las canciones del conjunto de datos.
*  _EDA_: análisis exploratorio de datos (EDA, gráficos y exploración del conjunto de datos.
*  _Baseline model_: implementación modelo baseline basado en la popularidad de las canciones.
*  _Collaborative Filtering_: implementación modelo de filtrado colaborativo.
*  _Neural Collaborative Filtering_: implementación modelo de filtrado colaborativo basado en redes profundas.
*  _Autoencoder Content Based_: implementación de un sistema de content-based con autoencoders.
*  _Autoencoder Content Based WHITOUT Mood_: implementación de un sistema de content-based con autoencoders, sin tener en consideración el estado anímico.
*  _Content Based using TF-IDF_: implementación de un sistema content-based mediante TF-IDF (Term Frequency-Inverse Document Frequency).
*  _Recommender_BERT4Rec_(transformers)_: implementación de un modelo basado en Transformers, específicamente en BERT4Rec.
