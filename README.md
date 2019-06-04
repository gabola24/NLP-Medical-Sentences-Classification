# Proyecto-U4
### Gabriel Maldonado & Catalina Zapata
El objetivo de este proyecto es lograr la clasificacion de sentencias medicas sobre enfermedades segun su contexto: causa de la enfermedad o tratamiento de una enfermedad.

*Ejemplo:*
* Sentencia sobre causa: 

*Abdominal pain related to serositis vasculitis or panniculitis may occur with SLE Physical exam Musculoskeletal exam arthritis is a feature of both SLE and WG Physical exam Peripheral vascular exam Asymmetry of pulses or the presence of vascular bruits may suggest vasculitis or large vessel arterial disease* 
* Sentencia sobre tratamiento: 

*Radiofrequency interstitial hyperthermia has been used for percutaneous ablation of hepatocellular carcinoma  under ultrasound guidance in local anesthesia* 

Las dos clases relacionan palabras de enfermedades pero en diferentes contextos, lo que permite crear herramientas que faciliten la busqueda de informacion para especialistas medicos, evaluadores de salud, investigadores entre otros..

* Se crearon 4 versiones del proyecto en donde se desarrollaron diferentes experimentaciones:
     * Datos Proyecto U4= Notebook con la descarga de los datos utilizados y con un primer analisis exploratorio y experimental de los datos.
     * Proyecto U4 - V2 = Se aborda el problema de clasificacion partiendo del preprocesamiento de los datos  y experimentando              con diversas variaciones de parametros con el fin de encontrar los que optimizaran el aprendizaje
     * Proyecto U4 - V3 = Se experimenta ahora con una variacion en el tokenizador disminuyendo el numero de palabras usadas en este, ademas se introduce el uso de la regularizacion l2 que mejora el desempeño del entrenamiento
     * Proyecto U4 - V4 = Con los hiperparametros seleccionados se implementa un analisis por medio de Glove, donde analiza la correlacion de las palabras y se transfieren los pesos al mejor modelo encontrado con el fin de mejorar los resultados. Se reportan los resultados de precision, recall y f1 score por clase para todas las experimentaciones.
     
 
