Proyecto Final: Página Web Colaborativa en GitHub

🎯 Objetivo del proyecto
Aplicar el flujo de trabajo de Git y GitHub en equipo, desarrollando una página web sencilla (por ejemplo, una landing page o portafolio) con ramas, commits, merges y Pull Requests.

🧱 1. Estructura sugerida del proyecto
Tipo de proyecto recomendado:
Sitio estático simple (HTML, CSS, opcionalmente JavaScript)
Sin frameworks ni dependencias externas
Enfocado en la colaboración, no en la complejidad del código
Ejemplos posibles:

    🌐 Página institucional del curso
    (Con secciones: inicio, participantes, galería, contacto)
    🧑‍💻 Portafolio colaborativo
    (Cada alumno crea su tarjeta o perfil con su nombre y enlaces)
    🎓 Mini sitio “Aprendiendo Git y GitHub”
    (Explica comandos básicos y muestra ejemplos de código)

🧩 2. Estructura básica del repositorio
/mi-pagina-github
│
├── index.html
├── style.css
├── /img
│   └── logo.png
├── /participantes
│   ├── leonicio.html
│   ├── ana.html
│   └── jose.html
└── README.md
index.html → estructura base del sitio
style.css → estilos compartidos
/participantes → cada alumno agrega su propio archivo o sección
README.md → descripción y guía del proyecto

Fase 1 – Preparación
El instructor crea el repositorio principal en GitHub.
Cada estudiante hace un fork del repositorio y lo clona localmente.
Fase 2 – Trabajo individual
Cada estudiante:
    Crea una nueva rama con su nombre:
    Crea su sección (por ejemplo, participantes/leonicio.html).
    Hace commits descriptivos:
    Sube su rama
Fase 3 – Integración
Desde GitHub, cada alumno abre un Pull Request hacia la rama main.
El instructor o un líder revisa y acepta los cambios (simulando revisión de código).
Si hay conflictos, se resuelven en equipo.
Fase 4 – Publicación
Cuando el proyecto esté integrado, se activa GitHub Pages:
Ir a Settings → Pages → Branch: main → / (root)
GitHub genera la URL del sitio (ejemplo: https://usuario.github.io/mi-pagina-github/)

⚙️ 4. Roles sugeridos
Para fomentar la colaboración:
Rol	                    Función
Líder de proyecto	    Revisa y aprueba pull requests
Diseñador/a	            Mejora el estilo CSS
Redactor/a	            Escribe contenido del sitio o README
Desarrollador/a	        Añade secciones o interactividad simple
Tester	                Revisa enlaces y errores visuales

📘 5. Evaluación práctica sugerida
Criterio	                                    Porcentaje
Configuración correcta del entorno Git/GitHub	20 %
Uso de ramas y commits con mensajes claros	    25 %
Correcto uso de pull requests y merges	        25 %
Contribución funcional al proyecto web	        20 %
Trabajo colaborativo y comunicación	            10 %