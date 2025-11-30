# ha_voice_custom_sentences
**Collection of custom sentences for Homeassistant**

## Categories
the following table contains the most important sentences included in each file as well as some further information
| File | Sentences      .       .| info |
|------|-------------------------|------|
|[TimerStart.yaml](./custom_sentences/de/TimerStart.yaml)|<li>2 Minuten<li>2 Minuten für die Pizza<li>2 Minuten Pizza<li>2 Minuten für unsere Pizza<li>2 Minuten für meine Pizza<li>Pizza 2 Minuten<li>für die Pizza 2 Minuten<li>für meine Pizza 2 Minuten<li>für unsere Pizza 2 Minuten<li>Pizza-Timer 2 Minuten<li>Pizza Timer 2 Minuten||
|[TimerStatus.yaml](./custom_sentences/de/TimerStatus.yaml)|<li>Wie lange noch<li>Restzeit<li>Wann ist die Pizza fertig<li>Wann ist meine Pizza fertig<li>Wann ist unsere Pizza fertig|"noch" is currently a skip word<br>As a result "Wie lange noch" matches the sentence definition "wie lange".
|[sun.yaml](./custom_sentences/de/sun.yaml)|<li>wann geht die Sonne unter<li>wann geht heute die Sonne unter<li>wann geht die Sonne wieder unter<li>wann wird es dunkel<li>wann wird es wieder dunkel<li>wann wirds draußen dunkel<li>wann wird es heute dunkel<li>wann wird es heute draussen dunkel<li>wann geht die Sonne auf<li>wann geht heute die Sonne auf<li>wann geht die Sonne wieder auf<li>wann geht morgen die Sonne auf<li>wann geht morgen die Sonne wieder auf<li>wann wirds heute hell<li>wann wirds wieder hell<li>wann wird es morgen hell<li>wann wird es draußen hell<li>wann wirds draußen hell<li>wann wirds draussen wieder hell<li>wann wirds heute draußen wieder hell<li>wann wird es morgen draußen wieder hell|for this file the responses "sun_dusk" and "sun_dawn" from [responses.yaml](./custom_sentences/de/responses.yaml) need to be defined as well<br><br>The "Sun" integration needs to be installed on the homeassistant instance.|
