# Plataforma de Captación de Socios Cooperadores
### Primera Compañía de Bomberos "Bomba Aconcagua" — San Felipe

Plataforma web de alta conversión diseñada para la captación e inscripción de socios cooperadores de la Primera Compañía de Bomberos "Bomba Aconcagua" de San Felipe. El sistema cuenta con un diseño completamente responsivo y un flujo de donación optimizado para garantizar la mejor experiencia de usuario.

---

## 1. Características Técnicas y Funcionales

* **Identidad Visual y Estilo:** Aplicación estricta de la paleta institucional (Rojo `#D32F2F`, Blanco `#FFFFFF` y Negro `#121212`) con tipografía jerarquizada mediante Google Fonts (*Montserrat* e *Inter*).
* **Diseño Responsivo:** Layout adaptativo basado en principios *Mobile First*, garantizando compatibilidad total con dispositivos móviles, tablets y monitores de escritorio.
* **Módulo Interactivo de Donación:**
  * Selección dinámica de montos predefinidos (\$3.000, \$5.000, \$10.000 y \$20.000 CLP) e ingreso de montos personalizados.
  * Selector de modalidad de aporte (Mensual recurrente o Único).
  * Cálculo y resumen de transacción actualizado en tiempo real.
* **Procesamiento de Formulario Serverless:** Enrutamiento asíncrono (*AJAX / Fetch API*) hacia Formspree para el envío de notificaciones por correo electrónico en tiempo real, evitando recargas de página y ofreciendo feedback inmediato mediante ventana modal.

---

## 2. Arquitectura de Tecnologías

* **Frontend:** HTML5 Semántico, CSS3 (Variables CSS, Flexbox, CSS Grid) y JavaScript Vanilla ES6+.
* **Librerías Externas:** Font Awesome v6 para la iconografía de la interfaz.
* **Integración de Backend:** Formspree API para recepción e integración de datos de contacto sin servidor propio.
* **Despliegue y CI/CD:** Vercel conectado al repositorio de GitHub para despliegue continuo.

---

## 3. Estructura del Repositorio

```text
/
├── index.html          # Documento principal con la estructura, estilos e interacción
├── logo.jpeg           # Isotipo/Insignia oficial de la Compañía
├── Escudo.jpeg         # Recurso gráfico para sección Hero
└── README.md           # Documentación técnica del proyecto
