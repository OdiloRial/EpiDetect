<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# EpiDetect

Final project for the Building AI course

## Summary
El proyecto está baado en la creación de una aplicación de IA capaz de intuir y avisar de  posibles episodios epilépticos 


## La idea

En este momento aún son muchas las epilepsias refractarias parciales complejas que se muestran resistentes a los tratamientos con fármacos, sin que lleguen a ser controlados los episodios,  todas tienen en común que son motivados por cambios en el organismo que ocurrriendo simultaneamente y particularmente provocan la respuesta neurologica que conocemos como Ataque Epiléptico. Una IA capaz de recibir constantemente información relevante del mayor numero de pacientes posible y de gestionar con un aprendizaje automatico toda esta infromación para postriormente tratarla con una red neuronal donde se reunan las convergencias de los datos de salud recibidos con la aparición de los episodios o ataques

## Primer paso, La optención de datos fiables.

Como solucion inmediata disponemos del incrible avance del desarllo de aplicaiones en relojes intelijentes, con sus aplicaciones de salud, capaces de informarnos en tiempo real de muchos datos importantes de forma cada vez mas precisa -que aumentan dia a dia-, oxigeno en sangre, tension artrial, fiebre, horas y calidad de sueño, actividad respiratoria, temperatura corporal, son algunos ejemplos, valiosisimos datos para la investigación, Solo hay que desarollar una APP que reciba y oredene estos datos y posteriormente los envie a un servidor central donde serán evaluados y gestionados. Esta APP tambien servira para que el sujeto paciente informe de sus episodios.

Acceso a la colaboración de equipos de investigación del caso, organismos de servivios sanitarios públicos y privados con acceso a un portal web donde informar de datos medicos como por ejemplo analiticas, resultados de exploración, donde estarán refernciados todos los sujetos inscritos desde la APP principal que lo deseen.



main()
```
## Proyecto AI:  EpiDetect
## Proposito y rpopuesta de arquitectura
En primer lugar, es importante  reúnir una cantidad significativa de datos precisos y completos de pacientes con epilepsia. Se puede recopilar datos de diversas fuentes, como los relojes inteligentes y otras aplicaciones de salud, y también de los propios pacientes que informan sobre sus episodios.
Una vez que tengamos los datos, podremos utilizar técnicas de aprendizaje profundo para analizarlos y buscar patrones o características que puedan estar asociados con los episodios de epilepsia. Es importante utilizar técnicas de preprocesamiento para limpiar y normalizar los datos antes de alimentarlos a la red neuronal.
Una arquitectura de red neuronal que podría ser útil para el proyecto es la red LSTM (Long Short-Term Memory), que es capaz de aprender secuencias de datos y mantener la memoria a largo plazo. También puedemos considerar la inclusión de otras técnicas de aprendizaje profundo, como las redes convolucionales o las redes generativas adversarias.
Es importante entrenar la red neuronal con suficientes datos y una variedad de casos, incluyendo datos de pacientes con diferentes tipos de epilepsia y gravedad de los síntomas. Deberemos utilizar técnicas de validación cruzada y pruebas en conjunto para evaluar la precisión y la generalización de la red neuronal.
Por último, es importante considerar la privacidad y la ética en el uso de los datos de salud de los pacientes. Asegúrate de cumplir con las regulaciones de protección de datos y obtener el consentimiento informado de los pacientes antes de utilizar sus datos.
### Para Proyecto del curso Building AI de Odilo Rial


