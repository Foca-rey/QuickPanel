# QuickPanel

QuickPanel is a modern, customizable floating desktop panel for Windows, inspired by the visual style of Windows 11.

> **Status:** The project is currently in preparation. The features described below are project goals and should not be considered implemented until functional code exists for them.

## Planned Features

- Digital clock and calendar.
- Real system information: CPU, RAM, and storage usage.
- Quick notes saved locally.
- Shortcuts to programs.
- Light and dark themes.
- A floating, always-on-top window that can be moved around the desktop.

## Planned Technologies

- Electron
- React, JSX, and CSS
- Target compatibility: Windows 10 and Windows 11

The application is designed to operate locally, without external services. Its Electron integration should keep Node.js disabled in the renderer process and use a minimal, validated API through `preload`/IPC.

## Setup and Running

The project structure and development/build commands will be defined alongside the implementation. Once `package.json` is added, use its scripts to install dependencies, start the application, and generate the Windows installer. No executable or compiled installer is included yet.

## Privacy

The goal is to store notes and preferences on the user's computer and obtain PC metrics directly from the local system. No external services or simulated performance data should be added.

## Credits and License

QuickPanel is distributed under the **QuickPanel Attribution License 1.0**, included in [`LICENSE`](LICENSE). If you copy, modify, or redistribute the project or substantial portions of it, you must give credit to **Foca-rey** and include a visible link to [https://github.com/Foca-rey](https://github.com/Foca-rey), while also retaining the license notice. See `LICENSE` for the complete terms.

## Contributions

Contributions are welcome. Before opening a proposal, verify that your changes preserve Windows compatibility and comply with the project's privacy and Electron security requirements.

---

# QuickPanel

QuickPanel es una aplicación de escritorio para Windows pensada como un panel flotante, moderno y personalizable, inspirado en la estética de Windows 11.

> **Estado:** proyecto en preparación. Las funciones descritas abajo son el objetivo del proyecto y no deben considerarse implementadas hasta que exista código funcional para ellas.

## Funciones previstas

- Reloj digital y calendario.
- Información real del sistema: CPU, memoria RAM y almacenamiento.
- Notas rápidas guardadas localmente.
- Accesos directos a programas.
- Temas claro y oscuro.
- Ventana flotante, siempre visible y desplazable por el escritorio.

## Tecnologías previstas

- Electron
- React, JSX y CSS
- Compatibilidad objetivo: Windows 10 y Windows 11

La aplicación está pensada para funcionar localmente, sin servicios externos. La integración con Electron deberá mantener desactivada la ejecución de Node.js en el proceso de renderizado y utilizar una API mínima y validada mediante `preload`/IPC.

## Preparación y ejecución

La estructura y los comandos de desarrollo/compilación se definirán junto con la implementación. Cuando se añada `package.json`, consulta sus scripts para instalar dependencias, iniciar la aplicación y generar el instalador de Windows. No se incluye todavía un ejecutable ni un instalador compilado.

## Privacidad

El objetivo es guardar notas y preferencias en el equipo y obtener las métricas del PC desde el propio sistema. No se deben añadir servicios externos ni datos de rendimiento simulados.

## Créditos y licencia

QuickPanel se distribuye bajo la **QuickPanel Attribution License 1.0**, incluida en [`LICENSE`](LICENSE). Si copias, modificas o redistribuyes el proyecto o partes sustanciales de él, debes dar crédito a **Foca-rey** e incluir un enlace visible a [https://github.com/Foca-rey](https://github.com/Foca-rey), además de conservar el aviso de licencia. Consulta `LICENSE` para conocer las condiciones completas.

## Contribuciones

Las contribuciones son bienvenidas. Antes de abrir una propuesta, comprueba que los cambios mantienen la compatibilidad con Windows y respetan los requisitos de privacidad y seguridad de Electron.
