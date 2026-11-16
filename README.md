Manual Técnico: Fusión de Fibra Óptica
Estudiante: Benjamin Nicolas Alvarez Aguilera  
Carrera:Ingeniería en Telecomunicaciones  
Asignatura:Infraestructura de Redes (TCB304)  
Institución:INACAP  
Sede: La Serena  

1.Glosario técnico

Núcleo (Core):Parte central de la fibra óptica por donde se transmite la luz. Posee un índice de refracción mayor que el revestimiento.

Cladding:Revestimiento de vidrio que rodea al núcleo y permite mantener la luz confinada mediante el fenómeno de reflexión interna total.

Cleaving:Procedimiento de corte de precisión de la fibra óptica que busca obtener una superficie perpendicular para facilitar la fusión.

Atenuación: Pérdida de potencia de la señal óptica durante su transmisión. Se expresa generalmente en decibelios (dB) o decibelios por kilómetro (dB/km).


2.Materiales y herramientas

Para realizar el procedimiento de fusión de fibra óptica se utilizan los siguientes elementos:

- Fusionadora de fibra óptica.
- Cortadora de precisión (Cleaver).
- Pinza peladora de fibra óptica.
- Alcohol isopropílico.
- Paños libres de pelusa.
- Manguitos termocontraíbles.
- Cable de fibra óptica.
- Recipiente adecuado para residuos de fibra.
- Lentes de seguridad.

3.Seguridad y preparación

Antes de comenzar la práctica se deben considerar las medidas de seguridad correspondientes.

- Utilizar lentes de seguridad durante toda la manipulación.
- Evitar el contacto directo con los fragmentos de fibra.
- Mantener limpia y ordenada el área de trabajo.
- Depositar los restos de fibra en un contenedor adecuado.
- Utilizar los productos de limpieza según las indicaciones del laboratorio.

Advertencia:Los fragmentos de fibra óptica pueden ser difíciles de visualizar y deben manipularse con precaución. Nunca deben dejarse sobre la mesa de trabajo.


4.Procedimiento técnico

-Stripping (Pelado de fibra)

El stripping consiste en retirar las capas protectoras del cable de fibra óptica mediante una pinza peladora adecuada, dejando expuesto el vidrio de la fibra de 125 micras.

Este procedimiento requiere precisión para evitar daños o rayaduras en el vidrio.

Imagen de la práctica:

![Proceso de stripping](assets/img/stripping.jpg)

-Limpieza de precisión

Una vez retirada la protección, se realiza la limpieza de la fibra utilizando alcohol isopropílico de alta pureza y paños libres de pelusa.

El objetivo es eliminar partículas de suciedad y residuos que puedan afectar la calidad del empalme.

-Cleaving (Corte de precisión)

El cleaving consiste en realizar un corte preciso en el extremo de la fibra utilizando una cortadora especializada.

El objetivo es obtener una superficie de corte perpendicular, cercana a los 90 grados, para facilitar la alineación y unión de ambas fibras.

Imagen de la práctica:

![Corte de precisión](assets/img/cleaving.jpeg)

-Proceso de termofusión

La termofusión permite unir dos extremos de fibra óptica mediante una fusionadora.

El equipo realiza la alineación de las fibras y utiliza un arco eléctrico para generar la unión entre ambos extremos.

La calidad del empalme depende de la preparación, limpieza, corte y alineación de las fibras.

Imagen de la práctica:

![Proceso de termofusión](assets/img/fusionadora.jpeg)

-Protección del empalme

Después de realizar la fusión, se instala un manguito termocontraíble sobre la unión.

Este elemento proporciona protección mecánica al empalme y ayuda a mantener su integridad.

![Protección del empalme](assets/img/fusion-final.jpeg)


5.Presupuesto óptico

El presupuesto óptico consiste en analizar las pérdidas de potencia de la señal en un enlace de fibra óptica.

Las pérdidas pueden deberse a:

-Fibra óptica. En la transmisión existen pérdidas (atenuación).

-Conectores. Se producen pérdidas por el hecho de conectar unos componentes con otros.

-Empalmes. Se pueden producir pequeñas pérdidas según la calidad del empalme.

-Margen de seguridad. Permite tener en cuenta cualquier variación o pérdida adicional que pueda darse en el enlace.

En una instalación de fibra óptica es posible conocer si la potencia recibida será adecuada para el correcto funcionamiento del sistema gracias al presupuesto óptico.

Consideración de la práctica: En esta actividad hemos trabajado el proceso de fusión de fibra óptica. No se ha pedido hacer ningún tipo de cálculo de presupuesto óptico. Por ello, en este apartado se incluye información técnica sobre el concepto y sus componentes.


6.Medición y verificación

La medición y verificación nos permite analizar la calidad de nuestro empalme de fibra óptica.

Los puntos a tener en cuenta son:

-Continuidad: Se chequea que haya continuidad óptica entre ambos extremos de fibra.

-Pérdida óptica: Es la caída de potencia que sufre la luz a través del empalme.

-Calidad de fusión: Depende de la preparación y limpieza de las fibras, así como de la calidad de corte y alineación.

-Protección: Consiste en mantener la integridad mecánica de la unión (manguito termocontraíble).

La propia fusionadora puede dar una estimación de la pérdida que tiene el empalme (dependiendo de las características). Los instrumentos de medida óptica específicos nos permiten hacer mediciones del enlace completo.

Consideración de la práctica: En esta actividad hemos trabajado en la parte de fusión sin incluir ningún tipo de cálculo o medición de presupuesto óptico.

7.Presupuesto óptico

El presupuesto óptico nos permite calcular las pérdidas de potencia que sufre la luz en un enlace de fibra óptica. Las pérdidas vienen dadas en decibelios (dB). Los factores que influyen son la distancia, el número de conectores y empalmes.

Elementos que generan pérdidas

-Atenuación por kilómetro. Es la pérdida de potencia que sufre la señal mientras atraviesa la fibra óptica. Está dada en dB/km.

-Conectores. Son los puntos de conexión de los diferentes elementos de la red. Pueden generar pérdidas.

-Empalmes. Son las conexiones entre fibras ópticas. En este punto se pueden minimizar las pérdidas si se realiza la fusión adecuadamente.

-Margen GPON. Es un margen de potencia que se reserva para garantizar el correcto funcionamiento del enlace. Sirve para compensar posibles pérdidas extra.

Cálculo del presupuesto óptico

Para estimar la pérdida total tenemos que utilizar la siguiente expresión:

Pérdida total = Atenuación por km x distancia + pérdidas de conectores + pérdidas de empalmes.

Por último se compara la pérdida con el presupuesto óptico disponible. De esta forma sabremos si el enlace es posible o no.

8.Advertencias y errores comunes

En la preparación y fusión de fibra óptica es importante tener en cuenta las siguientes precauciones:

En el momento de pelar(Stripping)

⚠️ NO se debe ejercer presión sobre la pinza peladora. Se podría dañar o romper la fibra de vidrio.

-Usar la herramienta adecuada.

-Se debe evitar rayar o mellarse la fibra de 125 micras.

En el momento de limpiar

⚠️ Es importante evitar la suciedad o residuos. Puede afectar la calidad del empalme y puede incrementar la atenuación.

-Usar alcohol isopropílico de alta pureza.

-Usar paños sin pelusa.

-Evitar contacto con los dedos en la zona limpiada.

En el momento de cortar (Cleaving)

⚠️ Es importante evitar que el corte sea irregular o inclinado. Esto puede generar una fusión incorrecta.

-Usar correctamente la cortadora de precisión.

-Debería buscarse un corte perpendicular (cerca de 90°).

-La zona de corte debe mantenerse limpia.

En el momento de realizar la termofusión.

⚠️ Es importante asegurar que las fibras están bien alineadas. De otra forma pueden generarse pérdidas adicionales en el enlace.

-Verificar que los extremos estén limpios.

-Introducir correctamente las fibras en la fusionadora.

-Verificar que el proceso de alineación y fusión terminen correctamente.

-En el momento de proteger el empalme.

⚠️ Es importante asegurar que el empalme está debidamente protegido. De otra forma puede dañarse la unión.

-Ubicar correctamente el manguito termocontraíble.

-Esperar a que termine el proceso de calentamiento.

-Evitar manipulaciones hasta que esté protegido.

-Seguridad y residuos.

⚠️ Los pequeños trozos de fibra de vidrio pueden causar lesiones.

-Usar lentes de seguridad.

-No se debe contactar directamente con los residuos de fibra.

-Los trozos deben ser colocados en un recipiente de residuos de fibra óptica.

-Debe mantenerse el orden y limpieza en el lugar de trabajo.
