# 📱 APK Studio — Tutorial completo

**Versión 7 · multipantalla**
Convierte una idea, un HTML o una web en una **app Android (.apk) real**, sin saber programar.

---

## Índice

1. [¿Qué es APK Studio?](#1-qué-es-apk-studio)
2. [Antes de empezar](#2-antes-de-empezar)
3. [Vista general: los 4 pasos](#3-vista-general-los-4-pasos)
4. [Paso 1 · Crear](#4-paso-1--crear)
5. [Paso 2 · Editar](#5-paso-2--editar)
6. [Paso 3 · Configurar](#6-paso-3--configurar)
7. [Paso 4 · Crear el APK](#7-paso-4--crear-el-apk)
8. [Instalar el APK en el móvil](#8-instalar-el-apk-en-el-móvil)
9. [Lo que pueden hacer las apps creadas](#9-lo-que-pueden-hacer-las-apps-creadas)
10. [Copias de seguridad y actualizaciones](#10-copias-de-seguridad-y-actualizaciones)
11. [Motor de IA](#11-motor-de-ia)
12. [Solución de problemas](#12-solución-de-problemas)
13. [Preguntas frecuentes](#13-preguntas-frecuentes)
14. [Ejemplo completo: app de XV años](#14-ejemplo-completo-app-de-xv-años)
15. [Contacto](#15-contacto)

---

## 1. ¿Qué es APK Studio?

APK Studio es **un solo archivo** (`apk-studio.html`) que se abre en el navegador (Chrome, Edge…) y permite:

| Puedes… | Cómo |
|---|---|
| 💡 Crear una app desde una **idea** | La IA la diseña por ti |
| 🧩 Empezar con una **plantilla** | 6 apps completas listas para personalizar |
| 📥 Convertir **tu propio HTML** | Un archivo `.html` o un `.zip` con tu web completa |
| 🌐 Convertir **una web publicada** | La app abre tu web con icono propio |
| 🎨 **Editar visualmente** | Tocas cualquier parte y la cambias |
| 📦 Obtener un **APK real** | Lo compila GitHub gratis y te da el enlace de descarga |

Todo se guarda **en tu navegador**. Nada se envía a ningún sitio, salvo a la IA que uses y a tu cuenta de GitHub cuando creas el APK.

---

## 2. Antes de empezar

### Lo que necesitas
- Un ordenador o móvil con **Chrome** o **Edge** actualizados (recomendado).
- Internet para la IA y para crear el APK. **Editar funciona sin internet.**
- Una **cuenta gratis de GitHub** (solo para crear el APK, ver el [paso 4](#7-paso-4--crear-el-apk)).

### ⚠️ Regla de oro: dónde vive tu proyecto
Tu proyecto se guarda **dentro del navegador, ligado a la ubicación exacta del archivo** `apk-studio.html`.

- Ábrelo siempre **con el mismo navegador** y **desde la misma carpeta**.
- Cuando recibas una versión nueva, **colócala en la misma carpeta y con el mismo nombre** que la anterior (renombra la vieja, por ejemplo `apk-studio-viejo.html`).
- **No borres los datos ni el historial del navegador** sin haber guardado antes una copia.
- Pulsa **💾 Guardar copia** con frecuencia (ver [sección 10](#10-copias-de-seguridad-y-actualizaciones)).

### Cómo saber qué versión tienes
Arriba a la derecha aparece una etiqueta verde, por ejemplo **«v7 · multipantalla»**.

---

## 3. Vista general: los 4 pasos

```
 ┌──────────┐   ┌──────────┐   ┌─────────────┐   ┌──────────────┐
 │ 1 CREAR  │ → │ 2 EDITAR │ → │ 3 CONFIGURAR│ → │ 4 CREAR APK  │
 │ idea /   │   │ visual,  │   │ nombre,     │   │ GitHub lo    │
 │ plantilla│   │ IA o     │   │ icono,      │   │ compila y te │
 │ / HTML   │   │ código   │   │ permisos    │   │ da el enlace │
 └──────────┘   └──────────┘   └─────────────┘   └──────────────┘
```

Puedes moverte entre pasos cuando quieras con la barra superior. En la parte de arriba siempre tienes:

- **💾 Guardar copia** — descarga una copia completa del proyecto.
- **📂 Abrir copia** — recupera un proyecto guardado.
- **💾 guardado hh:mm** — indica la última vez que se autoguardó.

---

## 4. Paso 1 · Crear

Hay **cinco formas** de empezar:

### 4.1 💡 Desde una idea (con IA)
1. Escribe tu idea como se la contarías a un amigo.
   > *«Una app para mi barbería con precios, galería de cortes, reservas por WhatsApp y horario.»*
2. O toca una **idea de ejemplo** (Tienda, Recetas, Quiz, Restaurante, Gimnasio, Tareas).
3. Elige (opcional): **tipo de app**, **estilo visual**, **color principal** y si debe **funcionar sin internet**.
4. Pulsa **✨ Crear mi app con IA**.
5. Verás el progreso en vivo (tiempo, caracteres recibidos y cada paso). Tarda entre **20 y 90 segundos**.
6. Al terminar se abre el editor automáticamente.

> La IA crea apps **con varias pantallas y menú inferior**, que luego puedes editar visualmente.

### 4.2 🧩 Empezar con una plantilla (recomendado)
Apps completas de **4 pantallas conectadas**, con diseño y botones ya configurados:

| Plantilla | Pantallas |
|---|---|
| 💗 **XV años / Evento** | Inicio (portada + cuenta regresiva) · Galería (fotos + álbum) · Agenda (itinerario + mapa) · Confirmar (formulario WhatsApp) |
| 🏪 **Negocio / tienda** | Inicio · Catálogo (productos con «Pedir») · Ofertas · Contacto |
| 🍽️ **Restaurante / cafetería** | Inicio · Menú · Reservas · Ubicación |
| 🎓 **Curso / clases** | Inicio · Lecciones (vídeos) · Material (PDF) · Dudas |
| 🎨 **Portafolio / fotógrafo** | Inicio · Trabajos · Sobre mí · Contacto |
| 📰 **Información / comunidad** | Inicio · Noticias · Recursos · Contacto |

Toca una plantilla y empieza a personalizarla.

### 4.3 📥 Ya tengo mi HTML
- **Arrastra** tu archivo `.html` a la zona punteada, o tócala para elegirlo.
- Si tu web usa **varios archivos** (CSS, JS, imágenes), comprímelos en un **`.zip`** y arrástralo: APK Studio encuentra el `index.html` y conserva todo.
- También puedes **pegar el código** y pulsar **Usar este código →**.

### 4.4 🌐 Convertir una web en app
Escribe la dirección (ej.: `https://www.mi-negocio.com`) y pulsa **Usar esta web →**.
La app abrirá tu web a pantalla completa, con tu icono. **Necesita internet.**

### 4.5 ✨ Ejemplos de 1 clic
Tienda, Recetas, Quiz, Restaurante y Rutinas: apps sencillas para probar.

---

## 5. Paso 2 · Editar

A la derecha siempre ves **el móvil de prueba** con tu app. Arriba del móvil:

| Botón | Para qué |
|---|---|
| **✋ Editar** | Tocas cualquier cosa de la app para cambiarla |
| **▶️ Probar** | Usas la app como si estuviera instalada (botones, menú, álbum…) |
| 🔄 | Recargar la vista |
| ⛶ | Abrir la app a pantalla completa en otra pestaña |

Hay tres formas de editar (pestañas superiores): **🎨 Diseño visual**, **🤖 Pedir a la IA** y **🧾 Código**.

### 5.1 🎨 Diseño visual

Tiene cinco sub‑pestañas:

#### ➕ Añadir — banco de elementos
Toca un elemento y se coloca **debajo de lo que tengas seleccionado** (o al final de la pantalla actual). Luego tócalo en el móvil para personalizarlo.

| Categoría | Elementos |
|---|---|
| **Básicos** | Título · Texto · Botón · Imagen · Separador · Espacio |
| **Secciones** | Portada · Tarjeta · Itinerario · Lista de precios · Frase/dedicatoria · Cabecera con «atrás» · Artículo · Preguntas frecuentes · Productos |
| **Fotos y vídeo** | Galería de fotos · **Álbum (fotos del móvil)** · Vídeo propio · Vídeo de YouTube · Carrusel de fotos · Lista de vídeos |
| **Interactivos** | Cuenta regresiva · Música de fondo · Efecto animado · Formulario → WhatsApp |
| **Contacto** | Botón WhatsApp · Botón llamar · Mapa · Redes sociales |
| **Botones y acciones** | Documentos PDF · Lista de botones · Menú de tarjetas · Botón «ver texto» · Botón «ver vídeo» · Botón «ver PDF» |

> Al añadir **Imagen**, **Galería**, **Carrusel**, **Vídeo** o **Música**, se abre directamente el selector para subir tu archivo.

#### 📄 Pantallas — apps con varias pantallas
- **Lista de pantallas**: la primera (⭐) es la de inicio.
  - **👁️** ver y editar esa pantalla en el móvil.
  - Cambiar **icono** (emoji) y **nombre** directamente en la lista.
  - **⬆️ ⬇️** ordenar · **⧉** duplicar · **🗑️** borrar.
- **➕ Nueva pantalla**: escribe un nombre y elige un modelo:
  En blanco · Galería · Vídeos · Documentos · Texto/artículo · Contacto · Botones y enlaces · Agenda.
- **Menú inferior**: barra fija abajo con todas las pantallas. **Se actualiza sola** al crear, renombrar o mover pantallas.
- Si tu app tenía una sola página, al crear la segunda **todo tu contenido pasa a «Inicio»** sin perderse.
- El **botón atrás del móvil** y los botones **«←»** vuelven a la pantalla anterior.

#### ✏️ Editar — propiedades de lo que tocas
Toca cualquier elemento en el móvil (modo ✋ Editar). Aparece resaltado en rosa y verás:

- **Migas** (arriba): saltar al bloque que lo contiene.
- **Contenido** (según el elemento):
  - **Texto**: escribe el nuevo texto (los saltos de línea se respetan).
  - **Imagen**: 📷 Cambiar foto · ajuste (rellenar / ver completa) · texto alternativo · ampliar al tocar.
  - **Vídeo**: 🎬 Elegir vídeo · reproducir solo · repetir.
  - **Galería**: miniaturas con ✕ para quitar · ➕ Añadir fotos · número de columnas.
  - **Álbum**: permitir fotos y vídeos, o solo fotos.
  - **Cuenta regresiva**: fecha y hora del evento.
  - **Música**: 🎵 Elegir canción · empezar al tocar la pantalla.
  - **Efecto animado**: tipo (corazones, estrellas, confeti, pétalos, mariposas, burbujas, nieve, notas, hojas, dinero) y cantidad.
  - **Mapa**: dirección.
  - **Vídeo de YouTube**: enlace.
  - **Formulario**: número de WhatsApp de destino.
- **👆 Acción al tocar** — ver [sección 5.2](#52--acción-al-tocar).
- **Estilo**: color de texto · fondo (color, degradado o 📷 foto) · tamaño de letra · negrita · cursiva · alineación · fuente · esquinas redondeadas · relleno · separación · ancho · transparencia · sombra.
- **Acciones**: ⬆️ Subir · ⬇️ Bajar · ⧉ Duplicar · 🗑️ Borrar · ➕ Añadir debajo.

#### 🌈 Ambiente — aspecto de toda la app
- **10 temas listos**: Quinceañera, Dorado, Lila sueño, Noche azul, Boda blanca, Natural, Neón, Infantil, Oscuro, Claro.
- **Fondo** de toda la app: colores, degradados o **una foto tuya**.
- **Color principal** (botones, títulos, elementos del banco).
- **Color del texto** y **letra** (Moderna, Elegante, Clásica, Manuscrita, Redondeada, Divertida, Impacto, Máquina).
- **Efecto animado** en toda la app.
- **↺ Quitar ambiente** para volver al diseño original.

> Si una sección mantiene su propio fondo, tócala y cámbialo en ✏️ Editar.

#### 🧱 Estructura
Lista ordenada de todas las partes de la app. Toca una para seleccionarla (aunque esté en otra pantalla) o muévela con ⬆️⬇️.

### 5.2 👆 Acción al tocar
**Cualquier** botón, tarjeta, imagen o texto puede hacer algo al tocarlo:

| Acción | Qué pide | Qué hace en la app |
|---|---|---|
| 📄 Ir a otra pantalla | Elegir pantalla (o **➕ crear y enlazar** una nueva) | Cambia de pantalla |
| 🔙 Volver atrás | — | Vuelve a la pantalla anterior |
| ▶️ Vídeo de YouTube | Enlace del vídeo | Abre la app de YouTube |
| 📺 YouTube dentro de la app | Enlace del vídeo | Lo reproduce en una ventana |
| 🎬 Ver mi vídeo | Subir vídeo | Lo reproduce a pantalla completa |
| 📄 Ver documento PDF | Subir PDF + título | Muestra el PDF página a página, con zoom y compartir |
| 📖 Mostrar un texto | Título + texto | Abre una ventana con el texto (se puede compartir) |
| 🖼️ Ver una imagen | Subir imagen | La muestra en grande |
| 🎵 Reproducir audio | Subir audio | Reproduce / pausa |
| 🌐 Abrir página web | Dirección | Abre el navegador |
| 💬 WhatsApp | Número + mensaje | Abre el chat con el mensaje escrito |
| 📞 Llamar | Teléfono | Abre el marcador |
| ✉️ Correo / 📱 SMS | Dirección / teléfono | Abre la app correspondiente |
| 📤 Compartir | Texto | Abre el menú de compartir del móvil |

> Si tocas un texto **dentro** de una tarjeta con acción, el editor te muestra la acción de la tarjeta («de … que lo contiene»).
> Para comprobar la acción, pulsa **▶️ Probar** y tócala.

**Sobre los PDF:** al subirlos, APK Studio convierte sus páginas en imágenes (hasta 60 páginas) para que se vean **sin internet**. Si en ese momento no hay conexión, el PDF se guarda igual y en la app **se abrirá con otra aplicación** del móvil.

### 5.3 🤖 Pedir a la IA
Escribe un cambio con tus palabras y pulsa **✨ Aplicar cambio**:
> *«Cambia el color a verde y añade una sección de horarios.»*

Atajos: 🎨 Más bonito · 🌙 Modo oscuro · 🚀 Bienvenida · 🔧 Corregir errores.
Para textos, colores y fotos es más rápido el diseño visual; usa la IA para **cambios grandes**.

### 5.4 🧾 Código
Para usuarios avanzados: el HTML completo de la app y la lista de archivos (fotos, vídeos, PDF).

### 5.5 🕘 Historial y deshacer
Cada cambio se guarda en el **historial**. Pulsa **↩️ Deshacer** o toca una versión anterior para recuperarla.

### 5.6 Peso de los archivos
- Las **fotos se reducen solas** (máx. 1600 px) para que la app no pese de más.
- Vídeos: máximo **90 MB**; recomendado **menos de 20 MB**.
- PDF: máximo **40 MB**.
- Las fotos y vídeos que borres de la app **no se incluyen** en el APK.

---

## 6. Paso 3 · Configurar

### 📛 Identidad
- **Nombre**: el que aparece bajo el icono (máx. 30 caracteres).
- **Identificador único (paquete)**: se crea solo a partir del nombre.
  - Formato: `com.tunombre.nombreapp` — solo **minúsculas sin acentos, números y _**, separadas por puntos.
  - ✅ `com.raulcordero.recetas` · ❌ `com.raúl.recetas` · ❌ `Mi-App`
  - **No lo cambies** después de instalar la app: el móvil la vería como otra app distinta.
- **Versión**: por ejemplo `1.0.0`.
- **Icono**: un emoji con color de fondo, o **🖼️ Subir mi logo**.

### 🎨 Aspecto y comportamiento
- Color de la **barra superior** y color de **arranque**.
- **Orientación**: vertical, horizontal o ambas.
- **Pantalla completa** (ideal para juegos) · **Mantener pantalla encendida**.
- **Abrir enlaces externos en el navegador** · **Permitir zoom**.

### 🔐 Permisos
Internet · Notificaciones · Vibración · Cámara · Micrófono · Ubicación (GPS) · Fotos y archivos · Descargas.
- Se marcan **automáticamente** según tu app; pulsa **🔍 Detectar permisos en mi código** para revisarlos.
- La app pide cada permiso **la primera vez que lo necesita**.

---

## 7. Paso 4 · Crear el APK

### 7.1 ✅ Revisión rápida
Comprueba que todo está en verde (contenido, nombre, identificador, versión, permisos).

### 7.2 🚀 Crear el APK automáticamente (recomendado)
GitHub (de Microsoft) compila tu app **gratis** en sus ordenadores.

**Preparación (solo la primera vez):**
1. Crea una cuenta en **github.com/signup**.
2. Pulsa el enlace **«crear tu llave de acceso»** que aparece en APK Studio.
   - En *Expiration* elige **No expiration** (o 1 año).
   - Deja marcadas **repo** y **workflow**.
   - Pulsa **Generate token**.
3. Copia el código que empieza por **`ghp_`**, pégalo y pulsa **🔗 Conectar**.

**Cada vez que quieras el APK:**
1. Revisa el **nombre del proyecto** en GitHub (se rellena solo) y la visibilidad:
   - **Público** (recomendado): descarga directa del APK.
   - **Privado**: solo tú, entrando en GitHub.
2. Pulsa **🚀 Crear mi APK**.
3. Sigue el progreso:
   `Conectar → Preparar proyecto → Subir tu app → Esperar ordenador → Compilar (3–6 min) → ¡APK listo!`
4. Al terminar verás:
   - Botón **⬇️ Descargar** con el tamaño del APK.
   - **Código QR** para descargarlo desde el móvil.
   - Enlace que **siempre apunta a la última versión**.

**Ventajas de la subida:**
- **Reanudable**: si se corta, al repetir solo sube lo que faltaba.
- **Reintentos automáticos** si falla la conexión.
- Cada foto o vídeo se sube **una sola vez**.
- **🔄 Comprobar última compilación** consulta el estado sin volver a subir nada.

### 7.3 🌐 Versión web + QR
Al crear el APK, tu app también se publica como **página web** (GitHub Pages). En el paso 4 aparece el enlace y un **QR** para probarla en cualquier móvil **sin instalar nada**. Puede tardar 1–2 minutos la primera vez.

### 7.4 Otras vías
- **⬇️ Descargar proyecto (ZIP)**: proyecto Android completo para Android Studio o para subirlo a GitHub a mano.
- **⬇️ Descargar app.html**: toda la app en un solo archivo (fotos incluidas), útil para AppsGeyser o para compartir.
- **PWABuilder**: con el enlace de la versión web puedes generar APK/AAB para Google Play.

---

## 8. Instalar el APK en el móvil

1. Abre el enlace de descarga **desde el móvil** (o escanea el QR).
2. Toca el archivo **.apk** descargado.
3. Si pide permiso para **«instalar apps desconocidas»**, actívalo para tu navegador o gestor de archivos.
4. Si aparece **Play Protect**: toca **Más detalles → Instalar de todos modos** (normal en apps propias no publicadas en Google Play).

**Para actualizar:** cambia tu app en APK Studio, pulsa otra vez **🚀 Crear mi APK** e instala el nuevo **encima**. Los datos (por ejemplo, las fotos del álbum) **se conservan**.

> 🔑 La primera compilación crea una **llave de firma** (`keystore/release.jks`) en tu proyecto de GitHub. **No la borres**: sin ella no podrás instalar actualizaciones encima de la app.

---

## 9. Lo que pueden hacer las apps creadas

Las apps son **apps Android nativas** que muestran tu contenido y además:

| Función | Detalle |
|---|---|
| 📴 Funcionan **sin internet** | Si el contenido es local (no en modo «web») |
| 📄 Varias pantallas | Menú inferior, botones de navegación y botón atrás del móvil |
| 📸 **Álbum vivo** | Quien usa la app **añade fotos y vídeos desde su móvil**; se guardan, se ven en grande pasando con el dedo, se **comparten**, se **guardan en la galería** o se borran |
| 🖼️ Visor de fotos | Galerías con ampliación, deslizar, compartir y guardar |
| 🎬 Vídeo, 🎵 audio, 📄 PDF, 📖 textos | Mediante «Acción al tocar» |
| 💬 WhatsApp, 📞 llamadas, ✉️ correo | Abren su app correspondiente |
| ▶️ YouTube | Abre la app de YouTube o se ve dentro |
| 📷 Cámara, 🎤 micrófono, 📍 GPS | Si marcas el permiso |
| 📂 Elegir archivos y fotos | Desde formularios de la app |
| ⬇️ Descargas | Guarda archivos en la carpeta Descargas |
| 📤 Compartir y 💾 guardar en galería | Funciones nativas del móvil |

**Para programadores:** la app expone `window.Android` con `toast(texto)`, `share(texto)`, `vibrate(ms)`, `open(url)`, `shareFile(base64, nombre, mime)` y `saveFile(base64, nombre, mime)`.

---

## 10. Copias de seguridad y actualizaciones

### 💾 Guardar copia
Arriba del todo. Descarga un archivo como `mi-app-copia-2026-10-08.apkstudio.zip` en tu carpeta de **Descargas**. Contiene **todo**: diseño, textos, fotos, vídeos, PDF y configuración.

### 📂 Abrir copia
Elige ese archivo y tu proyecto vuelve tal cual, en cualquier navegador u ordenador.

### Buenas prácticas
- Guarda una copia **después de cada cambio importante** y **antes de actualizar APK Studio**.
- Guárdala también **fuera del ordenador** (pendrive, correo, nube).
- Al recibir una versión nueva de APK Studio: **misma carpeta y mismo nombre** que la anterior.

---

## 11. Motor de IA

En el paso 1, **🤖 Motor de IA**:

- **IA gratis sin clave** (activada por defecto): Puter.js y Pollinations. Puter puede pedir, la primera vez, entrar con una cuenta gratis en una ventanita.
- **Plantilla sin internet**: si ninguna IA responde, se crea igualmente una app que funciona.
- **Tus claves API** (opcional, una por línea; el proveedor se detecta solo): Gemini (`AIza…`), OpenRouter (`sk-or-…`), Groq (`gsk_…`), Claude (`sk-ant-…`), OpenAI / DeepSeek (`sk-…`).
- **🧪 Probar motores**: comprueba cuáles responden desde tu conexión.
- **Avanzado**: elegir modelo, Ollama local o servidor propio.

**Orden de uso:** plataforma (si abres APK Studio en Perchance) → tus claves → IA gratis → plantilla. Si uno falla, pasa solo al siguiente.

---

## 12. Solución de problemas

| Problema | Solución |
|---|---|
| **No aparece mi proyecto** al abrir una versión nueva | Pon el archivo nuevo en la **misma carpeta y con el mismo nombre** que el anterior, y ábrelo con el **mismo navegador**. O usa **📂 Abrir copia** |
| La IA no responde / «Failed to fetch» | Pulsa **🧪 Probar motores**. Puede haber bloqueo por país o red: prueba otro proveedor (OpenRouter suele funcionar) o una VPN. Siempre puedes usar una **plantilla** |
| «GitHub rechazó la llave» | La llave caducó o se cambió. Crea una nueva, pégala, pulsa **Conectar** y **Crear mi APK**: lo ya subido **no se repite** |
| La compilación falla | Lee la línea **«📋 Motivo que da GitHub»** del registro y envíala al soporte |
| No se puede conectar con GitHub | Revisa internet; si GitHub está bloqueado en tu red, prueba con una **VPN** |
| La subida es muy lenta | Reduce el tamaño de los vídeos (menos de 20 MB) |
| El mapa o YouTube no se ven en la vista previa | Necesitan internet; en la app instalada funcionan con conexión |
| En modo «web» la vista previa sale en blanco | Esa web no permite mostrarse dentro de otra página; en el APK sí funciona |
| El móvil dice «App no instalada» al actualizar | Cambiaste el **identificador** o se perdió la llave de firma. Desinstala la versión anterior e instala la nueva |
| Play Protect bloquea la instalación | **Más detalles → Instalar de todos modos** |
| Un PDF se abre con otra app | Al subirlo no había internet para preparar sus páginas. Vuelve a subirlo con conexión |

---

## 13. Preguntas frecuentes

**¿Cuesta dinero?**
No. APK Studio, la IA gratis, GitHub y la compilación son gratuitos.

**¿Necesito saber programar?**
No. Todo se hace tocando y escribiendo. El código está disponible solo si lo quieres.

**¿Puedo publicar en Google Play?**
Sí, con una cuenta de desarrollador de Google. Para Play Store se recomienda crear tu propia llave de firma privada.

**¿Las fotos del álbum se pierden al actualizar la app?**
No, si instalas la nueva versión **encima** de la anterior (mismo identificador y misma llave).

**¿Dónde se guardan las fotos que añaden los usuarios en el álbum?**
Dentro de la propia app, en el móvil de cada usuario. Con 💾 se pueden guardar en la galería.

**¿Puedo hacer varias apps?**
Sí. Guarda una copia de cada proyecto y ábrela con **📂 Abrir copia** cuando quieras trabajar en ella. Usa un **nombre de proyecto en GitHub distinto** para cada app.

---

## 14. Ejemplo completo: app de XV años

1. **Paso 1** → **🧩 XV años / Evento**.
2. **Paso 2 · 🎨 Diseño visual**:
   - Toca el título «Mis XV Años» → escribe *«Los XV de Dafne Daniela»*.
   - Toca la **cuenta regresiva** → pon la fecha y hora de la fiesta.
   - **📄 Pantallas** → 👁️ **Galería** → toca la galería → **➕ Añadir fotos** (elige las tuyas).
   - Toca el **mapa** → escribe la dirección del salón.
   - **📄 Pantallas** → 👁️ **Confirmar** → toca el formulario → pon tu número de WhatsApp.
   - **➕ Añadir → Música de fondo** → elige la canción del vals.
   - **🌈 Ambiente** → tema **💗 Quinceañera** y efecto **🌸 Pétalos**.
   - Pulsa **▶️ Probar** y recorre la app.
3. **💾 Guardar copia**.
4. **Paso 3**: nombre *«XV Dafne»*, icono 👑, color rosa.
5. **Paso 4** → **🚀 Crear mi APK** → espera 3–6 min → escanea el **QR** con el móvil → instala.
6. Comparte el enlace con los invitados: podrán ver la galería, la agenda, confirmar por WhatsApp y **subir sus propias fotos al álbum** desde su móvil.

---

## 15. Contacto

¿Dudas, sugerencias o necesitas ayuda?

| | |
|---|---|
| 👤 **Autor** | Raúl Cordero García |
| ✉️ **Correo** | [corderorauly@gmail.com](mailto:corderorauly@gmail.com) |
| 📱 **Móvil / WhatsApp** | [+53 5508 1288](https://wa.me/5355081288) |

*APK Studio — Idea o HTML → app Android real.*
