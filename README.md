# ⚡ bfeOS — Windows Limpio, Privado y Listo para Usar

![Windows 10/11](https://img.shields.io/badge/Compatibilidad-Windows%2010%20%2F%2011-blue?logo=windows)
![Estado](https://img.shields.io/badge/Estado-Estable-brightgreen)
![Licencia](https://img.shields.io/badge/Licencia-MIT-orange)

**bfeOS** es una versión/modificación optimizada de Windows diseñada para ofrecer el máximo rendimiento, eliminar el bloatware innecesario, proteger tu privacidad y proporcionar una experiencia limpia y lista para usar desde el primer inicio.

---

## 🌟 Características Principales

- 🚀 **Alto Rendimiento:** Eliminación de procesos en segundo plano y servicios innecesarios de Windows.
- 🛡️ **Privacidad Mejorada:** Telemetría, rastreadores y servicios de recolección de datos desactivados por defecto.
- 🧹 **Sin Bloatware:** Libre de aplicaciones preinstaladas molestas (Cortana, Candy Crush, widgets publicitarios, etc.).
- 📦 **Listo para Usar:** Incluye configuraciones básicas listas para trabajar, jugar o transmitir sin perder tiempo configurando.
- 💻 **Bajo Consumo de RAM y CPU:** Ideal para aprovechar al máximo el hardware de tu equipo.

---

## 🛠️ Modificaciones y Ajustes (Tweaks)

| Categoría | Cambios aplicados |
| :--- | :--- |
| **Privacidad** | Desactivación de Telemetría, Bing Search en el menú inicio, Keylogger de Windows y Diagnósticos. |
| **Rendimiento** | Optimización de plan de energía, reducción de latencia del sistema y servicios innecesarios detenidos. |
| **Interfaz** | Menú contextual limpio, explorador de archivos ágil y sin distracciones. |
| **Redes** | Optimizaciones en la pila TCP/IP y desactivación de descargas automáticas en segundo plano. |

---

## 📥 Descarga e Instalación

> ⚠️ **Nota:** Se recomienda realizar una copia de seguridad de tus archivos importantes antes de procedes con la instalación.

### 1. Descargar la Imagen / Script
Puedes descargar la versión más reciente en la sección de [Releases](../../releases).

### 2. Crear un USB Booteable
Para grabar la ISO en un pendrive, recomendamos usar **Rufus**:
- [Descargar Rufus](https://rufus.ie/)
- Formato recomendado: **GPT / UEFI** o **MBR / Legacy** según tu tarjeta madre.

### 3. Instalación
1. Conecta el USB a tu PC y reinicia ingresando al menú de arranque (Boot Menu).
2. Selecciona la unidad USB y sigue las instrucciones en pantalla.
3. Al finalizar, el sistema se reiniciará con **bfeOS** completamente configurado.

---

## ⚙️ Post-Instalación (Opcional)

Si utilizas un script de personalización adicional o quieres instalar software esencial rápidamente con `winget`:

```cmd
winget install --id Git.Git -e
winget install --id Mozilla.Firefox -e
winget install --id 7zip.7zip -e
