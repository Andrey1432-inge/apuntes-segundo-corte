# Modelamiento de sistemas

# 1.Sistemas mecanicos 
## ¿Qué es un Sistema Mecánico?

- Conjunto de elementos mecánicos que transmiten o transforman el movimiento.
- Permiten modificar velocidad, dirección o tipo de movimiento (rectilíneo, circular).

## Tipos de Movimiento

1. Rectilíneo: en línea recta (ej: pistón).

2. Circular: en trayectoria circular (ej: polea).

3. Alternativo: vaivén (ej: sierra).

4. Oscilante: movimiento de vaivén con eje fijo (ej: péndulo).

## Elementos de Transmisión

- Poleas y correas

- Ruedas dentadas (engranajes)

- Ejes y árboles

- Levas y cigüeñales

## Ejemplo 1 - Transmisión con Poleas

- Dos poleas conectadas por una correa.

- Transmiten movimiento circular.

- Se puede modificar la velocidad o dirección del giro según el tamaño de las poleas.

## Ejemplo 2 - Engranaje Recto

- Dos ruedas dentadas conectadas.

- Transmiten movimiento circular con cambio de sentido.

- Relación de transmisión depende del número de dientes.

**Ejemplo práctico:**
Engranaje con 20 dientes → Engranaje con 40 dientes
→ reduce velocidad a la mitad, aumenta torque.

## Definiciones

- Trabajo: Esfuerzo realizado por una fuerza para mover un objeto.

- Energía: Capacidad para realizar trabajo.

**Ejemplo: Elevar una pesa requiere energía (potencial o cinética según el contexto).**

## Tipos:

- Energía Potencial

- Energía Cinética

## Energía Potencial

- Depende de la posición.

- Se almacena en resortes y masas.

- Equivale al trabajo de una fuerza externa.

**Ejemplo: Comprimir un resorte almacena energía que se libera al solta**

## Potencia

- Trabajo realizado respecto al tiempo.

**Ejemplo: Subir escaleras rápido consume más potencia que hacerlo lento.**

## Energía Potencial en un Resorte

- Trabajo neto al comprimir o estirar.

- Fórmula típica: $$𝐸𝑝 = \frac{1}{2}kx^2$$
 

**Ejemplo:** Un resorte con $$k=100N/m$$ comprimido 0.1 m almacena 0.5 J.

## Potencia en una Masa

- Relacionada con la aceleración de la masa.

**Ejemplo: Acelerar un carro requiere más potencia si la masa del carro es mayor.**

## Energía Disipada

- Trabajo que se pierde, generalmente en forma de calor, por fricción o amortiguamiento.

**Ejemplo: Un amortiguador disipa energía cuando el auto pasa por un bache.**

## Potencia Disipada en Amortiguador

- Potencia se disipa proporcional a la velocidad.

**Ejemplo: A mayor velocidad de compresión, mayor disipación.**

## Conservación de Energía

- Si no hay pérdidas, la energía total se mantiene.

**Ejemplo: Un péndulo ideal oscila conservando su energía cinética y potencial.**

## Sistema Conservativo

- No hay fricción.

- Energía externa = 0.

**Ejemplo: Masa oscilando en un resorte sin resistencia al aire.**

## Ejemplos

- Aplicación del método de conservación de energía.

- Se derivan ecuaciones de movimiento con base en la energía total.

**Ejemplo: Masa suspendida en un resorte que oscila verticalmente.**

## Comentarios

- Método energético útil para sistemas simples.

- Para sistemas complejos, mejor usar leyes de Newton o el método de Lagrange.

## Casos Frecuentes

- Conversión entre movimientos traslacionales y rotacionales.

## Trenes de engranes, Palancas y Bandas

- Transmisión de energía mediante mecanismos comunes.

## Ejemplo

- Análisis de sistemas con engranajes o palancas.

## Reflejar hasta el Torque de Origen

- Convertir las fuerzas/momentos en términos del eje motor para simplificar.

## Palancas

- Aplicación de relaciones de fuerza y movimiento.

** Ejemplo: Una palanca balanceada cumple: $$𝐹1 ⋅ 𝑑1 = 𝐹2 ⋅ 𝑑2$$
​
## Ejemplo con Ecuaciones

- Modelo dinámico con momento de inercia, fricción y fuerzas externas.

## Resumen

- Modelado mecánico requiere ecuaciones diferenciales.

- Movimiento lineal y rotacional se modelan de forma análoga.

## Conclusión

- Los sistemas mecánicos son esenciales para el funcionamiento de máquinas.

- El conocimiento de sus componentes permite diseñar y mantener mecanismos eficientes.

# 2. Sistemas electricos

## Circuito RLC

- Explicación del circuito usando las leyes de Kirchhoff.

- Se presentan ecuaciones básicas de los elementos:

- Resistencia: $$𝑅 = 𝑣(𝑡)𝑖(𝑡)$$ 

- Condensador: %%i(t)=C\frac{dv(t)}{dt}$$
​ 
- Inductor: $$v(t)=L\frac{di(t)}{dt}
​
## Ejemplo

- Aplicación de la ley de Kirchhoff de voltajes:

$$−u(t)+i(t)⋅R+L\frac{di(t)}{dt} +y(t)=0$$

Sustitución de i(t) con la relación del capacitor: $$i(t)=C\frac{dy(t)}{dt}$$ 

Resultado: EDO de segundo orden:

$$−u(t)+RC\frac{dy(t)}{dt} + LC\frac{d^2y(t)}{dt^2} + y(t)=0$$

## Aplicando nodos

- Aplicación de la ley de Kirchhoff de corrientes (LKC)

- Derivación de ecuación diferencial:

$$u(t)−6\frac{dy(t)}{dt} −2y(t)=0$$

## Introducción a amplificadores operacionales

- Uso de leyes de Kirchhoff y modelo simplificado del amplificador operacional.

- Supuestos: $$V+ =V−$$

- Corriente en entradas = 0

- Alta impedancia de entrada, baja impedancia de salida

## Amplificador no inversor

- Análisis del amplificador:

$$i1−i2 =0$$

$$\frac{eo−ei}{R1}-\frac{ei}{R2} = 0 ⇒ eo=ei(1+\frac{R2}{R1})$$

## Con elementos almacenadores de energía

- Análisis de circuito con resistencias y capacitores:

$$ei =−\frac{eo}{R2} − C\frac{deo}{dt}$$ ⇒(Modelo con EDO)
