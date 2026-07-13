# Manual de Usuario — StudyCards

**Versión 1.1**  
**Plataformas:** iOS 18+ • macOS 16+

---

## Tabla de contenidos

1. [Bienvenida](#1-bienvenida)
2. [Primeros pasos](#2-primeros-pasos)
3. [Organización y ordenación](#3-organización-y-ordenación)
4. [Modo de estudio](#4-modo-de-estudio)
5. [Importar y exportar](#5-importar-y-exportar)
6. [Compartir flashcards](#6-compartir-flashcards)
7. [Ajustes](#7-ajustes)
8. [Consejos](#8-consejos)

---

## 1. Bienvenida

¡Bienvenido a **StudyCards**! StudyCards es una aplicación de tarjetas de memoria (flashcards) diseñada para ayudarte a aprender y memorizar cualquier tema de forma efectiva. Con StudyCards puedes crear grupos de tarjetas, añadir fórmulas LaTeX e imágenes, estudiar en modo secuencial o aleatorio, y compartir tus tarjetas con otras personas.

![StudyCards — iOS](screenshots/ios/main.png)
![StudyCards — macOS](screenshots/macos/main.png)

### Características principales

- **Grupos de flashcards:** organiza tus tarjetas por tema o asignatura.
- **Flashcards completas:** cada tarjeta tiene un anverso y un reverso con soporte para texto, fórmulas LaTeX e imágenes.
- **Reordenación manual:** arrastra las flashcards para cambiar su orden dentro de un grupo.
- **Edición de grupos:** edita o elimina grupos desde el menú contextual (pulsación larga).
- **Ordenación y búsqueda:** ordena y busca grupos por nombre, fecha o número de flashcards.
- **Modo de estudio:** evalúa tu conocimiento clasificando cada tarjeta como *Fácil*, *Dudé* o *No supe*.
- **Importar y exportar:** lleva tus tarjetas a otro dispositivo mediante archivos CSV o JSON (con imágenes incrustadas en base64).
- **Compartir:** envía tus flashcards por correo electrónico, WhatsApp, AirDrop y otras apps.
- **Ajustes personalizables:** apariencia, idioma y orden de estudio.
- **Diseño adaptable:** se adapta automáticamente a iPhone, iPad y Mac.

### Requisitos

- iOS 18.0 o posterior / macOS 16.0 o posterior.
- Conexión a internet solo necesaria para la renderización de fórmulas LaTeX (MathJax).

---

## 2. Primeros pasos

### 2.1 Crear un grupo

Los grupos te permiten organizar tus flashcards por tema, asignatura o categoría.

**Pasos:**

1. Abre StudyCards.
2. Pulsa el botón **＋** situado en la parte superior derecha de la pantalla.
3. Escribe un nombre para el grupo (por ejemplo, *Historia de España*).
4. (Opcional) Añade una descripción para identificar el contenido del grupo.
5. Pulsa **Guardar** para confirmar.

![Crear grupo — iOS](screenshots/ios/create_group.png)
![Crear grupo — macOS](screenshots/macos/create_group.png)

> **Consejo:** Usa nombres descriptivos para encontrar tus grupos fácilmente. Puedes crear tantos grupos como necesites.

### 2.2 Editar o eliminar un grupo

Puedes editar o eliminar un grupo directamente desde la lista.

**En iOS:**

1. Mantén pulsado sobre el nombre del grupo hasta que aparezca el menú contextual.
2. Selecciona **Editar** para modificar el nombre o la descripción.
3. Selecciona **Eliminar** para borrar el grupo y todas sus flashcards.

**En macOS:**

1. Haz clic derecho sobre el nombre del grupo.
2. Selecciona **Editar** o **Eliminar**.

> **Precaución:** Eliminar un grupo borra permanentemente todas sus flashcards. Asegúrate de exportarlas antes si necesitas una copia de seguridad.

### 2.3 Crear una flashcard

Una vez dentro de un grupo, puedes añadir tarjetas nuevas.

**Pasos:**

1. Abre el grupo donde quieres añadir la tarjeta.
2. Pulsa el botón **＋** para crear una flashcard nueva.
3. Escribe el contenido del **anverso** (la pregunta o concepto).
4. Escribe el contenido del **reverso** (la respuesta).
5. (Opcional) Añade una imagen pulsando **Seleccionar imagen**.
6. (Opcional) Escribe una fórmula LaTeX entre delimitadores `$...$` (inline) o `$$...$$` (bloque).
7. Pulsa **Guardar**.

![Crear flashcard — iOS](screenshots/ios/create_card.png)
![Crear flashcard — macOS](screenshots/macos/create_card.png)

### 2.4 Fórmulas LaTeX

StudyCards renderiza fórmulas matemáticas utilizando MathJax. Para incluir una fórmula, escríbela entre los delimitadores correctos:

| Tipo | Sintaxis | Ejemplo |
|------|----------|---------|
| En línea | `$f(x) = x^2$` | La función es $f(x) = x^2$ |
| Bloque | `$$\int_0^1 x^2 \, dx$$` | Fórmula en línea aparte |

Ejemplos de fórmulas populares:

- **Ecuación cuadrática:** `$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$`
- **Teorema de Pitágoras:** `$a^2 + b^2 = c^2$`
- **Integral definida:** `$$\int_a^b f(x)\,dx = F(b) - F(a)$$`

> **Nota:** Las fórmulas se renderizan automáticamente al guardar la tarjeta y al estudiar.

### 2.5 Añadir imágenes

Puedes añadir una imagen al anverso o al reverso de cualquier flashcard.

**Pasos:**

1. Al crear o editar una flashcard, pulsa **Seleccionar imagen**.
2. Selecciona una imagen desde tu galería o toma una foto con la cámara.
3. La imagen se mostrará junto al texto de la tarjeta.

![Añadir imagen — iOS](screenshots/ios/add_image.png)
![Añadir imagen — macOS](screenshots/macos/add_image.png)

> **Nota:** Las imágenes se redimensionan automáticamente a un máximo de 1024 píxeles para optimizar el almacenamiento. Al exportar como JSON, las imágenes se incluyen en formato base64.

### 2.6 Eliminar una flashcard

Puedes eliminar una flashcard deslizándola hacia la izquierda.

**Pasos:**

1. En la lista de flashcards de un grupo, desliza la tarjeta hacia la izquierda.
2. Aparecerá un botón rojo **Eliminar**.
3. Pulsa **Eliminar** para confirmar la acción.

![Eliminar flashcard — iOS](screenshots/ios/swipe_delete.png)
![Eliminar flashcard — macOS](screenshots/macos/swipe_delete.png)

> **Precaución:** La eliminación es permanente. Asegúrate de exportar tus tarjetas antes de borrarlas si no tienes una copia de seguridad.

---

## 3. Organización y ordenación

### 3.1 Reordenar flashcards manualmente

Puedes cambiar el orden de las flashcards dentro de un grupo arrastrándolas.

**En iOS:**

1. Abre el grupo con las flashcards que quieres reordenar.
2. Pulsa **Editar** en la barra de herramientas (esquina superior izquierda).
3. Aparecerán las manecillas de reordenación ⟟ junto a cada flashcard.
4. Arrastra la flashcard a la posición deseada.
5. Pulsa **Listo** para guardar el nuevo orden.

**En macOS:**

1. Abre el grupo con las flashcards que quieres reordenar.
2. Pulsa el botón **Reordenar** (icono ↕) en la barra de herramientas.
3. Arrastra la flashcard a la posición deseada.
4. Pulsa **Listo** para salir del modo reordenación.

> **Nota:** El orden manual se mantiene al exportar e importar flashcards.

### 3.2 Ordenar grupos

Puedes ordenar la lista de grupos por diferentes criterios.

**Pasos:**

1. Pulsa el botón de ordenación (icono ↕) en la barra de herramientas.
2. Selecciona uno de los criterios de ordenación:

| Criterio | Descripción |
|----------|-------------|
| **Nombre (A-Z)** | Orden alfabético ascendente |
| **Nombre (Z-A)** | Orden alfabético descendente |
| **Más recientes** | Grupos creados más recientemente primero |
| **Más antiguos** | Grupos creados más antiguamente primero |
| **Número de flashcards** | Grupos con más flashcards primero |

> **Nota:** La ordenación se aplica tanto en la sección **Grupos** como en **Estudiar**.

### 3.3 Buscar grupos

**En iOS:**

1. Desliza hacia abajo en la lista de grupos para mostrar la barra de búsqueda.
2. Escribe el nombre del grupo que buscas.

**En macOS:**

1. Usa la barra de búsqueda situada en la parte superior del sidebar.
2. Escribe el nombre del grupo que buscas.

---

## 4. Modo de estudio

El modo de estudio es el corazón de StudyCards. Te permite repasar tus flashcards de forma interactiva y evaluar tu nivel de conocimiento.

### 4.1 Iniciar una sesión de estudio

**Pasos:**

1. Selecciona la pestaña **Estudiar** en la barra de navegación.
2. Busca y selecciona el grupo que quieres estudiar.
3. La primera flashcard aparecerá en pantalla.

![Iniciar estudio — iOS](screenshots/ios/start_study.png)
![Iniciar estudio — macOS](screenshots/macos/start_study.png)

### 4.2 Navegar entre tarjetas

Durante la sesión de estudio:

1. Lee el contenido del **anverso** (pregunta).
2. Piensa en la respuesta.
3. Pulsa **Revelar respuesta** o toca la tarjeta para ver el **reverso** (respuesta).
4. Evalúa tu conocimiento con uno de los tres botones:

| Botón | Significado | Descripción |
|-------|-------------|-------------|
| 🟢 **Fácil** | La sabías bien | La tarjeta se marcará como dominada. Aparecerá con menos frecuencia. |
| 🟡 **Dudé** | La recordaste con dificultad | La tarjeta volverá a aparecer pronto para reforzarla. |
| 🔴 **No supe** | No la sabías | La tarjeta se repetirá más veces para que la aprendas. |

**Atajos de teclado (macOS):**

| Tecla | Acción |
|-------|--------|
| **Espacio** | Voltear la tarjeta |
| **1** | Calificar como Fácil |
| **2** | Calificar como Dudé |
| **3** | Calificar como No supe |

![Modo estudio — iOS](screenshots/ios/study_session.png)
![Modo estudio — macOS](screenshots/macos/study_session.png)

### 4.3 Completar la sesión

Cuando hayas repasado todas las tarjetas del grupo:

1. StudyCards mostrará un resumen de tu sesión.
2. Verás cuántas tarjetas clasificaste como *Fácil*, *Dudé* y *No supe*.
3. Pulsa **Estudiar de nuevo** para repetir o **Volver a grupos** para salir.

![Resumen estudio — iOS](screenshots/ios/study_summary.png)
![Resumen estudio — macOS](screenshots/macos/study_summary.png)

---

## 5. Importar y exportar

StudyCards te permite mover tus flashcards entre dispositivos o crear copias de seguridad mediante archivos CSV y JSON.

### 5.1 Exportar flashcards

**Pasos:**

1. Abre el grupo que quieres exportar.
2. Pulsa el menú de acciones (icono ⋯) y selecciona **Exportar**.
3. Selecciona el formato de exportación:
   - **CSV:** formato Tabla. Ideal para abrir en hojas de cálculo (Excel, Numbers). No incluye imágenes.
   - **JSON:** formato completo. Incluye texto, fórmulas LaTeX e imágenes en base64.
4. Elige dónde guardar el archivo (Archivos, iCloud Drive, etc.).

![Exportar — iOS](screenshots/ios/export.png)
![Exportar — macOS](screenshots/macos/export.png)

### 5.2 Estructura del archivo JSON

El archivo JSON exportado tiene la siguiente estructura:

```json
{
  "groupName": "Historia de España",
  "version": "1.0",
  "createdAt": "2026-07-12T10:30:00Z",
  "cards": [
    {
      "front": "¿En qué año comenzó la Guerra Civil Española?",
      "back": "En 1936.",
      "frontLatex": null,
      "backLatex": null,
      "difficulty": 0,
      "frontImage": "base64_encoded_string...",
      "backImage": null
    }
  ]
}
```

### 5.3 Estructura del archivo CSV

El archivo CSV utiliza las siguientes columnas:

```csv
anverso,reverso,latex_anverso,latex_reverso,dificultad,imagen_anverso,imagen_reverso
"¿En qué año comenzó la Guerra Civil Española?","En 1936.","","","0","",""
```

> **Nota:** Las imágenes en formato CSV se exportan como cadenas base64 en las columnas `imagen_anverso` e `imagen_reverso`.

### 5.4 Importar flashcards

**Pasos:**

1. En la lista de flashcards de un grupo, pulsa el menú de acciones y selecciona **Importar**.
2. Selecciona un archivo CSV o JSON desde tu dispositivo.
3. StudyCards importará las flashcards al grupo actual.

![Importar — iOS](screenshots/ios/import.png)
![Importar — macOS](screenshots/macos/import.png)

> **Nota:** Si importas un archivo JSON con imágenes en base64, las imágenes se mostrarán correctamente en las flashcards.

### 5.5 Errores comunes de importación

| Error | Causa | Solución |
|-------|-------|----------|
| *Formato no reconocido* | El archivo no es CSV ni JSON válido | Verifica que el archivo tenga la extensión correcta y no esté corrupto |
| *Archivo vacío* | El archivo no contiene tarjetas | Comprueba que el archivo tenga al menos una fila de datos |

---

## 6. Compartir flashcards

StudyCards te permite compartir tus flashcards directamente con otras personas o dispositivos.

### 6.1 Compartir un grupo como JSON

**Pasos:**

1. Abre el grupo que quieres compartir.
2. Pulsa el menú de acciones y selecciona **Compartir**.
3. Se abrirá el selector de compartición del sistema.
4. Elige la aplicación o método de envío:
   - **AirDrop** — para dispositivos Apple cercanos.
   - **Correo electrónico** — envía el archivo JSON como adjunto.
   - **WhatsApp** — envía el archivo JSON como documento.
   - **Mensajes** — envía por iMessage.
   - **Otras apps** — cualquier app que acepte archivos adjuntos.

![Compartir — iOS](screenshots/ios/share.png)
![Compartir — macOS](screenshots/macos/share.png)

### 6.2 Recibir flashcards compartidas

Cuando alguien te envíe un archivo JSON de StudyCards:

1. Abre el archivo en tu dispositivo.
2. Selecciona **Abrir en StudyCards** o **Importar**.
3. El grupo se añadirá automáticamente a tu colección.

---

## 7. Ajustes

StudyCards ofrece varios ajustes para personalizar tu experiencia. Accede a ellos desde la pestaña **Ajustes** en la barra de navegación.

### 7.1 Apariencia

Controla el aspecto visual de la aplicación.

| Opción | Descripción |
|--------|-------------|
| **Sistema** | Usa el tema del sistema operativo (claro u oscuro según la configuración del dispositivo). |
| **Claro** | Fuerza el tema claro siempre. |
| **Oscuro** | Fuerza el tema oscuro siempre. |

**Pasos:**

1. Ve a la pestaña **Ajustes**.
2. En la sección **Apariencia**, selecciona una de las tres opciones.
3. El cambio se aplica inmediatamente.

![Ajustes apariencia — iOS](screenshots/ios/appearance.png)
![Ajustes apariencia — macOS](screenshots/macos/appearance.png)

### 7.2 Idioma

StudyCards está disponible en 8 idiomas. Puedes forzar un idioma específico o usar el del sistema.

| Idioma | Código |
|--------|--------|
| **Sistema** | Selecciona automáticamente el idioma del dispositivo |
| Español | es |
| English | en |
| Português | pt |
| Français | fr |
| Deutsch | de |
| Italiano | it |
| 日本語 | ja |
| 中文 | zh |

**Pasos:**

1. Ve a la pestaña **Ajustes**.
2. En la sección **Idioma**, selecciona el idioma deseado.
3. El cambio se aplica inmediatamente sin necesidad de reiniciar.

![Ajustes idioma — iOS](screenshots/ios/language.png)
![Ajustes idioma — macOS](screenshots/macos/language.png)

### 7.3 Orden de estudio

Define el orden predeterminado en que se muestran las flashcards durante el modo de estudio.

| Opción | Descripción |
|--------|-------------|
| **Secuencial** | Las tarjetas se muestran en el orden en que fueron creadas (o el orden manual si reordenaste). |
| **Aleatorio** | Las tarjetas se muestran en orden aleatorio en cada sesión. |

**Pasos:**

1. Ve a la pestaña **Ajustes**.
2. En la sección **Orden de estudio**, selecciona tu preferencia.
3. El cambio se aplicará a todas las sesiones de estudio futuras.

![Ajustes orden estudio — iOS](screenshots/ios/study_order.png)
![Ajustes orden estudio — macOS](screenshots/macos/study_order.png)

---

## 8. Consejos

### Organización

- **Crea un grupo por cada materia o tema.** Esto te ayudará a encontrar rápidamente lo que necesitas estudiar.
- **Usa nombres claros y cortos** para los grupos y las flashcards. Evita textos demasiado largos que sean difíciles de leer en pantalla.
- **Reordenar manualmente** las flashcards para poner las más importantes al principio.
- **Revisa tus grupos periódicamente.** Elimina las tarjetas que ya dominas y añade nuevas que se ajusten a tu progreso.

### Estudio

- **Utiliza el intervalo espaciado.** Estudia las mismas tarjetas en diferentes días para consolidar la memoria a largo plazo.
- **No ignores las tarjetas difíciles.** Si marcas una tarjeta como *No supe*, estudia de nuevo ese grupo pronto.
- **Mezcla los modos de estudio.** Alterna entre orden secuencial y aleatorio para evitar memorizar la posición de las tarjetas.
- **Usa los atajos de teclado** en macOS para estudiar más rápido (Espacio, 1, 2, 3).
- **Estudia en sesiones cortas.** De 10 a 20 minutos es suficiente para una sesión productiva.

### Contenido

- **Escribe preguntas claras y concisas.** Evita ambigüedades.
- **Una idea por tarjeta.** No sobrecargues el anverso o el reverso con demasiada información.
- **Aprovecha las imágenes.** Un diagrama o una imagen puede ser más efectivo que un párrafo de texto.
- **Usa fórmulas LaTeX** para contenido matemático o científico. Son precisas y se ven profesionales.

### Copias de seguridad

- **Exporta tus grupos regularmente.** Guarda copias en iCloud Drive o en tu ordenador.
- **Usa formato JSON** si quieres conservar las imágenes. El formato CSV solo guarda texto.
- **Comparte tus flashcards** con compañeros de clase o colegas para colaborar en el estudio.

### Rendimiento

- **Cierra otras aplicaciones** cuando estudies para que StudyCards funcione sin interrupciones.
- **Mantén la aplicación actualizada** para acceder a nuevas funciones y correcciones de errores.
- **Si las fórmulas LaTeX no se renderizan**, verifica tu conexión a internet. MathJax necesita descargar los recursos necesarios la primera vez.

---

## Información legal

- **StudyCards** es una aplicación desarrollada de forma independiente.
- El uso de MathJax está sujeto a su licencia Apache 2.0.
- Tus datos se almacenan únicamente en tu dispositivo. StudyCards no recopila ni comparte información personal.

---

*Manual de usuario de StudyCards — Versión 1.1 — Julio 2026*
