# Asesor-Academico-UNAB

Sistema de recomendación de asignaturas - UNAB Sprint 2



\# Asesor Académico UNAB



Sistema automatizado de recomendación de asignaturas para estudiantes.



\## 📦 Repositorio

https://github.com/oyanadelbastian/Asesor-Academico-UNAB



\## 🚀 Sprint 2 - Procesamiento e integración

\*\*Período:\*\* 03-nov al 23-nov-2025  

\*\*Objetivo:\*\* Flujo n8n end-to-end con generación de reportes PDF



---



\## 📁 Estructura del proyecto

```

Asesor-Academico-UNAB/

├── flujos/

│   ├── sprint1/           # HU1, HU2, HU3 (Sprint 1 completado)

│   └── sprint2/           # HU8, HU4, HU7 (en desarrollo)

├── docs/

│   ├── diagramas/         # Diagramas de flujo

│   └── plantillas/        # Templates HTML, etc.

├── datos/                 # Datos de prueba

│   ├── malla\_curricular.json

│   └── estudiantes\_prueba.json

├── .gitignore

└── README.md

```



---



\## 👥 Equipo Sprint 2



\- \*\*Product Owner:\*\* Daniel

\- \*\*Scrum Master:\*\* Mirko

\- \*\*Developer Líder:\*\* Bastián

\- \*\*Developers:\*\* Lorenzo, Diego



---



\## 📝 Cómo trabajar con Git



\### 1. Clonar el repositorio (solo la primera vez)

```bash

git clone https://github.com/oyanadelbastian/Asesor-Academico-UNAB.git

cd Asesor-Academico-UNAB

```



\### 2. Antes de empezar a trabajar (siempre)

```bash

git pull origin main

```



\### 3. Trabajar en tu HU

\- Lorenzo: Exporta tu flujo como `HU8\_Recomendaciones\_v1.json`

\- Mirko: Guarda tu plantilla como `plantilla\_reporte.html`

\- Sube a las carpetas correspondientes



\### 4. Subir tus cambios (al final del día)

```bash

git add .

git commit -m "Descripción de lo que hiciste"

git push origin main

```



\*\*Ejemplo de commits:\*\*

```

git commit -m "HU8: Add Google Sheets API integration"

git commit -m "HU4: Add HTML template for PDF report"

git commit -m "T67: Add malla curricular with 20 subjects"

```



---



\## 🔐 Credenciales



\*\*⚠️ NUNCA subir credenciales al repositorio\*\*



Las credenciales se configuran localmente en n8n:

\- Google Sheets API (OAuth2)

\- Gmail SMTP (App Password)

\- Google Drive API (OAuth2)



---



\## 📝 Nomenclatura de nodos n8n



\*\*Usar SIEMPRE estos prefijos:\*\*



\- `AUTH\_` - Autenticación

\- `API\_` - Llamadas APIs externas

\- `MAP\_` - Transformación de datos

\- `CTRL\_` - Lógica de control

\- `OUT\_` - Salidas (PDF, email, Drive)

\- `LOG\_` - Registro de eventos



\*\*Ejemplos:\*\*

\- `API\_ObtenerMalla`

\- `MAP\_ClasificarAsignaturas`

\- `OUT\_GenerarPDF`

\- `OUT\_EnviarCorreo`



---



\## 🎯 Historias del Sprint 2



| HU | Descripción | Responsable | Story Points |

|---|---|---|---|

| HU8 | Generación de recomendaciones | Lorenzo + Diego | 5 |

| HU4 | Reporte PDF + correo | Mirko + Bastián | 5 |

| HU7 | Flujo integrado E2E | Bastián (líder) | 8 |



\*\*Total:\*\* 18 Story Points



---



\## 📞 Contacto



\*\*Dudas técnicas:\*\* Bastián (dev líder)  

\*\*Dudas de alcance:\*\* Daniel (PO)  

\*\*Impedimentos:\*\* Mirko (SM)



---



\*\*Última actualización:\*\* 12-nov-2025

