# Boss-Helper NG (Mystery Merchant Helper)

Muestra información y notificaciones sobre la aparición de los NPC especificados en la zona (monstruo de evento / jefe mundial / jefe del gremio / comerciante).
Cuando un NPC aparece en el rango visible, se marcará con un marcador.Hay funciones de teletransporte y búsqueda automática de NPC.Idiomas disponibles en inglés y ruso (detecta automáticamente).

### Seguridad

La función de búsqueda automática (el comando **scan**) es fácilmente detectable, por lo tanto, si se detecta, puede ser baneado. Utilice esta función bajo su propio riesgo.

## Módulo de comandos
Toolbox(/8) | Descripción del comando
--- | --- 
**bh** | Habilitar/deshabilitar módulo (habilitado por defecto). 
**bh&nbsp;alert** | Habilitar/deshabilitar mensajes de advertencia en pantalla. 
**bh&nbsp;notice** | Habilitar/deshabilitar mensajes de notificación en pantalla. 
**bh&nbsp;message** | Habilitar/deshabilitar mensajes de chat. 
**bh&nbsp;party** | Habilitar/deshabilitar enviar mensajes a los miembros del grupo. 
**bh&nbsp;marker** | Habilitar/deshabilitar Marcadores NPC. 
**bh&nbsp;clear** | Quitar marcador de NPC. 
**bh&nbsp;teleport** | Habilitar/deshabilitar teletransporte instantáneo. 
**bh&nbsp;hpbar** | Habilitar/deshabilitar función BAM-HP-Bar. 

### Mystery Merchants
Toolbox(/8) | Descripción del comando
--- | --- 
**mm** | Muestra los tiempos de reaparición de los Mystery Merchants. 
**mm&nbsp;scan** | Busca Mystery Merchants en la zona actual. 
**mm&nbsp;stop** | Detener la búsqueda. 
**mm&nbsp;loc** | Muestra las ubicaciones de Mystery Merchants de la zona actual. 
**mm&nbsp;to&nbsp;&lt;id&gt;** | Teletransportarse a la ubicación especificada. 

* Mostrar los tiempos de reaparición de los Mystery Merchants (el comando **mm**):   
  ![](https://i.imgur.com/MRSGHDo.png)

### World Bosses
Toolbox(/8) | Descripción del comando
--- | --- 
**wb** | Muestra los tiempos de reaparición de los World Bosses. 
**wb&nbsp;scan** | Busca World Bosses en la zona actual. 
**wb&nbsp;stop** | Detener la búsqueda. 
**wb&nbsp;loc** | Muestra las ubicaciones de World Bosses de la zona actual. 
**wb&nbsp;to&nbsp;&lt;id&gt;** | Teletransportarse a la ubicación especificada. 

* Mostrar tiempos de reaparición de World Bosses (el comando **wb**):   
  ![](https://i.imgur.com/RPXfTFV.png)

### Raid Bosses
Toolbox(/8) | Descripción del comando
--- | --- 
**rb** | Muestra los tiempos de reaparición de los Raid Bosses. 

* Mostrar los tiempos de reaparición de los Raid Bosses (el comando **rb**):   
  ![](https://i.imgur.com/A6kpUCK.png)

## Más información

* El módulo tiene la funcionalidad incorporada del módulo BAM-HP-Bar de Lambda11 (con **fixed Ortan**):   
  ![](https://i.imgur.com/kLNyQJL.png)
* NPC comerciante con marcador (fácilmente visible en la distancia):   
  ![](https://i.imgur.com/tdIJKJv.png)
* Todos los identificadores de NPC: https://github.com/neowutran/TeraDpsMeterData/tree/master/monsters
* Ubicaciones de aparición de comerciantes: https://home.gamer.com.tw/creationCategory.php?owner=d0305011&c=444485

## Créditos
- **[ZC](https://github.com/tera-mod)** - Desarrollador original del módulo Boss-Helper
- **[Owyn](https://github.com/Owyn)** - Autor del módulo field-boss_time
- **[Lambda11](https://github.com/Lambda11)** - Author of the bam-hp-bar module
