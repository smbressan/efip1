# Gestion de Expedientes Judiciales


> El siguiente caso describe un sistema de gestion de expedientes judiciales. Se desarrollan algunos requerimientos funcionales, requerimientos no funcionales como asi tambien los diagramas de Casos de Uso, diagrama de clases y diagrama de red.  

## :memo: Requerimientos Funcionales

- RF1: El sistema debe permitir al donante crear su perfil de donante con nombre, dirección, correo electrónico y teléfono. 
- RF2: El sistema debe permitir al donante iniciar sesión utilizando su Correo electrónico y contraseña. 
- RF3: El sistema debe permitir al donante visualizar las campañas disponibles 
- RF4: El sistema debe permitir al donante realizar una donación, eligiendo el monto a donar y la posibilidad de pagarlo con tarjeta o desde una transferencia bancaria y asignarla a una campaña específica. 
- RF5: El sistema debe ser capaz de generar y enviar automáticamente recibos o certificados de donación a los donantes cuando se acredita una donación a una campaña.
- RF6: El sistema debe permitir al administrador iniciar sesión con usuario y contraseña
- RF7: El sistema debe permitir al administrador la creación, gestión, eliminación y seguimiento de campañas de recaudación de fondos, incluyendo la definición de objetivos financieros, descripciones, y configuración de fechas de inicio y finalización.
- RF8: El sistema debe permitir al administrador geneonante realizar una donación, eligiendo el monto a donar y la posibilidad de pagarlo con tarjeta o desde una transferencia bancaria y asignarla a una campaña específica.rar informes financieros y estadísticos que permitan el seguimiento de donaciones y el análisis del progreso de las campañas de recaudación de fondos.
- RF9: El sistema debe integrar funcionalidades para enviar comunicaciones personalizadas a los donantes, incluyendo, pero no limitado a, agradecimientos y actualizaciones de campañas, a través de correo electrónico o correo tradicional.

### :memo: Requerimientos No Funcionales

- RNF1: El sistema debe poder ser ejecutado en sistema operativo Windows, asi como tambien en Celulares android y Iphone
- RNF2: El sistema debe estar disponible las 24 hs del dia , los 7 dias de la semana
- RNF3: La base de datos debe ser MySQL 11, con encriptación y sus discos deben ser capaces de procesar 3000 operaciones de entrada/salida por segundo. 
- RNF4: El sistema debe ser adaptable a diferentes dispositivos y plataformas: Tablet, celular, PC
- RNF5: El sistema debe contar con mecanismos de recuperación de desastres y copias de seguridad incrementales diarias. 

:::info
:bulb: **Info:** Solo los requerimientos funcionales deben ser tenidos en cuenta a la hora de escribir los casos de uso. 
:::

### :mag_right: Casos de Uso

| CU # | Nombre CU                         | RF # |
| -----|-----------------------------------|------
| 1    | Crear Perfil                      | RF1
| 2    | Iniciar Sesion                    | RF2, RF6
| 3    | Enviar comunicacion personalizada | RF9
| 4    | Ver campaäas                      | RF3
| 5    | Realizar Donacion                 | RF4
| 6    | Pagar Donacion                    | RF4
| 7    | Enviar Recibo                     | RF5
| 8    | Gestionar Campaöas                | RF7
| 9    | Generar informe                   | RF8
| 10   | Asignar Donacion                  | RF4





---
:::info
### Diagramas
Los diagramas de casos de uso, clases y red se encuentran en github
:::


