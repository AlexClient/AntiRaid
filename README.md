![](https://img.shields.io/codefactor/grade/github/Darkempire78/Raid-Protect-Discord-Bot?style=for-the-badge) 
![](https://img.shields.io/github/repo-size/Darkempire78/Raid-Protect-Discord-Bot?style=for-the-badge) 
![](https://img.shields.io/badge/SOURCERY-ENABLED-green?style=for-the-badge) <a href="https://discord.com/invite/sPvJmY7mcV"><img src="https://img.shields.io/discord/831524351311609907?color=%237289DA&label=DISCORD&style=for-the-badge"></a>

# Raid Protect Discord Bot

Raid Protect es un bot de Discord que permite proteger tu servidor de Discord de manera eficiente.

## Captcha
![](https://media.discordapp.net/attachments/971225663438741616/972266318780858418/Capture1.png?width=481&height=123)

## Instalación

Instalar todas las dependencias:

* `pip install -r requirements.txt`
* Luego coloque su token de Discord que se puede encontrar en el portal de desarrolladores de Discord dentro `config.example.json` (no cambies nada más)
* Cambiarle el nombre a `config.json`
* Este bot debe usar la "server members intents", por lo que debe habilitarlo en el portal de desarrolladores de Discord

Finalmente, aloje el bot e invítelo a su propio servidor.

## Características

Este Discord Bot protege su servidor Discord con muchas funciones.
* Captcha firewall
* Edad mínima de cuenta requerida
* imagen contra la desnudez
* Anti profanity
* AntiSpam
* Logs
* Comandos básicos de moderación
* Soporte multigremio
* Multi lenguaje (EN, FR)

¡Las restricciones no afectan a los miembros con permiso de ADMINISTRADOR!

## Logs

![](https://media.discordapp.net/attachments/971225663438741616/972266579691708496/Capture2.png?width=273&height=283)

## Comandos

```
?setup <on/off> : Configura la protección captcha.
?settings : Muestra la lista de ajustes.
?giveroleaftercaptcha <role ID/off> : Asigne un rol después de que el usuario haya pasado el captcha.
?minaccountage <number (hours)> : establezca una edad mínima para unirse al servidor (24 horas por default).
?antinudity <true/false> : Habilite o deshabilite la protección de imágenes de desnudos.
?antiprofanity <true/false> : Habilite o deshabilite la protección contra la blasfemia.
?antispam <true/false> : Habilite o deshabilite la protección contra correo no deseado.
?allowspam <#channel> (False) : Habilite o deshabilite la protección contra correo no deseado en un canal específico.
?lock | unlock <#channel> : Bloquear/Desbloquear un canal específico.

?userinfos <@user/ID> : Obtener información del usuario.

?ban <@user/ID> : Banear al Usuario
?kick <@user/ID> : Kickear a un usuario

?changeprefix <prefix> : Cambia el prefijo del bot para el Guild
?changelanguage <language> : Cambia el idioma del bot para el Guild
?help : mostrar help
```

## Posibles errores

###ImportError: no se puede importar el nombre 'joblib' forma 'sklearn.externals'
Tienes que descargar la última versión de profanity_check.
Desinstale su versión actual y descargue la v1.0.6 con `git+https://github.com/dimitrismistriotis/profanity-check` 

## Discord

¡Únete al servidor de Discord!

[[Discord]](https://discord.gg/wBpqcQQASE)

## Contribuyendo

Las solicitudes de extracción son bienvenidas. Para cambios importantes, abra un problema primero para discutir lo que le gustaría cambiar.

Asegúrese de actualizar las pruebas según corresponda.


## Licencia

Este proyecto está bajo [GPLv3](https://github.com/AlexClient/Raid-Protect-Discord-Bot/blob/838e73e31b63d135cb6038ef0b24a4a6a3cef369/LICENSE).

## Astrónomos
[![Observadores de estrellas a lo largo del tiempo](https://starchart.cc/Darkempire78/Raid-Protect-Discord-Bot.svg)](https://starchart.cc/Darkempire78/Raid-Protect-Discord-Bot)

# Consejo :

Deberías usar [Discord Tools](https://marketplace.visualstudio.com/items?itemName=Darkempire78.discord-tools) to code your Discord bots on Visual Studio Code easier.
Funciona para Python (Discord.py), Javascript (Discord.js, Eris) y Java (JDA). Generar código y bot de plantilla (snippets).
- **Descargar :** https://marketplace.visualstudio.com/items?itemName=Darkempire78.discord-tools
- **Repositorio :** https://github.com/Darkempire78/Discord-Tools
