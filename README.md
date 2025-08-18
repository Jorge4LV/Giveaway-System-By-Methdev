
<div align="center">

# 🎉 Giveaway System By MethDev  

![MethDevLogo](https://github.com/user-attachments/assets/8b6128e7-d26a-47e3-b587-e51b1619d157)


![Static Badge](https://img.shields.io/badge/MethDev-Neon%20Dark-7D00FF?style=for-the-badge&logo=github&logoColor=00FFE1)  
![Static Badge](https://img.shields.io/badge/Status-Activo-00FFE1?style=for-the-badge&logo=discord&logoColor=7D00FF)  
![Static Badge](https://img.shields.io/badge/BDFD-Compatible-FF00FF?style=for-the-badge&logo=codeforces&logoColor=00FFE1)  

</div>  

---

## 🌌 Introducción  

Después de algunos obstáculos, **MethDev** trae para ustedes el **Sistema de Giveaways** para **BDFD** ⚡.  

Aunque intentamos simplificarlo lo más posible, la realidad es que debido a las limitaciones de **BDFD**, fue necesario hacer ciertas maniobras para que este sistema funcione.  
Esperamos que les sea de gran utilidad.  

---

## ⚠️ ADVERTENCIA ⚠️  

<div align="center">

❌ **Está prohibido modificar el sistema**.  
❌ **Está prohibido hacer un uso indebido o intentar aprovecharse del sistema**.  
✅ Si detectamos **actividad inusual** de algún usuario, cuenta o dispositivo, nos reservamos el derecho de **bloquear su acceso permanentemente**.  

</div>

> 💀 El incumplimiento de estas reglas resultará en un **bloqueo sin previo aviso**, sin posibilidad de apelación.  

---

## 📌 ¿Qué se necesita?  

1. **Acceder a la plataforma MethDev** y enlazar tu cuenta de Discord.  
   - 🔒 *Solo obtenemos tu ID, avatar y nickname.* - 🚫 *No recopilamos información confidencial.* 2. **Generar tu Token único** desde la plataforma.  
   - Este token es **personal e intransferible**.  
   - Compartirlo puede resultar en un **baneo permanente** bajo nuestros **Términos y Condiciones**.  

3. **Configurar el sistema de Giveaway** en BDFD con las variables necesarias.  

---

## 🛠️ Variables necesarias  

| Nombre Variable | Valor                                                                 | Tipo |
|-----------------|----------------------------------------------------------------------|------|
| `sysgive`       | `{"estado": "0", "canal": "No", "time": "0", "create": "No", "token": "No", "id": "0", "win": "1"}` | JSON |

---

## 🚀 Instrucciones para la Configuración

A continuación, te guiaremos a través de los pasos necesarios para configurar y poner en marcha el sistema de sorteos en tu servidor.

### Paso 1: Obtén tu Token Personal

El primer paso es conseguir tu token, que es esencial para que el sistema funcione.

1.  Dirígete a la página de MethDev: **[https://giveaway-by-methdev.vercel.app/](https://giveaway-by-methdev.vercel.app/)**
2.  Inicia sesión con la cuenta de Discord que usarás para el sistema. Ten en cuenta que solo se accederá a tu nombre de usuario, avatar, correo electrónico y los servidores a los que perteneces.
3.  Una vez completado el inicio de sesión, recibirás tu **token personal**. Este token es único y no debe ser compartido.

> **⚠️ Aviso:** MethDev se reserva el derecho de bloquear o eliminar el acceso al sistema si se detecta un uso indebido. Se recomienda usar el sistema con discreción.

### Paso 2: Descarga el Código del Sistema

Con tu token en mano, el siguiente paso es obtener el código necesario para BDFD.

1.  Accede a este mismo repositorio de GitHub.
2.  Aquí encontrarás tanto el **código base** como el de las **interacciones**, que son cruciales para el funcionamiento del sistema.

### Paso 3: Configura el Sistema en BDFD

Ahora, es el momento de integrar el código en Bot Designer for Discord.

1.  Coloca el código base y el de las interacciones en tu bot de BDFD.
2.  En el código de la interacción `$onInteraction`, busca la variable llamada `token`.
3.  Configura esta variable con el **token personal** que obtuviste en el paso 1.
4.  El código base se puede ejecutar de dos maneras:
    * **Comando trigger:** `.giveaway`
    * **Comando slash:** `/giveaway`

### Paso 4: Aprende a Usar el Sistema

Una vez configurado, te animamos a explorar y hacer pruebas para familiarizarte con el sistema.

> **Importante:** Por limitaciones técnicas, solo se admiten sorteos con tiempos preestablecidos. La edición o mala configuración del sistema podría resultar en el baneo del usuario.

### Paso 5: ¡Disfruta!

¡Listo! Ya puedes disfrutar del sistema de sorteos que MethDev ha desarrollado para tu comunidad. Esperamos que les sea de gran utilidad.

---

<div align="center">💡 MethDev — creando sistemas potentes, seguros y con estilo Neón/Dark para la comunidad.

</div>

