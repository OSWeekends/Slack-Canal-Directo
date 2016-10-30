![shieldsIO](https://img.shields.io/github/issues/OSWeekends/Slack-Canal-Directo.svg)
![shieldsIO](https://img.shields.io/github/release/OSWeekends/Slack-Canal-Directo.svg)
![shieldsIO](https://img.shields.io/github/license/OSWeekends/Slack-Canal-Directo.svg)
![shieldsIO](https://img.shields.io/david/OSWeekends/Slack-Canal-Directo.svg)


# Slack-Canal-Directo
El robot que utilizamos para automatizar los comunicados en el canal [#directo](https://osweekends.slack.com/) de Slack.


### Funcionalidades

- Escucha activamente ciertos hashtags de Twitter.
- Escucha activamente conversaciones en Google Hangouts
- Envia mensajes en Google Hangouts
- Envia mensajes en Slack
- Envia mensajes al azar clasificados por prioridad en Slack
- Envia mensajes de Error y estado al administrador en Goolgle Hangouts
- Puede ser desplegado en multiples entornos (Raspbian, Linux, OSX, Windows, C9...)
- Permite desplegar multiples avatares y personalidades desde la configuración para comunicarse en Slack

### Influencias

Este proyecto reutiliza mucho código de los siguiente repositorios/proyectos:
- [Curratelo](https://github.com/UlisesGascon/curratelo)
- [Simple Hangouts Bot (v0.0.1)](https://github.com/UlisesGascon/simple-hangouts-bot/releases/tag/v0.0.1)

### Utilización

Es necesario completar los detalles del archivo *config.js* y después instalar las dependencias de Node.js. 

```bash
npm install && node directo
```

### Dependencias

- [hangouts-bot](https://github.com/jaxbot/hangouts-bot)
- [scheduled](https://github.com/pillarsjs/scheduled)
- [slack-node](https://github.com/clonn/slack-node-sdk)
- [twitter](https://github.com/desmondmorris/node-twitter)
