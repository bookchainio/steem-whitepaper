# Steem

## Una plataforma de contenido público, basada en blockchain, con incentivos.

Agosto de 2017

# Notas del traductor

Versión actual traducida, actualizada, revisada y aprobada por @nehomar. Versión anterior traducida por @fernando-sanz. Agradecimientos a @testz por subirlo a Crowdin. Todas las fuentes al final del documento están en inglés.

# Abstract

Steem es una base de datos blockchain que permite la contrucción comunitaria e interacción social con premios en criptomoneda. Steem combina conceptos de *social media* con los aprendizajes provenientes de la construcción de criptomonedas y sus comunidades. Una clave importante para inspirar participación de cualquier comunidad, moneda o economía de libre mercado es un sistema de contabilidad justa que refleje consistentemente la contribución de cada persona. Steem es la primer criptomoneda que intenta recompenzar de forma acertada y transparente una cantidad indeterminada de individuos que realizan *contribuciones subjetivas* a su comunidad.

# Tabla de contenidos

<!-- toc -->

# Introducción

El contenido generado colectivamente por usuarios ha creado billones de dólares en valor para los accionista de compañias de *social media* como Reddit, Facebook y Twitter. **En 2014, Reddit hipotetizó que su plataforma podría ser mejorada si todos los que contribuyen en reddit.com posteando historias, agregando comentarios o votando fuesen premiados con una cantidad justa de participación en Reddit, Inc[^1]**. Steem apunta a apoyar comunidades online y de *social media* devolviendo gran parte de su valor a la gente que provee valiosas contribuciones, premiándolos con criptomoneda, y a través de este proceso crear una moneda que puede alcanzar un mercado masivo, incluyendo gente que aún no ha participado en alguna economía de criptomoneda.

Hay algunos principios clave que han sido utilizados para guiar el diseño de Steem. El más importante es que todos los que contribuyen a una empresa deben recibir una participación prorrateada, pago o débito de la empresa. Este principio es el mismo que se aplica en casi todas las *Startups*, estas colocan acciones durante la fundación y durante rondas de inversión subsecuentes.

El segundo principio es que todas las formas de capital son igualmente valiosas. Esto significa que aquellos que contribuyen su escaso tiempo y atención en producir y curar contenido para otros, son tan valiosos como quienes contribuyen con su capital. Este es el principio de equidad de sudor[^2] y es un concepto que previo a las criptomonedas ha tenido problemas para proveer a no más de algunas docenas de individuos.

El tercer principio es que la comunidad produce productos para servir a sus miembors. Esto se ejemplifica con las uniones de crédito, coperativas de alimentos, planes de salud compartidos, que sirven a los miembros de sus comunidades mas que vender productos o servicios a la gente fuera de la comunidad.

La comunidad de Steem provee los siguientes servicios a sus miembros:

1. Una fuente de noticias y comentarios curada.
2. Medios para obtener respuestas de alta calidad a preguntas personalizadas.
3. Una criptomoneda estable vinculada al Dólar Estadounidense.
4. Pagos libres.
5. Trabajos que proveen los servicios antes mencionados a otros miembros.

El útil realineamiento de incentivos económicos de Steem tiene el potencial de producir resultados justos y mas inclusivos para todos los involucrados que las plataformas de *social media* y criptomonedas que la preceden. Este documento explorará los incentivos económicos existentes y demostrará cómo Steem y sus incentivos podrán resultar mejor para la mayoría de los participantes.

## Reconociendo las contribuciones

Steem está diseñado desde cero para resolver las mayores barreras para su adopción y monetizaciones de una economías basada en *social media*. Nuestra tésis es que las mismas técnicas usadas para hacer crecer las mas grandes plataformas de *social media* pueden ser utilizadas para iniciar una criptomoneda existosa. Incentivos económicos habilitados por criptomoneda pueden facilitar dramáticamente el crecimientod de una nueva plataforma de *social media*. Es la sinergía entre criptomoneda y *social media* lo que creemos que puede dar a Steem una poderosa ventaja en el mercado.

El reto afrontado por Steem es derivar un algoritmo para tasar contribuciones individuales que la mayor parte de los miembros de la comunidad consideren una evaluación justa del valor subjetivo de cada contribución. En un mundo perfecto, los miembros de la comunidad coperarían para valuar la contribución de cada par y devolver una justa compensación. En el mundo real, deben diseñarse algoritmos de tal forma que sean resistentes a manipulación intencional con fines de lucro. Cualquier abuso del sistema de tasación podría causar la pérdida de fe en la percepción de justicia del sistema económico por parte de sus miembros.

Las plataformas existentes operan en un principio de un usuario, un voto. Esto crea un ambiente donde los rankings pueden ser manipulados por ataques de profeta y los proveedores de servicio deben proactivamente identificar y bloquar abusadores. La gente actualmente intenta manipular los sistemas de tasacipon de Reddit, Twitter y Facebook siendo la única ganancia el tráfico web o la censura.

La unidad fundamental de contabilidad en la plataforma de Steem es STEEM, un token de criptomoneda. Steem opera sobre la base de un-Steem, un-Voto. Bajo este modelo, los individuos que más han contribuido a la plataforma, medidos por el saldo de su cuenta, tienen la mayor influencia sobre la forma en que se califican las contribuciones. Además, Steem solo permite a los miembros votar con STEEM cuando este es sujeto a un esquema de adjudicación. Bajo este modelo, los miembros tienen un incentivo financiero para votar de una manera que maximiza el valor a largo plazo de su STEEM.

Steem está diseñado alrededor de un concepto relativamente simple: *toda contribución significativa a la comunidad debería ser reconocida por el valor que añade.* Cuando la gente es reconocida por sus contribuciones, continúan contribuyendo y la comunidad crece. Cualquier desequilibrio en el dar y recibir dentro de una comunidad es insostenible. Eventualmente los dadores se cansan de soportar a los miembros que restan y atentan contra la comunidad.

El reto es crear un sistema capaz de identificar qué contribuciones son necesarias y su valor relativo de manera que pueda escalar a un numero indeterminado de gente.

Un sistema comprobado para evaluar y premiar contribuciones es el libre mercado. El libre mercado puede ser visto como una comunidad única donde todos intercambian con otros y las recompenzas son asignadas por pérdidas y ganancias. El sistema de mercado premia aquellos que proveen valor a otros y castiga a quienes consumen más valor del que producen. El mercado libre soporta muchas monedas diferentes y el dinero es simplemente una *commodity* que todos encuentran fácil de intercambiar.

Desde que el libre mercado es un sistema comprobado, es tentador intentar crear un sistema de igual característica donde los consumidores de contenido pagan directamente a los productores del mismo. De todas formas, el pago directo es ineficiente y realmente inviable para la creación y curado de contenido. El valor de la mayoría del contenido es muy bajo en relación con el costo cognitivo, financiero y de oportunidad asociado con hacer un pago que algunos pocos lectores eligen beneficiar. La abundancia de alternativas libres significa que la aplicación de un *muro de pago* derivará a los lectores a otro lado. Han habido gran cantidad de intentos de implementar micro pagos por artículo de parte de los lectores hacia los autores, pero ninguno se ha alcanzado una amplitud considerable.

Steem está diseñado para permitir micropagos efectivos por cualquier tipo de contribución al cambiar la ecuación económica. Los lectores ya no tienen que decidir si pagar o no a alguien desde su propio bolsillo, en cambio votan o restan votos y Steem usa estos votos para determinar premios individuales. Esto significa que se le otorga a la gente una interfaz familiar y ampliamente utilizada y ya no enfrentan los costos de oportunidad, cognitivos y financieros asociados tradicionalmente a los micropagos y plataformas de propinas.

El voto de los miembros de la comunidad es crítico para que Steem acomode los pagos a los contribuyentes de forma precisa. El voto puede por lo tanto ser visto como una contribución crucial y digno de ser recompenzado en sí mismo. Algunas plataformas, como Slashdot, usan meta-moderación [^3] como una forma de rankear y premiar a los moderadores honestos. Steem entonces premia a quienes mas contribuyen al total de la promoción de una pieza de contenido pagando a los votantes proporcionalmente al pago principal del creador del contenido votado.

# Formas de contribuír

Esta sección delínea las ideas detrás de Steem y sus recompenzas para la gente que provee contribuciones significativas y mesurables a la comunidad de Steem.

## Contribuciones de capital

Hay dos items que una comunidad puede ofrecer para atraer capital: deuda y propiedad. Quienes compran propiedad ganan cuando la comunidad crece pero pierden si la misma decrece. Quienes compran deuda obtienen la garantia de un cierto monto de interpes pero no llegan a participar de las ganancias realizadas por el crecimiento de la comunidad. Ambos tipos de contribuciones de capital son valiosas para el crecimiento de la comunidad y la valuación de su moneda. Adicionalmente hay dos formas en que la propiedad puede conservarse: liquidez y colocación. La colocación de propiedad genera un compromiso de largo plazo y no puede ser vendida por un determinado período de tiempo.

La red Steem denomina a estas diferentes clases de *assets* Steem (STEEM), Steem Power (SP), y Steem Dollars (SBD).

## Steem (STEEM)

Steem es la unidad fundamental contable en el blockchain de Steem. Los demás tokes derivan su valor del de STEEM. STEEM es una moneda líquida y por lo tanto puede ser comprado o vendido en los mercados, así como transferido a otros usuarios como forma de pago.

## Steem Power (SP)

Las Startups o los emprendimientos requieren un compromiso de capital a largo plazo. Aquellos que invierten su dinero en estas companías calculan esperar años antes de poder vender sus acciones y efectivizar su ganancia. Sin compromiso a largo plazo, una *startup* buscando recolectar capital adicionar a través de la venta de acciones adicionales estaría compitiendo con accionistas existentes queriendo retirarse. Los inversores compresivos quieren que sus contribuciones de capital hagan crecer la compañía, pero el crecimiento no puede suceder si el nuevo capital es entregado a los que buscan retirarse.

Hay un valor significativo en tener compromiso a largo plazo porque habilita a las comunidades a hacer planes a largo plazo. El compromiso a largo plazo de los *stakeholders* también causa que estos voten por el crecimiento a largo plazo en lugar de bombeos de corto plazo.

En el espacio de las criptomonedas, los especuladores saltan de criptomoneda en criptomoneda basados mayormente en las expectativas de crecimiento a corto plazo. Steem busca armar una comunidad que sea propiedad y controlada enteramente por aquellos con perspectivas a largo plazo.

Users are able to commit their STEEM to a thirteen week vesting schedule, providing them with additional benefits within the platform. STEEM that has been committed to a thirteen week vesting schedule is called Steem Power (SP). El balance de SP es intransferible y no-divisible excepto a través de las solicitudes de conversión automáticamente recurrentes. Esto significa que SP no puede negociarse fácilmente en bolsas de criptomonedas.

Cuando los usuarios votan el contenido, su influencia sobre la distribución de *pool* de premios es directamente proporcional a la cantidad de SP que tienen. Los usuarios con más SP tienen más influencia en la distribución de recompensas. Esto significa que SP es un token de acceso que otorga a sus poseedores poderes exclusivos dentro de la plataforma de Steem.

Los poseedores de SP también cobran intereses en el equilibrio del SP que permanece concedido. 15% de la inflación anual es pagada a los poseedores de SP como interés. El importe de los intereses que reciben es directamente proporcional a la cantidad de SP que poseen en relación con la cantidad total de SP adquirido a través de todos los usuarios.

Transferir STEEM a SP se conoce como "power up", mientras que la transferencia de SP a STEEM se conoce como "power down". El SP producto del *power down* se devuelve al usuario durante un período de trece semanas, vía 13 pagos semanales iguales, a partir de una semana después de iniciado el *power down*.

## Steem Dollars (SBD)

La estabilidad es un componente importante en las economías globales exitosas. Sin estabilidad, los individuos en distintas partes del mundo no podrían tener costos cognitivos bajos al participar en el comercio y ahorro. Por este motivo, los *Steem Dollars* fueron diseñados como un intento de traer estabilidad al mundo de las criptomonedas y a los individuos que usen la red Steem.

Los Steem Dollars (SMD) son creados por un mecanismo similar a las notas convertibles, que son usualmente utilizadas para financias *startups*. En el mundo de las *startups*, las notas convertibles son instrumentos de deuda a corto plazo que pueden ser convertidos a propiedad a un ritmo determinado en el futuro, típicamente durante una futura ronda de inversión. Un *token* basado en blockchain puede ser visto como propiedad mientras una nota convertible puede ser vista como deuda con denominación en otra *commodity* o moneda. Los términos de la nota convertible permiten a su dueño convertirla al *token* que la respalda con una antelación mínima al precio justo del mercado del *token*. Crear dólares convertibles a *tokens* habilita a los blockchains a aumentar su efecto de red mientras se maximiza el retorno a los poseedores de *tokens*.

Los *Steem Dollars* son nomenclados con el símbolo SBD, acrónimo de "Steem Blockchain Dollars". Para crear los SBD se requiere una combinación entre un indicador de precio confiable, y reglas para prevenir el abuso. Proveer un indicador de precio confiable implica tres factores: minimizar el impacto de un indicador incorrecto, maximizar el costo de producir un indicador incorrecto, y minimazar la importancia de la cadencia.

### Minimizando comisiones fraudulentas

Los poseedores de SP eligen individuos, llamados testigos, para publicar indicadores de precio. Estos testigos seleccionados son presumiblemente confiables para aquellos que tienen un interés personal en la calidad del indicador. Al pagarle a quienes son elegidos, Steem crea un mercado competitivo para obtener el derecho de producir indicadores. Mientras mas productores de indicadores reciben pagos menos les conviene a éstos publicar información falsa.

Habiendo varios productores electos y confiables, el precio determinado para conversiones puede ser derivado entonces del promedio de los indicadores. De esta forma si alguna minoría de productores de indicadores publican valores atípicos, éstos tienen entonces un impacto mínimo en el promedio pero de todas formas se afecta su reputación.

Aún si todos los productores son honestos, existe la posibilidad que la mayoría de éstos sean afectados por eventos que estén más allá de su control. La red de Steem está diseñada para tolerar corrupciones de corto plazo en el indicador promediado mientras la comunidad trabaja activamente en la corrección del problema. Un ejemplo de un problema que puede tomar cierto tiempo para corregir es la manipulación de mercado a corto plazo. La manipulación de mercado es dificultosa y costosa de mantener por períodos largos. Otro ejemplo sería la falla de un servicio de intercambio centralizado o la corrupción de los datos publicados por el mismo.

Steem elimina el factor de las fluctuaciones de precio de corto plazo usando el promedio del período de tres días y medio. El indicador de promedio publicado es generado cada hora.

Siempre que una corrupción en el indicador de precios dure menos que la ventana de tiempo del promedio móvil, habrá un impacto mínimo en el precio de conversión. Si eventualmente el indicador es corrompido, los participantes de la red tendrán una oportunidad para votar la expulsión de los productores de indicadores corrompidos antes que impacten en el precio efectivo de conversión. Tal vez lo mas importante es que le da a los productores una oportunidad para detectar y corregir los problemas antes que sus indicadores comiencen a afectar el precio promediado.

Con una ventana de tiempo de tres días y medio, los miembros de la comunidad tienen aproximadamente un día y medio para responder y mitigar los problemas que puedan surgir.

### Mitigando ataques de cadencia

Los participantes del mercado tienen acceso a información antes de lo que el promedio móvil de tres días y medio del precio de conversión pueda reaccionar. Esta información puede ser utilizada para beneficio de los operadores a expensas de la comunidad. Si hay un incremento repentino en el valor de STEEM, los operadores podrían solicitar la conversión de sus SBD al precio anterior, más bajo, y luego vender los STEEM recibidos a un nuevo precio mayor con muy bajo riesgo.

Steem nivela el juego al imponer a todos los pedidos de conversión un retardo de tres días y medio. Esto significa que ni los operadores ni el blockchain tienen ventaja con respecto al precio cuando la conversión se ejecuta.

### Minimizando el abuso de conversiones

Si los usuarios puediesen convertir libremente en ambas direcciones, los operadores podrían tomar ventaja de las medidas de conversión del blockchain al intercambiar grandes volúmenes sin modificar el precio. Los operadores que ven un aumento masivo en el precio podrían convertir a SBD al mayor precio (cuando hay mas riesgo) y luego reconvertir luego de la corrección. El protocolo de Steem proteje a la comunidad de este tipo de abusos al permitir únicamente la conversión de SBD a STEEM y no al revés.

El blockchain decide cómo y cuándo crear SBD y quién debe recibirlos. Esto mantiene estable el ritmo de creación de SBD y elimina formas de abuso.

### Deuda sostenible a relaciones de propiedad

Si un *token* es considerado propiedad en el total de provisión de *tokens*, entonces un *token* convertible a dólar puede ser considerado como deuda. Si la deuda de propiedad tiene una relación muy alta, la moneda entera puede volverse inestable. Las conversiones de deuda pueden incrementar dramaticamente la provisión de *tokens*, los cuales por su parte pueden ser vendidos en el mercado suprimiendo el precio. Las conversiones subseuentes requieren la emisión de aún más *tokens*. Si no se comprueba el sistema puede colapsar dejando una montaña de deuda respaldada por propiedad sin valor. A mayor relación entre deuda a propiedad, menos inversores nuevos desearán aportar capital a la mesa.

Un cambio repentino en el valor de STEEM puede cambiar dramáticamente la relación deuda/propiedad. El blockchain impide que la relación deuda-propiedad llegue demasiado alta, reduciendo la cantidad de STEEM otorgado a través de conversiones de SBD, si el nivel de deuda superó el 10%. Si el monto de la deuda de SBD nunca supera el 10% de la PAC de mercado total de STEEM, el blockchain automáticamente reducirá la cantidad de STEEM generado a través de conversiones hasta un máximo de 10% de la capa del mercado. Esto asegura que el blockchain nunca tendrá más de 10% de una relación de deuda a la posesión.

El piso de porcentajes usado para computar la creación de STEEM se basa en la provisión incluyendo el valor de STEEM de todo el SBD y SP existente (tal como lo determine la relación / indicador del momento).

### Intereses

SBD retribuye intereses a los poseedores. La relación de interés es definida por la misma gente que publica el indicador de precio de forma que se puede adaptar a las condiciones cambiantes del mercado. Toda deuda acarrea riesgo para el prestador. Quien posee SBD sin redimirlo está efectivamente prestando a la comunidad el valor de un dólar. Ellos están confiando que en cierto punto en el futuro alguien estará dispuesto a comprarles los SBD por un dólar o que habrán especuladores e inversores dispuestos a comprar el STEEM al que lo conviertan.

Los poseedores de STEEM y SP ganan apalancamiento cuando los miembros de la comunidad se dispongan a sostener sus SBD. Este apalancamiento amplifica las ganancias por la crecida mientras también contribuyen a la misma. Quienes poseen STEEM sufren incremento de dilución si el precio cae. Los proyectos de Criptomonedas han demostrado que las ganancias de incrementar la base de usuarios dispuestos a confiar en la red con capital, terminan por sumar mas valor a la red que cualquier dilución que pueda ocurrir durante una baja.

### Definiendo fuentes de precios

Lectores astutos reconocerán que los activos de provisión limitada que generan intereses pueden ser intercambiados mayor o menos que el activo subyacente dependiendo de otras oportunidades para ganar interés sobre el mismo activo. Con una relación mas alta de interés sobre un activo vinculado al USD (dólar estadounidense) muchas personas intentarán ofertar sobre esta oferta limitada de Steem Dollars hasta que ya no valgan $1. En economía hay un principio conocido como "La Trinidad Imposible"[^4] que sugiere que resulta imposible tener todas las siguientes condiciones al mismo tiempo:

1. Relación de intercambio estable
2. Movimiento libre de capital
3. Una política monetaria independiente

Si los productores de indicadores apuntan a tener una política monetaria independiente para permitirles crear y destruír Steem Dollars y simultáneamente tener control total sobre la tasa de interés, entonces encontrarán problemas. La trinidad imposible dice que los Steem Dollars necesitan restringir el movimiento de capital, tener una tasa de intercambio inestable o tener control limitado sobre la tasa de interés.

La principal preocupación de los productores de indicadores de Steem es mantener una relación 1 a 1 estable entre SBD y el USD (Dólar estadounidense). Cuando el SBD sea consistentemente intercambiado por sobre $1 USD los pagos de interés deben ser detenidos. En un mercado donde el 0% de interés aún exige una prima, es seguro afirmar que el mercado está dispuesto a extender mas crédito del que la comunidad está dispuesta a tomar como deuda. Si ésto sucede el SBD será valuado a mas de $1.00 y poco podrá hacer la comunidad sin cobrar tasas de interés negativas.

Si la relación deuda/propiedad se encuentra bajo y el SBD está siendo intercambiado por menos de $1.00 entonces la tasa de interés debería incrementarse. Esto estimula a mas gente a sostener sus SBD y apoyar el precio.

Si el SBD se intercambia por menos de $1.00 USD y la relación deuda/propiedad está por sobre el 10%, el indicador debería ajustarse en subida para pagar mas STEEM por SBD. Esto incrementa la demanda de SBD mientras reduce la tasa de deuda/propiedad y la paridad entre SBD y USD.

Asumiendo que el valor de STEEM crece mas rápido de lo que Steem crea nuevos SBD, la relación deuda/propiedad debería permanecer debajo de la tasa necesaria y el interés ofrecido beneficia a todos. Si el valor de la red es plano o en caída, entonces cualquier interés ofrecido sólo hará peor la relación deuda/propiedad.

En efecto, los productores de indicadores son confiados con la responsabilidad de aplicar una política monetaria con el propósito de mantener un vínculo estable al USD. Abusar de este poder puede dañar el valor del STEEM de forma que los poseedores de SP deben ser listos al votar a los testigos (*witnesses*) con quienes contar para ajustar el indicador de precio y tasas de interés de acuerdo a las reglas recién especificadas.

Si la relación deuda/propiedad se posiciona peligrosamente alta y los participantes del mercado eligen evitar los pedidos de conversión, se debería ajustar el indicador para incrementar la tasa a la que se paga STEEM al convertir desde SBD.

Los cambios en la política de tasa de interés y/o cualquier prima/descuento en la relación de conversión de STEEM/SBD deberían ser una respuesta lenta y mesurada a la desviación promedio en el largo plazo en lugar de intentar responder a las condiciones de corto plazo del mercado.

Es nuestra creencia que estas reglas darán a los participantes del mercado la confianza de que la probabilidad de perder dinero por mantener SBD comprados al precio de $1.00 será poco probable. Esperamos completamente que habrá un rango de intercambio acotado entre $0.95 y $1.05 para el SBD bajo condiciones del mercado normales.

## Contribuciones subjetivas

La Prueba Subjetiva de Trabajo (*Subjective Proof of Work*) presenta un enfoque alternativo de distribución de moneda que "mejora" el PoW (*Proof of Work*) completamente *objetivo* tal como es el minado. Las aplicaciones de una moneda que implementa una prueba de trabajo *subjetiva* son mucho mas amplias que *cualquier* sistema de prueba de trabajo porque puede ser aplicada para construir una comunidad en torno a cualquier concepto que tenga un prósito lo suficientemente definido. Cuando los individuos acceden a una comunidad éstos compran acceso a un conjunto particular de creencias y pueden votar para reforzar los valores o propósito de la comunidad.

En efecto, el criterio por el cual se evalúa un trabajo es completamente subjetivo y su definición radica fuera del código de fuente en sí. Una comunidad puede desear premiar a artistas, poetas, comediantes. Otras podrían preferir premiar causas de caridad o apoyar agendas políticas.

El valor que cada moneda alcance depende de la demanda de influencia dentro de una comunidad en particular y de cuán grande el mercado crea que cada comunidad pueda ser. A diferencia de otros sistemas existentes, la prueba de trabajo subjetiva permite a una comunidad financiar colectivamente el desarrollo o lo que considere valioso y habilida la monetización de su tiempo otrora no monetizable.

### Distribuyendo la moneda

Hay dos formas en las que la gente puede involucrarse en una comunidad de criptomoneda: pueden *comprar* su acceso, *o trabajarlo*. En ambos casos, los usuarios agregan valor a la moneda, sin embargo, la basta mayoría de personas tienen mas *tiempo libre* que *efectivo a disposición*. Imagine el objetivo de fundar una moneda en una comunidad de escasos recursos y sin *efectivo* pero con suficiente *tiempo* disponible. Si la gente puede ganar dinero trabajando el uno por el otro, podrán crear valor a través del intercambio mutuo facilitado por un sistema justo de contabilidad/moneda.

Distribuír una moneda a la mayor cantidad de gente posible de una forma que sea generalmente percibida como justa es una tarea desafiante. Las tareas que pueden ser enteramente evaluadas por un algoritmo computacional objetivo son limitadas en su naturaleza y generalmente hablando, tienen limitados beneficios externos. En el caso del minado al estilo *Bitcoin*, puede resultar en una producción de hardware especializado y causar problemas para invertir tiempo desarrollando algoritmos mas eficientes para tal fin. Incluso puede servir encontrar números primos, pero ninguna de estas cosas provee valor con sentido a la sociedad o a la entera comunidad poseedora de la moneda. Aún mas importante, las economías fuerza de mercado y escala terminan excluyendo de la participación a todos salvo a los expertos con éste tipo de distribución. Finalmente, el minado basado en cómputos es sólo otra forma de *comprarse* acceso porque requiere dinero para pagar los costos de electricidad o el desarrollo del hardware necesario para realizar el trabajo.

Para otorgar a cada uno una oportunidad equitativa de involucrarse y recibir moneda, las personas deben tener la oportunidad de trabajar. El desafío es cómo juzgar la calidad relativa y cantidad de trabajo que los individuos proveen y de qué forma lograr que se que repartan eficientemente los premios a millones de usuarios. Esto requiere la introducción de un proceso de votación escalable. En particular se requiere que la autoridad que reparta los fondos sea tan distribuída y descentralizad como sea posible.

El primer paso para premiar millones de usuarios es encomendarse a la distribución de un monto fijo de moneda mas allá de cuánto trabajo sea realizado o cómo votan los usuarios. Esto cambia la pregunta de *"¿Debemos pagar?"* a *"¿A quién pagar?"* y señalar al mercado que la moneda está siendo distribuida y subastada a quien "oferte" más *trabajo*. Esto es similar al *Bitcoin* encomendado premios de 50 BTC a quien encuentre los hashes mas difíciles. Como en *Bitcoin*, todo el trabajo debe ser realizado previo al pago y nada debe ser pagado especulativamente bajo la promesa de realización del trabajo a futuro.

El próximo paso es premiar con algo a cada uno que haga *algo* aunque sea remotamente positivo. Esto se logra clasificando todo el trabajo hecho y distribuyendo proporcionalmente a su valor. Mientras más competitivo se vuelva el mercado (mayor calidad o cantidad), más difícil se torna recibir el mismo pago.

### Votando sobre la distribución de la moneda

Asumiendo que hay un monto fijo de dinero para distribuir, y que aquéllos que tienen intereses creados a largo plazo en el valor a futuro y utilidad de la moneda son quienes deben decidir como distribuirlo. Todos los usuarios con inversión emiten sus votos a quien haya hecho el mejor trabajo y al final del dia el dinero disponible para ese día es dividido proporcionalmente a los votos de manera que todos los que tengan al menos un voto positivo neto, obtiene algo.

The naive voting process creates a N-Person Prisoner’s Dilemma[^5] whereby each individual voter has incentive to vote for themselves at the expense of the larger community goal. Si cada votante se votara a si mismo entonces no habría dinero distribuído y la moneda entera fallaría en ganar efecto de red. Por otro lado, si sólo un votate se autovota, entonces él obtendría ganancias no merecidas mientras el efecto en el valor total de la moneda sería mínimo.

#### Abuso del voto

Independiente de cuánto dinero tenga cualquier individuo, siempre hay varios otros individuos con riquezas similares. Incluso el individuo más enriquecido raramente tiene mucho mas que la combinación de los que le siguen en cantidad de riquezas. Incluso, aquéllos que tienen una gran inversión en una comunidad también tienen más riesgo de perder al intentar jugarle al sistema de votos para su beneficio. Sería como si el CEO de una compañía decidiese dejar de pagar salarios para guardarse las ganancias en su bolsillo. Todos dejaría de trabajar y se irían a otras compañías y su empresa quedaría vacía y sin valor, dejando al CEO en bancarrota en lugar de rico.

Afortunadamente, cualquier trabajo que esté obteniendo una gran concentración de votos también gana más escrutiño (publicidad). A través de la adición de *votación negativa* es posible para participantes de menor talla nulificar el poder de voto de grupos confabulado o contrarrestar a los grandes poseedores. Tambipen, los grandes poseedores tienen mas para perder si la oneda falla en su valor debido a abusos de lo que pueden ganar por autovotarse. De hecho, los grandes poseedores honestos son usualmente mas efectivos en castigar el abuso y usando votos negativos de lo que serían al votar contribuciones mas pequeñas.

El uso de *votos negativos* para evitar que la gente abuse el sistema apalanca la *mentalidad "cangrejo"* que muchas personas poseen cuando se percibe que un individuo está obteniendo ganancias a expensas de los demás. Mientras la mentalidad de "cangrejo" normalmente se refiere a personas de corta visión detrimentando a las buenas personas, también permite a las buenas personas mantener a las malas abajo. El único "problema" con la mentalidad de cangrejo es cuando la gente *cree equivocadamente* que alguien está beneficiándose a expensas del resto.

**La Historia de la cubeta de cangrejos**[^6]

*Un hombre se encontraba caminando por la playa y vió a otro hombre pescando en el muelle con una cubeta a su lado. A medida que se acercaba, vió que la misma estaba destapada y tenía cangrejos vivos en su interior.

"¿Por qué no tapa su cubeta para que no escapen los cangrejos?", preguntó.

"No entiendes.", respondió el pescador, "Si hay sólo un cangrejo en la cubeta, éste trepará y escapará rápidamente. Sin embargo, cuando hay muchos cangrejos en ésta, si uno trata de trepar por un lado, los demás lo tomarán y lo devolverán adentro para que sufra el mismo destino que el resto."*

También sucede con las personas. Si uno intenta hacer algo diferente, obtener mejores notas, mejorarse, escapar a su entorno, soñar en grande, otras personas intentarán arrastrarlo abajo y compartir su destino.

Eliminar el "abuso" no es posible y tampoco debería ser el objetivo. Incluso aquellos quienes intentan "abusar" del sistema también están trabajando. Cualquier compsensación que obtengan por sus intentos satisfactorios de abusar o confabularse es cuando menos valioso para el propósito de de distribuír la moneda como en el sistema de trabajo empleado por la minería tradicional de *Bitcoin* o de minería confabulada a través de *pools* de minado. Todo eso es necesario para asegurar que el abuso no sea tan rampante como para socavar el incentivo para realizar verdadero trabajo de soporte de la comunidad y su moneda.

La meta de desarrollar una moneda comunitaria es obtener mas "cangrejos en la cubeta". Tomar medidas extremas para eliminar todo abuso es como intentar poner una tapa en la cubeta para prevenir que se escapen algunos cangrejos y viene a expensas de hacerlo mas difícil de agregar nuevos integrantes. Alcanza con hacer las paredes resbaladizas y dar a otros "cangrejos" el suficiente poder para prevenir que otros "escapen".

### Tasa limitada de voto

Una mayor parte de minimizar el abuso es limitar la tasa de voto. Los usuarios individuales sólo pueden leer y evaluar tántos items de trabajo diarios. Cualquier intento de votar mas frecuentemente que ésto es una señal de automatización y potencial abuso. A través del límite de tasa de voto, los participantes que voten más frecuentemente tienen su voto menos valioso que los participantes que votan con menos frecuencia. Los intentos de dividir *tokens* entre múltiples cuentas también divide la influencia y por ende no resulta en un incremento neto en influencia ni saltea el límite de tasa impuesto en el voto.

A los usuarios se asigna una cantidad fija de poder de voto. El poder de voto es multiplicado por los *tokens* invertidos de un usuario para determinar la parte que debería ser colocada en el *pool* de pagos para determinado ítem. Cada voto utiliza un porcentaje del poder de voto restante. Los usuarios pueden votar por más posts, pero cada voto valdrá menos y tardará más en llegar a la plena potencia de voto otra vez. El poder de voto se recarga a una tasa lineal fija del 20% por día.

### Distribución de pagos

Una de las metas primordiales del sistema de premios de Steem es producir las mejores discusiones en internet. Cada año el 75% de la inflación anual es distribuida a los usuarios que envían, votan y discuten contenido. Con el tamaño del *Bitcoin* ésto podría ser tanto como varios millones de dólares por día siendo entregados a los mejores contribuyentes.

La distribución efectiva dependerá del patrón de votación de los usuarios, pero sospechamos que la amplia mayoría de los premios será distribuída entre el contenido mas popular.

La Ley de Zipf[^7] es una de esas reglas empíricas que caracterizan muy bien un sorprendente rango de fenómenos del mundo real. Ésta dice que si ordenamos determinada colección grande por tamaño o popularidad, el segundo elemento en la colección medirá aproximadamente la mitad del primero, el tercero un tercio del primero y así sucesivamente. En general, el item en la posición k medirá aproximadamente 1/k del primero.

![](\img_the_new_marketplace.png)

Tomando la popularidad como una medida de valor tosca, entonces el valor de cada item individual es dado por la Ley de Zipf. Esto es, si tenemos un millón de items, entonces los 100 mas populares contribuirán un tercio del valor total, los próximos 10.000 otro tercio, y los restantes 989.900 el tercio restante. El valor de la coleccion de *n* items es proporcional a *log(n)*.

El impacto de esta distribución de votos y pagos ofrece grandes recompenzas al buen contenido mientras se mantiene el premiado a los pequeños jugadores por el *long-tail* de su contribución.

El efecto económico de ésto es similar a la lotería donde la gente sobrestima su probabilidad de obtener votos y por ende trabaja mas del valor esperado de su premio y por lo tanto maximizan el monto total de trabajo realizado en servicio de la comunidad. El hecho de que todos "ganen algo" juega sobre la misma psicología que suelen usar los casinos para mantener a la gente apostando. Dicho de otra forma, los pequeños premios ayudan a reforzar la idea de que es posible ganar premios mayores.

### Pagos

Cuando un post recibe un pago, éste toma la forma de 50% de SBD y 50% de SP. El Steem Power da al usuario un poder aumentado de voto y transacción mientras que el SBD da al usuario un beneficio inmediato en una moneda estable. Como ya hemos analizado en profundidad, el SP está diseñado para alentar la posesión a largo plazo en lugar de la venta a corto plazo. Esto anima a los usuarios a tener un interés personal en el éxito a largo plazo de la plataforma.

Los usuarios también tienen la opción de ser recompensados con 100% SP, así como declinar el pago de los posts. Cuando un usuario declina el pago de un post, el dinero que se le habría pagado a ellos permanece en el *pool* de premios, para ser distribuido a los otros usuarios.

# Algoritmo de consenso

El consenso es el proceso por el cual una comunidad llega a un acuerdo no ambiguo y universalmente reconocido sobre una pieza de información. Hay muchos algoritmos desarrollados por la sociedad para alcanzar consenso sobre quién es dueño de qué. Cada gobierno en la tierra es un algoritmo de consenso primitivo con el cual la población acuerda atenerse a cierto conjunto de reglas encapsuladas en una Constitución. Los gobiernos establecen cortes, jueces y jurados para interpretar hechos subjetivos y emitir una decisión final. La mayoría de las veces la gente se atiene a estas decisiones incluso si son erróneas.

Los algoritmos utilizados por las criptomonedas proveen una mejor forma para alcanzar consenso. Testimonios criptográficamente firmados por individuos son registrados en un registro público que establece un orden global absoluto de eventos. Una algoritmo computacional determinístico puede procesar este registro para derivar una conclusión universalmente aceptada. En tanto los miembros de una comunidad estén de acuerdo en el algoritmo de proceso, el resultado de dicho algoritmo es autoritario.

La consideración primaria es determinar qué testimonio es permitido para entrear el registro público. Los sistemas deberían ser diseñados para minimizar el potencial para su censura. La censura en el registro público es similar a prevenir que alguien vote en una elección. En ambos casos un individuo tiene su impacto en el consenso global imposibilitado.

## Consenso en Steem

Conceptualmente, el algoritmo de consenso adoptado por Steem es similar al algoritmo de consenso adoptado por compañías de todo el mundo. Gente con interés invertido en el valor futuro de Steem, vota para elegir individuos responsables de incluír testimonios en el registro público. El peso del voto es determinado proporcionalmente al interés invertido de cada individuo.

En el mundo de las criptomonedas, se refiere comunmente al registro público como *blockchain*. Un *block* o bloque es un grupo de transacciones firmadas (testimonios).

En Steem, la producción de bloques es realizada en rondas. En cada ronda se seleccionan 21 testigos para crear y firmar bloques de transacciones. Veinte (20) de éstos testigos son seleccionados para aprobar las votaciones, y un puesto es compartido por tiempo por cada testigo que no logró entrar en el *top* 20 proporcional de más votados. Los 21 testigos activos son mezclados en cada ronda para prevenir que cualquiera de los testigos ignore constantemente bloques producidos por el mismo testigo ubicado anteriormente en ese puesto. Cualquier testigo que se salte un bloque y no haya producido en las últimas 24 horas, será desactivado hasta que actualice su clave de firma de bloque.

Este proceso está diseñado para proveer la mejor confiabilidad mientras se asegura que todos tengan potencial para participar en la producción de bloques independientemente de si son suficientemente populares para ser votados dentro de la lista de los. Las personas tienen tres opciones para superar la censura de los principales 20 testigos elegidos: pacientemente esperar en fila con todos los demás que no están en el top 20, o comprar más SP para mejorar el poder de voto. Generalmente hablando, aplicar censura es una buena forma de elegir testigos para perder su trabajo y por lo tanto, es improbable que sea un problema real en la red de Steem.

Debido a que los testigos activos son conocidos de antemano, Steem puede acomodar los testigos para producir bloques cada 3 segundos. Los testigos sincronizan sus producción de bloques a través del protocolo NTP. Una variante de este algoritmo ha sido utilizada por la red BitShares por alrrededor de una año donde ha demostrado ser confiable.

# Eliminando comisiones de transacción

Steem va más allá para beneficiar a quienes contribuyen a la red. Sería contraproducente dar la espalda y cobrar a los usuarios cada vez que intentan interactuar con la comunidad.

La tecnología blockchain actualmente depende de comisiones de transacción para prevenir spam. Estas comisiones sufren de todos los problemas conocidos con las microtransacciones y previenen que los blockchains sean usados para transacciones de bajo costo. Las aplicaciones verdaderamente descentralizadas deben ofrecer a los usuarios el atractivo de transacciones gratuitas si se desea competir ante sus alternativas centralizadas. Este documento explica el método utilizado por Steem para eliminar la necesidad de comisiones y por ende habilitar un amplio rango de aplicaciones anteriormente inviables de manera descentralizada.

## El problema de las comisiones

Los blockchains son redes descentralizadas donde todas las transacciones son emitidas a todos los pares (*peers*). Cada tanto se produce un bloque que incluye alguna o todas las transacciones pendientes. Todos los blockchains deben encontrar una solución para prevenir que usuarios maliciosos consuman todo o gran parte de la capacidad disponible de la red con transacciones sin valor o inútiles. Estas transacciones sin valor evitan que transacciones valiosas y útiles sean procesadas en detrimento de la red.

La solución adoptada por la mayoría de los blockchains hasta ahora es cargar una comisión mínima de transacción. Una comisión con un costo de unos pocos centavos es suficiente para lograr que atacar la red no sea redituable e incluso costoso. Mientras ésta solución resuelve el problema del *spam*, introduce nuevos problemas. Imagine resolver el problema del *spam* en emails introduciendo una pequeña comisión en cada correo enviado; la gente no usaría el correo electrónico.

### Los micropagos no funcionan

El problema fundamental de cargar comisiones de transacción reside en que los micropagos no funcionan, especialmente por el bajo valor de las acciones de los usuarios. Cuando se carga una comisión en cada transacción, se limitan los tipos de transacciones que una red descentralizada puede procesar. Independientemente de cuán racional sea el argumento para la necesidad de las comisiones, los usuarios aún detestan la experiencia de dejar unos centavos por cada cosa que hacen.

Imagine que los sitios web que usamos a diario cobraran una comisión por cada vez que modificamos nuestras cuentas o cambiamos la contraseña. Los usuarios esperan que ciertas cosas sean gratuitas. Requerir a los usuarios que tomen una decisión sobre que acción merece o no una pequeña comisión crea ansiedad que causa que éstos se retiren. Una transacción no puede valer tanto como para requerir una decisión pero vale tan poco que la decisión es automática. Hay una cierta cantidad de ansiedad en cualquier decisión de comprar, no importa lo pequeño, y deriva no de la interfaz o el tiempo necesario, sino del el acto mismo de decidir.

Igual que todos los pagos, los micropagos, requieren de una comparación: *"¿Vale X lo mismo que Y?"* Hay un costo mínimo de transacción "psicológica" creado por este hecho que no se puede optimizar, ya que la transacción que un usuario esté dispuesto a aprobar sin pensar, será la que no les cuesta nada, que no es una transacción en realidad.

– Clay Shirky[^8]

En el mundo de los pagos financieros, pequeñas comisiones son aceptables debido a que el valor de la transacción es extremadamente alto en relación a la comisión cobrada, y el comprador ya ha tomado la decisión de comprar. El mundo de aplicaciones potenciales de blockchai es mucho mas grande que simplemente el de pagos financieros e incluye muchas transacciones necesarias para las cuales las comisiones son simplemente inaceptables para los usuarios.

Sistemas como BitShares, Nxt, Ripple, Counterparty y Stellar permiten a los usuarios colocar órdenes de límite en el blockchain y todos cobran a los usuarios una pequeña comisión para realizar esta acción. Luego si el usuario desea cancelar su orden, se le cobra otra comisión. Sistemas como Ethereum llevan los micropagos a un nivel completamente nuevo: cobrar por cálculo. Todos estos sistemas luchan para atraer nuevos usuarios *mainstream* por la misma razón por la que un motor de búsqueda se esforzaría para atraer nuevos usuarios desde google si cobrara una pequeña comisión por cada búsqueda. No importa cuan bueno sea el servicio, la gente espera que ciertas cosas sean gratuitas. Esto es cierto incluso si un usuario finalmente termina pagando más en una estructura diferente.

### Las comisiones son barreas para el acceso

Cualquier comisión crea una barrera de entrada a los nuevos usuarios. Antes que alguien pueda experimentar con Ethereum debe adquirir *tokens* de *ETH*. Cualquiera que desee desarrollar una aplicación descentralizada en Ethereum debe trasladar el costo a sus clientes. Comprar una criptomoneda no es una tarea fácil y raramente tiene sentido por montos menores a $10. Esto quiere decir que los usuarios nuevos queriendo probar una nueva aplicación descentralizada debe primero ser convencido de empezar con $10.

### Cambiando las comisiones

Con el tiempo una red debe ajustar las comisiones. Esto puede suceder tanto por un incremento en el valor del *token* o al aumento en la capacidad. Los usuarios prefieren comisiones predecibles y servicio garantizado. Aún siendo posible ajustar dinámicamente las comisiones en tiempos de mucho uso, el resultado es una pobre experiencia de usuario.

### Ataques de identidad o Ataques Sybil (Sybil attacks)

Los sitios web centralizados previenen el spam limitando la frecuencia o alguna forma de verificación de identidad. Incluso algo tan simple como un *CAPTCHA* [^9] es suficiente para limitar la creación de cuentas falsas. Si alguien abusa de su cuenta, los sitios web centralizados tienen la libertad de bloquear la cuenta.

En un sistema descentralziado no hay forma directa de prohibir usuarios ni un proveedor centralizado que pueda alojar un *CAPTCHA* para imponer un límite de frecuencia de creación de cuentas. De hecho, la falta de habilidad para censurar usuarios es un de los principales puntos atractivos de la tecnología del blockchain.

### Reserva completa vs. reserva fraccionada

Veamos el blockchain como un Proveedor de Servicio de Internet (*ISP*) cooperativo que posee todos los cables en pueblo y tiene un ancho de banda máximo que puede proveer en cualquier momento. La gente viviendo en el pueblo puede comprar acciones en el *ISP* y a cambio obtienen el derecho de utilizar una porción del ancho de banda disponible.

El *ISP* tiene dos opciones, correr un sistema de "reserva completa" o uno de "reserva fraccional". Bajo un sistema de reserva completa a cada usuario solo se le permite una fracción del ancho de banda máximo proporcional a sus acciones. Debido a que no todos usan Internet al mismo tiempo, la red del pueblo sería significativamente subutilizada.

En un sistema de reserva fraccional los usuarios individuales podrían utilizar mas ancho de banda del que tienen otorgado en cualquier momento mientras no todos usen Internet en ese mismo tiempo. El problema al operar una reserva fraccionada es que las congestiones ocurren cuando mucha gente desea usar la red al mismo tiempo. El *ISP* necesita una forma de priorizar el ancho de banda durante períodos congestionados. En el caso mas extremo, una red completamente congestionada debe revertirse a un sistema de reserva completa. El desafío es implementar la proporción correcta de reserva fraccional.

## Iterando mas allá de los micropagos

La solución a los problemas de los micropagos es implementar *reservas fraccionales dinámicas*. Bajo este modelo el blockchain automáticamente ajustará la proporción de reserva para la red durante períodos de congestión. El blockchain ubicará un objetivo de utilización que deje suficiente margen para oleadas de demanda en cortos plazos. En cualquier momento que se mantengan oleadas de uso el blockchain reduce el ancho de banda máximo por acción. Cuando una oleada se acaba y sobra capacidad, el blockchain puede lentamente incrementar el ancho de banda por acción.

El ancho de banda utilizado por un usuario individual debería ser medido sobre un período de tiempo apropiadamente largo para permitir que el usuario puede invertir el horario de su uso. Los usuarios tienen a acceder, hacer varias cosas al mismo tiempo, y luego salir. Esto significa que su ancho de banda durante un período de tiempo corto puede parecer mucho mas alto que si es visto sobre un período mas largo. Si la ventana de tiempo se estira demasiado entonces la proporcion de reserva no se ajustará lo suficientemente rápido para responder al incremento a corto plazo, si la ventana es demasiado estrecha entonces agrupar el uso tendrá un impacto muy grande en usuarios normales.

En nuestra estimación debería ser suficiente medir el promedio semanal de ancho de banda de los usuarios. Cada vez que un usuario firma una transacción, ésta es ténida en cuenta en el promedio móvil individual del usuario. En el momento en que el promedio móvil de un usuario excede el límite actual de la red, su transacción es retrasada hasta que su promedio se acomode debajo de ese punto.

### Impacto de capacidad

La capacidad del blockchain no está necesariamente limitada. Está bien dentro de la capacidad tecnológia de la infraestructura internet incrementar el tamaño de bloque de Bitcoin a 10MB lo que en cambio reducirá el balance mínimo requerido por un factor de 10. Mientras Bitcoin actualmente soporta aproximadamente 3 transacciones por segundo, implementaciones alternativas pueden permitir mas de 1000 transacciones por segundo.

### Comparación de comisiones

Si asumimos que un usuario con $25 dólares en BTC transacciona una vez por semana y paga una comisión de $0.04 cada vez entonces ellos pagarían mas de $2 en comisiones por año. Un usuario tendría que ganar una tasa de retorno de 8% sobre sus $25 sólo para no salir perdiendo al pagar comisiones. Todo indica que los usuarios van a mantener su dinero en el blockchain de todas formas, entonces este usuario con $25 en BTC ha ahorrado $2 en el transcurso de un año al adoptar una propuesta de tasa limitada en lugar de una libre de comisiones. Con solo $175 podrían transaccionar todos los días y ahorrar $14 al año.

### Creación de cuenta

El sistema de Steem, basado en cuentas de con balances públicamente conocidos simplifica la implementación del algoritmo de limitación de tasa basado en el ancho de banda. Cualquier cuenta con un balance por debajo del mínimo requerido para transaccionar una vez por semana no debería poder transaccionar. Esto implica que todas las nuevas cuentas deberían ser cargadas con al menos éste balance mínimo. Esto tambien implica que los usuarios deseando transaccionar en montos menores puedan, mientras mantengan un balance mayor y reutilicen la cuenta.

Es posible para una cuenta con balance bajo creada durante un tiempo de bajo uso volverse inaccesible si el uso de la red se dispara. Los fondos podrían ser recuperados en cualquier momento delegando temporalmente un balance mayor a la cuenta.

Con el fin de mantener una experiencia de usuario razonable con un mínimo de cuentas colgadas, todas las nuevas cuentas debe comenzar con un balance 10 veces el mínimo requerido para transaccionar por semana. De esta forma si la demanda se incrementa por un factor de 10, la cuenta continuará utilizable.

Cualquier balance de cuenta inicial debería tener que venir del usuario creando la cuenta y no de la creación de *token* debido al peligro de ataques de identidad (*Sybil attacks*).

### Justificando balances mínimos

El concepto de forzar a los usuarios a mantener un balance mínimo fluye naturalmente del valor de un usuario[^10]. Cualquier corriendo un negocio sabe que cada usuario tiene un valor significativo. Los negocios gastan entre $30 y $200 para adquirir un usuario. A veces pagan usuarios directamente, otras veces pagan por publicidad, e incluso otras veces compañías enteras son adquiridas solo por su base de usuarios. Luego de que una compañía adquiere un usuario generalmente le otorga varios *servicios gratuitos* para mantenerlos cerca lo suficiente para monetizarlos a través de otros medios.

Ripple usa un balance mínimo[^11] que escala al uso de recursos de la cuenta y requiere que nuevas cuentas sean fundadas con al menos éste balance mínimo. Actualmente este balance mínimo es de alrrededor de $0.15, el cual es mayor al $0.10 que estimamos que permitiría a alguien transaccionar libremente al menos una vez por semana.

Un blockchain puede imponer un valor mínimo por usuario a través del simple proceso de requerir un balance mínimo. Cualquier negocio que desee traer un nuevo cliente al blockchain puede precargar esa cuenta con un balance mínimo que le permitiría transaccionar. Requiriendo una comisión relativamente grande ($1.00) para registrar nuevos usuarios naturalmente forzará a cualquiera que ofrezca cuentas gratis considerar la calidad y singularidad de cada cuenta antes de registrarlas con el blockchain.

Mantener un balance mínimo es efectivamente lo mismo que hacer que los usuarios paguen comisiones de transacción con el interés que podrían haber ganado en su balance. El balance mínimo es simplemente el balance requerido para ganar suficiente interes para pagar una comisión en un período de tiempo relativamente corto.

Afortunadamente, el balance mínimo requerido puede ser tan bajo como un dólar y ésto es algo que los usuarios pueden entender y apreciar. El costo de oportunidad de interés perdido no incurre en el costo cognitivo de una microcomisión y es mucho mas aceptable para los usuarios.

El STEEM usado para precargar una cuenta es convertido a Steem Power en la nueva cuenta (ej.: *Powering Up*). Parte del SP usado para financiar una nueva cuenta, pudiera ser delegado desde la cuenta del creador de esa cuenta. Cuando se delega a un usuario SP, pueden utilizar el SP para la votación y para ancho de banda como si fueran suyo, pero la propiedad del SP se mantiene al usuario que lo delega. Un usuario puede quitar la delegación en cualquier momento. Después de un período de enfriamiento, el SP vuelve a sus cuenta.

### Efectividad relativa a comisiones

Para comparar la efectividad de la tasa de limitación a comisiones debemos considerar cuánto ambos sistemas reaccionan a la inundación intencional de la red por parte de un atacante. En Bitcoin, un atacante con $10.000 puede afectar el servicio por un día entero llenando cada bloque. El mismo atacante no podría afectar el servicio ni siquiera durante un bloque bajo la propuesta de tasa de limitacion de reserva fraccional dinámica.

Si vamos a un caso mas extremo y asumimos que el atacante posee el 1% de todas las monedas entonces asumimos un atacante con 60 millones dólares. Tal atacante podría denegar el servicio del blockchain de Bitcoin por 16 años a no ser que los minadores aumentes las comisiones o la capacidad. Incluso si las comisiones fueren incrementadas a $15 por transacción, el atacantes podría aún continuar afectando la red por 16 dias.

Bajo el enfoque de limitación de tasa, alguien que posea el 1% de todas las monedas con intenciones de inundar la red lograría su objetivo por menos de 30 segundos.

### Renta vs. Compra vs. Tiempo compartido

Cuando alguien es dueño de una casa espera el derecho de uso de la misma de forma gratuita. Si un frupo de gente compra una casa en conjunto entonces ellos pueden pretender el derecho de usarla proporcionalmente al porcentaje que les corresponda de la casa. Un blockchain basado en comisiones es como rentar la casa a sus propios dueños, donde limitar la tasa es como dividirse el tiempo de uso entre los propietarios.

Si una casa es propiedad de múltiples personas, ellos deben decidir como desean compartir la casa. Alguien que tenga el 50% de la propiedad pero sólo la utiliza un fin de semana por año podría esperar que los individuos le paguen por el tiempo sin usarla. Esta es la idea de un sistema basado en comisiones.

Por otro lado, alguien que posea el 50% de la casa está especulando que la demanda por la casa aumente en el futuro y ellos podrán vender su parte por más. Cualquier dueño que posea mas de la casa de lo que utiliza se convierte en un especulador de bienes raíces. Con esta idea en lugar de recolectar renta, recolecta apreciación.

El valor de una acción procede de cuanto tiempo tiempo puede potencialmente otorgar a su propietario. Poseer el 1% de una casa y obtener un fin de semana por año es el valor mas bajo de una acción. Sin embargo, si la mitad de los propietarios nunca utilizan su fin de semana, entonces el valor por tiempo compartido aumenta a 2 fines de semana por año. Si aquellos usuarios inactivos optan por rentar su tiempo sin uso, entonces éste baja nuevamente a 1 fin de semana por año. Si esos tiempos sin usar fuesen vendidos a gente que los usara entonces el valor del tiempo compartido caería un 50%. A menos que la renta recolectada sea mayor que la caída del valor de las acciones, los dueños del tiempo compartido estarán cometiendo un error de cálculo económico.

Usando esta racional podemos asumir que un sistema basado en comisiones será mas caro para sus usuarios o ser menos redituable para sus propietarios colectivos. Un propietario individual pequeño puede obtener ganancias al rentar su pequeña porción de tiempo, pero solo a expensa de todos los demás dueños. En efecto, el costo del decreciente valor del tiempo compartido es repartido entre todos los propietarios donde las ganancias son centralizadas en el dueño singular que decidió rentar su parte.

Podemos concluír de ésto que un blockchain es mejor servido si no se usa ninguna comisión. Si una comisión de uso fuese cobrada como una alternativa de tasa limitante, entonces debería ser equivalente a comprar el tiempo compartido suficiente y disponerse a mantenerlo el tiempo suficiente para ganar el derecho a usarlo una sola vez.

Dicho de otra forma, una comisión de transacción debería equivaler al balance mínimo de cuenta necesario para transaccionar una vez por semana y debería ser recargado al final de la semana. Asumamos que el mínimo balance de cuenta es $1 y permite a alguien transaccionar una vez por semana. Si alguien con un balance de $1 desea concretar 5 transacciones de una sola vez, tendrá que incrementar su balance a $5 por semana tanto antes o después de sus transacciones.

En teoría un mercado podría formarse donde los usuarios pueden conseguir la inversión necesaria. En la práctica es mas eficiente para los usuarios simplemente comprar y vender el tiempo compartido necesario para alcanzar su tasa de utilización deseada. En otras palabras, el costo de negociar micropréstamos es mayor que el costo de mantener un balance apto para el máximo uso semanal.

La limitación de tasa descentralizada puede habilitar nuevos tipos de aplicaciones descentralizadas que no eran viables cuando todos los usos de la aplicación requerían un micropago. Este nuevo modelo da a los desarrolladores de aplicaciones la habilidad de decidir si y cuando cobrar a sus usuarios por las transacciones.

# Performance y escalabilidad

La red Steem está construpida sobre *Graphene*, la misma tecnología que empodera BitShares. Graphene ha sido públicamente demostrado sustentando mas de 1000 transacciones por segundo en una red de pruebas distribuída. *Graphene* puede fácilmente escalar a 10.000 o mas transacciones por segundo con mejoras relativamente directas a la capacidad de servidores y protocolos de comunicación.

## Escala Reddit

Steem puede manejar una base de usuarios mas grande que Reddit. En 2015 los 8,7 millones de usuarios de Reddit generaron un promedio de 23 comentarios por segundo[^12], con un promedio de 83 comentarios anuales por usuario. Hubieron 73 millones de posts de primer nivel, para un promedio de 2 nuevos posts por segundo. 7 mil millones de votos positivos creando un promedio de velocidad de 220 votos por segundo. Dicho todo ésto, si Reddit estuviese operando en un blockchain requerirpia un promedio de 250 transacciones por segundo.

Para lograr este rendimiento de líder de la industria, Steem ha juntado lecciones aprendidas del *LMAX Exchange*[^13], que puede procesar 6 millones de transacciones por segundo. Entre estas lecciones se encuentras los sigueintes puntos clave:

1. Mantener todo en memoria.
2. Mantener el núcleo de la logica de negocio en un sólo hilo.
3. Mantener las operaciones criptográficas (hashes y firmas) fuera de la lógica del núcleo de negocio.
4. Dividir la validación en comprobaciones dependientes e independientes del estado.
5. Usar un modelo de datos orientado a objetos.

Al seguir estas simples reglas, Steem puede procesar 10.000 transacciones por segundo sin un esfuerzos significativos en términos de optimización.

Mantener todo en memoria es cada vez mas viable dada la reciente introducción de la tecnología *Optane™* de *Intel* [^14]. Debería ser posible para el hardware manejar toda la lógica del negocio asociada con Steem en un sólo hilo con todos los posts mantenidos en memoria para una indexación rápida. Incluso Google mantiene su índice completo de internet en RAM. El uso de la tecnología blockchain hace trivial replicar la base de datos en varias máquinas para prevenir la pérdida de datos. A medida que la tecnología *Optane™* avance, el RAM se volverá aún mas veloz mientras se gana persistencia. En otras palabras, Steem está diseñado para la arquitectura del futuro y diseñado para escalar.

# Asignación y suministro

## Suministro y asignación inicial

La red Steem comienzó con una provición de moneda de 0 y colocó STEEM a través de la prueba de trabajo (*Proof of work*) a una velocidad de aproximadamente 40 STEEM por minuto a los mineros, con un adicional de 40 STEEM por minuto siendo creados para financiar el contenido y fondos para premios de curado (totalizando 80 STEEM por minuto). Entonces la red empezó a premiar a los usuarios que convertían a SP. En este punto, STEEM creció a una velocidad de aproximadamente 800 STEEM por minuto debido a los efectos combinados de los distintos Premios de Contribución sumarizados abajo:

Premios por contribución:

- Premios de curado: 1 STEEM por bloque o 3,875% anual, el que sea mayor
- Premios de creación de contenido: 1 STEEM por bloque o 3,875% anual, el que sea mayor
- Premios de producción de bloques: 1 STEEM por bloque o 0,750% anual, el que sea mayor
- Premios por inclusión de POW previos al bloque 864.000: 1 STEEM por bloque (entregados como 21 STEEM por ronda)
- Premios por inclusión de POW posteriores al bloque 864.000: 0,0476 STEEM por bloque (entregados como 1 STEEM por ronda) o 0.750% anual, el que sea mayor.
- Premios por liquidez: 1 STEEM por bloque (entregados como 1200 STEEM por hora) o 0,750% anual, el que esa mayor

### Premios por poder:

- Steem Power premia: Por cada STEEM creado por los premios de arriba, 9 STEEM se dividen entre todos los poseedores de Steem Power.

### Operaciones de SBD:

- Premios SBD: Un porcentaje del valor del SBD es creado en un set APR por los testigos y abonado en forma de SBD a los poseedores de SBD

La imagen general del suministro es complicada por el efecto de las operaciones de SBD, las que pueden resultar en creación o destrucción a larga escala de STEEM a través del seguimiento de tasa de alimentación y premios SBD, como se explica en la sección SBD. Other, smaller-scale complicating effects also exist, including unclaimed incentives (e.g. block rewards for missed blocks), and abandoned accounts.

## Suministro y asignación actual

Starting with the network's 16th hard fork in December 2016, Steem began creating new tokens at a yearly inflation rate of 9.5%. The inflation rate decreases at a rate of 0.01% every 250,000 blocks, or about 0.5% per year. The inflation will continue decreasing at this pace until the overall inflation rate reaches 0.95%. This will take about 20.5 years from the time hard fork 16 went into effect.

75% de los nuevos tokens que se generan van al *pool* de recompensas, que se reparte entre los autores y curadores. 15% de los *tokens* nuevos son dados como premio a los poseedores de SP. The remaining 10% pays for the witnesses to power the blockchain.

### Impacto de Tasa de creación de tokens

It is often said that a coin with an inflationary model is not sustainable, but we know from countless real-world examples that the quantity of money does not have a direct and immediate impact on its value, though it certainly plays a role.

From August 2008 through January 2009 the U.S. money supply[^15] grew from $871B to $1,737B, a rate of over 100% per year and then continued to grow at about 20% per year for the next 6 years. Dicho ésto, el suministro de dinero en EEUU ha crecido 4,59x durante menos de 7 años. During that same time, the value of the dollar relative to goods and services has fallen less than 10% according to the government's price index[^16]. Este ejemplo del mundo real demuestra que el suministro es sólo un componente del precio.

For the first 2 years of Bitcoin’s life the network sustained an annual inflation rate[^17] of over 100%. Durante los primeros 5 años estaba sobre el 30%, y por los primeros 8 años se encontraba sobre el 10%. All told the total “spending” Steem does to fund content, curation, and block production amounts to less than 10% APR.

El precio de un *commodity* digital, como STEEM, es conducido tanto por el suministro y la demanda. Cuando un poseedor a largo plazo decida salir, el suministro de STEEM en el mercado se incrementará y empujará el precio hacia abajo. Esta presión es contrarresetada cuando un nuevo poseedor a largo plazo decide comprar STEEM y convertilo de nuevo a SP. Additional supply and demand may be be added due to market speculators buying and selling liquid STEEM based on their predictions of the future market price.

# El poder de Steem

Steem reconoce que el valor de todas las contribuciones de los usuarios (posts y votos) es mayor que la suma de sus partes. Un simple comentario vale casi nada, pero millones de posts curados vale muchos millones (o incluso miles de millones) de dólares. Un solo voto provee poco valor de curado, pero mil millones de votos es un curado efectovo. El contenido sin curado es de valor limitado. Dado todo el contenido de internet menos los enlaces entre éstos, Google lucharía para producir resultados de búsqueda útiles. Son los enlaces entre informaciones que le dan valor significativo.

Por el hecho de que todos se benefician, todos deberían pagar. En otras palabras, ningún usuario individual debería esperar pagar por nada, pero en cambio debería recibir un pago por todo lo que hacen que de valor a Steem. All we need to do is ascertain which user contributions bring a social network value and which ones don’t.

Colectivamente los usuarios de Reddit votan 220 veces por segundo y crean 23 posts por segundo. Reddit is valued between $500 million[^18] and $4 billion[^19] which means that each and every upvote and post is worth between $0.06 and $0.50 assuming the value of Reddit is mostly within the past year’s worth of activity. Uno podría argumentar que la mayor parte del valor de Reddit son las discusiones cercanas al tiempo real que han ocurrido la semana pasada que incrementarían dramáticamente el valor de la nueva actividad. La gente va donde están todos hoy, no donde estuvieron el año pasado.

## Sin micropagos, propina opcional

Los intentos existentes de integrar una criptomoneda en una plataforma de *social media* se han enfocado en habilitar a los usuarios a pagarse entre sí. Muchos servicios han intentado introducir propinas. La teoría es que si hacemos el acto de dar propina lo suficientemente simple entonces mas gente lo haría. Other services attempt to get people to pay to promote or boost their content’s ranking. Otros aún intentan construir pequeños mercados de predicción de cuanta propina un artículo recibirá.

Todas estas propuestas recaen en micropagos. Estas difieren solo en quién está haciendo el pago. Todas sufren de falta de compromiso de parte de la gente haciendo los micropagos. In the search for incentivised content production entrepreneurs have been so focused on who should pay that they missed the obvious reality: everyone benefits from everyone’s actions so everyone should pay or no one should pay, depending on how you look at it.

Steem se salta los micropagos por completo porque cuando un usuario vota un post es la comunidad quien paga la cuenta. El mismo monto de dinero será gastado tanto si el usuario vota un post o no y los fondos no vendrán del votante.

La energía mental asociada a tomar una desición económica se vuelve una barrera para la participacion para la mayoría de las personas.

*Ya enfrentamos una multitudo de opiciones a diario con respecto a qué acceder en línea en esta era digital de la explosión de información, y cada decisión adicional que debemos hacer simplemente se agrega a la incertidumbre y ansiedad que enfrentamos. Quienes apoyan los micropagos creen que una implementación simplificada puede minimizar la intrusividiad de los micropagos y mejorar la experiencia de usuarios, pero su argumento solo crea doble estándares para el proceso de toma de decisión \[2\]. Una transacción no puede simultáneamente ser suficientemente valiosa para garantizar una desición y valer tan poco que la desición es automática. **Las únicas transacciones que los usuarios pueden aprobar sin pensarlo son aquellas que no cuestan nada**, en consecuencia cualquier microtransacción de valor positivo incurrirá en costos mentales a través de su requerimiento de tomar una desición. Además, el costo de transacción mental de hecho crece bajo cierto umbral de valor, un fenómeno que ubica los micropagos en aún mayor desventaja. Por ejemplo, es muy fácil pensar que una copia de los periódicos actuales cuestan $1, pero los lectores enfrentan mucha mas dificultad y ansiedad en decidir el valor de cada artículo o palabra. Tal dilema solo será replicado y exsacervado si todo el contenido en línea fuese desglosado en sus componentes e individualmente cotizado dentro de un sistema de micropagos.*

-Micropayments: A Viable Business Model[^20]

Bajo Steem, los micropagos son pagados al productor del contenido, pero aquéllos que votan el contenido no pagan. En su lugar, el costo del premio es pagado a través de nuevos *tokens*. Alguien puede ingresar en el sistema, votar para pagarle a alguien, y luego irse del sistema con mas dinero del que tenían cuando comenzaron (asumiendo que la valuación del mercado del sistema de Steem se mantenga constante). En otras palabras, las solución de los micropagos provista por Steem provee una experiencia de usuarios similar a muchos sitios web ampliamente utilizados que tienen contenido moderado.

Además, ¡Steem le paga a la gente para determinar a quién se debería pagar!. Este tipo de pensamiento es revolucionario.

## El valor está en los enlaces

Internet perdería la basta mayoría de su valor si todos los enlaces entre contenidos fuesen removidos. Es esta relación entre páginas web que permite a Google identificar la mejor receta de tarta de manzanas entre 16 millones de resultados. Sin estos enlaces la única información que Google tendría es la frecuencia de palabras.

Los enlaces pueden tomar varias formas y adaptarse en el tiempo. Every time a user votes on content in a social network they add a connection between themselves and the content. Esto en cambio enlaza al consumidor con el productor a través del contenido. The more connections a network has the more valuable the information becomes. Es la conexión intencional y relativa de la información que le da valor.

A social network can maximize the value extracted from a set of content by maximizing the quantity and quality of connections. Curar contenido es caro y consume tiempo mientras es casi imposible para las computadoras realizar ésto ante la ausencia de enlaces. Steem rewards users who are among the first to find and identify new content.

Al incentivar el curado, la red Steem puede usar algoritmos automatizados para extraer la información mas valiosa de un monto masivo de contenido.

## Resolviendo el problema de abordaje de las criptomonedas

It isn’t easy to get into cryptocurrency[^21]. Alguien que descubre Bitcoin y quiere probarlo rápidamente se da cuenta de que necesitará registrarse a un *exchange* y cargar su cuenta con una tarjeta de crédito o una transferencia bancaria. What would Facebook’s adoption rate have been like if you had to fork over money and a two forms of ID?

Steem resuelve este problema dándole a cada uno una forma de recibir pagos por hacer tareas simples pero valiosas. Esto ayudará a distribuír ampliamente los *tokens* STEEM. This is helpful because cryptocurrencies have a network effect (i.e. more users make it more useful; for an extreme example, consider that if Satoshi had kept 100% of Bitcoin for himself, Bitcoin would be worthless.)

## Resolviendo el problema de liquidación de las criptomonedas

Una moneda que es difícil de usar o imposible de vender tiene poco valor. Alguien que viene con $1,00 en Bitcoin descubrirá que cuesta mas de $1,00 vender ese Bitcoin. Tendrá que crear una cuenta en un *exchange*, llevar a cabo una validación KYC, y pagar comisiones. Pequeños montos de criptomoneda son como el cambio chico que la gente no está dispuesta a agacharse a juntar del piso.

Los mercaderes dan a los usuarios un camino para convertir rápidamente su criptmoneda en bienes tangibles y servicios. Estos mercaderes necesitan una moneda vinculada a su unidad de cuenta, normalmente dólares. Aceptar una moneda volátil introduce una carga significativa de contabilidad.

Los mercaderes aceptarán cualquier moneda si ésta incrementa sus ventas. Tener una gran base de usuarios con una moneda estable tal como SBD baja la barrera de entrada para los mercaderes. La presencia de mercaderes mejora el sistema al crear una salida del sistema para los usuarios sin tener que entrar en problemas de utilizar un *exchange*.

Another way that people can liquidate the small amounts of cryptocurrency they receive from participating on the Steem platform is through *tipping* others. Esto es como dejar el cambio chico como propina al mesero. Cuando mucha gente deja su pequeña propina ésta se añado a un monto significativo. Usted y el mesero se benefician de la propina.

## Censura

Steem is a decentralized network that is operated by witnesses in jurisdictions around the world. Todas las acciones de los usuarios son públicamente grabadas en el blockchain, y pueden ser públicamente verificadas. Esto significa que no hay una única entidad que pueda censurar contenido que es valioso para los poseedores de STEEM.

Los sitios web individuales como *steemit.com* puede censurar contenido en su sitio particular, pero el contenido publicado en el blockchain es inherentemente tráfico emitido y sitios en todo el mundo pueden continuar haciéndolo disponible.

La libertad de expresión es la fundación del resto de las libertados e infringir la libertad de expresión socava los únicos medios pacíficos de alcanzar consenso: la discusión. Sin discusión libre los votantes no pueden ser completamente informados y votantes desinformados son una mayor amenaza para la sociedad que perder el derecho a votar. La censura es un medio para robar votos a través de la limitación del discurso público. Steem está comprometido a habilitar la libertad de expresión y construír una sociedad libre.

## Resolviendo el descubrimiento orgánico a través de la optmización en motores de búsqueda

La mayoría de las criptomonedas generan poco valor para aquellos que no usan la red activamente. Steem, por contraste, genera contenido y alienta a los usuarios a compartirlo. Este contenido es indexado por motores de búsqueda y finalmente traerán valor a un gran número de usuarios pasivos. Este tráfico de búsqueda crea publicidad orgánica para la red Steem y hace crecer el efecto de red.

## Viraje hacia la atribución basada en blockchain

Internet representa el medio mas fácil para distribuír información en el mundo. Dicho ésto, puede ser un lugar aterrador para los creadores de contenido que quieran ser dueños de su contenido y lo tienen compartido con la atribución correspondiente. En las plataformas de *social media* actuales, la atribución es algo que puede perderse de la noche a la mañana - un video posteado o una imagen pueden ser replicados y recompartidos sin consentimiento o reconocimiento al creador.

Bajo la *social media* basada en blockchain, un creador o autor siempre estaría habilitado para apuntar a un registro público y sello de fecha mostrando una prueba del origen de su contenido. En una circunstancia donde el creador quiera encargarse de quienes hayan compartido el contenido sin permiso o atribución, los registro basados en el blockchain proveen una prueba pública de que el contenido fue posteado por un usuario particular en determinado momento. En el futuro, la atribución basada en blockchain puede ser reconocida por gobiernos por su autenticidad y podría tener peso en la corte, lo cual daría a los creadores de contenido mayores poderes para controlar su trabajo.

While a timestamping service can be built on almost any blockchain, and several efforts exist to build this kind of service on the Bitcoin network, Steem has a useful advantage in this realm because content publishers are “first class citizens” -- the Steem blockchain is built from the ground up around the use case of content publication, which allows content creators to have the blockchain to validate their content at a certain point in time simply by writing their post using the same authoring tools used by other Steem users.

## Reemplazando la publicidad con recompenzas de contenido basado en blockchain

Bajo la mayoría de modelos de monetización, los creadores de contenido apalancan la publicidad de una forma y otra. Many creators recognize how advertising may diminish their work’s value to the consumer, yet creators very often must seek returns on their time by monetizing. La publicidad representa una espada de doble filo: Con anuncios, un creador puede generar dinero mas fácil. Sin anuncios, la monetización se hace difícil pero el contenido es mas rico.

Creators posting to social media outlets that are connected to Steem may monetize merely by having their work recognized (or ”liked”) by the Steem community. Los pagos basados en blockchain son completamente digitales y no tienen intermediarios. Por lo tanto la monetización por premios de contenido basados en blockchain deberían ser mas rápidos y con menos barreras para usar que la monetización por publicidad.

# Conclusion

Steem es un experimento diseñado para hacer frente a los desafíos en las industrias de *social media* y criptomonedas combinando los mejores aspectos de ambas. Steem presenta oportunidades de ganancias a los creadores de contenido y lectores de internet de formas que aún no existían dentro de la industria de *social media*. Dentro de Steem, los individuos reciben ganancias reales en línea que son directamente correlativas a sus contribuciones. Those rewards may have dollar value due to the market price discovery and liquidity of Steem, and the people who hold Steem may have more exclusive earning powers than those who do not.

[^1]: Reddit’s Cryptocurrency, Forbes, Erika Morphy, October 2014 http://www.forbes.com/sites/erikamorphy/2014/10/01/reddits-cryptocurrency-could-have-many-uses/\#4e07b05332b9

[^2]: Sweat Equity, Investopedia http://www.investopedia.com/terms/s/sweatequity.asp

[^3]: Meta-moderation is a second level of comment moderation. Users are invited to rate a moderator's decision in order to improve moderation. https://en.wikipedia.org/wiki/Meta-moderation\_system

[^4]: The Impossible Trinity, economic theory https://en.wikipedia.org/wiki/Impossible\_trinity

[^5]: N-Person Prisoner’s Dilemma https://cs.stanford.edu/people/eroberts/courses/soco/projects/1998-99/game-theory/npd.html

[^6]: The Story of the Crab Bucket http://guidezone.e-guiding.com/jmstory\_crabs.htm

[^7]: Zipf’s Law https://en.wikipedia.org/wiki/Zipf%27s\_law

[^8]: Clay Shirky, The Case Against Micropayments http://www.openp2p.com/pub/a/p2p/2000/12/19/micropayments.html

[^9]: reCAPTCHA, Easy on Humans, Hard on Bots https://www.google.com/recaptcha/intro/index.html

[^10]: Forbes, Tristan Louis, “How Much is a User Worth?” http://www.forbes.com/sites/tristanlouis/2013/08/31/how-much-is-a-us

[^11]: Ripple, Account Reserves https://ripple.com/build/reserves/

[^12]: Reddit Statistics, Number of Users and Comments per Second http://expandedramblings.com/index.php/reddit-stats/2/

[^13]: Martin Fowler, The LMAX Architecture http://martinfowler.com/articles/lmax.html

[^14]: Introducing Intel Optane Technology – Bringing 3D XPoint Memory to Storage and Memory Products https://newsroom.intel.com/press-kits/introducing-intel-optane-technology-bringing-3d-xpoint-memory-to-storage-and-memory-products/

[^15]: United States Money Supply, 2009 https://research.stlouisfed.org/fred2/graph/?s%5B1%5D%5Bid%5D=AMBNS

[^16]: CPI Inflation Index, United States Dollar 2008-2016 http://data.bls.gov/cgi-bin/cpicalc.pl?cost1=1&year1=2008&year2=2016

[^17]: Bitcoin Annual Inflation Rate, Bitcoin Talk Forum https://bitcointalk.org/index.php?topic=130619.0

[^18]: Reddit Valuaton, Newsweek, 2014 http://www.newsweek.com/investors-think-reddit-worth-500-million-26

[^19]: Worth of Web, March 2016 http://www.worthofweb.com/website-value/reddit.com/

[^20]: Micropayments: A Viable Business Model http://www.openp2p.com/pub/a/p2p/2000/12/19/micropayments.html

[^21]: Dailydot, Jon Southurt, April 2015 http://www.dailydot.com/opinion/bitcoin-cryptocurrency-adoption-hard