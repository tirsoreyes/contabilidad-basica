# Unidad 5 — Catálogo de cuentas

Guía privada del docente. Cuarto sábado, 180 minutos: catálogo y práctica integradora. Cuadernillo: `alumnos/05_catalogo_ejercicios.docx`. La quinta semana queda reservada para la evaluación que se acuerde; este caso es práctica con acompañamiento, no un examen.

## Qué necesitas comprender

Un **catálogo de cuentas** es una lista ordenada y codificada de las cuentas que una entidad utilizará. Establece nombres y una estructura compartida. Si una persona registra «Banco», otra «Cuenta bancaria» y otra «Dinero en banco» para el mismo concepto sin reglas comunes, después será difícil reunir la información.

Para ti puede parecerse a un diccionario de datos con identificadores, jerarquía y definiciones. Para los alumnos, usa una comparación con organizar productos por categorías: el código ayuda a localizarlos y agruparlos, pero necesita un significado claro. No es necesario conocer programación.

El catálogo no es una lista de operaciones ni un balance. La cuenta Bancos puede existir aunque su saldo sea cero. El saldo cambia al registrar; el código identifica la cuenta. Tampoco hay un único catálogo interno idéntico para todos los negocios. Debe responder al giro, al tamaño y a la información requerida. Los códigos de este material son didácticos, no códigos oficiales del SAT.

## Cobertura y objetivo

Se cubren 5.1 concepto y 5.2 diseño del catálogo. Al finalizar deben construir un catálogo pequeño coherente, distinguir cuentas agrupadoras de cuentas de registro y usarlo en operaciones conocidas. La práctica final recupera cuenta, naturaleza, partida doble, T, saldos y balance.

## Un diseño sencillo que puedes explicar

Primero define lo que necesitas saber: cuánto dinero hay, cuánto inventario, qué equipo se usa, a quién se debe y cuánto aportó la dueña. Después crea grupos, elige nombres, asigna códigos y escribe qué incluye cada cuenta. Comprueba el catálogo con operaciones de ejemplo antes de añadir más cuentas.

Usaremos tres niveles, separados por puntos para leerlos fácilmente:

- Primer nivel: `1` Activo, `2` Pasivo, `3` Capital contable.
- Segundo nivel: `1.1` Activo circulante, `1.2` Activo no circulante, `2.1` Pasivo de corto plazo, `2.2` Pasivo de largo plazo, `3.1` Capital aportado como grupo.
- Tercer nivel: cuentas donde se registra, por ejemplo `1.1.02` Bancos.

Los grupos suman información de sus cuentas; no registramos el mismo importe tanto en el grupo como en la cuenta. Si se cargan $5,000 a Bancos y otros $5,000 a Activo por la misma entrada, se duplica el registro. En este diseño se registra únicamente en el nivel final.

## Catálogo modelo para la papelería

| Código | Cuenta de registro | Naturaleza normal | Qué incluye |
|---|---|---|---|
| 1.1.01 | Caja | Deudora | Efectivo físico del negocio |
| 1.1.02 | Bancos | Deudora | Depósitos disponibles del negocio |
| 1.1.03 | Mercancías | Deudora | Artículos adquiridos para vender |
| 1.1.04 | Clientes | Deudora | Cobros por ventas a crédito del giro |
| 1.2.01 | Mobiliario | Deudora | Muebles utilizados por el negocio |
| 1.2.02 | Equipo de cómputo | Deudora | Computadoras para uso del negocio |
| 2.1.01 | Proveedores | Acreedora | Deudas de corto plazo por mercancía |
| 2.1.02 | Acreedores diversos | Acreedora | Otras deudas de corto plazo de nuestros casos |
| 2.1.03 | Préstamos bancarios a corto plazo | Acreedora | Principal bancario exigible en el corto plazo |
| 2.2.01 | Préstamos bancarios a largo plazo | Acreedora | Parte del principal clasificada a largo plazo |
| 3.1.01 | Aportaciones de la propietaria | Acreedora | Recursos aportados por Ana como capital |

«Capital aportado» en unidades anteriores corresponde a la cuenta de registro «Aportaciones de la propietaria» de este catálogo. Se explicita la correspondencia para no crear dos cuentas para el mismo hecho. «Mercancías» y «Inventario de mercancías» también podrían ser nombres válidos, pero dentro de un catálogo debes elegir uno y mantenerlo.

Clientes aparece para reconocer su lugar, aunque el caso integrador no incluye ventas. Para una contabilidad real se necesitan también cuentas de resultados, impuestos y otras según las operaciones. El catálogo presentado es suficiente para estos casos de apertura, no es una plantilla completa lista para cumplir obligaciones fiscales.

## Reglas prácticas de diseño

1. Un código identifica una sola cuenta dentro del catálogo; no debe repetirse con significados distintos.
2. Los nombres deben decir qué se registra. «Varios» sin definición suele ocultar mezclas.
3. El detalle responde a una necesidad: pueden añadirse auxiliares por banco, cliente o proveedor si se necesita seguimiento individual.
4. Deja posibilidad de crecimiento sin renumerar todo. Escribir códigos como texto conserva su estructura.
5. Aclara qué nivel permite registros. En nuestro caso, solo el tercer nivel.
6. Escribe una definición breve y ejemplos de cuándo aumenta y disminuye. Eso se acerca a una guía o manual de cuentas, que complementa el catálogo.

Para un negocio con dos bancos se podrían abrir auxiliares bajo Bancos y registrar en ellos. Si se adopta esa ampliación, Bancos pasaría a agruparlos: no se duplica el registro entre cuenta y auxiliar. No hace falta implementar ese cuarto nivel hoy.

## Ejemplo guiado de uso

Operación independiente: compra mercancía a crédito por $3,500, pagadera en 30 días. Se usa cargo `1.1.03 Mercancías` $3,500 y abono `2.1.01 Proveedores` $3,500. El código no decide el cargo: primero identificamos activo que aumenta y pasivo que aumenta. Después buscamos los identificadores correspondientes.

Si después se paga $1,000 por transferencia, se carga `2.1.01 Proveedores` $1,000 y se abona `1.1.02 Bancos` $1,000. No se crea una cuenta «Pago a proveedor de hoy»: es una operación de una cuenta ya existente. Proveedores conserva saldo acreedor $2,500 en esta secuencia; el saldo completo de Bancos depende de su situación previa.

## Secuencia de clase

| Minutos | Acción |
|---|---|
| 0–15 | Recordar resultados de la unidad 4; completar pendientes breves |
| 15–45 | Explicar catálogo, jerarquía y ejemplo guiado |
| 45–80 | Actividades A y B: diseñar y depurar catálogo |
| 80–90 | Descanso |
| 90–145 | Caso integrador C en parejas |
| 145–170 | Comparar resultados y explicar decisiones |
| 170–180 | Dudas y recordar el acuerdo de evaluación |

Si el ritmo es lento, entrega el catálogo modelo para el caso C y conserva el diseño propio como práctica posterior. Si el grupo avanza rápido, pide justificar auxiliares para dos proveedores o investigar un error que conserve las sumas. No añadas ventas con impuestos en los últimos minutos.

## Actividades A y B con respuestas

**A. Diseña un catálogo mínimo.** Debe incluir Caja, Bancos, Mercancías, Equipo de cómputo, Proveedores y Aportaciones de la propietaria. Pide código, nombre, grupo y naturaleza. Una respuesta válida usa `1.1.01`, `1.1.02`, `1.1.03`, `1.2.02`, `2.1.01` y `3.1.01` del modelo. También son válidas otras codificaciones coherentes; no evalúes coincidencia exacta de números como si fuera una ley.

**B. Corrige un catálogo defectuoso.** Se dan: `1.1.01 Caja`, `1.1.01 Bancos`, `1.1.03 Dinero`, `2.1.01 Proveedores`, `2.1.02 Deudas por mercancía` y `3.1.01 Ventas`.

Solución razonada: eliminar código duplicado asignando Bancos `1.1.02`; quitar o definir «Dinero» porque mezcla Caja y Bancos; evitar duplicar Proveedores y Deudas por mercancía para la misma función; retirar Ventas del grupo Capital, pues es una cuenta de ingresos, y usar allí Aportaciones de la propietaria. No se exige diseñar las cuentas de resultados: basta reconocer el problema. Eliminar una categoría en este ejercicio de diseño no equivale a borrar historia en un sistema real.

## Caso C integrador y solucionario

Escenario independiente desde cero. Papelería Horizonte realiza seis operaciones sin impuestos, intereses ni ajustes. La deuda por mercancía y la de equipo vencen en 30 días.

1. Ana aporta $30,000 al banco del negocio.
2. Compra mercancía por $12,000; paga $7,000 por banco y debe $5,000 al proveedor.
3. Compra equipo de cómputo para uso del negocio por $6,000 a crédito, sin pagaré.
4. Paga $2,000 al proveedor de mercancía por banco.
5. Traslada $1,000 del banco a la caja del negocio.
6. Paga $1,500 de la deuda del equipo por banco.

Pide usar o completar su catálogo, registrar el diario con códigos, pasar a T, obtener saldos y preparar un balance sencillo. Antes del paso 3, verifica que hayan incorporado Acreedores diversos: el catálogo mínimo A no bastaba para este caso.

| Op. | Código y cuenta cargada | Código y cuenta abonada |
|---|---|---|
| 1 | 1.1.02 Bancos 30,000 | 3.1.01 Aportaciones de la propietaria 30,000 |
| 2 | 1.1.03 Mercancías 12,000 | 1.1.02 Bancos 7,000; 2.1.01 Proveedores 5,000 |
| 3 | 1.2.02 Equipo de cómputo 6,000 | 2.1.02 Acreedores diversos 6,000 |
| 4 | 2.1.01 Proveedores 2,000 | 1.1.02 Bancos 2,000 |
| 5 | 1.1.01 Caja 1,000 | 1.1.02 Bancos 1,000 |
| 6 | 2.1.02 Acreedores diversos 1,500 | 1.1.02 Bancos 1,500 |

Total del diario por lado: $52,500. Verifica la operación 2: cargo $12,000 = abonos $7,000 + $5,000. No son dos compras.

| Cuenta | Referencias en el debe | Referencias en el haber | Saldo |
|---|---|---|---|
| Caja | (5) 1,000 | Ninguna | 1,000 deudor |
| Bancos | (1) 30,000 | (2) 7,000; (4) 2,000; (5) 1,000; (6) 1,500 | 18,500 deudor |
| Mercancías | (2) 12,000 | Ninguna | 12,000 deudor |
| Equipo de cómputo | (3) 6,000 | Ninguna | 6,000 deudor |
| Proveedores | (4) 2,000 | (2) 5,000 | 3,000 acreedor |
| Acreedores diversos | (6) 1,500 | (3) 6,000 | 4,500 acreedor |
| Aportaciones de la propietaria | Ninguna | (1) 30,000 | 30,000 acreedor |

Esta tabla permite comprobar cada T del alumno. Movimientos deudores y acreedores totales: $52,500 por lado. Saldos deudores y acreedores totales: $37,500 por lado.

**Balance al cierre del caso C, en MXN.** Activo circulante: Caja $1,000 + Bancos $18,500 + Mercancías $12,000 = $31,500. Activo no circulante: Equipo de cómputo $6,000. Activo total $37,500. Pasivo a corto plazo: Proveedores $3,000 + Acreedores diversos $4,500 = $7,500. Capital: Aportaciones de la propietaria $30,000. Total pasivo más capital $37,500.

Respuestas de interpretación: dinero disponible $19,500; deuda total $7,500; el equipo se usa en el negocio y no se compró para revender; mover dinero a Caja no genera ingreso; pagar una deuda reduce pasivo y activo; no se puede llamar utilidad al saldo bancario ni a la aportación. Una compra a crédito registrada como pagada podría cuadrar pero describir mal la situación.

## Computadora y alternativa sin equipo

Plan A: tabla de catálogo con columnas Código, Nombre, Grupo y Naturaleza; configurar Código como texto. Otra tabla para los asientos con operación, código, cuenta, cargo y abono. Las T y la balanza pueden hacerse con sumas sencillas. Si los códigos cambian al copiar, revisa el formato de las celdas.

Plan B: completar catálogo en el cuadernillo, diario en sus filas y T en las páginas de trabajo o cuaderno. Las cuentas y operaciones son las mismas. Si solo hay un equipo por pareja, la persona que no captura verifica los registros en papel; cambian después de la operación 3.

## Revisión para aprender y cierre del curso

Revisa sin asignar porcentajes: que el catálogo no tenga códigos duplicados; que las cuentas estén bien clasificadas; que cada asiento cuadre y refleje el hecho; que las T mantengan referencias; que el balance use saldos; y que cada alumno pueda explicar una operación. Esta lista sirve para dar retroalimentación y no constituye una rúbrica formal.

Pregunta al terminar: «Si mañana la papelería abre otra cuenta bancaria, ¿qué cambiarías en el catálogo y por qué?». Una respuesta suficiente propone distinguir bancos mediante auxiliares y conservar agrupación coherente. No se requiere dominar un sistema contable comercial.

La modalidad de evaluación y los porcentajes siguen pendientes del acuerdo en clase. No presentes este caso como examen ni prometas que será idéntico a la evaluación. Guarda las preguntas que aún tengan para decidir qué recuperar antes de evaluar en la quinta semana.
