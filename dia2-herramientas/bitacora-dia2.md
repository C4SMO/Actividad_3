# Bitácora · Día 2 · Herramientas de desarrollo

- **santiago:**
- **18/10/2026**
- **johan Alexander Rivera Vasquez**

---

## 1. Mi entorno de desarrollo (Etapa 1)

- Versión de Ubuntu:
- Versión de Python:
- ¿Dónde está instalado Python? (resultado de `which python3`):/usr/bin/python3

- Con mis palabras, la diferencia entre un compilador y un intérprete es: en como interactuan y resuleven la instruccion, el compilador traduce todo de golpe mientras que el interprete lo hace linea por linea.

- ¿Qué pasó con la línea 4 de `hola.py` y por qué?: debido a que mensaje secreto no esta definido  por eso el sistema no sabe que hacer con el.
y suspende su ejecucion.
| Herramienta | ¿Qué es? (sistema operativo, editor, intérprete, compilador o navegador) |
|---|---|
| Ubuntu |sistema operativo |
| VS Code |editor |
| Python |interprete |
| Chrome |navegador |
| gcc |compilador |

## 2. Reinstalación de VS Code (Etapa 2)

- ¿Cómo estaba instalado VS Code? (snap, .deb o no estaba):Estaba instalado por medio de un archivo.dep

- Comando que usé para desinstalarlo:sudo apt remove code

- Comando que usé para instalarlo:sudo apt install ./code_*.deb

- ¿Por qué es importante instalar desde la fuente oficial?:es importante instalar dede la fuente oficial por motivos de seguridad instalarlo desde otras fuentes puede dar la posibilidad de instalr codigo malicioso

- ¿Qué pasó con mi configuración al desinstalar? ¿Dónde vive?:mi configuracion se mantuvo porque no pertenecia a los archivo base del VS code, el visual se mantiene en /usr/bin/code mientra que la configuracion personal se guarda en /home/cohorte8/.config/code

## 3. Perfiles y extensiones (Etapa 3)

- Con mis palabras, un perfil de VS Code es: Es una configuracion que organiza configuraciones que establece el usuario
- ¿Qué cambia en el Explorador entre un perfil y otro?: las imagnes de los directorios, el estilo es agradable a la vista
- ¿Por qué VS Code pregunta si confío en el publicador de una extensión?: por que la extencion puede traer instrucciones dañinas se le esta dando permiso para hacer alteraciones al sistema

## 4. Duelo de perfiles (Etapa 4)

| Prueba | Perfil2-Basico | Perfil1-Pro |
|---|---|---|
| 1. Auto guardado | | |
| 2. Auto Rename Tag | | |
| 3. Error Lens | | |
| 4. Íconos | | |
| 5. Guías de indentación | | |
| 6. Extensiones corriendo | | |

**Reflexión**

1. ¿Noté diferencias en la experiencia de trabajo entre los dos perfiles? ¿Cuáles? 
   -El tamaño el diseño de los directorios la linea de tabulacion es mas voluminosa 
2. ¿Qué ventajas tiene usar múltiples perfiles en VS Code?
   -Permite secmentar herramientas y un perfil de trabajo
3. ¿Cómo influyen las extensiones en la productividad y en el rendimiento del editor?
   -El uso de extenciones es supremamente util pero se tiene que usar con moderacion porque el uso masivo de varias termina perjudicando el rendimiento y agregando funcionalidades y riesgos innesesarios 
4. ¿Cuándo sería útil usar perfiles distintos en un entorno profesional? (dos ejemplos)
   - cuando compartes el computador con otra persona o cuando tienes que trabajar con diferentes enfoques 

## 5. Inspección y modificación (Etapa 5)

- Página que usé:
- Cinco etiquetas que encontré y para qué sirven:
  1.html sostiene toda la estructura del documento 
  2.main supongo que es la que contiene como el funcinamiento base del sistema
  3.h1 titulo de la pagina
  4.li sostiene el texto 
  5.div supongo que maneja proporciones o tal vez segmenta bloques de texto
- ¿Qué pasó con mis cambios al recargar y por qué?:los cambios solo se presentan en mi pc esos cambios se dan por que son cabios temporales y locales cuando vuelvo a hacer la peticion a la pagina web mi pc me trae los datos originales
- Con mis palabras, el DOM es:es como una interfaz de programacion que viene en el navegador web

## 6. La consola (Etapa 6)

| Operación | Mi predicción | Resultado real |
|---|---|---|
| `2 + 3` |5 | |
| `10 - 4 * 2` |2 | |
| `(10 - 4) * 2` |12 | |
| `10 / 4` |2.5 | |
| `10 % 3` |1 | |
| `2 ** 8` |256 | |
| `120000 * 0.19` |22800 | |
| `365 * 24` |8760 | |

- ¿Por qué `0.1 + 0.2` no da exactamente `0.3`?:
- Errores o advertencias que encontré en la página (o "ninguno"):
- Diferencia entre un error y una advertencia:

## 7. La red / Network (Etapa 7)

| Imagen | Formato | Tamaño | Tiempo | Código de estado |
|---|---|---|---|---|
|120px-Metro_de Medellin |jpeg |5,67|72mb|200 |
|250px-Pueblito-Paisa |jpeg |18,22|74mb|200 |
|250px-Carre_edifice |jpeg |18,22|74mb |200 |

| Experimento | Solicitudes | Transferido | Load |
|---|---|---|---|
| A. Sin caché |html |219,93 kB |1,34MB |72
| B. Con caché |html |en cache |1,34MB | 0
| C. Red lenta |html |219,93 kB |1,34MB |127

- Archivo más pesado de la página y su tipo: es un archivo tipo html 
- ¿Por qué la página cargó más rápido con caché?: por que ya tenia guardado datos que nesesitaba
- ¿Por qué un desarrollador querría probar con una red lenta?: para evaluar el desempeño en esa condicion
- ¿Qué haría para que una imagen pesada cargue más rápido?: supongo que buscar una mejor red a demas de disminuir su peso
## 8. Dispositivos móviles (Etapa 8)

| Ancho (px) | Dispositivo | ¿Cambia el menú? | ¿Imágenes bien? | ¿Scroll horizontal? | Observación |
|---|---|---|---|---|---|
| 320 | |no |si |no |todo se ve pequeño |
| 375 | |no |si |no |aumento un poco el tamaño de las imagenes |
| 768 | |no |si |no |sin cambio aparente |
| 1024 | |no |si |no |sin cambio significativo |
| 1440 | |no |no |si |el meno no cambio pero ya es incomodo andar en la pagina |

- ¿Por qué es importante probar varias resoluciones antes de entregar un proyecto?: permite visulizar desde la perspectiva de usurio y de los diferentes dispositivos

## 9. Laboratorio de errores (Etapa 9)

| # | Tipo | ¿Dónde lo detecté? | Mensaje o síntoma | Causa | Solución aplicada |
|---|---|---|---|---|---|
| 1 |404 |pestaña red |pagina sin colores |error con la ruta |renombre el archivo y lo movi |
| 2 TypeError |consola |bonton is null |el js buscaba btn-saludar pero era boton-saludar |cambie el nombre del boton |
| 3 |ReferenceError |consola al hacer clic |Reference error |nombreCoder pero se uso nombreCodr |corregi el nombre |
| 4 |Recuerso no encontrado |pestaña red |no encuentra el logo |la ruta .. no conincidia |movi el archivo a images|

- Uno de los errores, descrito con detalle, y cómo lo resolví:hubo un error en el texto en http cuando intentaba llmar a el usuario no lo encontraba debido a que en su momento no existia 
- ¿Qué vi al pausar con el breakpoint?:
- ¿Qué pasó al cambiar `visitas` por 99 y al borrarlo?:
- ¿Para qué usan el localStorage las páginas reales? ¿Qué NO debería guardar ahí?:
- Ancho exacto en el que se apilan las tarjetas y regla de CSS responsable:
- ¿Por qué no basta con mirar solo la consola para encontrar errores?:

## 10. Comparación con Firefox (Etapa 10)

| Herramienta | Chrome: nombre y atajo | Firefox: nombre y atajo | Diferencia que noté |
|---|---|---|---|
| Inspeccionar HTML y CSS |elements ctrl+shift i |inspector mismo comando |En Chrome casi todo está dentro de Elements. |
| Consola |Ctrl+Shift+J |Ctrl+Shift+K |Misma función. Firefox tiene filtros por Errores, |
| Red |pestaña dentro de DevTools |Ctrl+Shift+E |Los 404 se ven en rojo en ambos. |
| Simulación de dispositivos |Ctrl+Shift+M |Ctrl+Shift+M|En Firefox la simulación táctil es un botón aparte |
| Almacenamiento local |Application → Local storage |Almacenamiento → Almacenamiento |Misma idea con otro nombre |
| Mensaje del error que reintroduje |Cannot read properties of null |TypeError: boton is null |Como presentan el error |

- Una característica de Firefox interesante o diferente a Chrome (qué es, para qué sirve y cómo la probé):

## 11. Reflexión final (Etapa 11)

- La herramienta que más voy a usar y por qué:
- Lo más difícil del día y cómo lo resolví:
- Las DevTools explicadas para alguien que no programa (3 líneas):