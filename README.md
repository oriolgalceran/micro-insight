# micro-insight

Micro Insight és una eina per proporcionar informació sobre moviments i presència de persones a petita escala.

El sistema funciona gràcies al fet que les terminals mòvils amb capacitat de connexió WiFi emeten un anunci públic que conté l'adreça MAC del mòvil per trobar i activar els punts d'accés que tenen a prop.

Si disposem una sèrie d'"escoltadors" en xarxa a punts geogràficament diferents, podem escoltar aquests missatges i determinar la presència de persones a aquests punts. El problema es manifesta quan es desitja diferenciar entre punts relativament propers, ja que es poden generar ambigüitats entre dos detectors diferents. El nostre sistema permet decidir a quin punt es troba la terminal utilitzant dades relatives a la intensitat de la senyal rebuda.

El sistema és simple en funcionament i en construcció, i disposa de dos mòduls WiFi, un per dur a terme la detecció i un per connectar-se a Internet i distribuïr les dades obtingudes. Això permet eliminar la necessitat de connectar un cable de dades a la instal·lació, i només cal proporcionar alimentació, ja sigui mitjançant un cable o una bateria de llarga durada.

La instal·lació està continguda dins d'una caixa IP68 per poder-se instal·lar sense problemes a exteriors.

Al contrari que altres mètodes, com l’anàlisi d’imatges de càmeres de seguretat o altres mètodes més invasius, aquest sistema permet fer anàlisis de qualitat sense arriscar-se a qüestions de privacitat o de protecció de dades, ja que la informació obtinguda no permet identificar a l’usuari. A més, aquest sistema és immune a la foscor o a fenòmens meteorològics adversos que puguin limitar la visió del sistema.
