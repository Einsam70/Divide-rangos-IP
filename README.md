# Gestor de Rangos IP (IP Range Splitting Utility)

Una utilidad local, ligera y portable diseñada para fraccionar rangos de direcciones IP en bloques de tamaño personalizado. Ideal para administradores de sistemas y gestión de direccionamiento de red.

## 🚀 Características

- **Unificación Completa:** Las utilidades individuales y masivas ahora residen en una única e intuitiva interfaz modular (Single Page Application).
- **Procesamiento Independiente:** Cada modo (Un Rango / Múltiples Rangos) mantiene de forma aislada sus datos de entrada, el tamaño de bloque configurado y su caja de resultados.
- **Soporte Bilingüe:** Interfaz con cambio de idioma en caliente (Español / Inglés).
- **Modo Oscuro Nativo:** Conmutador visual para adaptar la interfaz a entornos de baja luminosidad.
- **100% Local & Portable:** Sin dependencias, bases de datos ni llamadas a servidores externos. Funciona directamente haciendo doble clic desde tu disco duro o una unidad USB.

---

## 🛠️ Modos de Uso

La aplicación cuenta con dos pestañas optimizadas según tus necesidades:

1. **Un Rango:** Diseñado para procesar un único rango de IPs de forma rápida mediante un campo de texto simple.
2. **Múltiples Rangos:** Pensado para el procesamiento por lotes. Permite introducir una lista de rangos (uno por línea) para dividirlos masivamente de una sola vez.

A diferencia de versiones anteriores, **los tamaños de los bloques y los resultados resultantes son completamente independientes entre pestañas**, permitiéndote trabajar en ambos modos en paralelo sin que se pisen los datos. Cada pestaña incluye además su propio botón de **Reiniciar** para limpiar el formulario al instante.

---

## 💻 Tecnologías utilizadas

- **HTML5 & CSS3:** Maquetación limpia y diseño adaptativo mediante Variables CSS nativas para el cambio de tema.
- **JavaScript Vanila (ES6):** Núcleo de cálculo optimizado mediante desplazamientos de bits binarios de alta velocidad, garantizando una ejecución fluida en navegadores modernos como Firefox sin necesidad de librerías de terceros.

---

## 🔧 Cómo utilizar

1. Descarga el archivo `index.html`.
2. Haz doble clic sobre él para abrirlo en tu navegador web.
3. Elige el modo de entrada, define el número de IPs deseadas por bloque y haz clic en **Dividir Rango**.

---

## 📸 Capturas de Pantalla

![Pestaña de rango único y vista general de la aplicación](screenshots/app_preview.png)