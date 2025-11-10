# Analizar un dashboard de gobernanza, detectar riesgos y proponer acciones

## Objetivo de la práctica:
Al finalizar la práctica, serás capaz de:
- Objetivo1
- Objetivo2
- Objetivo3

## Objetivo Visual 
Crear un diagrama o imagen que resuma las actividades a realizar, un ejemplo es la siguiente imagen. 

![diagrama1](../images/img1.png)

## Duración aproximada:
- xx minutos.

## Tabla de ayuda:
Agregar una tabla con la información que pueda requerir el participante durante el laboratorio, como versión de software, IPs de servers, usuarios y credenciales de acceso.
| Contraseña | Correo | Código |
| --- | --- | ---|
| Netec2024 | edgardo@netec.com | 123abc |

## Instrucciones 
<!-- Proporciona pasos detallados sobre cómo configurar y administrar sistemas, implementar soluciones de software, realizar pruebas de seguridad, o cualquier otro escenario práctico relevante para el campo de la tecnología de la información -->

### Tarea 1. Pasos básicos para intentar activar los flujos del CoE Core
Paso 1. Abrir el entorno correcto

Entra a make.powerapps.com

Arriba a la derecha selecciona el entorno donde instalaste el Core Components.

Paso 2. Ir a la solución del CoE Core

Navega a Soluciones → Center of Excellence – Core Components.

Paso 3. Filtrar los flujos más relevantes para la demo

Busca y muestra estos (mínimos para ilustrar el propósito):

Admin | Sync Template v4 (Apps)

Admin | Sync Template v4 (Flows)

Admin | Sync Template v4 (Environments) *O similar como: CLEANUP HELPER - Environment Capacity

Admin | Sync Template v4 (Maker) *Opcional

Paso 4. Intentar activarlos

Abre cada flujo → clic en Activar.

Si da error (por el mensaje de InvalidPaginationPolicy o Managed properties), no es por falta de permisos del usuario ni por la licencia de Microsoft 365. Es una restricción técnica: el CoE Starter Kit viene instalado como una Managed Solution, lo que significa que sus componentes están protegidos contra edición directa. Esto lo hace Microsoft para evitar que se dañen los flujos base del kit. Por eso no podemos guardar ni activar algunos flujo.

Si quisiéramos modificar o activar estos flujos, tendríamos que instalar una versión Unmanaged del CoE Core. Esa versión sí permite editar, guardar y activar sin restricciones, porque no está protegida. 

En este curso proporcionado por Microsoft usamos un entorno de práctica educativo, por eso algunos flujos del CoE aparecen bloqueados.
Pero cuando una organización implementa el CoE Starter Kit en su propio entorno empresarial, sí puede configurarlo completamente porque cumple tres condiciones que aquí no tenemos:
1️⃣ Tiene permisos de administrador global o de Power Platform Admin.
2️⃣ Dispone de los conectores necesarios (por ejemplo, Power Platform for Admins).
3️⃣ En algunos casos, puede solicitar directamente al equipo de TI una versión Unmanaged del CoE si desean personalizar los flujos.

### Tarea 2. Importar desde Power BI. La lógica detrás de esos flujos es la que recopila datos de Power Platform y los guarda en Dataverse, para luego verse en Power BI. 

Paso 1. Debe de relatar el instructor en verbo infinito, claro y conciso cada actividad para ir construyendo paso a paso en el objetivo de la tarea.

Paso 2. <!-- Añadir instrucción -->

Paso 3. <!-- Añadir instrucción -->

### Resultado esperado
En esta sección se debe mostrar el resultado esperado de nuestro laboratorio
![imagen resultado](../images/img3.png)
