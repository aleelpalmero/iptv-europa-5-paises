# IPTV Europa — 5 países

Lista M3U de **303 emisiones gratuitas** seleccionadas de [IPTV-org](https://github.com/iptv-org/iptv). Conserva nombres, identificadores y logotipos de la fuente. Se contrastaron fuentes adicionales con el catálogo de [TDTChannels](https://github.com/LaQuay/TDTChannels/blob/master/TELEVISION.md), sin añadir emisiones externas a las cinco listas de IPTV-org.

| País | Canales y variantes |
| --- | ---: |
| España | 113 |
| Alemania | 50 |
| Reino Unido | 62 |
| Francia | 27 |
| Italia | 51 |

## Organización

Cada país dispone de dos grupos amplios:

- **Televisión**: cadenas convencionales, autonómicas, regionales, locales, TDT, noticias, deportes e institucionales disponibles en la selección.
- **Series y entretenimiento**: emisiones gratuitas temáticas y FAST de cine, series, documentales, música y programas.

No se crean categorías con un único canal. Se conservan variantes regionales y de idioma; se eliminan fuentes y entradas duplicadas de la misma emisión. Los canales gratuitos de titularidad privada también pueden aparecer: «gratuito» se refiere al acceso a la emisión y no a que la cadena sea de propiedad pública.

## Uso

Descarga [IPTV-Europa-5-Paises.m3u](./IPTV-Europa-5-Paises.m3u) o abre esta URL de red en VLC, Kodi o TiviMate:

```text
https://raw.githubusercontent.com/aleelpalmero/iptv-europa-5-paises/main/IPTV-Europa-5-Paises.m3u
```

No hace falta ejecutar scripts. Tras un cambio del repositorio, actualiza la lista en tu reproductor; las cachés de GitHub o del reproductor pueden tardar en mostrar la nueva versión.

## Selección y comprobación

Revisión ampliada del **28 de octubre de 2026**. Cada emisión incluida superó una comprobación de acceso al manifiesto HLS y a un fragmento multimedia desde la conexión de comprobación durante esta sesión. En emisiones HLS con AES-128 estándar se verificaron la clave suministrada públicamente por el servidor y el contenedor multimedia descifrado. Se excluyen sistemas DRM, autenticación, fuentes dudosas, entradas de la lista de bloqueo de IPTV-org y enlaces que no superaron la prueba. La primera versión descartaba todo cifrado HLS; esta revisión distingue AES-128 estándar de DRM.

Las marcas originales **[Geo-blocked]** y **[Not 24/7]** se conservan. Que una emisión responda desde la conexión de comprobación no garantiza que funcione en tu ubicación, durante todos los programas o a cualquier hora. No se evita ninguna restricción geográfica ni de acceso.

La selección prioriza fuentes identificables de cadenas y proveedores gratuitos. Una URL accesible no constituye por sí sola una certificación de derechos. Los derechos territoriales y las condiciones de los proveedores pueden cambiar. No hay actualización automática configurada.

## Fuentes

- [España](https://iptv-org.github.io/iptv/countries/es.m3u)
- [Alemania](https://iptv-org.github.io/iptv/countries/de.m3u)
- [Reino Unido](https://iptv-org.github.io/iptv/countries/uk.m3u)
- [Francia](https://iptv-org.github.io/iptv/countries/fr.m3u)
- [Italia](https://iptv-org.github.io/iptv/countries/it.m3u)
- [Catálogo de canales y lista de bloqueo de IPTV-org](https://github.com/iptv-org/api)
- [Catálogo de emisiones oficiales de TDTChannels](https://github.com/LaQuay/TDTChannels/blob/master/TELEVISION.md)

El repositorio contiene enlaces y metadatos. Las emisiones y los logotipos pertenecen a sus respectivos titulares. Para solicitar correcciones o retirada de un enlace, abre una incidencia.
