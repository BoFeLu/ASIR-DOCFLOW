# DOCFLOW_AULA.md
## Guía de aula — Workflow profesional de documentación técnica ASIR-DevOps

### 1. Propósito de la práctica

Familiarizar al alumnado con el concepto de “documentación como código” (Docs-as-Code), aplicando principios DevOps y herramientas profesionales para la creación, versionado y automatización de documentación técnica.

El objetivo no es solo generar un PDF, sino entender cómo la documentación puede integrarse en los mismos flujos de trabajo que el software o la infraestructura.

---

### 2. Objetivos de aprendizaje

1. Comprender la utilidad del formato Markdown en entornos profesionales.  
2. Aprender a automatizar tareas mediante Makefile (Linux) o PowerShell script (Windows).  
3. Introducir el uso básico de Pandoc y XeLaTeX para conversión de formatos.  
4. Practicar versionado con Git y publicación automatizada mediante CI/CD (GitHub Actions).  
5. Aplicar los principios DevOps a la documentación: reproducibilidad, trazabilidad y mejora continua.  
6. Desarrollar hábitos de escritura técnica profesional y colaborativa.

---

### 3. Competencias específicas

- ASIR-MOD-1: Administración de sistemas operativos — organización, documentación y mantenimiento.  
- ASIR-MOD-3: Implantación de aplicaciones web — control de versiones y documentación técnica.  
- ASIR-MOD-4: Planificación y administración de redes — registro y seguimiento de configuraciones.  
- Competencia transversal: Comunicación técnica clara, documentada y verificable.

---

### 4. Material necesario

- PC con Linux o Windows.  
- Visual Studio Code (editor recomendado).  
- Pandoc + XeLaTeX instalados.  
- Acceso opcional a GitHub (para pruebas de automatización).  
- Archivos base del ejercicio:  
  - docflow-template.zip (Linux)  
  - docflow-windows.zip (PowerShell)

---

### 5. Actividades propuestas

1. Abrir la plantilla y crear una guía técnica propia (por ejemplo, instalación de servidor Apache o configuración de red virtual).  
2. Editar el Markdown en VSCode.  
3. Generar el PDF mediante make pdf o .\build-doc.ps1.  
4. Revisar el resultado (encabezados, tabla de contenidos, formato).  
5. (Opcional) Versionar con Git y activar el flujo de GitHub Actions para generación automática.  
6. Entregar al profesor el PDF final y la estructura de proyecto.

---

### 6. Criterios de evaluación

| Criterio | Indicador de logro | Ponderación |
|-----------|--------------------|--------------|
| Estructura profesional del documento | Cumple formato, índice y coherencia de secciones | 20 % |
| Uso de Markdown y formato limpio UTF-8 | Sin estilos ocultos ni errores de sintaxis | 15 % |
| Automatización funcional | make pdf o build-doc.ps1 generan correctamente el PDF | 25 % |
| Control de versiones (opcional) | Uso correcto de Git (commits, tags, historial) | 15 % |
| Presentación y redacción técnica | Claridad, lenguaje formal, ortografía | 15 % |
| Entrega y autoevaluación | Cumple plazos, verifica el PDF final | 10 % |

---

### 7. Observaciones metodológicas

- La práctica puede realizarse individualmente o en parejas.  
- Ideal para sesiones de 2-3 horas de duración.  
- En centros sin Linux, usar la versión PowerShell (docflow-windows.zip).  
- Permite integrar esta actividad en proyectos mayores (por ejemplo, documentación de despliegue DevOps).  
- Refuerza simultáneamente competencias técnicas y comunicativas.
