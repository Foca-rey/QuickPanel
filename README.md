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
