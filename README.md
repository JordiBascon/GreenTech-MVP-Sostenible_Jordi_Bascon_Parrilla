# GreenTech: MVP Sostenible
**Alumno:** Jordi Bascón Parrilla  

---

## Filosofía del Proyecto
Este trabajo se centra en la aplicación de buenas prácticas de **Green Computing**. El objetivo principal ha sido refactorizar el MVP original para eliminar dependencias innecesarias, reducir el peso de transferencia de datos y optimizar el tiempo de renderizado en el cliente.

## Optimizaciones Implementadas

### 1. Sustitución de Frameworks por CSS Nativo
Se ha eliminado la dependencia de **Bootstrap** para evitar la carga de miles de líneas de código no utilizado. 
* **Resultado:** Reducción drástica del peso del archivo y mayor control sobre los estilos.
* **Impacto:** Menor consumo de recursos al procesar el CSS.

### 2. Gestión Eficiente de Tipografías
Se ha prescindido de **Google Fonts** en favor de fuentes del sistema.
* **Resultado:** Eliminación de peticiones HTTP externas.
* **Impacto:** Mejora en la privacidad del usuario y carga instantánea de textos.

### 3. Optimización de Imagenes
Sustitución de imágenes externas por archivos locales en formato **.webp**.
* **Resultado:** Reducción significativa del tiempo de carga sin comprometer la calidad de las imágenes en el navegador.
* **Impacto:** Reducción del ancho de banda necesario para visualizar la web.

### 4. Refactorización y Calidad de Código
* **Limpieza de Especificidad:** Tras eliminar Bootstrap, se ha eliminado el uso de `!important` en el CSS, permitiendo una jerarquía de estilos más limpia y profesional.
* **Separación del CSS:** Se ha separado el CSS del archivo HTML principal.
* **Resultado:** Mejora en la mantenibilidad del código y aprovechamiento del almacenamiento en la caché del navegador.

## Conclusión de Sostenibilidad
Al reducir el peso total de la web, el sitio no solo es más rápido, sino que consume menos energía tanto en el servidor como en el dispositivo del usuario que abra la web.
