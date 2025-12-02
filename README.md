<!-- algo x: introducir algo en blanco aquí -->

# Cómo crear un Pull Request (PR) — Guía breve

Esta es una guía corta en español para crear un Pull Request en GitHub. Está pensada para estudiantes que están aprendiendo el flujo básico de trabajo con Git.

**Resumen:**
- **Crear una rama:** trabajar en una rama nueva para tu cambio.
- **Hacer commits claros:** commits pequeños y descriptivos.
- **Subir la rama (push):** compartir tu trabajo en el remoto.
- **Abrir PR:** crear el Pull Request en GitHub y pedir revisión.

**Pasos detallados (línea de comandos):**

1. Asegúrate de estar en la rama principal y traer los últimos cambios:

```bash
git checkout main
git pull origin main
```

2. Crea y muévete a una rama nueva (usa un nombre descriptivo):

```bash
git checkout -b feature/mi-cambio
```

3. Haz tus cambios en el código/archivos y agrégalos al stage:

```bash
git add archivo1 archivo2
git commit -m "Breve descripción del cambio"
```

4. Sube la rama al remoto:

```bash
git push -u origin feature/mi-cambio
```

5. Ve a GitHub, abre la página del repositorio y crea un nuevo Pull Request desde `feature/mi-cambio` hacia `main` (u otra rama objetivo).

6. En el PR escribe un título claro y una descripción que explique:
- Qué problema resuelve o qué agrega.
- Pasos para probarlo (si aplica).
- Si requiere revisión específica (por ejemplo, revisar tests o estilo).

**Checklist recomendable antes de pedir revisión:**
- [ ] El código compila o corre localmente.
- [ ] No hay errores obvios ni pruebas rotas.
- [ ] Mensajes de commit claros.
- [ ] Documentación o comentarios mínimos si es necesario.

Si quieres, puedo añadir un ejemplo de título y descripción de PR o ayudarte a crear un mensaje de commit.

<!-- Nota: el comentario anterior con 'algo x' sirve como placeholder para introducir contenido en blanco o instrucciones internas. -->

