# Ayuda de StartWork

> [Deutsch](../support) · [English](../en/support) · [Français](../fr/support) · [Português](../pt/support)

StartWork registra el tiempo de trabajo en Jira. La app funciona en tu
dispositivo y solo se comunica con **tu propia** instancia de Jira.

**Contacto:** [info@iamnotadev.xyz](mailto:info@iamnotadev.xyz)
Respuesta normalmente en pocos días. Puedes escribir en español; la
respuesta llega en inglés o alemán.

Para ayudarte más rápido, indica: la versión de la app, si usas Jira Cloud o
Jira Server/Data Center, y el texto exacto del mensaje de error.

---

## Preguntas frecuentes

### ¿Qué versiones de Jira son compatibles?

Jira Cloud (`…atlassian.net`) y también Jira Server y Data Center. Con Cloud
inicias sesión con tu correo y un token de API; con Server y Data Center, con
un token de acceso personal.

### ¿Dónde consigo un token?

**Jira Cloud:** en <https://id.atlassian.com/manage-profile/security/api-tokens>.

**Jira Server / Data Center:** en tu Jira, en *Perfil → Personal Access
Tokens*. Si esa opción no aparece, los administradores de Jira la han
desactivado — entonces solo queda pedírselo a ellos.

### La app dice que mi ticket no existe.

O la clave es incorrecta, o tu cuenta no tiene permiso para ver el ticket.
Puedes comprobar ambas cosas abriendo el ticket en el propio Jira.

### No puedo registrar tiempo en un ticket.

Si el ticket está en un estado como «cerrado» o «hecho», Jira bloquea el
registro de tiempo. Tampoco se puede evitar en el propio Jira — elige un
ticket abierto.

### Usamos Tempo. ¿Funciona?

Sí. StartWork escribe un registro de trabajo estándar de Jira, y Tempo lee
esos registros. **Pero:** si tu empresa exige campos de Tempo (*Work
Attributes*), quedan vacíos. Que eso baste depende de tu configuración.

### ¿Qué pasa con mis datos?

Se quedan en el dispositivo. No hay servidor del proveedor, ni cuenta, ni
analítica. Los detalles están en la [política de privacidad](./).

### ¿Cómo lo borro todo?

*Icono del engranaje → Borrar todos los datos de este dispositivo.* Esto
elimina las credenciales, tus propios mosaicos y todo el historial. El tiempo
ya registrado en Jira no se ve afectado — está en el servidor de Jira.

### ¿Qué hace «Pulir»?

El botón envía tu comentario del registro a Anthropic y recibe una redacción
objetiva. Viene **desactivado** y necesita dos cosas: tu propia clave de
Anthropic y tu consentimiento expreso. Sin ambas, nada sale del dispositivo.
Puedes retirar el consentimiento en cualquier momento desde el icono del
engranaje.

### ¿Qué idiomas habla la app?

Español, inglés, alemán, francés y portugués. Sigue el idioma de tu iPhone;
en el icono del engranaje puedes elegir uno expresamente.

---

Jira es una marca de Atlassian y Tempo una marca de Tempo ehf. StartWork no
está vinculado a estas empresas.
