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

## Architecture Decisions and Design Patterns (Usability)

- Architectural Style: For the development of the Android shopping list app, we will utilize the MVVM (Model-View-ViewModel) architectural pattern. This pattern facilitates a clear separation of concerns between the business logic, user interface, and data management.

- Components and Module Design: The app will be divided into separate modules to define clear responsibilities. We will have distinct modules for the business logic, user interface, and data management.

- Technology Stack: The app will be developed using Android Studio and the Java programming language. Choosing Android Studio provides us with a powerful development environment specifically designed for the Android platform.

- Performance Tests: To ensure optimal performance, we will employ Apptim for conducting performance tests. These tests will help us identify any bottlenecks within the app and make necessary optimizations to ensure a smooth user experience.

- UI Tests: We will utilize Espresso for conducting UI tests, ensuring the proper functioning of the user interface and seamless interaction with users.

- Data Management: Google Firebase will be utilized for data management. Firebase offers a comprehensive platform for data storage and synchronization, including features such as authentication, real-time database, and cloud storage. This enables efficient data management for our shopping list app.

- Mockup and UI Implementation: We created the app's design mockup using Figma to visualize the user interface. The UI implementation was then carried out in Android Studio using XML files. This approach enables effective design and implementation of the user interface.

These architectural decisions provide a solid foundation for developing a functional and user-friendly shopping list app. They promote a clear separation of responsibilities, efficient data management, and testing to ensure optimal performance and user experience

We decided to put a bar below with the most important functions at the bottom. The advantages of placing important functions at the bottom of the screen:
- Easier accessibility with one hand
- Improved usability and simplified interaction
- Scroll down without adjusting grip or hand position
- Using the bottom screen area for easier navigation
- Ensuring constant visibility of important functions through placement at the bottom of the screen
