# Utility Tree
| Quality attribute| Refinment |  Source                 |     Stimulus                           |     Artifact               |     Environment             |    Response                                                       |            Response measure                           | Business value | Technical risk |
|------------------|-|-----------------------------|--------------------------------|--------------------|------------------|-----------------------------------------------------------|---------------------------------------|----------------|----------------|
| Availability     | User add a list with a name which already exists in the UI and databank | User | enter list which already exists | backend / databank | overloaded operation | send errror message (list already exists) | lists cannot have the same name   | H              | M              |
|                   |App is usable without wifi connection | User | request lists from databank | backend/ databank | Normal operation|lists are stored local           |    ...                                   |   M             |     L           |
| Interoperability |Google API for listing near supermarkets | Google API  | receive nearest supermarket  | supermarket databank | supermarketView UI | nearest supermarkets listed in the app  | the nearest supermarkets can be viewed in the UI  | H              | L |
|                  |Chefkoch API for listing recipes | Chefkoch API |  receive recipes |  recipes databank |  listview UI  | recipe is listed as a grocery list | recipes can be viewed in the UI|   M   | L |
| Modifiability    |Developer decides to add the funcitionality of sign up's | Backend developer   | add a technology (login/sign up) | code | build time | make and test modification | minimal downtime                      |L  | M |
| Performance      |User adds too many lists and overloads the backend databank by too many requests | Adding too many lists | too many requests | backend / databank | overloaded operation | throttling  | ...  | M | H |
| Usability        |User who don't know about smartphones and apps wants to use our grocery app | Gen-Z user          | doesn't know how to use the app | frontend, UI design | regular use      | easy understandable, simple design | user feedback | H | L |

## Architecture Decisions and Design Patterns
- Simple & minimalistic frontend design
- maximum amount of lists
- working with Google API to receive near supermarkets
- get recipes from chefkoch website as grocery list
- store in json
