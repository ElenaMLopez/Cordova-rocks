# Hooks:

Los hooks son ganchos que lo que hacen es añadir funcionalidades como mándame un mail cuando hagas un build

Plugins

Res:
    icon: tiene un montón de carpetas dentro, que básicamente tiene todas las cosas que necesita para operar con los difetentes sistemas.
    Cuando tengas el icono de la app vas a esta carpeta y cambias el icono que viene por el tuyo, y cada plataforma tiene su propio formato. Puede 
    buscarse en google, y lo suyo es que le **cambies el icono y conservar el nombre** para que no de problemas.
    Todo lo que queramos q sea recurso nativo de la app va aquí.
    
    screen: tiene las pantallas por defecto para mostrar mientras carga la app. 
    
En config.xml está el archivo de config por defecto muy completo

### carpeta www

En esta carpeta lo que tiene es básicamente una Web, y es en ella donde debemos crear las cosas, es donde se alojan los estácticos. En img hay un logo, y en js 
los metodos de cordova.

1. Añadir plataformas: cordova platform nos dice que plataformas hay. Para instalar una concreta cordova platform add browser por ejemplo. Cuando hace el build 
 lo que hagamos lo va a meter dentro de cada una de las plataformas en la carpeta www.
2. Dentro de la carpeta pluggins q estaba vacía, ahora hay cosas, una carpeta de cordova-plugin y documentación
3. Para ejecutar la app, poner en consola cordova run

