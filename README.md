# ASIR_Mission-Start
Acabas de ser contratado como Desarrollador Junior en NextGen Web Solutions. Tu primera misión no es escribir código desde cero, sino preparar tu "estación de combate" digital y resolver un problema de rendimiento que está afectando a un cliente importante.  +1

Milestone 1: Setup del Entorno y Repositorio

Issue 1: Configurar VS Code.
Descripción: Instalar las extensiones ESLint y Prettier, y activar el formato automático al guardar. Esto automatiza la limpieza del código y evita fallos de sintaxis básicos sin tener que revisarlo a mano.

Issue 2: Inicializar dependencias.
Descripción: Ejecutar npm init -y en la terminal. Esto genera el archivo package.json, que es el inventario donde se registrarán las librerías externas que necesite el proyecto.

Issue 3: Configurar control de versiones.
Descripción: Arrancar Git, crear el archivo .gitignore (imprescindible incluir node_modules/ para no subir archivos pesados e innecesarios) y realizar el primer commit para asegurar el estado inicial.

Milestone 2: Auditoría y Diagnóstico

Issue 4: Analizar tiempos de carga.
Descripción: Usar la pestaña Network de las DevTools para ordenar los recursos por peso y tiempo. El objetivo es detectar qué imágenes o scripts están ralentizando la web del cliente.

Issue 5: Revisar códigos de estado.
Descripción: Rastrear las peticiones en la red buscando fallos. Hay que localizar códigos 4xx (recurso no encontrado/sin permisos) o 5xx (caída del servidor) que estén rompiendo la carga.

Issue 6: Identificar errores silenciosos.
Descripción: Inspeccionar la pestaña Console del navegador para cazar errores de JavaScript (en rojo). Son fallos que bloquean funciones de la página por debajo, sin avisar al usuario.

Milestone 3: Reporte y Acción

Issue 7: Documentar hallazgos.
Descripción: Redactar un reporte conciso con los cuellos de botella de red y los fallos de consola exactos encontrados durante la auditoría del sprint anterior.

Issue 8: Aplicar correcciones iniciales.
Descripción: Empezar a tocar el código para solucionar los errores críticos de JavaScript detectados en la consola y estabilizar el funcionamiento básico de la web.