# Data Communication Task

**Objetivo:** Elaborar una narrativa propia sobre los video juegos a partir de los datos suministrados.

## Descripción de los datos

Los datos de este proyecto fueron recopilados por el proyecto comunitario de Tableau #GamesNightViz.

#GamesNightViz es un proyecto comunitario de Tableau que se centra en el uso de datos de sus juegos favoritos para mejorar sus habilidades con la visualización de datos. El libro de trabajo *Exploring The History of Video Games.twbx* contiene la data ya preparada. Al final de estas instrucciones se proporciona una definición de los tipos de datos que existen en el libro de Tableau.

## Exploración de los datos

Utilice el libro de trabajo *Tutorial - Press Start_ Exploring The History of Video Games* para comenzar la exploración con las preguntas que se enumeran a continuación:

- ¿Cuántos videojuegos se han lanzado?
- ¿Cuántos juegos se lanzaron cada año?
- Los videojuegos se pueden clasificar en diferentes géneros. ¿Cuál es la distribución de cada género en relación con el porcentaje del total?
- Cada juego tiene una clasificación de madurez (Esrb Rating). ¿Cuántos juegos se incluyen en cada tipo de clasificación?
- Utilice gráficos de distribución que le ayuden a describir: ¿Cuánto tiempo suele llevar completar un videojuego? ¿Ese número aumenta si realizas todas las misiones y premios adicionales?

Sumérgete y explora los datos.

## Explicación de datos

Después de practicar y explorar el conjunto de datos, el próximo paso es usar los datos para contar tu propia historia. ¿Cuál es tu experiencia con los videojuegos? ¿Eres un jugador y quieres contar una historia sobre tu juego favorito? ¿Eres nuevo en los videojuegos y quieres saber más sobre qué juegos jugar primero? Busca conexiones y perspectivas interesantes y cuenta tu propia historia.

A medida que comienzas a trabajar en tu historia ten presente siempre los principios de comunicación visual que estudiamos. He aquí algunas preguntas que te puedes hacer:

- ¿Quién es tu audiencia?
- ¿Qué preguntas crees que son interesantes responder?
- ¿Qué visualizaciones responden a tus preguntas?
- ¿Has seleccionado el tipo de gráfico más adecuado para tu análisis?
- ¿Utilizas múltiples tipos de datos y una alta densidad de datos para enriquecer tu narrativa?
- ¿Tienes explicaciones que argumenten por qué se ve lo que se ve en los gráficos?
- ¿Has limitado la cantidad de colores y formas?
- ¿Todas las visualizaciones contribuyen a contar la historia?
- ¿Tu información más importante aparece en la esquina superior izquierda?
- ¿Haces uso de textos junto a las imágenes para dar explicaciones y coherencia a tu historia?
- ¿Has colocado las acciones o recomendaciones que haces?
- ¿Tiene suficiente documentación: fuentes, autores, fechas?
- ¿Aplicas la técnica de data-ink ratio?

Relee el documento *Principios_para_la_Comunicacion_Visual_de_la_Informacion_Cuantitativa.pdf* que suministramos para recordar los principios que debes siempre tener en cuenta.

## Entrega

Un documento con su historia sobre los video juegos. Puede ser en formato de Tableau .twbx, PDF, o Word.

---

# Data Description (Tableau)

The data used in this study is sourced from public information. Information from this site is collected and aggregated by [#GamesNightViz](https://www.gamesnightviz.com) to help facilitate public discussion. A definition of the data types is provided below.

| Field Name | Field Type | Description | Example |
|---|---|---|---|
| Developer | String | This is a string value to indicate the developer or studio who created the video game. | 2K Games |
| ESRB Rating | String | This is a string value to indicate the official rating from the Entertainment Software Rating Board (ESRB). | Everyone |
| First Released | Date | This is a date value to indicate the first released date of the video game. Do note that some games may have multiple releases due to re-releases on newer console platforms. | 1987 |
| Game Genre | String | This is a string value to indicate the main genre of video game. | Action |
| Game Synopsis | String | This is a string value to indicate a short synopsis of the video game. | |
| Game Thumbnail | String | This is an image role value to retrieve the thumbnail of the video game. This is a combination of both Metacritic and Wikipedia sources. | |
| Game Title | String | This is a string value to indicate the title of the video game. Do note that certain games may have been remastered/remade/rereleased in different years under the same name even though they might be entirely different in gameplay. In some cases, the year has been appended to the game title to make it less ambiguous. | 4X4 Evolution |
| Publisher | String | This is a string value to indicate the publishing company who released the video game into the market. | AMC Games |
| Released on Console | Number | This is a boolean value to indicate if a video game has been released at least once on any of the home-based consoles (released after 1983 - the 3rd generation). | 1.00 |
| Released on Handheld | Number | This is a boolean value to indicate if a video game has been released at least once on any of the handheld devices (released after 1989 - the 4th generation). | 1.00 |
| Released on Mobile | Number | This is a boolean value to indicate if a video game has been released at least once on any of the mobile devices. | 1.00 |
| Released on Nintendo | Number | This is a boolean value to indicate if a video game has been released on Nintendo Switch. | 1.00 |
| Released on PC | Number | This is a boolean value to indicate if a video game has been released on PC, Mac, or Linux. | 1.00 |
| Released on Playstation | Number | This is a boolean value to indicate if a video game has been released on any home-based PlayStation Consoles. | 1.00 |
| Released on Xbox | Number | This is a boolean value to indicate if a video game has been released on any home-based Xbox Consoles. | 1.00 |
| All Playstyles (Average) | Number | This numerical value represents the average minutes of the three playstyles (Main Only, Main + Extra, Completionist). This data is a combination of all times submitted by the community to the web repository HowLongToBeat. | 525 min |
| All Playstyles (Maximum) | Number | This numerical value represents the maximum average minutes of the three playstyles (Main only, Main + Extra, Completionist). This data is a combination of all times submitted by the community to the web repository HowLongToBeat. | 700 mins |
| All Playstyles (Minimum) | Number | This numerical value represents the minimum average minutes of the three playstyles (Main Only, Main + Extra, Completionist). This data is a combination of all times submitted by the community to the web repository HowLongToBeat. | 300 mins |
| Completionist (Average) | Number | This numerical value represents the average minutes to fully complete the game + achievements. This data is a combination of all times submitted by the community to the web repository HowLongToBeat. | 500 mins |
| Completionist (Maximum) | Number | This numerical value represents the maximum minutes to fully complete the game + achievements. This data is a combination of all times submitted by the community to the web repository HowLongToBeat. | 700 mins |
| Completionist (Minimum) | Number | This numerical value represents the minimum minutes to fully complete the game + achievements. This data is a combination of all times submitted by the community to the web repository HowLongToBeat. | 300 mins |
| Main and Extra (Average) | Number | This numerical value represents the average minutes to complete the main story + side quests. This data is a combination of all times submitted by the community to the web repository HowLongToBeat. | 700 mins |
| Main and Extra (Maximum) | Number | This numerical value represents the maximum minutes to complete the main story + side quests. This data is a combination of all times submitted by the community to the web repository HowLongToBeat. | 500 mins |
| Main and Extra (Minimum) | Number | This numerical value represents the minimum minutes to complete the main story + side quests. This data is a combination of all times submitted by the community to the web repository HowLongToBeat. | 250 mins |
| Main Story Only (Average) | Number | This numerical value represents the average minutes to complete the main story only. This data is a combination of all times submitted by the community to the web repository HowLongToBeat. | 200 mins |
| Main Story Only (Maximum) | Number | This numerical value represents the maximum minutes to complete the main story only. This data is a combination of all times submitted by the community to the web repository HowLongToBeat. | 250 mins |
| Main Story Only (Minimum) | Number | This numerical value represents the minimum minutes to complete the main story only. This data is a combination of all times submitted by the community to the web repository HowLongToBeat. | 300 |
| Metascore | Number | Metacritic curates a diverse group of highly respected critics and assigns scores to their reviews. The weighted average of those scores results in a single number and color, the Metascore for each game. | 90 |
| Number of Reviewers (critics) | Number | This numerical value represents the number of critics who have contributed to the Metascore for each game. | 15 |
| Number of Reviewers (users) | Number | This numerical value represents the number of users who have submitted a User Score for a specific game. | 20 |
| Underscore | Number | Based on user scores submitted to Metacritic, these scores are different from the Metascore and go from 0 to 10 instead. All user scores are averaged and assigned to each game. | 8.0 |

## Contributors

- Louis Yu: GamesNightViz
- Ant Pulley: GamesNightViz
- Will Sutton: GamesNightViz
- Tina Covelli: GamesNightViz
- John Keegan: Tableau

## References

- GamesNightViz
- Tableau Visualization Best Practices
- Enable the Tableau Public Hire Me button
- Getting Started with the Tableau Community
- Getting Started with Ad-Hoc Tableau Calculations
