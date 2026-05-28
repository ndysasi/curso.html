
# 📏 UNIDADES DE MEDIDA EN DISEÑO WEB

--------------------------------------------------

## 🔍 1. ¿Qué son las unidades de medida en diseño web?

Las unidades de medida en diseño web son valores utilizados en HTML y CSS para definir tamaños de:

• textos
• imágenes
• botones
• márgenes
• espacios
• contenedores

🎯 Objetivo:
Crear páginas web adaptables y organizadas para diferentes dispositivos.

--------------------------------------------------

## 📚 2. ¿En qué se basan las unidades de medida?

| 📏 Unidad | 📌 Se basa en |
|-----------|------------------------------|
| px        | Píxeles de pantalla |
| %         | Tamaño del elemento padre |
| em        | Tamaño de fuente del padre |
| rem       | Tamaño raíz del documento |
| vw        | Ancho de la ventana |
| vh        | Alto de la ventana |

--------------------------------------------------

## 🎯 3. Tipos de unidades de medida

| 🔧 Tipo | 📌 Definición | 🎯 Ejemplo |
|---------|------------------------------|----------------|
| Absolutas | Tamaño fijo | px, cm, mm |
| Relativas | Se adaptan al dispositivo | %, em, rem, vw, vh |

--------------------------------------------------

## 🔹 3.1. Unidades Absolutas

### 📌 a) px (Píxeles)

Es la unidad más utilizada en diseño web.
Define tamaños exactos y fijos.

✅ Ejemplo:

font-size: 30px;

📌 El texto tendrá exactamente 30 píxeles.

--------------------------------------------------

### 📌 b) cm y mm

Son poco usadas en páginas web.
Se utilizan más para impresión.

✅ Ejemplo:

width: 10cm;

--------------------------------------------------

## 🔹 3.2. Unidades Relativas

### 📌 a) %

Se basa en el tamaño del contenedor padre.

✅ Ejemplo:

width: 50%;

📌 El elemento ocupará la mitad del espacio disponible.

--------------------------------------------------

### 📌 b) em

Depende del tamaño de fuente del elemento padre.

✅ Ejemplo:

font-size: 2em;

📌 Si el padre tiene 16px:
2em = 32px

--------------------------------------------------

### 📌 c) rem

Se basa en el tamaño raíz del documento.

✅ Ejemplo:

font-size: 2rem;

📌 Si html tiene 16px:
2rem = 32px

--------------------------------------------------

### 📌 d) vw y vh

| 📏 Unidad | 📌 Significado |
|-----------|----------------|
| vw | View Width |
| vh | View Height |

✅ Ejemplo:

width: 100vw;
height: 100vh;

📌 El elemento ocupará toda la pantalla.

--------------------------------------------------

## 🖥️ 4. Diferencias entre unidades

| 📌 Característica | 🔒 Absolutas | 🔄 Relativas |
|------------------|--------------|--------------|
| Tamaño fijo | ✅ Sí | ❌ No |
| Responsive | ❌ No | ✅ Sí |
| Adaptables | ❌ Limitado | ✅ Muy usadas |

--------------------------------------------------

## 📱 5. Importancia en Diseño Responsive

Las unidades permiten:

✅ Adaptar páginas a celulares.
✅ Mejorar la experiencia del usuario.
✅ Crear diseños modernos.
✅ Mantener proporciones correctas.

📌 Las más recomendadas actualmente son:

• rem
• %
• vw
• vh

Porque ayudan al Responsive Design.

--------------------------------------------------


## 💡 6. Recomendaciones al usar unidades de medida

✅ Usar rem para textos.
✅ Usar % para tamaños adaptables.
✅ Usar vh y vw para pantallas completas.
✅ Evitar usar muchos px en diseños responsive.

--------------------------------------------------

## 📖 7. Conclusión

Las unidades de medida en diseño web son fundamentales para crear páginas modernas, ordenadas y adaptables.

📌 Las unidades relativas son las más utilizadas actualmente porque permiten que una página web funcione correctamente en diferentes tamaños de pantalla y dispositivos.