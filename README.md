# micro-insight

Micro Insight és una eina per proporcionar informació sobre moviments i presència de persones a petita escala.

El sistema funciona gràcies al fet que les terminals mòvils amb capacitat de connexió WiFi emeten un anunci públic que conté l'adreça MAC del mòvil per trobar i activar els punts d'accés que tenen a prop.

Si disposem una sèrie d'"escoltadors" en xarxa a punts geogràficament diferents, podem escoltar aquests missatges i determinar la presència de persones a aquests punts. El problema es manifesta quan es desitja diferenciar entre punts relativament propers, ja que es poden generar ambigüitats entre dos detectors diferents. El nostre sistema permet decidir a quin punt es troba la terminal utilitzant dades relatives a la intensitat de la senyal rebuda.

