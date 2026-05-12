# 📖 MANUAL: CÓMO HICIMOS TU PÁGINA WEB
## De cero a publicada en internet

---

## 🗺️ EL MAPA GENERAL (resumen de todo)

```
TU COMPUTADOR                    INTERNET
─────────────────                ──────────────────
  Claude Code          →→→        GitHub
  (aquí construimos)   sube       (guarda el código)
                                      ↓
                                  GitHub Pages
                                  (publica la web)
                                      ↓
                               Tu link público 🌐
                    https://marilanz76-lgtm.github.io/
                              -nexora-ai-studio-/
```

---

## PASO 1 — ¿QUÉ ES CLAUDE CODE Y QUÉ HIZO?

Claude Code es Claude en versión que puede tocar archivos de tu computador.

Lo que hizo Claude:
- Escribió todo el código HTML, CSS y JavaScript de tu página
- Guardó el archivo en tu computador en la carpeta:
  C:\Users\maria\PROYECTOS CLAUDE CODE\
- Editó el archivo cada vez que pediste un cambio
- Copió las fotos de Descargas a la carpeta del proyecto

💡 Sin Claude Code tendrías que escribir el código tú misma.
   Con Claude Code él lo escribe, tú solo pides los cambios.

---

## PASO 2 — EL ARCHIVO QUE CREAMOS

Todo tu sitio web vive en UN solo archivo:

```
📁 PROYECTOS CLAUDE CODE
   │
   ├── 📄 nexora-ai-studio.html  ← Tu página web completa
   ├── 📄 index.html             ← Copia exacta (para GitHub)
   ├── 🖼️ foto1-ai-hero.png      ← Imagen del hero
   ├── 🖼️ foto2-rpa.png          ← Imagen automatización
   ├── 🖼️ nexora-logo.png        ← Tu logo
   ├── 🖼️ foto-apps.jpg          ← Imagen Desarrollo Apps
   ├── 🖼️ foto-agentes.jpg       ← Imagen Agentes IA
   ├── 🖼️ foto-landing.jpg       ← Imagen Landing Pages
   ├── 🖼️ foto-integraciones.png ← Imagen Integraciones
   └── 🖼️ foto-consultoria.png   ← Imagen Consultoría
```

💡 El index.html es la copia de tu página porque GitHub Pages
   busca siempre un archivo llamado exactamente "index.html"
   para mostrar la web.

---

## PASO 3 — ¿QUÉ ES GITHUB Y PARA QUÉ LO USAMOS?

Piensa en GitHub como una USB en la nube pero más poderosa:

| GitHub es como...  | Porque...                              |
|--------------------|----------------------------------------|
| 📦 Una bodega online | Guarda todos tus archivos            |
| 📸 Un álbum de fotos | Guarda el historial de CADA cambio   |
| 🌐 Un servidor web   | Puede publicar tu página gratis      |

¿Por qué lo necesitamos?
Cuando Claude hace cambios en tu página, solo se ven en TU COMPUTADOR.
Para que el mundo entero pueda verlos, necesitamos subir los archivos
a internet → eso lo hace GitHub.

¿En qué otros casos se usa GitHub?
- Programadores que trabajan en equipo comparten código
- Guardar versiones de un proyecto (si algo falla, puedes volver atrás)
- Publicar páginas web gratis (GitHub Pages)
- Empresas como Google y Microsoft guardan su código ahí

---

## PASO 4 — ¿QUÉ ES GITHUB PAGES?

GitHub Pages es el servicio GRATUITO de GitHub que convierte
tu código en una página web pública.

```
Tu código en GitHub  →  GitHub Pages  →  Link público
(solo tú lo ves)        (lo activa)       (todo el mundo)
```

¿Es gratis para siempre?
✅ Sí, GitHub Pages es 100% gratis para páginas estáticas
   (HTML, CSS, JS) sin límite de tiempo.

---

## PASO 5 — LOS COMANDOS QUE USAMOS (GIT)

Para subir archivos de tu computador a GitHub usamos Git.
Solo se usan 3 comandos básicos (Claude los ejecuta por ti):

```bash
# 1. PREPARAR los archivos para subir
git add index.html nexora-ai-studio.html

# 2. GUARDAR con un mensaje descriptivo
git commit -m "Descripción del cambio"

# 3. SUBIR a GitHub
git push
```

💡 Así como guardas un Word con Ctrl+S, nosotros "guardamos
   en GitHub" con estos 3 pasos. Claude los hace automáticamente.

---

## PASO 6 — ¿QUÉ ES EL TOKEN Y POR QUÉ LO NECESITAMOS?

Cuando intentamos subir a GitHub, él pregunta: "¿Quién eres tú?"
En lugar de contraseña, GitHub usa un Token — es como una llave secreta.

Tu token: guárdalo en un lugar seguro (no escribirlo en documentos públicos)
Cuando caduque, genera uno nuevo siguiendo los pasos de abajo.

⚠️ Los tokens duran un tiempo limitado. Si un día el push falla
   con error de autenticación, hay que generar uno nuevo.

¿Cómo generar un token nuevo?
1. Entra a github.com → tu foto de perfil → Settings
2. Baja hasta "Developer settings"
3. "Personal access tokens" → "Tokens (classic)"
4. "Generate new token" → selecciona "repo" → Generate
5. Copia el token y dáselo a Claude

---

## PASO 7 — EL FLUJO COMPLETO CADA VEZ QUE HACES UN CAMBIO

```
1. Le pides el cambio a Claude en el chat
        ↓
2. Claude edita el archivo en tu computador
        ↓
3. Claude copia nexora-ai-studio.html → index.html
        ↓
4. Claude ejecuta: git add + git commit + git push
        ↓
5. GitHub recibe los archivos (espera 2-3 minutos)
        ↓
6. Tú recargas con Ctrl+Shift+R y ves el cambio
```

---

## PASO 8 — ¿QUÉ ES MCP?

MCP son herramientas extras que tiene Claude Code para hacer
cosas fuera del chat:

| Herramienta MCP | Para qué sirve                                    |
|-----------------|---------------------------------------------------|
| 🌐 Browser      | Abre tu página y toma capturas para verificar     |
| 📁 Archivos     | Lee y edita archivos en tu computador             |
| 🔍 WebFetch     | Analiza páginas web externas                      |

💡 Sin MCP Claude solo puede hablar. Con MCP puede actuar —
   abrir el browser, ver tu página, editar archivos, ejecutar comandos.

---

## 📋 RESUMEN EN UNA TABLA

| ¿Qué?            | ¿Para qué?                    | ¿Lo usas tú?                    |
|------------------|-------------------------------|----------------------------------|
| Claude Code      | Escribe y edita el código     | No, lo hace Claude               |
| Archivo HTML     | Es tu página web completa     | No, lo crea Claude               |
| Git              | Sube archivos a GitHub        | No, lo hace Claude               |
| GitHub           | Almacena tu código online     | Solo para crear el repositorio   |
| GitHub Pages     | Publica tu web gratis         | Solo para activarlo (1 sola vez) |
| Token            | Contraseña para Git           | Copiar y pegar cuando caduca     |
| MCP Browser      | Verificar que todo se ve bien | No                               |
| index.html       | Copia requerida por GitHub    | No, lo hace Claude               |

---

## 🚨 ¿QUÉ DEBES RECORDAR TÚ?

Solo 3 cosas:

### 1️⃣ Tu link siempre es el mismo
https://marilanz76-lgtm.github.io/-nexora-ai-studio-/

### 2️⃣ Para ver cambios nuevos: Ctrl + Shift + R
(espera 2 minutos después de que Claude suba los cambios)

### 3️⃣ Si pides un cambio → Claude lo hace todo
Tú solo dices qué quieres cambiar 😊

---

## 📌 DATOS IMPORTANTES DE TU PROYECTO

- Repositorio GitHub: https://github.com/marilanz76-lgtm/-nexora-ai-studio-
- Página publicada:   https://marilanz76-lgtm.github.io/-nexora-ai-studio-/
- Rama (branch):      main
- Carpeta local:      C:\Users\maria\PROYECTOS CLAUDE CODE\
- WhatsApp Nexora:    +56 941142290
- Archivo principal:  nexora-ai-studio.html
- Archivo GitHub:     index.html

---

Creado con Claude Code — Mayo 2026
