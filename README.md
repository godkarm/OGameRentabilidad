# OGame Rentabilidad (Android)

App 100 % offline (sin permiso INTERNET). Datos en SQLite (Room): `ogame_rentabilidad.db`.

## Compilar
1. Android Studio (Koala o superior) → *Open* → esta carpeta. Sincroniza Gradle (genera el wrapper).
2. Run ▶ en el móvil/emulador, o *Build > Build APK(s)*.
3. Tests de cálculo: `./gradlew test`.

## Qué hace
- **Inversiones**: ranking de mejoras (minas de metal/cristal/deuterio por planeta + plasma) por tiempo de amortización en horas y días, y un plan voraz de 30 pasos.
- **Planetas**: niveles, posición, temperatura, crawlers.
- **Registro**: iniciar → completar/cancelar; al completar actualiza el nivel. Lo "en curso" ya cuenta para la siguiente recomendación.
- **Ajustes**: velocidad, clase, geólogo/oficiales, alianza, plasma, tasas de cambio.

## Fuera de alcance (v1)
Formas de vida, planta de fusión/energía, astrofísica, boosters de recursos.
