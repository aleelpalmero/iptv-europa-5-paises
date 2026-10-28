# IPTV Europa — 5 países

Lista M3U de **245 emisiones gratuitas** seleccionadas de [IPTV-org](https://github.com/iptv-org/iptv). Conserva nombres, identificadores y logotipos de la fuente. Se contrastaron fuentes adicionales con el catálogo de [TDTChannels](https://github.com/LaQuay/TDTChannels/blob/master/TELEVISION.md), sin añadir emisiones externas a las cinco listas de IPTV-org.

| País | Canales y variantes |
| --- | ---: |
| España | 104 |
| Alemania | 48 |
| Reino Unido | 29 |
| Francia | 16 |
| Italia | 48 |

## Organización

Cada país dispone de dos grupos amplios:

- **Televisión**: cadenas convencionales, autonómicas, regionales, locales, TDT, noticias, deportes e institucionales disponibles en la selección.
- **Series y entretenimiento**: emisiones gratuitas temáticas y FAST de cine, series, documentales, música y programas.

No se crean categorías con un único canal. Se conservan variantes regionales y de idioma; se eliminan fuentes y entradas duplicadas de la misma emisión. Los canales gratuitos de titularidad privada también pueden aparecer: «gratuito» se refiere al acceso a la emisión y no a que la cadena sea de propiedad pública.

## Criterio territorial estricto

Depuración editorial del **28 de octubre de 2026**: se retiran **58 entradas** de la versión de 303, y se corrige la categoría de **16**. Cada grupo conserva las cadenas nacionales, autonómicas, regionales y locales asignadas a ese país. Las ediciones nacionales identificables, como QVC, conservan su país de emisión editorial; la nacionalidad de su propietario no determina el grupo.

Se excluyen las señales dirigidas expresamente a otras regiones, los FAST genéricos de origen extranjero y las procedencias o ediciones nacionales que no se han podido confirmar. Estar disponible en un país o usar su idioma no basta para incluir una señal. No se traslada una versión española de un canal británico al grupo británico, ni una versión británica de un canal español al español: esas versiones se retiran para no cambiar de mercado manteniendo el mismo flujo.

La depuración usa los identificadores de procedencia de IPTV-org, el mercado de la señal y el contraste de casos ambiguos con fuentes del operador. Los identificadores del catálogo pueden contener errores; esta revisión es una selección conservadora, no una certificación independiente de todos los metadatos.

El idioma no determina por sí solo el país: se conservan canales comunitarios con entidad británica identificable, como Anand TV, Kanshi TV y Panjab TV. Se retiran MTA Al-Arabia, Africa y America por ser señales para otros mercados, y Nolly Africa por su orientación internacional a Nollywood.

Esta revisión cambia la selección y los grupos; **no repite las pruebas de reproducción** de la revisión anterior. Conserva las URL, identificadores, nombres y logotipos de las entradas que permanecen.

### Contrastes de procedencia

- [Panjab TV: programación, público británico y dirección del operador](https://panjabtv.uk/about-us/).
- [Anand Media: distribución para su comunidad europea](https://www.anandmedia.uk/) y [entidad británica del operador](https://find-and-update.company-information.service.gov.uk/company/07072969).
- [Kanshi TV: entidad británica del operador](https://find-and-update.company-information.service.gov.uk/company/07618375).
- [MTA: señales diferenciadas World, Europe, Al-Arabia, Africa y America](https://auth.mta.tv/tv-guide).
- [African Movie Channel: Nolly Africa, sede y distribución mundial](https://www.africanmoviechannel.tv/about-amc).

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

## Registro de la depuración territorial

Las exclusiones por falta de confirmación no implican que la emisión sea ilegal o de pago.

| Identificador retirado | Grupo anterior | Motivo |
| --- | --- | --- |
| EWTN.us@SpainLatinAmerica | España | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| France24.fr@Spanish | España | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| TVEStar.es@HD | España | Señal de distribución internacional dirigida a América; fuera de la selección doméstica española. |
| BBCDrama.uk@Spain | España | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| MrBeanAnimated.uk@ES | España | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| MyTimeMovieNetwork.es@SD | España | Marca internacional; no se confirma origen editorial doméstico español. |
| NatureTime.ca@SD | España | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| ThePetCollective.us@Spain | España | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| WaterBear.ch@SD | España | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| DW.de@Russian | Alemania | Edición en ruso dirigida a otro mercado; fuera de la selección doméstica alemana. |
| LoveThePlanet.es@DE | Alemania | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| DunyaNewsUK.uk@SD | Reino Unido | Edición internacional de una red pakistaní; se excluye con el criterio doméstico estricto. |
| HalaLondon.uk@SD | Reino Unido | Señal internacional angloárabe; no se confirma una edición doméstica británica. |
| MTA3AlArabia.uk@SD | Reino Unido | Señal dirigida al público árabe, fuera de la selección británica doméstica. |
| MTA4Africa.uk@SD | Reino Unido | Señal dirigida a África, fuera de la selección británica doméstica. |
| MTA5Africa.uk@SD | Reino Unido | Señal dirigida a África, fuera de la selección británica doméstica. |
| MTA8America.uk@SD | Reino Unido | Señal dirigida a América, fuera de la selección británica doméstica. |
| Trailers.es@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| DogtheBountyHunter.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| DuckDynasty.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| FailArmy.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| GhostHunters.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| HellsKitchen.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| HomesUnderHammer.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| InsideCrime.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| McLeodsDaughters.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| MovieSphere.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| MysteryTV.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| MyTimeMovieNetwork.uk@SD | Reino Unido | Marca internacional; no se confirma origen editorial doméstico británico. |
| NatureTime.ca@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| NollyAfrica.uk@SD | Reino Unido | Canal británico de distribución global especializado en Nollywood; fuera de la selección doméstica estricta. |
| RakutenTVActionMovies.es@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| RakutenTVComedyMovies.es@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| RakutenTVDramaMovies.es@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| RakutenTVFamilyMovies.es@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| RakutenTVTopMovies.es@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| SoReal.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| Strongman.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| Tastemade.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| ThePetCollective.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| UndercoverBossGlobal.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| WorldPokerTour.us@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| XITEHits.nl@UK | Reino Unido | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| ZeeOne.uk@UK | Reino Unido | Marca internacional de programación india; no se confirma origen editorial doméstico británico. |
| Africa24.fr@SD | Francia | Señal panafricana; fuera de la selección doméstica francesa. |
| Africa24English.fr@SD | Francia | Señal panafricana en inglés; fuera de la selección doméstica francesa. |
| Africa24Sport.fr@SD | Francia | Señal panafricana; fuera de la selección doméstica francesa. |
| DBMTV.fr@SD | Francia | No se confirma procedencia editorial doméstica actual con las fuentes consultadas. |
| CineWestern.fr@SD | Francia | Fuente identificada para Rakuten UK; no se confirma que sea la edición francesa. |
| MrBeanAnimated.uk@FR | Francia | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| NatureTime.ca@France | Francia | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| QwestTVJazzBeyond.fr@SD | Francia | Fuente identificada para Samsung Australia; no se confirma edición francesa. |
| TraceBrazuca.fr@SD | Francia | Señal para Brasil; fuera de los cinco países. |
| TraceSportStars.fr@HD | Francia | Fuente identificada para Samsung Australia; no se confirma edición francesa. |
| TraceUrban.fr@SD | Francia | Fuente identificada para Samsung Australia; no se confirma edición francesa. |
| FailArmy.us@Italy | Italia | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| MrBeanAnimated.uk@IT | Italia | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |
| ThePetCollective.us@Italy | Italia | La procedencia del canal en IPTV-org no coincide con el país del grupo; se excluye esta versión en lugar de trasladar un flujo dirigido a otro mercado. |

### Cambios de categoría

- MusicTVGranada.es@SD: España | Televisión → España | Series y entretenimiento.
- Radio3.es@SD: España | Televisión → España | Series y entretenimiento.
- RadioCarnavalTV.es@SD: España | Televisión → España | Series y entretenimiento.
- SolMusica.es@SD: España | Televisión → España | Series y entretenimiento.
- SX3.es@SD: España | Televisión → España | Series y entretenimiento.
- BibelTVMusik.de@SD: Alemania | Televisión → Alemania | Series y entretenimiento.
- DMF.de@SD: Alemania | Televisión → Alemania | Series y entretenimiento.
- Dokusat.de@SD: Alemania | Televisión → Alemania | Series y entretenimiento.
- EchtJetztTV.de@SD: Alemania | Televisión → Alemania | Series y entretenimiento.
- KiKA.de@SD: Alemania | Televisión → Alemania | Series y entretenimiento.
- WeltderWunderTV.de@SD: Alemania | Televisión → Alemania | Series y entretenimiento.
- V2BEATTV.uk@SD: Reino Unido | Televisión → Reino Unido | Series y entretenimiento.
- GenerationsTV.fr@SD: Francia | Televisión → Francia | Series y entretenimiento.
- LittoralFMTV.fr@SD: Francia | Televisión → Francia | Series y entretenimiento.
- 7080TV.it@SD: Italia | Televisión → Italia | Series y entretenimiento.
- BeJoykids.it@HD: Italia | Televisión → Italia | Series y entretenimiento.
