# Microsoft 365 — Tickets de Soporte Técnico N1

Documentación de incidentes simulados utilizando herramientas gratuitas de Microsoft 365, enfocados en diagnóstico, resolución y validación de problemas frecuentes de usuarios.

## M365-001 — Problema de recepción de correos en Outlook

**Servicio:** Outlook Web  
**Estado:** Resuelto

**Problema:** Un usuario no recibe determinados correos en su bandeja de entrada.

**Diagnóstico:** Se identifica una regla de Outlook que mueve automáticamente los mensajes a otra carpeta.

**Solución:** Se desactiva la regla y se realiza una nueva prueba de recepción.

**Resultado:** Los correos llegan correctamente a la bandeja de entrada.

### Evidencias

![Regla de correo](img/01-regla.png)

![Correo en carpeta incorrecta](img/02-diagnostico.png)

![Recepción correcta](img/03-solucion.png)

---

## M365-002 — Problema de sincronización en OneDrive

**Servicio:** OneDrive (Windows 11 / Web)  
**Estado:** Resuelto

**Problema:** Los archivos modificados localmente no se actualizan en OneDrive Web.

**Diagnóstico:** Se detecta que la sincronización del cliente OneDrive está pausada.

**Solución:** Se reanuda la sincronización desde el cliente de Windows.

**Resultado:** Se verifica que los archivos se actualizan correctamente en la nube.

### Evidencias

![Sincronización pausada](img/04-pausado.png)

![Diagnóstico](img/05-diagnostico.png)
![Diagnóstico2](img/05-1-diagnostico.png)

![Sincronización reanudada](img/06-solucion.png)

![Archivo sincronizado](img/07-validacion.png)

---

**Entorno:** Windows 11, Outlook Web, OneDrive y cuentas personales de Microsoft.

*Incidentes simulados en un entorno de laboratorio con fines de aprendizaje y documentación técnica.*