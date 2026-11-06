# test-manager-library-3239188-page

> **Prueba técnica · Ficha ADSO 3239188**  
> Sitio público estático de presentación para *Manager Library*.

Este repositorio contiene la **página pública estática** e informativa de la biblioteca.

---

## 1. Cumplimiento del Spec (Tarea T-23)

* **Autónomo e independiente:** Se ejecuta y se visualiza directamente sin requerir conexión a la API backend.
* **Diseño responsive:** Optimizado para dispositivos móviles, tablets y pantallas de escritorio.
* **Contenido alineado a reglas de negocio:**
  * Presentación de las **cinco categorías oficiales** (Novela, Ciencia, Tecnología, Historia, Infantil).
  * Políticas de préstamo de 14 días y límite de 3 libros sin devolver por socio.
  * Horarios de atención, servicios de afiliación de socios y preguntas frecuentes.

---

## 2. Cómo visualizarlo

No requiere compilación ni dependencias de Node.js:

1. Abrir directamente el archivo `index.html` en cualquier navegador web moderno:
   * Doble clic en `index.html`
   * O con extensión *Live Server* en VS Code.
   * O usando un servidor estático rápido:
     ```bash
     npx serve .
     # o con python:
     python -m http.server 8080
     ```

2. Abrir en el navegador: `http://localhost:8080`.
