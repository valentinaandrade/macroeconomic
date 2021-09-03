# Referencias

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->
<!-- code_chunk_output -->

- [Referencias](#referencias)
  - [De Gregorio (2007) Macroeconomía: teoría y política](#de-gregorio-2007-macroeconomía-teoría-y-política)
    - [Capítulo 15: Teoría cuantitativa, neutralidad y demanda por dinero](#capítulo-15-teoría-cuantitativa-neutralidad-y-demanda-por-dinero)
    - [5.1 La función del dinero](#51-la-función-del-dinero)
  - [Capítulo 16: La oferta de dinero, política monetaria e inflación](#capítulo-16-la-oferta-de-dinero-política-monetaria-e-inflación)
    - [16.1 La oferta de dinero](#161-la-oferta-de-dinero)
  - [16.2 : La política monetaria](#162-la-política-monetaria)
      - [**Formas de crear dinero base:**](#formas-de-crear-dinero-base)
    - [Formas de crear dinero (M1 y M2) *dada* una base monetaria**](#formas-de-crear-dinero-m1-y-m2-dada-una-base-monetaria)
  - [Corridors and Floors in monetary policy](#corridors-and-floors-in-monetary-policy)
    - [Introduction about Federal Reserve (FED)](#introduction-about-federal-reserve-fed)
  - [Implementing monetary policy](#implementing-monetary-policy)
      - [Demand for Reserve Balances](#demand-for-reserve-balances)
      - [Supply of Reserve Balances](#supply-of-reserve-balances)
  - [Friedman: Monetary policiy](#friedman-monetary-policiy)
    - [La política monetaria para la estabilidad de precios](#la-política-monetaria-para-la-estabilidad-de-precios)
    - [La política monetaria para la estabilidad en los precios y el empleo](#la-política-monetaria-para-la-estabilidad-en-los-precios-y-el-empleo)
    - [La política monetaria y la oferta de dinero](#la-política-monetaria-y-la-oferta-de-dinero)
      - [Monetary policy cannot do](#monetary-policy-cannot-do)
      - [What monetary policy can do](#what-monetary-policy-can-do)
      - [Conducted monetary policy](#conducted-monetary-policy)
  - [Discusiones](#discusiones)
  - [Friedman](#friedman)
  - [Implementación PM](#implementación-pm)

<!-- /code_chunk_output -->



## De Gregorio (2007) Macroeconomía: teoría y política

### Capítulo 15: Teoría cuantitativa, neutralidad y demanda por dinero


### 5.1 La función del dinero

La importancia de este: independiente de su valor actual (por cambios en la inflación), el dinero puede usarse para hacer transacción (función fiduciaria)


**Definición del dinero**
Es un **activo** que cumple con la condición de ser **líquido**. Esta característica lo hace más probable para el uso de sus liquidaciones.

El grado de liquidez nos dará diferentes definiciones de dinero (M1,M2, M3, donde M1 es más líquido que M2 )

Matemáticamente se define como
$$M_1 = C + D_v$$ (1), donde

- *C*: billetes y monedas de libre circulación o **circulante**
- $D_v$: depósitos a la vista, que pueden ser liquidados rápidamente (ejemplo, con un cheques o vales, es decir, dinero que proviene de cuentas corrientes)

$$M_2 = M_1 + D_p$$ (2), donde
- $D_p$: depósitos a plazo


**Funciones del dinero**

**1. Medio de pago**
- Utilizable para transacciones de bienes y servicios
- El formato de transacción puede ser físico o virtual [^1], lo que tiene implicancias en la demanda por dinero.


[^1]: Las tarjetas de crédito **no son** dinero.Si son un medio de intercambio, pero son **deuda** de quién las ocupa, y no un **activo**

2. Unidad de cuenta

- Los precios de los bienes se expresan en términos de dinero.
- Como *unidad de cuenta* **indexada** a los *precios* no es única. En un país [^2] puede tener diversas unidades de cuenta, UF (Unidad de Fomento en Chile), UI (unidad indexada). También con diferentes objetivos (pago de impuestos, arriendos).

[^2]: Estas formas han surgido en países con alta inflación como una forma de protegerse de las fluctuaciones de poder adquisitivo

- Es un *estándar de pagos diferidos*: estipulan pagos futuros

- La moneda es dinero si y solo si es aceptado su uso o por ley (moneda de curso legal) [^2]

3. Depósito de valor

- Medio de ahorro de activos

**El dinero y los gobiernos**
- Emisión de un papel por parte del Banco Central, autoridad que respalda y certifica el dinero.
- Relación 1:1 (oro:dinero), por el respaldo. [^3]. Luego esa necesadad de respaldo ya no era tal pues **el valor del dinero dependía de lo que podía comprar y no del oro que lo respaldaba**.
- Releva la importancia de la certificación que especifique cierto valor y que sea aceptado para hacer transacciones.


[^3]: Convertibilidad en Argentina (2001)

**Tipos de dinero**

1. Dinero mercancía: aquel que tiene un valor en sí mismo
2. Dinero fiduciario: sin valor intrínseco, sino que vale lo que la gente acepta para **transacciones** (más allá de lo normativo o legal)

El **valor del dinero depende de la cantidad de bienes que puede comprar**.  Por eso, en países donde hay inflación, es lo mismo decir "el precio de los bienes sube" o " el precio del dinero baja".

## Capítulo 16: La oferta de dinero, política monetaria e inflación

### 16.1 La oferta de dinero

**1. Liquidez**

El dinero no solo es **medio de pago** (transacciones), sino que está constituido por activos financieros líquidos (transacciones líquidas). Según ello, el $M$ va a variar. En general, hablaremos de

$$M = C + D  \tag{16.1} $$  donde $D$ podría ser $D_v \lor D_p$.

**2. Emisión**

Quién tiene el monopolio de la emisión de dinero, dinero de alto poder o base monetaria ($H$) es el Banco Central.

- En **sistema 100% reservas** *(sistema financiero sin préstamo y deuda)*  lo que el BC ha emitido se encuentra en libre circulación (C) o en forma de depósitos (D). Por lo tanto

$$H = M = C + D \tag{16.2}$$


**3. Encaje**

- Los intermediarios financieros, bancos comerciales, prestan $D$, pero por ley una proporción deben reservarla. Eso es el **encaje**:

$$R = \theta D \tag{16.3}$$ donde $R$ es reserva o **encaje**, $\theta$ es el porcentaje y $D$ depósitos


**El encaje permite:**
  - **Estabilizar la demanda de dinero** y tasas interbancarias
  -  Dar solidez al sistema bancario
  -  No solo es dinero, sino que podrían ser líneas de crédito (p.437)
  -  Gastos operacionales y cumplimiento de ley  (por lo general se debe cumplir en promedio en un periodo)

En caso contrario, se producen problemas de liquidez del sistema bancario y *crisis de pagos*. Ahora bien, evidentemente  el $R$ tiene un *costo de oportunidad* (R se iguala a mínimo legal). Por lo tanto, **considerando el encaje la emisión es**

$$H = C + R \tag{16.4}$$ es decir, la **base monetaria** o **emisión del BC** son reservas de bancos y circulante (billetes y monedas), y no los depósitos.

**Creación de dinero**

Las personas mantienen una razón igual a $\bar{c}$ entre lo circulante y sus depósitos.

$$C = \bar{c} D \tag{16.5}$$

La decisión entre pasar el dinero de C a D o viceversa **depende del costo de transacción**

![](img/dgreg16.jpg)

- El multiplicador monetario es mayor que 1 debido a que $\theta < 1$
- La emisión del banco se ve amplificada por el sistema bancario.


## 16.2 : La política monetaria

- Qué hacen los bancos para afectar la **oferta monetaria**
- El equilibrio del mercado monetario
- Objetivos de los bancos centrales: fijar la tasa de interés interbancarias

**La creación de dinero**

Partir por los análisis de los balances financieros de cada sector económico para consolidar el sistema monetario.

![](img/balances-bancos.jpg)

**Banco Central**
 1. Activos [^4]
   - Reservas internacionales: depositadas en moneda extranjera en el exterior
   - Credito interno: a instituciones financieras
   - Deuda: del gobierno, que es un pasivo del gobierno
 2. Pasivos
   - Emisión: circulante ($C$) (activo público), encaje (activo de bancos)
   - Deuda: podría tener pero se consolida con la deuda del gobierno

[^4]: Activo son recursos a disposición, y pasivo, es parte de las obligaciones que va a tener la institución. En macroeconomía un activo es el conjunto de bienes y derechos de una sociedad, es decir, lo que posee más lo que le deben. El activo nos habla de en qué ha invertdo la sociedad, mientras que pasivo sobre el origen de los fondos para realizar las inversiones.


**Sistema financiero**

1. Activos
  - El sistema financiero le presta al sector privado, banco central y al gobierno
  - Reservas de encaje en el banco central
2. Pasivos
  - Le debe al banco central el credito interno
  - Le debe al público los depositos.

**Sector publico y privado**
Activos
- Dinero (M) = D + C
Pasivos
- Deuda del gobiernos
- Deuda del sector privado con los bancos.


**Balance**

- La base (H) corresponde a los pasivos monetarios del banco central, es decir, excluye deuda y patrimonio neto.
- El dinero (M) son los **pasivos** monetarios del sistema financiero consolidado con el banco central.


####  **Formas de crear dinero base:**
Estas dos formas juegan un rol escencial en analizar los régimenes cambiarios.

**1. Operaciones de cambio**
Si el banco central compra moneda extranjera los cambiará por moneda doméstica (pesos).

A partir del aumento de sus reservas internacionales, se aumentará el **circulante** y con esto se crea dinero.

*Banco Central sin intervención*
En sistemas cambiarios de **libre flotación** el Banco Central **no** interviene en el mercado cambiario y por lo tato sus reservas internacionales son constantes y no hay operaciones de cambio.

*Banco Central interviniendo*, cambiando R*
1.1 Régimen de tipo de cambio fijo
1.2 Régimen de flotación sucia
1.3 Intervención esterilizada: operación opuesta para **retirar dinero emitido**

**2. Operaciones de crédito interno**:  corresponde a todas las operaciones que **no** invucran directamente cambio de **reservas internacionales**, a partir de

- Emisión:  "sin tener ninguna otra repercusión" (*helicopter drop*). Lamsam que no tienen ninguna contrapartida.

- **Crédito a los bancos**: para que ellos presten al *sector privado* (firmas). No es muy utilizada pues incolucra decisiones de quién recibe el crédito y en qué condiciones (además el Banco Central asumiría el riesgo del crédito, pasando a actuar como un banco comercial).

Actúa como prestamista directo **en última instancia**. Pero igual con esto los bancos podrían efectuar prestamos **aumentando su activos**

- **Operaciones de mercado abierto**: comprar y vender instrumentos financieros a cambio de dinero. El funcionamiento de estas operaciones **dependerá de las caracteristicas institucionales de la economía**.

*Un ejemplo de emisión con compra de deuda del fisco*

Banco Central **compra deuda del gobierno a bancos** , expandiendose la *base monetaria*. **Sumado a ello** los bancos privados reducirán sus préstamos al gobierno (cae $B_g^f$) aumentando sus colocaciones hacia el sector privado el que aumentaría su stock de dinero a través del proceso multiplicador (*Hacer dibujo*).

Evidentemente ese tipo de financiamiento fiscal no siempre está permitido para el Banco Central, pese a que sea compra de deuda pública en un mercado secundario.

Otro ejemplos para **aumentar la cantidad de dinero** son la compra por parte del Banco Central de:
1. Título de licitaciones
2. Letras hipotecarias
3. Acciones (menos frecuente)

Ejemplos para **redicr la cantidad de dinero** (retirando liquidez)
1. Venta de deuda

### Formas de crear dinero (M1 y M2) *dada* una base monetaria**

1. Variar el encaje exigido: permitiendo que el encaje sea menor, con lo cuál el multiplicador aumentaría, expandiendo la demanda de dinero.

## Corridors and Floors in monetary policy

### Introduction about Federal Reserve (FED)

1. Regulate and oversee the nations commercial banks by making sure that banks have enough money to avoid bank runs

2. Conduct **monetary policiy** which is increasing or deacresing the money supply to speed up or slowd down the overall economy.

Recordemos que la política fiscal cambia gasto publico e impuestos, mientras que la política monetaria la **oferta de dinero**.

- Tasas de interes: es el monto al cuál se presta dinero. Cuando los bancos prestan dinero espera que se pague el monto que se prestó, llamado capital.

Cuando las tasas de interés son bajas, se facilitará a los prestatarios el reembolso de los prestamos, por lo que ellos podrán  pedir más dinero y gastar más dinero.

Cuando las tasas de interés son altas, los prestatarios tienen menos dinero y gastarán menos dinero.

En muchos países, y en general, los Bancos Centrales **no tienen el poder de fijar la tasa a la cuál los bancos comerciales fijan las tasas de interés**, solo pueden hacer esto **cambiando la oferta monetaria**:

- Si el Banco Central aumenta la oferta monetaria, los bancos privados tendrán más dinero que prestar.

*Veamos la siguiente situación:*
- Los individuos (prestatarios) buscarán la mejor oferta para buscar un préstamo. Luego, los bancos se verán obligados a bajar las tasas de interés pues tendrán que competir o de lo contrario nadie les pedirá prestado.
- Una disminución de la oferta monetaria afecta negativamente pues los bancos tendrán menos dinero que prestar, y por tanto la tasa de interés será más alta pues será más caro prestar (o más difícil).

1. Política expansiva: para acelerar la economía, se debe aumentar la oferta monetaria pues esto reducirá las tasas de interés y con esto se conducirá a más prestamos y gastos.

2. Política contractiva: para frenar la economía, se reduce la oferta monetaria, y menos dinero disponible hará que las tasas de interés aumenten y disminuya el gasto

Algunos ejemplos de situaciones y tipo de política implementada.

1. Recesión o brecha de estancamiento: producción era baja, desempleo alto. Al aumentar la oferta de dinero, se facilitó el endeudamiento y aumentó el gasto. Como resultado la economía comenzó a crecer nuevemente.

2. En los 70s los precios subían un 13% al año, produciéndose una inflación del 3 a 4%. El FED redujo la oferta monetaria, y con eso las tasas de interés subieron mucho. Pero la gente compró menos casas y autos, y cayó la inversión empresarial. La política monetaria redujo la inflación pero resultó en una tasa de desempleo.

3. Gran depresión: el año 1973  Bernanke mismo indica que lo hicieron mal dado que no cumplieron dos condiciones relevantes para la sanidad del sistema financiero:

1. Confianza: Cuando los clientes depositan dinero en un banco deben estar seguros que recuperarán su dinero. Durante la gran Depresión varios bancos se vieron en quiebra (cerca de 1/3)

2. Liquidez: los bancos quiebrn pues no tienen activos liquidos (liquid assets). Tenían acciones, bonos e hipotécas pero no dinero. Entonces, cuando los depositantes entraron en pánico, los bancos no tenían dinero.

La culpa ha sido del FED pues no dio prestamos de emergencia a los bancos, lo que hubiese aumentado liquidez de bancos y hubiese aumentado la oferta de dinero.


**Formas de cambiar la política monetaria**

Cuando ponemos dinero en el banco, el banco se queda con una parte en depositos (reserva fraccionaria = encaje y depositos) y presta el resto ($C$)

1. Encaje o *reserve requierement*: reducir el requisito de reserva aumenta la oferta monetaria.

2. Tasa de descuento: Como el banco central es el banco de los bancos, estos pueden pedirle dinero al Banco Central cuando quieren hacer más prestamos.

Reducir la tasa de descuento facilita pedir prestamos a los bancos, y de esta forma la oferta monetaria aumentará.

3. Operaciones de mercado abierto: esto es cuando el FED compra o vende bonos del fisco a corto plazo ("el gobeierno devoverá más adelante"). Esto se hace pues es menos riesgoso que acciones.

  1. Compra de bonos: con esta operación se aumenta la liquidez y con eso la oferta monetaria a ese banco.
  2. Vende o emite bonos: el banco tendrá menos efectivo y menos dinero que prestar, y con eso reducirá oferta monetaria.

Quién define esto es el Comité de Mercado abierto (FOMC)

**Decisiones de la política monetaria**
Con estas estrategias los Bancos Centrales pueden **aumentar o reducir la oferta monetaria *muy rápidamente***

Durante la crisis financiera de 2008 cuando la economía estaba en una profunda recesión, el FED compró muchos bonos. Con esto las tasas de interés bajaron prácticamente a cero. Pero esto no fue suficiente: la economía estaba en una situación mala. Entonces el FED hizo algo muy fuera de norma a los bancos centrales. Aumentó el estimulo monetario con algo llamado **flexibilización cuantitativa** (quantitative easing Q.E). Esto es que el banco central compro activos a largo plazo a los bancos, como si fueran hipotecas.

La compra fue con "dinero falso" pues esta relajación cuantitativa generó hiperinflación, pues cuando se agrega mucho dinero falso a la economía **los precios pueden subir**. Miltron Friedman dijo "La inflación siempre y en todas partes, un fenómeno monetario"

- Se dejó guardado más de las reservas, pues las leyes de prestamos eran muy alto.
- Baja inflación en USA se debe a la reserva de dólares en Europa

## Implementing monetary policy

Federal Open Market Committe (FOMC, from *FED*) has discussed strategies to normalizing the conduct of monetary policy. There is two *institutional frameworks* to implementing monetary policy, ie, the **money supply**: (1) corridor-type system and (2) floor type-system.

These frameworks use same tools but in a different way and procedures to influence conditions in money market. Principal tools are interest rates.

**A. Interest rates**

When we talk about interest rates, we can see to agents in the money market, that perceive in a different way the interests rates (**mark up**):

1. Lenders: who benefit from discount rates because they receive them when a creditor asks them for credit.
2.  Creditors: who benefit from the reserve rates, as they receive them when they deposit their money in the bank's reserves.

**Interest rates from the Central Bank perspective**
We frequently see this dynamic in the relationship that individuals establish with commercial banks. Now, there is a "bank of banks" that coordinates this relationship in the money market: the Central Bank.

**B. Steps to implement monetary policy**

*What is the procedure to achieve monetary policy implementation, i.e. to influence money market conditions?*

**Step 1**. The monetary authority choose a **target for the federal funds rate**, which is **average of market determined interest rate**[^tpm] at which **banks and certain other institutions lend funds to each other** (**interbank leading rate**) on an overnight basis. [^chile-bc]


[^chile-bc]: In Chile, at 9 AM.

**Step 2.**  Central Banks define two interest rates:

  1.  **Discount rate**: money that is *charged* to private banks if they want to ask to borrow money from the Central Bank.
  *Central Bank as lender*
  2.  **Interest-on-reserves**: money that the Central Bank *pays* to private banks for keeping their money in the reserve fund for one night.
  *Central Bank as a creditors*.

![](img/summary02.jpg)
Figure 1. Interest rates in money market

**Step 3.** Demand and supply

#### Demand for Reserve Balances

Case A: *A normal day of a bank A, when reserve balances tend to zero.*

Let us imagine an extreme case where at the end of the day *Bank A* does not have enough money to pay its customers with liquid money. This *Bank A* will have two options: (1) ask the Central Bank or (2) ask Bank B, C or D.

What *Bank A* would have to pay to the Central Bank to receive this money is the **discount rate**. But *Bank B, C and D* will compete with that rate, offering a lower rate to *Bank A*. That is why the **discount rate** is said to be the *"ceiling "* of credit interest.

Figure 2 shows the demand curve of reserve. The main idea is the **inelastic** region when banks meet their reserve requirement because in this point reserve demand is **insensitive to changes un intereset rate**, and is more dertermined by *banks* resire to make payments (case B)

![](img/summary01.jpg)
Figure 2. Demand curve reserve

Case B: *A normal day of a Bank B, when the reserve balances tend to infinity*

Now, let us imagine that a *Bank B* ends its day with a surplus in its reserve balances. This Bank B, in order to generate more money, could keep its money at the Central Bank (overnight, and that is why it is called overnight) to receive interest on that money. That is the **interest-on -reserves**.

Now, as in the previous case, *Bank B* could go to the money market and see that *Bank A* is willing to pay a higher rate than the one offered by the Central Bank to reserve that money. That is why it is said that the **interest-on -reserves** is the floor or *minimum rate* paid for the reserves or savings in monetary market.

Again, in Figure 2 we can see the demand curve flattens out into a **elastic region** where the demand is much more sensitive to changes in interest rates. Banks have sufficient balances (as Bank B) and there are **perfectly liquid**, with interest bearing. At least, Bank B could eran the interest reserve rate (only if deposited at the Central Bank).

#### Supply of Reserve Balances

Central Bank objetives are:

1. **Financial stability**: aims to achieve through interest rates (1) and (2), which on average generate an interbank rate at which banks lend money to each other. It also works on the basis of reserve requirements (to avoid bank runs).

2. **Maintain inflation levels**: at the lowest possible level, achieved by interest rates and open market operations (buying securities to increase balances or selling securities to decrease balances). Lower discount rates will increase the circulating assets, which will make possible a higher consumption and demand for goods. Then, the prices of goods will rise and inflation will increase.

With **demand** and **supply** surve we can clearly see why Central Bank define upper and lower limits in interest rate to control money market.

**¡Atention!** Remember that the Central Bank does not have the possibility of controlling the demand for money, but rather what it does is to create instruments within the money supply to adjust this demand for money and in this way, be able to fulfill its main objectives as monetary authority.


**C. Frameworks**

|  | **Corridor system** | **Floor system |
|---|---|---|
| Types of interest | 1. Discount rate <br> 2. Interest on reserves | 1. Interest on reserves |
| Role of discount rate | Defines the maximum amount that banks can earn from lending money | There is no concern about the ceiling because everyone is very willing to lend money. It's more importat floor |
| Role of interest-on-reserves | Because they are lower than the market interest rate, its role is limited to ensuring a minimum level of interest in making reservations (and the reserve requierement in order to law) | Banks can earn the market rate of interest on all their reserve balances |
| Target rate position | Often in the middle of interests rates | In the interest-on-reserves rate |
| Market characteristics | 1. Can use open market operation <br> 2. They have incentive to invest time to economize quantity of balances | 1. Banks with larger quantity of reserve are perfectly safe. <br> 2. Some literature indicates floor system's are used in recession context|
| | ![](img/corridor.jpg) | ![](img/floor.jpg)




## Friedman: Monetary policiy

Economic policy goals: high employment, stable prices and rapid growth. Instruments of economic policy are: fiscal policy and monetary policy. In economics is a wide discussion about the rol of both, but **monetary policy** shows a "apparently" more consensus about it limitated potential. Friedman discuss this ideas

A lo largo de la disciplina se han desarrollado tres perspectivas respecto del rol de la política monetaria

### La política monetaria para la estabilidad de precios

- **Política monetaria sin efecto alguno en la economía**: Hasta la Gran Depresión, gran parte de los economistas planteaban que las nuevas tecnologías de la política monetaria eran tan importantes que eran capaces de controlar los ciclos económicos. Con la crisis del 1929, se planteó que la política monetaria incluso podría no afectar a las tasas de inflación.

- Rol: promote price stability and to preserve the gold standard.
- Chief criteria of monetary policy wew the state of "speculation" and the movement of gold

### La política monetaria para la estabilidad en los precios y el empleo

- **Política monetaria con efecto restringido**: Keynes, uno de sus principales exponentes, plantea que monetary operations involve simply substituting money for other assets without chainging total wealth (**distribution hypothesis**)
  - Liquidity preference is absolute, interest rates cannot be lowered by monetary measures
  -  Fiscal policy is a better aproximation (tax reductions, etc.)

-  *Keynesianism* indicates that monetary policy affect aggregates demand, but not the interest rate.
  -  In a world of flexible prices, a position of equilibrium at full employment might not exist. Unemployment had again to be explained by rigidities or **imperfections**, *not as the natural of a fully operative market process*.

- Monetary policy is an assistant to governemnt spending: helps to maintining high level of aggreate demand.

- Rol:
- Chief crteria of monetary policy: promotion of full employment, with the prevention of inflation (but secondary)

### La política monetaria y la oferta de dinero

This views are very similar. First don't take the importat role of this [^friedman1], and the second assigng to monetary policy a larger role than it can perform. Both are **danger** because they ask it to accomplish *task* and *contribution* that monetary policy cannot achieve.

[^friedman1]: Milton Friedman indicates Keynes subestimate the the aggresive monetary policy that take place during the Great Contraction (since 1929-1933), despite the contraction consequences. For example, they indicates "promotion of full employment" by prevention of inflation, but money market conditions seems to be secondary. Althought, there was a revival of the importance of monetary policy, and Friedman shows two main causes: 1. *Central Bank fails in its main objetive*: Federal Reserve System permitted a sharp reduction in monetary base ($H$), failing to provide liquidity to banking system. 2. *Desillusionment with fiscal policy*, with its potential to aggregate demand. Expenditures turned out to respond slow and with long lags to attempts to adjust them to the course of economic activity.


#### Monetary policy cannot do

**1. Pegging of Interest rates** (*for more than very limited periods*)

- ***Misunderstood of the relation between money and interest rates***: during wartime and postware, FED keep interest rates down **buying securities**, and as a consequence it increase the **quantity of reserves** avaible to banks, hence the **amount of bank credit**, and, ultimately the **total quantity of money**. The main idea was to increase money to lower interest rates. But this process is **initial** :

  1. Throught the impact of rapid rate of monetary rate to **investment of lower interest rates *will stimulated spending***.
  2. One man's spending is an other man's income, and rising income will rise liquidity preference and demand for loans;
  3. Raising prices, which **would reduce the real quantity of money**.

- *Misunderstood **cyclical adjustment of interest rates***: is highly likely to raise interest rates temporarily beyond inicial level.

- ***Effect of individual price expectation on interest rates***: higher rate of monetary expansion will correspond to a higher *not lower*, level of interest rates than would otherwise have prevailed. It can occurs when people expect thst prices will continue to rise.  High and rising nominal interest have been associated with rapid growth in money (Chile, Brazil 1960)

- ***Temporal Significance on levels of interest rates***: low interest rates are sign that monetary *has been tight*, and high interest rates are sign monetary policy *has been easy*. An importan conclusion is interest rates are  misleading indicator of other monetary policy, that we need to consider widely to understand possible pradoxical cases.

**2. Pegging the rate of unemployment** (*for more than very limited periods*)

**Monetary authority cannot adopt a target for employment or unemployment**: despite when *monetary growth is widely held, will tend to stimulated employment*, the reason is the inmediate and delayed consequences of such policies are different than interest rates.

  **1. Nominal and real rates**

**Difference in interest rates and employment**

  Interest rates: monetary authority can make the market rate less than the "natural" rate only by *inflation*. It is requiered when the rise of norminal rates need a more rapid inflation to hold down the market rate.

  **Employment rates**: there is some level of unemployment which has the property that is consistent with the equilibrium structure of real wages (**exogenous to the money market**). Real wages tend to a **average** at nominal or secular rate[^personal1].

  - A lower level of unemployment indicates a excess demand for labor, that will produce pressure to real wages rates. On other hand, higher levels of unemployment indicates excess of supply, that downward real wages (*Phillips Curve*).

  - "Natural" unemployment rate depends on structure of labor and commodity markets, including market imperfections, stochastic variabilities.

  - The factor determined by money supply is nominal wages, that must rise at the rate simply to keep real wages unchaged. But, **the demand and supply of labor is not the same of level of wages, rather is a consequence in a rise or downward in nominal wages.**

**Effect of monetary policy in employment**

- Monetary illusion: First, making nominal cash balances higher, stimulated spending. Here, still have the "natural" employment rate.
- Second, people expect prices to be stable and therefore increase their level of consumption. Firms react to the initial expansion in aggregate demand by increasing output, employees working longer hours and increase employment, *by taking jobs now ofered at former nominal wages*.
- Third, unemployment increase.  The fall *ex psot* in real wages to employers and the rise *ex ante* in real wages to employees is what enable employment to increase. Selling prices of products typically respond to an unanticipaed rise in **norminal demand faster than prices of factors of production**, real wages received have gone down.

**Temporary trade-off**

Is there a **temporary-trade off** between inflation and unemployment ("rising"); there is no "permanent trade-off" ("high").
- In interest rate we can use controls to peg nominal quantitys (nominal by nominal), such exchange rates, price levels, national incomes, quantity of money.
- In employment we cannot use nominal control. It's no possible to peg real quantities by nominal  quantities, we don't know de "change of the trade-off".

[^personal1]: We talk about wage distribution, no "level of wage"

#### What monetary policy can do

Despite cannot peg real magnitudes, there is an important **effect over these magnitudes**. To growth economy, as money es *ominipresent*, monetary policy can **adjust** $\Longrightarrow$ "avoid major mistakes", ie, prevnt money being a *major source* of economic *disturbance*. Monetary authority can solve problems even when there hasn't been intervetion by monetary policy.

**Monetary authority tasks**

 1. **Stability in financial and bank system:**
 - Suggest improvement in monetary tools that will reduce chances that it will get out of order
 - Use own powers to keep supply money working

  2. **Provide trust and certain**
  - Stable background for the economy, in flow balace of payments (reserves and inflation)
  - Certain to consumers, employers and employees ("know the future") keep in health economy

    **Problems**

    **Unflexible normatives**
    - In prices and wages, thus cannot adjust to dinamic changes and technology.
    - Normative rules can change absolute levels of prices but are not economic tools

    **Relationship with goverment**
    - Central Banks will be impersonal and delibertaed, to do automatic process when is needed.

  **3. Contribute to offsetting major**
    - Disturbances in economic system (postwar, COVID, etc) can contains with money supply. But the first task to monetary authority is **protect inflationary***. This can helps goverment, deficit in balance of payment flows *without sterilizing*.
    - Also, monetary policy in offsetting other (non-economic) forces is **limited**
    - Central Banks can do policy when they offer a *clear* and *present* danger to the economy.

#### Conducted monetary policy

There is two major requirements

1. Tools and magnitud can **control**
  - Control: exchanges rates. price level by index, qunatity of monetary total (deposits, commercual banks reserve)
  - No control: interest rates and unemployment
2. Avoid sharp swings in policy
  - "Too late" and "too much". The reason for propensity to overreact is *decision by today conditions* have a **lag** of *effect*.
  - Remember Central Bank task is give us **trust** in economy by **certain**: is more important a **kwown rate** or **fixed rate** that would on the average produce moderate inflation.
  - Give *thruth springs of economic growth* (enterprise, ingenuity, invention) a favorable climate to effective operations.




----

Important question: what is monetary policy and what cannot do.
Friedman indicates how monetary policy in this period, affects **aggregate demand**.

-¿Cheap money policies?
- Simple minded Keynes ideas

## Discusiones

## Friedman

El rol de la política monetaria versus la política fiscal. ¿Es el rol de la política monetaria solo mantener las tasas de interés bajas? ¿Es solo realmente un "instrumento"?

La discusión sobre el rol ha sido pedular, según Friedman. Pese a que tienen muchas diferencias, **la potencia** atribuida sobre la política monetaria va a variar.

## Implementación PM

Institucionalmente, cuáles son los mecanismos institucionales que hacen que funcione la oferta de dinero.

En general, en los mercados financieros de forma más pronunciada que en otros mercados, hay una brecha que perciben los agentes de manera distinta. Ese es el markup: tasa de interés de los prestamistas y de los acreedores.

- Tasas de reservas: de acredores

- Tasas de descuentos: prestamistas.

¿Cómo funciona el procedimiento?

A las 9 de la mañana, el Banco Central le hace prestamo a bancos privados. Y por ese prestamo se hace por una ***tasa de descuento*** (o tasa de prestamo interbancario). Y esta es la tasa de interés es la máxima que se puede cobrar en el mercado. ¿Por qué es el techo?

Pues si el Banco Central te presta al 3%, y si alguien te dice 4% vas al Banco Central.

Luego está el Banco Central como acreedor (o FDE) le da plata a los bancos, como interés, *por las reservas que tienen en el banco central*. En la mayoría de los paises capitalistas modernos, tiene que haber una reserva para evitar corridas. Y este es el piso. Imaginemos que tienes plata y quieres depositar la plata. Pero el Banco Central te da poco (tasa de reservas) es el piso.

**2. Formas de implementar la política monetaria**

- Corridor: se fija piso y techo, y se trabaja con operaciones de mercado abierto.

- Floor: se fija la tasa de interés sobre las reservas y lo que intentas estar pegada al piso.
