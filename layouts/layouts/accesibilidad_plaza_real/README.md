## Disposición: Accesibilidad y confort peatonal en Plaza Real

Disposición de botones para OSMTracker creada para el curso **Sistemas de Información Geográfica (TEC)**. Sirve para mapear, en el espacio público de **Plaza Real (Alajuela, Costa Rica)**, qué tan fácil, cómodo y seguro es moverse a pie, en silla de ruedas, con coche de bebé o con movilidad reducida.

Los datos capturados con esta disposición alimentan un mapa temático dinámico publicado en GitHub Pages.

### Pantalla principal

| Botón | Qué registra | Etiqueta OSM sugerida |
|---|---|---|
| 🎤 / 📷 / 📝 | Audio, fotografía o nota de texto | — |
| Rampa | Rampa para silla de ruedas o coche | `kerb=lowered` / `ramp:wheelchair=yes` |
| Escaleras | Gradas o escaleras (barrera para silla de ruedas) | `highway=steps` |
| Obstáculo | Algo que bloquea el paso (poste, carro, materiales, etc.) | `barrier=*` |
| Acera buena | **Desde aquí** la acera está en buen estado | `highway=footway` + `smoothness=good` |
| Acera dañada | **Desde aquí** la acera está dañada o es irregular | `highway=footway` + `smoothness=bad` |
| Baño accesible | Servicio sanitario accesible | `amenity=toilets` + `wheelchair=yes` |
| Parqueo discapacidad | Espacio de parqueo para personas con discapacidad | `amenity=parking_space` + `parking_space=disabled` |
| Mobiliario ➜ | Abre la página de mobiliario urbano | — |
| Percepción ➜ | Abre la página de percepciones | — |

### Página «Mobiliario»

| Botón | Qué registra | Etiqueta OSM sugerida |
|---|---|---|
| Banca | Lugar para sentarse | `amenity=bench` |
| Basurero | Recipiente de basura | `amenity=waste_basket` |
| Bebedero | Fuente de agua potable | `amenity=drinking_water` |
| Iluminación | Poste o lámpara | `highway=street_lamp` |
| Sombra | Lugar con sombra (techo, toldo) | `covered=yes` |
| Árbol | Árbol que da sombra | `natural=tree` |

### Página «Percepción»

| Botón | Qué registra |
|---|---|
| Me siento seguro | Punto donde la persona se siente segura |
| Me siento inseguro | Punto donde la persona se siente insegura |
| Lugar agradable | Espacio cómodo o agradable para estar |
| Ruido excesivo | Ruido que molesta |
| Poca luz | Zona oscura o mal iluminada |
| Zona descuidada | Basura, abandono o falta de mantenimiento |

Los íconos están en la carpeta `accesibilidad_plaza_real_icons/`.
