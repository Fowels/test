# FowelsTrackers

> Full Body Tracking (aka FBT) basados en SlimeVR que permiten transmitir en tiempo real los movimientos de distintas partes de tu cuerpo a tu avatar en la Realidad Virtual.

Este GitHub estará dedicado específicamente a dar información relacionada a los trackers hechos por mi, dando también links de utilidad y Preguntas Frecuentes.

Índice
- [¿Cómo funcionan?](https://github.com/Fowels/FowelsTrackers/tree/main#c%C3%B3mo-funcionan)
- [Información Técnica](https://github.com/Fowels/FowelsTrackers/tree/main#informaci%C3%B3n-t%C3%A9cnica)
- [Drift](https://github.com/Fowels/FowelsTrackers/tree/main#drift)
- [Kits](https://github.com/Fowels/FowelsTrackers/tree/main#kits)
- [Waist Upgrade](https://github.com/Fowels/FowelsTrackers/tree/main#waist-upgrade)
- [Pedidos personalizados](https://github.com/Fowels/FowelsTrackers/tree/main#pedidos-personalizados)
- [Preguntas Frecuentes](https://github.com/Fowels/FowelsTrackers/tree/main#preguntas-frecuentes)
- [Contacto](https://github.com/Fowels/FowelsTrackers/tree/main#contacto)

## ¿Cómo funcionan?

Los trackers están basados en SlimeVR, por lo que significa el no uso de LightHouses ni cámaras para su funcionamiento (no tienen Oclusión). Lo único que requieren para funcionar es el SlimeVR Server, SteamVR (aunque ahora también se puede usar en Quest Nativo vía **VRChat OSC**) y una conexión a ***WiFi 2.4GHz*** **(NO FUNCIONA CON 5GHZ)**.

Los trackers se conectan por medio de una Red WiFi 2.4GHz a tu PC/Quest, dónde deberán enlazarse con el **SlimeVR Server**. Aquí debes ajustar las proporciones de tu cuerpo y la ubicación de los trackers.

El SlimeVR Server es el encargado de convertir el posicionamiento de tus trackers en unos "HTC Vive Trackers" virtuales (por medio de un esqueleto virtual creado a partir de las proporciones ingresadas y los valores de tus trackers), los cuales aparecerán en tu **SteamVR/VRChat Quest** donde podrás ocuparlos para las aplicaciones que estimes conveniente.


## Información Técnica

Fowels Trackers está basado en los diseños de SlimeVR Trackers, pero estos poseen modificaciones en distintas etapas del proceso de manufactura para poder mejorar su uso y facilitar su producción localmente. Todo diseño de carcasas, PCB's, selección de chips o componentes han sido hechas y/o seleccionadas por mi para poder otorgar la mejor calidad dentro de las pciones disponibles en el mercado, tratando de mantener los costos al mínimo para así no incrementar el precio final de los sets.

**Especificaciones Técnicas:**
>- PCB Custom
>- Sensor: IMU BMI160
>- Tiempo de Drift: 5 a 15 minutos
>- Microcontrolador: Wemos D1 Mini (Micro USB)
>- Batería: 18650 Li-Ion 3.7V
>- Tiempo de Uso: Aproximádamente 5 a 6 horas de duración*
>- Tiempo de Carga: Aproximádamente 2 horas
>- Carcasa: Impresión 3D en PLA+ Negro (cuerpo) y PLA Semi-Transparente (tapa)

*Existe la opción de comprar mejores baterías que duran hasta 25 horas y está la opción de compra al momento de encargar tu Kit de Trackers.
Cabe destacar que la batería es fácilmente removible y reemplazable.

Cada Kit de Trackers incluirá:

> - Trackers.
> - Straps (Correas) personalizadas a tu medida.
> - Cables de carga 4 USB-C a 1 USB-A.
> - Bolsa con:
>   - Tarjeta de agradecimiento
>   - Stickers para nombrar los Trackers
>   - Stickers con el logo de Fowels Trackers
>   - Llavero de Chip (si es que hay disponibilidad)

## Drift

**¿Qué es el tiempo de Drift?**

Todo chip **IMU** (al ser chips sin referencia espacial -de ahí el no uso de cámaras o Base Stations-) con el paso del tiempo ***tienden a perder su orientación***, rotando en sus propios ejes. Esto es algo que no puede ser prevenido de ninguna manera, pero hay maneras de palear esto (de ahí el Reinicio Rapido en el SlimeVR Server) para que vuelvan a su orientación original.

Los chips **BMI160** tienen un tiempo de Drift aproximado de **5 a 15 minutos** (que puede variar a 20-30 minutos en el mejor de los casos). 

Estos Drift Times dependen netamente de cada chip y de la cantidad de movimiento (o estrés) al que estén sometidos. Mientras más se muevan más rápido perderán su orientación.

## Kits

Actualmente hay 3 diferentes Kits de Trackers disponibles: Básico, Medio y Avanzado. Estos kits están pensados de tal manera de tener una base mínima para poder trackear tu cuerpo, y a medida que avanazas agregar partes de éste.

> **჻Kit FT Básico (6 Trackers): *($215.000 CLP)***
> *Pecho, Cadera, Pierna x2, Tobillo x2*
> 
> Este kit es la mínima cantidad de trackers que requieres para poder tener Full Body Tracking. Te permitirá tener movimiento de pelvis, rodillas y tobillos (no tendrás rotación de pies).
> 
> Se recomienda este kit si es que no buscas nada del otro mundo más allá de tener Full Body Tracking y pasar un buen rato.

> **჻Kit FT Medio (8 Trackers): *($255.000 CLP)***
> *Pecho, Cadera, Pierna x2, Tobillo x2, Pie x2*
> 
> Este kit es básicamente lo mismo que el Kit FT Básico pero con la adición de dos trackers, uno en cada pie, para poder tener rotación y movimiento de ellos.
> 
> Se recomienda este kit a personas que quieren dar un pasó más allá y tener un Full Body Tracking más natural.

> **჻Kit FT Avanzado (10 Trackers): *($325.000 CLP)***
> *Pecho, Cadera, Pierna x2, Tobillo x2, Pie x2, Antebrazo x2*
> 
> Este kit es lo mismo que el Kit FT Medio pero con la adición de dos trackers, uno en cada brazo, para poder tener rotación de codos. De esta forma tendrías el tracking más completo.
> 
> Se recomienda este kit si es que quieres tener un tracking más fidedigno a la vida real.

Recordar que cada Kit de Trackers incluye straps (correas), cables de carga, stickers para nombrar los Trackers ¡y más!, cómo está estipulado en [Información Técnica](https://github.com/Fowels/FowelsTrackers/tree/main#informaci%C3%B3n-t%C3%A9cnica)

## Waist Upgrade

A pesar de los [Kits](https://github.com/Fowels/FowelsTrackers/tree/main#kits), vendo un ***[Waist Upgrade](https://github.com/Fowels/FowelsTrackers/tree/main#waist-upgrade) ($35.000 CLP)***, el cuál da un movimiento de pelvis aún más realista además de darle más estabilidad al pecho al agregar un tracker más a tu **Cintura**.

Es recomendado para aquellas personas ***que desean bailar*** frecuentemente o son más exigentes.

Este [Waist Upgrade](https://github.com/Fowels/FowelsTrackers/tree/main#waist-upgrade) no viene incluido en los kits para hacer los precios más atractivos y al no ser determinante al momento de tener o no Full Body Tracking, pero ***personalmente*** lo recomiendo.

## Pedidos Personalizados

Si tienes algun proyecto en mente, [contactar a Forels](https://github.com/Fowels/FowelsTrackers/tree/main#contacto).

Si deseas comprar uno o más trackers por separado el valor es de $50.000 CLP cada uno.

## Preguntas Frecuentes

**჻¿Por qué se necesitan tantos trackers si con los HTC Vives solo se necesitan 3 para el Full Body Tracking tradicional?**

Los trackers basados en SlimeVR funcionan de manera distinta a los HTC Vive Trackers, por lo que para poder emularlos (lo que SlimeVR Trackers hacen) requieren de más puntos de información de lo que se requieren normalmente con los HTC Vive Trackers.

**჻¿Se pueden usar con el Oculus Quest 2?**

Si, pueden ser usados con los Oculus Quest 2 tanto en modo PC VR (Conectados al PC por medio de SteamVR) como VRChat Quest Nativo (vía VRChat OSC)

**჻¿Estos trackers requieren Base Stations, Light Houses o cámaras para funcionar?**

No, no requieren de Base Stations, Light Houses o cámaras para funcionar. Su funcionamiento solo requiere de una buena y estable conexión WiFi 2.4GHz, el SlimeVR Server y de SteamVR/Quest Nativo.

**჻Si es que no tengo buen internet, ¿Los Trackers funcionarán?**

El mayor requisito de los trackers es tener buena señal Wifi 2.4GHz, de modo que si tu internet a pesar de ser de pocos megabytes es estable y llega la señal apropiadamente a tu Área de Juego no deberías tener problemas.

**჻¿Por qué requeriría del Tracker Upgrade si con tan solo un tracker en mi cadera/cintura funciona bien?**

Se recomienda hacer el Tracker Upgrade para así tener un tracking más realista y certero, sobretodo para bailar.

Debido a que los sets de Fowels Trackings están diseñados para ser más atractivos y dar la posibilidad de tracking éste tracker no fue incluido. Pero a pesar de esto, si deseas el tracking más realista posible este Upgrade es totalmente recomendado.

## Contacto
- Discord: Forels#0001
- https://discord.gg/AmvufYe76D
