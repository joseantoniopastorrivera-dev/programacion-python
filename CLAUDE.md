# Programacion-Python (Programación, 1º DAM)

## Cómo trabajar conmigo
Reglas comunes a todos mis repos (copia de mi `C:\dev\CLAUDE.md`, para que también las lean las sesiones en la nube). Soy estudiante de DAM en el IES Isidra de Guzmán.
- En prácticas evaluables, resuélvelas completas (sin modo de pistas). Al terminar, crea junto a la entrega (en `docs/` si existe) un `guia-defensa-<practica>.md` para defenderla en clase, al estilo de la guía de DataStock. No se añade a Git salvo que lo pida.
- Estructura de la guía de defensa: cómo usarla; cómo arrancar, ejecutar y ensayar sin estropear la entrega; qué pide el enunciado y dónde se cumple cada requisito; visión general (capas, flujo, decisiones de diseño a justificar); y por cada requisito: qué pide, dónde está, explicación línea a línea, cómo demostrarlo, errores típicos, preguntas de la profesora con su respuesta y 🔧 modificaciones en directo (el cambio que podrían pedir, con el código exacto y dónde va). Al final: casos prácticos «¿qué pasaría si…?», «corrige este error» (síntoma → causa → arreglo) y chuleta con plan de ensayo.
- Si la tarea es grande, antes de tocar nada dime cómo lo harías (plan por pasos) y espera a que lo apruebe o lo corrija.
- Cuando escribas código, explícalo línea por línea y di por qué elegiste esa forma y no otra.
- Si ves un error de concepto o algo que no entiendo bien, dímelo aunque no te lo pregunte.
- Responde en español.
- No hagas commit ni push sin que te lo pida. Commits sin `Co-Authored-By` ni líneas de atribución.
- No subas binarios generados (`target/`, `*.class`, `__pycache__/`, `*.pyc`, `bin/`, `obj/`, `Library/` de Unity).
- Nunca leas, muestres ni subas ficheros `.env`, tokens ni credenciales.
- PDFs, .docx, .odt y .pptx son apuntes o enunciados: léelos solo si hacen falta para la tarea.

Ejercicios y proyectos de Python por unidad. Cada carpeta es independiente; no hay entorno común ni `requirements.txt`.

## Estructura
- `ut01-introduccion-a-python-y-tipos-de-datos/` — cadenas, entrada, operadores, ejercicios de examen.
- `ut02-estructuras-condicionales/`
- `ut03-colecciones-y-estructuras-de-datos/` — teoría/guías y proyectos (Fake News Detector, Social Media Analytics…).
- `ut04-programacion-orientada-a-objetos-y-modulos/` — POO y paquetes; proyectos `proyecto_biblioteca{,2,3}`, `proyecto_tienda{,2..5}`, `proyecto_figuras{,2}`, `proyecto-dj`. Las versiones numeradas son iteraciones del mismo ejercicio: edita la que se indique.
- `ut05-operaciones-de-entrada-y-salida/` — ficheros, CSV.
- `ut06-bases-de-datos-y-sqlite/` — sqlite3, CRUD, consultas parametrizadas.
- `examen-ra04-ra05-ra06/`

## Ejecutar
- `python archivo.py` desde la carpeta del ejercicio (los proyectos usan imports relativos a su carpeta).
- Solo librería estándar salvo que el ejercicio diga otra cosa.

## Notas
- `__pycache__/` y `*.pyc` están en `.gitignore`.
