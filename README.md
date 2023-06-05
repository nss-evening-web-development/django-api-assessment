# Self-Assess Your Django Competencies

## 🐟 Tuna Piano API

This API enables developers to create applications that provide song recommendations based on genre. It manages non-user specific data, including artists, their songs, and the associated genre for each song.

Let's make millions! 💰 💰 💰

## Assessment Instructions

Follow these steps to complete the assessment:

1. Start by cloning the template repository to your local machine.
   - Use this link to copy over the template to your GitHub profile: [GitHub Template Link](https://githubtools.reppedintech.com/u/nss-evening-web-development/django-api-assessment)

2. Once you have cloned the repository, navigate to the project directory using the command line.
   - Use the `cd` command to change to the project directory.

3. Activate the Pipenv environment to ensure you are using the correct dependencies.
   - Run the command `pipenv shell` to activate the Pipenv environment.

4. Install the necessary dependencies for the project.
   - Use the command `pipenv install` to install the required dependencies.

5. Open the project in your preferred code editor (e.g., Visual Studio Code) to start working on the implementation.

6. Study the provided Entity Relationship Diagram (ERD) to understand the data structure and relationships between entities.
   - You can find the ERD [here](https://dbdocs.io/trinitycterry/Tuna-Piano-API?view=relationships).

7. Plan the construction of the API based on the MVP requirements and the information provided in this Readme.
   - Make sure you understand the expected functionality and any constraints.

8. Implement the specified MVP features, following the guidelines and examples provided in this Readme.
   - Refer to the Readme for detailed information on each route and its requirements.

9. Thoroughly test your API to ensure its functionality and reliability.
   - Utilize appropriate testing methodologies and frameworks to validate your code.

10. Once you have completed the assessment, present your work to the instructional team.
    - Provide all necessary documentation, including the link to your GitHub repository.

## MVP Routes by Entity

These are all the available routes for this API. Each route has an associated ticket containing the following information:
- Route description.
- Request structure:
    - HTTP method.
    - Route path.
    - JSON body (if applicable).
- Response structure:
    - JSON body (if applicable).
    - Status code.

### 🎶 Songs

- [Create a Song](./documentation/issue-tickets/Create-Song.md)
- [Delete a Song](./documentation/issue-tickets/Delete-Song.md)
- [Update a Song](./documentation/issue-tickets/Update-Song.md)
- [View a List of all the Songs](./documentation/issue-tickets/List-Songs.md)
- [Details view of a single Song and its associated genres and artist details](./documentation/issue-tickets/Details-Song.md)

### 👩🏾‍🎤 Artists

- [Create an Artist](./documentation/issue-tickets/Create-an-Artist.md)
- [Delete an Artist](./documentation/issue-tickets/Delete-an-Artist.md)
- [Update an Artist](./documentation/issue-tickets/Update-an-Artist.md)
- [View a List of all the Artists](./documentation/issue-tickets/List-Artists.md)
- [Details view of a single Artist and the songs associated with them](./documentation/issue-tickets/Details-Artist.md)

### 🎸 Genres

- [Create a Genre](./documentation/issue-tickets/Create-Genre.md)
- [Delete a Genre](./documentation/issue-tickets/Delete-Genre.md)
- [Update a Genre](./documentation/issue-tickets/Update-Genre.md)
- [View a List of all the Genres](./documentation/issue-tickets/List-Genres.md)
- [Details view of a single Genre and the songs associated with it](./documentation/issue-tickets/Details-Genre.md)

### Stretch Goals

These are examples of stretch goals that you can tackle once you have been MVP approved for the above features:

- Plan and Build the Frontend for the MVP routes
- [Retrieve a list of popular genres based on the number of associated songs](./documentation/issue-tickets/Popular-genres.md)
- [Retrieve artists with similar genres](./documentation/issue-tickets/Related-artists.md)
- [Search songs by genre](./documentation/issue-tickets/Search-songs-by-genre.md)
- [Search artists by genre](./documentation/issue-tickets/Search-artists.md)
- Implement a search functionality to search all entities by name, title, or description.

## Data Design

To understand the data structure and relationships between entities, refer to the Entity Relationship Diagram (ERD) provided [here](https://dbdocs.io/trinitycterry/Tuna-Piano-API?view=relationships).

## Seeking Help and Clarification

If you encounter any challenges during the assessment and need help or clarification, follow these steps:

1. Create a discussion ticket in the [NSS Evening Web Development Discussions](https://github.com/orgs/nss-evening-web-development/discussions) repository.
2. Include all the required information in the ticket, such as the problem you're facing and any relevant code or error messages.
3. Post the ticket in the Help Thread in the cohort channel to seek assistance from your peers and instructors.

## Code Organization and Best Practices

To ensure clean and well-structured code, consider the following tips and best practices:

- Follow the guidelines and examples provided in the Readme to maintain consistency in coding style and structure.
- Use meaningful variable and function names that accurately describe their purpose.
- Break down your code into smaller functions or modules to improve readability and maintainability.
- Implement error handling and data validation to ensure the API handles unexpected situations gracefully.
- Consider implementing security measures, such as authentication and authorization, based on the requirements of your application.
- If you're building the frontend for the MVP routes, follow best practices for organizing code, structuring endpoints, and managing state in your chosen frontend framework.

By adhering to these best practices, you can create a well-designed and efficient Django API that meets the specified requirements.

Remember, the purpose of this assessment is to showcase your Django competencies and demonstrate your ability to build a functional API. Good luck, and don't hesitate to seek help when needed!
