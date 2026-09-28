# Política de privacidad — StartWork

Versión del 28 de septiembre de 2026 · Información según el art. 13 del RGPD

> Esta traducción se ofrece por comodidad. La
> [versión alemana](https://daddycation.github.io/startwork-datenschutz/)
> es la jurídicamente vinculante.
>
> [English](https://daddycation.github.io/startwork-datenschutz/en/) · [Français](https://daddycation.github.io/startwork-datenschutz/fr/) · [Português](https://daddycation.github.io/startwork-datenschutz/pt/)

## Lo esencial en tres frases

StartWork funciona en tu dispositivo. El proveedor de esta app **no recoge,
no almacena ni recibe ningún dato tuyo** — no hay servidor del proveedor, ni
cuenta, ni analítica, ni seguimiento, ni identificadores publicitarios.

Los datos solo salen de tu dispositivo hacia destinos **que eliges tú**.

## 1. Responsable del tratamiento

```
Philip Müller
Theaterstraße 27
09111 Chemnitz
Alemania

Correo: info@iamnotadev.xyz
```

Según el Reglamento de Servicios Digitales de la UE (DSA), estos mismos datos
aparecen como información del comerciante en la página de la app en el App
Store. Es obligatorio para una app de pago y no se puede desactivar.

## 2. Qué se guarda en el dispositivo

| Datos | Dónde | Finalidad |
|---|---|---|
| Dirección de tu instancia de Jira, correo (solo Cloud), ajustes | Almacenamiento del dispositivo (iOS: UserDefaults) | para no tener que introducirlos cada vez |
| Token de acceso de Jira, clave de IA | **Llavero del dispositivo** (iOS: Keychain) | inicio de sesión en tu instancia de Jira |
| Tus registros de tiempo (ticket, duración, comentario, hora) | Almacenamiento del dispositivo | vista del día y de los días anteriores |

Nada de esto se transmite al proveedor. **Base jurídica:** art. 6.1.b) del
RGPD — sin estos datos la app no puede cumplir su función.

## 3. Adónde van los datos

### 3.1 Tu instancia de Jira

Al registrar tiempo, StartWork envía la clave del ticket, la duración, la hora
de inicio y tu comentario **al servidor de Jira que tú mismo indicaste**. Tu
token se envía para iniciar sesión; al buscar un ticket, se envía su clave.

Quién opera ese servidor y qué ocurre allí **no** lo determina el proveedor
de esta app — normalmente es tu empresa o Atlassian. El operador de la
instancia es responsable de ese tratamiento.

### 3.2 Anthropic (opcional, solo con tu consentimiento)

La función «Pulir» envía **tu comentario del registro junto con la clave y el
título del ticket** a Anthropic (`api.anthropic.com`, Estados Unidos), donde
el texto se procesa y se devuelve reformulado.

Esto ocurre **solo** si

1. has guardado tu propia clave de Anthropic **y**
2. has aceptado expresamente la transferencia en un diálogo aparte **y**
3. usas de verdad ese botón.

**Base jurídica:** art. 6.1.a) del RGPD (consentimiento). La transferencia a
EE. UU. se basa en la relación contractual entre tú y Anthropic — usas tu
propio acceso.

**Retirada:** en cualquier momento desde el icono del engranaje, sin dar
motivos y sin limitar el resto de la app. La retirada surte efecto hacia el
futuro.

Aviso de privacidad de Anthropic: <https://www.anthropic.com/legal/privacy>

### 3.3 Nada más

Sin analítica, sin informes de fallos, sin redes publicitarias, sin fuentes
ni scripts de servidores de terceros. La app no contiene componentes que
abran una conexión sin una acción tuya.

## 4. Conservación

Hasta que lo borres. No hay borrado automático.

**Borrarlo todo:** icono del engranaje → «Borrar todos los datos de este
dispositivo». Esto elimina las credenciales, la clave de IA, tus propios
mosaicos y todo el historial de registros. Si se elimina la app, todo se va
con ella.

El tiempo **ya registrado en Jira** no se ve afectado — está en el servidor
de tu instancia y hay que borrarlo allí.

## 5. Tus derechos

Acceso, rectificación, supresión, limitación, portabilidad y oposición
(arts. 15 a 21 del RGPD), además del derecho a presentar una reclamación ante
una autoridad de control (art. 77 del RGPD).

En la práctica: como el proveedor **no** tiene ningún dato tuyo, no hay nada
que comunicar ni que borrar. Todos los datos están en tu dispositivo, bajo tu
control. Para los datos de tu instancia de Jira, dirígete a su operador.

## 6. Menores

La app está dirigida a profesionales, no a menores.

## 7. Cambios

La fecha de arriba se actualiza cuando cambia esta política. Los cambios
importantes en las transferencias de datos requieren un nuevo
consentimiento.
