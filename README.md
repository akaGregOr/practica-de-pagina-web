<div align="center">

<!-- Reemplazar la ruta por la ubicación definitiva del logotipo de IDAT. -->
<img src="https://www.greatplacetowork.com.pe/images/certification/2021/idat/logo-2.png" alt="Logo de IDAT" width="180">

# Práctica integradora: NovaTech

### Desarrollo Web · Sesiones 16 y 17

**HTML5 + CSS3 | Sistema visual, Box Model y maquetación**

[Repositorio base del docente](https://github.com/miguelramosalarcon/practicaS16-S17)

</div>

---

## 1. Datos del estudiante

| Campo | Información |
|---|---|
| **Nombres y apellidos** | [Completar] |
| **Institución** | IDAT |
| **Curso** | Desarrollo Web |
| **Ciclo** | [Completar] |
| **Sección / turno** | [Completar] |
| **Docente** | Miguel Ramos Alarcon |
| **Repositorio personal** | [Pegar URL] |
| **Sitio publicado (GitHub Pages)** | [Pegar URL, cuando corresponda] |

> **Indicaciones:** cada estudiante debe editar esta tabla con sus propios datos y mantener actualizado su README conforme avance el proyecto. No dejar información de ejemplo en la entrega.

## 2. Presentación de la práctica

**NovaTech** es una landing page ficticia de servicios digitales. La actividad consiste en reproducir progresivamente el diseño de referencia utilizando **HTML semántico y CSS puro**, sin Bootstrap ni JavaScript.

El trabajo se divide en dos sesiones para comprender primero **cómo se ve cada elemento** y después **cómo se distribuyen los elementos en la página**.

### Objetivo general

Construir y documentar una página web sencilla, aplicando estilos reutilizables, un contenedor de ancho controlado y modelos de maquetación CSS.

### Resultados de aprendizaje

- **Sesión 16:** aplicar variables CSS, paleta de colores, tipografía, unidades, dimensiones y propiedades del Box Model para establecer un sistema visual coherente.
- **Sesión 17:** organizar las secciones del sitio con el flujo normal, Flexbox y CSS Grid, utilizando alineación, distribución y separación de elementos.

## 3. Recursos proporcionados

El repositorio base contendrá los archivos iniciales publicados por el docente:

- Plantilla HTML de la página.
- Plantilla CSS para completar o modificar.
- Imagen de referencia del resultado esperado.
- Imágenes para el hero, la sección «Nosotros» y los proyectos.
- Logotipo institucional, si se incluye como recurso de la práctica.

**Importante:** conservar la estructura y los nombres reales de los archivos entregados. Las rutas que aparecen en este documento son una propuesta y pueden ajustarse a las plantillas definitivas.

## 4. Estructura de carpetas recomendada

```text
practicaS16-S17/
├── index.html
├── css/
│   └── styles.css
├── img/
│   ├── logo-idat.png
│   ├── 01-hero-laptop.jpg
│   ├── 02-equipo.jpg
│   ├── 03-proyecto-cafe.jpg
│   ├── 04-proyecto-fitlife.jpg
│   └── 05-proyecto-gestion.jpg
└── README.md
```

> Si el docente publica una estructura diferente, utilizar esa estructura como fuente principal. No duplicar carpetas ni cambiar rutas sin necesidad.

## 5. Preparación del entorno

1. Acceder al [repositorio base](https://github.com/miguelramosalarcon/practicaS16-S17).
2. Obtener una copia para trabajar en un **repositorio personal** (por ejemplo, mediante *Fork* o descargando las plantillas y creando un repositorio propio, según las indicaciones del docente).
3. Abrir la carpeta del proyecto en Visual Studio Code.
4. Verificar que `index.html` esté vinculado correctamente con `css/styles.css`.
5. Comprobar las rutas de las imágenes.
6. Abrir la página en el navegador y revisar su estado inicial.
7. Completar los datos personales de este README.

**No trabajar directamente sobre el repositorio del docente.** Cada estudiante debe conservar sus avances en su propio repositorio.

## 6. Sesión 16 — Sistema visual y Box Model

### Propósito

Establecer la identidad visual de NovaTech y controlar el tamaño, los espacios y la presentación de sus componentes.

### Actividades

- [ ] Revisar la estructura HTML proporcionada e identificar `header`, `main`, `section`, `article` y `footer`.
- [ ] Definir variables reutilizables en `:root` para colores y dimensiones.
- [ ] Aplicar una limpieza inicial razonable, incluyendo `box-sizing: border-box`.
- [ ] Configurar tipografía, colores de texto, fondos y altura de línea.
- [ ] Crear una clase `.container` con un ancho máximo de **1200 px**, centrada horizontalmente.
- [ ] Dar estilo al encabezado y a los enlaces de navegación.
- [ ] Diseñar el hero: título, párrafo, botones, imagen y degradado de fondo.
- [ ] Aplicar `padding`, `margin`, `border`, `border-radius` y dimensiones a las tarjetas.
- [ ] Dar estilo a las secciones «Servicios», «Nosotros» y «Proyectos».
- [ ] Diseñar un footer sencillo con copyright y enlace a política de privacidad.
- [ ] Revisar visualmente los cambios en el navegador.

**Alcance:** en esta sesión **no se exige** que las tarjetas, el menú o las columnas queden distribuidos exactamente como en la referencia. La distribución con Flexbox y Grid corresponde a la Sesión 17.

### Commit sugerido

**Summary**

```text
style: definir sistema visual y box model
```

**Description**

```text
Se configuraron variables CSS, tipografía, colores, contenedor,
espaciados, bordes y estilos base de las secciones de NovaTech.
```

## 7. Sesión 17 — Maquetación con Block, Flexbox y Grid

### Propósito

Transformar los bloques estilizados en una página con distribuciones claras y coherentes, tomando como referencia el layout entregado.

### Actividades

- [ ] Reconocer el flujo normal de los elementos y las diferencias entre `block`, `inline` e `inline-block`.
- [ ] Aplicar Flexbox al encabezado para organizar logo, menú e iconos sociales.
- [ ] Utilizar `justify-content`, `align-items` y `gap` donde corresponda.
- [ ] Organizar el hero en una composición de texto e imagen, según la estructura entregada.
- [ ] Crear la distribución de las tres tarjetas de servicios con CSS Grid.
- [ ] Organizar la sección «Nosotros» con texto e imagen.
- [ ] Crear una cuadrícula para las tarjetas de proyectos.
- [ ] Revisar cuándo conviene utilizar Block, Flexbox o Grid.
- [ ] Corregir desbordamientos, espacios y alineaciones visibles.
- [ ] Comparar el resultado final con la imagen de referencia.
- [ ] Actualizar este README y registrar los cambios en Git.

**Alcance:** la adaptación responsive mediante media queries se trabajará formalmente en la sesión siguiente. Se permite utilizar comportamientos flexibles básicos, pero no se exige resolver todos los tamaños de pantalla todavía.

### Commit sugerido

**Summary**

```text
style: maquetar secciones con flexbox y grid
```

**Description**

```text
Se organizaron la navegación, el hero, los servicios, la sección
Nosotros y los proyectos utilizando Flexbox y CSS Grid.
```

## 8. Reglas de desarrollo

- Utilizar **HTML5 semántico** y **CSS externo**.
- No utilizar Bootstrap, Tailwind, bibliotecas de componentes ni JavaScript.
- Mantener los estilos organizados y evitar repetir valores cuando puedan reutilizarse mediante variables CSS.
- Usar nombres de clases claros y consistentes.
- Mantener rutas relativas correctas para estilos e imágenes.
- Añadir textos alternativos descriptivos a las imágenes informativas; usar `alt=""` si una imagen es puramente decorativa.
- Conservar enlaces y botones con su elemento HTML adecuado según la acción que realizan.
- No copiar el código de otros compañeros: el propósito es comprender y reproducir el diseño.

## 9. Evidencias y documentación del estudiante

Completar esta sección a medida que se avance:

| Etapa | Trabajo realizado | Evidencia o enlace |
|---|---|---|
| Inicio | Preparación del proyecto y revisión de plantillas | [Completar] |
| Sesión 16 | Sistema visual, Box Model y contenedor | [Completar] |
| Sesión 17 | Maquetación con Flexbox y Grid | [Completar] |
| Resultado | Página final y comparación con la referencia | [Completar] |

### Dificultades encontradas y soluciones

**Dificultad 1:** [Describir el problema].  
**Solución:** [Explicar cómo se resolvió].

**Dificultad 2:** [Opcional].  
**Solución:** [Opcional].

### Aprendizajes principales

[Escribir un breve párrafo personal sobre lo aprendido en ambas sesiones: qué propiedad CSS fue más útil, qué diferencia existe entre Flexbox y Grid, y qué mejoraría del proyecto.]

## 10. Entrega y revisión

Antes de compartir el trabajo, verificar:

- [ ] El repositorio personal contiene los archivos HTML, CSS y recursos necesarios.
- [ ] La página abre correctamente y no muestra imágenes rotas.
- [ ] La hoja de estilos externa se aplica sin errores de ruta.
- [ ] El contenido mantiene una estructura HTML comprensible.
- [ ] El trabajo de ambas sesiones está reflejado en el historial de commits.
- [ ] El README contiene los datos personales, avances y aprendizajes.
- [ ] El enlace al repositorio personal funciona.
- [ ] Si se solicita publicación, el enlace de GitHub Pages funciona.

**Entrega:** compartir el enlace del repositorio personal mediante el medio indicado por el docente. La fecha y el procedimiento exactos serán comunicados en clase o en EVA.

## 11. Referencias

- [Repositorio base de la práctica](https://github.com/miguelramosalarcon/practicaS16-S17)
- [MDN — CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [MDN — Flexbox](https://developer.mozilla.org/es/docs/Web/CSS/CSS_flexible_box_layout)
- [MDN — CSS Grid](https://developer.mozilla.org/es/docs/Web/CSS/CSS_grid_layout)

---

<div align="center">

**IDAT · Desarrollo Web**  
**Docente: Miguel Ramos Alarcon**

*Aprender a programar implica construir, probar, equivocarse y mejorar.*

</div>
