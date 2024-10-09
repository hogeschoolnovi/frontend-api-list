# Lijst met gevalideerde API's
Een door NOVI gevalideerde lijst van API's om te gebruiken voor jouw Integrale Eindopdracht Frontend.

## API's
Sommige API's hebben een rate limit. Dit betekent dat je niet meer dan x requests per dag mag maken in de gratis versie. Dit is in principe geen probleem, maar kan tijdens het testen soms vervelend zijn.

| **Naam**                                                                                   | **Onderwerp** | **Beschrijving**                                                                                                             | **Opmerkingen**                                                                         |
|--------------------------------------------------------------------------------------------|---------------|------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| [Astronomy API](https://ipgeolocation.io/documentation/astronomy-api.html)                 | Astronomy     | Haalt astronomische gegevens op over de maan en de zon op basis van een locatie                                              |                                                                                         |
| [Dummy API](https://dummyapi.io/docs)                                                      | Dummy Data    | Haalt gegevens op over gebruikers, blogposts en comments. Hier kun je dus een nep-blog mee maken                             |                                                                                         |
| [Random User API](https://randomuser.me/documentation)                                     | Dummy Data    | Haalt random nepaccounts op (denk aan email, username, afbeelding, geslacht, woonplaats, etc.)                               | _Let op_: vereist het meesturen van de app-id bij ieder request                           |
| [Fake Store API](https://fakestoreapi.com/docs)                                            | Dumy Data     | Nepdata over producten in een webshop. Je kunt producten en categorieen ophalen, maar ook producten verwijderen of toevoegen |                                                                                         |
| [Bored API](https://www.boredapi.com/documentation) TIJDELIJK NIET BESCHIKBAAR             | Entertainment | Haalt willekeurige activiteiten op om te doen, op basis van aantal personen, type of prijs                                   | _Let op_: deze API bevat zelf niet voldoende data voor een volwaardige eindopdracht. Deze is wel te gebruiken in combinatie met andere API's.                                                                                         |
| [Marvel API Database](https://developer.marvel.com/docs)                                   | Entertainment | Haalt Marvelinformatie op, zoals o.a. series, verhalen en karakters                                                          |                                                                                         |
| [Edamam API](https://www.edamam.com/)                                                      | Food          | Haalt informatie op op basis van recepten, ingredienten en nutrienten                                                        | _Let op:_ endpoints zijn alleen toegankelijk wanneer je de API key meestuurt              |
| [Spoonacular](https://spoonacular.com/food-api/docs)                                       | Food          | Haalt zeer uitgebreide informatie op over recepten, producten, ingredienten, etc.                                            | Rate limit van 150 requests per dag (dit is aan de lage kant)                           |
| [The Cocktail DB](https://www.thecocktaildb.com/api.php)                                   | Food          | Haalt cocktailnamen, recepten en ingredienten op                                                                             | _Let op:_ endpoints werken alleen als je er `https://` voor zet                           |
| [Open Brewery DB](https://www.openbrewerydb.org/documentation)                             | Food          | Maakt bierbrouwerijen in Amerika doorzoekbaar                                                                                |                                                                                         |
| [Pokemon API](https://pokeapi.co/docs/v2)                                                  | Entertainment | Geeft data over alle PokéMon terug, waaronder alle abilities, moves, uiterlijk, etc.                                         |                                                                                         |
| [Advice Slip API](https://api.adviceslip.com/)                                             | Entertainment | Geeft generiek tegeltjes-advies terug, zoals "No one knows anyone else in the way you do."                                   | _Let op:_ deze API verschaft heel weinig data                                             |
| [Open Library API](https://openlibrary.org/developers/api?ref=apilist.fun)                 | Literature    | Haalt literatuurinformatie op op basis van boeknamen, auteur of onderwerp                                                    |                                                                                         |
| [Make Up API](https://makeup-api.herokuapp.com/)                                           | Make-up       | Haalt informatie op over make up merken en hun producten                                                                     | _Let op:_ bij het eerste request naar deze API kan de response even op zich laten wachten |
| [The Movie Database API](https://developers.themoviedb.org/)                               | Movies        | Haalt filminformatie op op basis van filmtitel, genres, netwerk etc (beschrijving, genre, rating, etc.)                      | _Let op:_ maak gebruik van versie 3                     |
| [IMDB API](https://imdb-api.com/api)                                                       | Movies        | Doet hetzelfde als OMDB, alleen met meer mogelijkheden                                                                       | Rate limit van 100 requests per dag (dit is aan de lage kant)                           |
| [The Audio DB](https://www.theaudiodb.com/api_guide.php?ref=apilist.fun)                   | Music         | Haalt gegevens op over artiesten, nummers, discografie, etc.                                                                 |                                                                                         |                                                          |                                                                                         |
| [National Park Services API](https://www.nps.gov/subjects/developer/api-documentation.htm) | Nature   **   | Haalt informatie over Nationale parken op in Amerika. Denk aan faciliteiten, parknamen, events en kampeergebieden            |                                                                                         |
| [News API](https://newsapi.org/docs)                                                       | News          | Haalt gewone en "breaking" nieuwsartikelen op, op basis van advanced search                                                  | Rate limit van 100 requests per dag (dit is aan de lage kant)                           |
| [Spacex API](https://github.com/r-spacex/SpaceX-API)                                       | Space         | Haalt lanceer-, raket-, kern-, capsule-, starlink-, lanceerplatform- en landingsplatformgegevens op                          |                                                                                         |
| [Football Soccer API](https://www.scorebat.com/video-api/?ref=apilist.fun)                 | Sports        | Haalt video's op van wedstrijden tussen specifieke voetbalteams                                                              | _Let op:_ deze API verschaft heel weinig data                                             |
| [The Sports DB](https://www.thesportsdb.com/api.php)                                       | Sports        | Haalt algemene sportinformatie op, zoals teams, events en spelers                                                            |                                                                                         |
| [RAWG.io API](https://api.rawg.io/docs/)                                                   | Video games   | Haalt videogame informatie op, zoals genres, gamenamen en ontwikkelaars                                                      |                                                                                         |
| [OpenWeather](https://openweathermap.org/api)                                              | Weather       | Haalt weersvoorspellingen op                                                                                                 |  Gratis versie haalt alléén huidige weervoorspelling op                                                                                       | 
