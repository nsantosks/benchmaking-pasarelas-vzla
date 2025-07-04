# benchmaking-pasarelas-vzla
## Análisis Interactivo: Instapago vs. PagoFlash

Este repositorio contiene el código de una página web estática e interactiva diseñada para comparar dos pasarelas de pago prominentes en Venezuela: **Instapago** y **PagoFlash**.

El objetivo es ofrecer un análisis claro, visual y fácil de navegar para ayudar a negocios y emprendedores a tomar una decisión informada. La comparación está especialmente orientada a las necesidades de un negocio digital de bajo volumen que prioriza costos bajos, facilidad de integración y rapidez en la liquidación de fondos.

![Demo del Dashboard](dashboard-benchmarking.gif)


## 🚀 Características Principales

*   **Dashboard Interactivo:** Toda la información se presenta en una única página con una estructura de dashboard para facilitar la comparación directa.
*   **Navegación por Secciones:** El usuario puede saltar directamente a la sección que más le interese (`Resumen`, `Comisiones`, `Usabilidad`, `Liquidación`, etc.) sin tener que desplazarse por un reporte lineal.
*   **Visualización de Datos:** Se utiliza un gráfico de barras (creado con **Chart.js**) para comparar visualmente las comisiones, el factor más crítico para muchos negocios.
*   **Análisis Lado a Lado:** Las características cualitativas (como facilidad de uso, métodos de pago y seguridad) se presentan en tablas y listas comparativas para una evaluación rápida.
*   **Veredicto y Recomendación Clara:** La página no solo presenta datos, sino que ofrece una recomendación final fundamentada, explicando por qué una opción es superior para el perfil de usuario analizado.
*   **Diseño Moderno y Responsivo:** Construido con **Tailwind CSS**, la interfaz es limpia, legible y se adapta perfectamente a dispositivos móviles y de escritorio.

## 🏆 El Veredicto: ¿Cuál es Mejor?

Basado en el análisis detallado presentado en la página, el proyecto concluye que **PagoFlash es la opción superior** para un emprendedor o pequeño negocio digital en Venezuela.

Las razones clave son:

1.  **✅ Costos y Transparencia:** PagoFlash ofrece una comisión fija y predecible (3.5%), mientras que la de Instapago es variable y menos transparente (2.4% - 5.3%).
2.  **✅ Simplicidad y Autonomía:** PagoFlash destaca por sus herramientas "plug-and-play" como los enlaces de pago, que no requieren conocimientos técnicos para su implementación.
3.  **✅ Liquidez Rápida:** Los fondos se reciben en 48 horas con PagoFlash, una mejora significativa frente a los 4-5 días hábiles de Instapago.
4.  **✅ Flexibilidad de Moneda:** La capacidad de mostrar precios en USD con conversión automática es una ventaja crucial en el mercado venezolano.

## 🛠️ Tecnologías Utilizadas

Este proyecto es puramente frontend y no requiere de un backend para funcionar.

*   **HTML5:** Estructura semántica del contenido.
*   **CSS3 (con Tailwind CSS):** Framework para un diseño rápido, moderno y responsivo.
*   **JavaScript (ES6):** Para la interactividad del dashboard (cambio de pestañas) y la lógica del gráfico.
*   **Chart.js:** Librería para la creación de gráficos interactivos y visualmente atractivos.
*   **Google Fonts:** Para la tipografía (fuente Inter).

## 📦 Cómo Utilizar o Ver el Proyecto

Dado que es un proyecto autocontenido con dependencias a través de CDN, es muy fácil de ejecutar.

### Opción 1: Localmente

1.  Clona este repositorio en tu máquina local:
    ```bash
    git clone https://github.com/tu-usuario/tu-repositorio.git
    ```
2.  Navega a la carpeta del proyecto:
    ```bash
    cd tu-repositorio
    ```
3.  Abre el archivo `index.html` directamente en tu navegador web preferido (Google Chrome, Firefox, etc.).

### Opción 2: GitHub Pages (Demo en vivo)

Puedes alojar este proyecto de forma gratuita usando GitHub Pages para tener una demo en vivo.

1.  Ve a la pestaña `Settings` de tu repositorio.
2.  En el menú de la izquierda, selecciona `Pages`.
3.  En la sección `Build and deployment`, bajo `Source`, selecciona `Deploy from a branch`.
4.  Elige la rama `main` (o `master`) y la carpeta `/root`.
5.  Haz clic en `Save`. GitHub te proporcionará una URL pública para tu proyecto en unos minutos.