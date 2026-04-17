# Proyect-CORTEX-Asistente-analitico-de-equipoos-FPC
## integrantes:
-andres ferrer
-fernando cardona
-alejandro carrillo 
<img width="1349" height="770" alt="image" src="https://github.com/user-attachments/assets/9345cb8b-3a35-4e9a-92e8-56b266ded5d8" />
# tabla: aspectos cognitivos relevantes 
<img width="851" height="638" alt="image" src="https://github.com/user-attachments/assets/91537f4b-df21-4d7e-9669-0d5bc4be3dc9" />

-
## Justificacion de la calificacion de cada proceso:

-Atencion: Requiere de una buena atencion para poder entender que se le esta solicitando con base a los datos de los resultados de los equipos del fpc pero no tanta.
-Memoria: El asistente requiere de tener mucha memoria, osea una base de datos de los resultados de los equipos del fpc, para asi dar una respuesta acertada a lo que se le este solicitando.
-Emocion: No requiere tanta emocion no se enfoca en algo que conecte emocin almente si no mas un astitente que ayude a valorar e identificar patrones y estadisticas en el rendimineto de los clubes del fpc.
-Lenguaje: Requiere de un lenguaje tecnico con ciertas exprsiones muy utlizadas dentro de las predicciones futbolistica pero tampoco tiene que ser muy sofisticado.

<img width="1056" height="514" alt="image" src="https://github.com/user-attachments/assets/f20bad32-757c-4ca5-8320-dc3ecf3668eb" /> 

<img width="617" height="559" alt="image" src="https://github.com/user-attachments/assets/026d1a4c-0dd7-4941-8043-9a679aa94966" /> 

<img width="677" height="496" alt="image" src="https://github.com/user-attachments/assets/7071802a-207f-416c-9f7e-035fcf47cc00" />




semana 6: 

## Regla 1
- **Si el mensaje del usuario tiene más de 500 palabras:**
 El mecanismo de atención priorizará únicamente:
1. Los **sustantivos clave** (nombres de equipos, jugadores, torneos, estadísticas explícitas).
 2. La **última frase** del mensaje.
 El resto del contenido se tratará como algo inecesario y se descartará para la generación de la respuesta.
## Regla 2
**Si la intención es predictiva**
dar como Prioridad: contexto temporal (fecha/hora del partido), lesiones actuales, rendimiento reciente (últimos 5 partidos), lugar del partido.
**Si la intención es estadística:**
  dar como Prioridad: números exactos, competencia específica (Liga, Copa), período solicitado.
**Si la intención es emocional**
  dar como Prioridad: el resultado del último partido mencionado y su contexto (local/visitante).
## Regla 3
Cualquier timestamp (ej. "7pm", "mañana") debe evaluarse contra el evento mencionado.
Si el evento ya ocurrió y el usuario no solicita retrospectiva, se responde con resultado final, no con predicción.
Si el evento es inminente (menos de 4 horas), la respuesta debe incluir advertencia de urgencia y datos confirmados de última hora.
## Regla 4 orden de prioridades 
**Datos confirmados** (resultados de estadisticas de jigadores, alineaciones oficiales, lesiones confirmadas).
**Tendencias históricas** (rendimiento en el pais de origen o si esta visitante, últimos enfrentamientos).
**Análisis predictivo** (solo si se si se solicita o se pregunta).
semana 7

![WhatsApp Image 2026-04-10 at 11 37 04 AM](https://github.com/user-attachments/assets/86c89bfa-b087-48c0-9534-2ab7cff39e29)

semana 8
![WhatsApp Image 2026-04-10 at 11 40 17 AM](https://github.com/user-attachments/assets/4ff9b057-131e-47b9-8800-4ec795711f53)
Semana 9 
## regla de limpieza de cache 
El bot olvidara la coversacion 10 minutos despues de que el usuario salga de la aplicacion o deje de utilizar el asistente virtual.
El sistema implementa una Regla de Limpieza de Caché diseñada para optimizar el rendimiento y garantizar la privacidad del usuario. Bajo este protocolo, el asistente virtual procederá a eliminar el historial de la sesión activa tras un periodo de 10 minutos de inactividad total o una vez que el usuario cierre la aplicación. Este cierre automático asegura que la memoria temporal sea liberada, permitiendo que la próxima interacción comience desde un estado limpio y eficiente.

| Elemento     | Regla Logica                                    | Ejemplo de output |
|--------------|-------------------------------------------------|-------------------|
| Tono         | Profesional, analítico y ligeramente dinámico.  | Dato 3            |
               Evitar el fanatismo.
| Uso de Emojis| Dato 5                                          | Dato 6            |
|Jerga Tecnica |                                                 |                   |
|Longitud      |                                                 |                   |
