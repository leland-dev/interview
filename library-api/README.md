# Library API Take-Home Exercise (Backend)

## Instructions

Your task is to create an API for a simple book management system that allows users to manage information about authors and the books they have written. This exercise is intentionally open-ended, and you are welcome to implement your solution using the language and tech stack of your choice. If you are familiar with GraphQL, please use that for your submission (as opposed to a RESTful API). The core functionality of the application should be expressed through your own original code.

You should aim to spend no more than 2 hours on this project. If you don't complete everything in 2 hours, please submit what you have - we value your time and want to see your prioritization skills.

### Application Description

Implement an API that allows users to perform CRUD (Create, Read, Update, Delete) operations on authors and books. Each author should have the following properties:

```
- id (unique identifier)
- name
- bio
- created at (timestamp)
```

Each book should have the following properties:

```
- id (unique identifier)
- title
- description
- author id (foreign key referencing the author)
- published date
- created at (timestamp)
```

The API should support the following operations:

1. Create a new author
2. Retrieve a list of all authors
3. Retrieve a specific author by ID
4. Update an author
5. Delete an author
6. Create a new book
7. Retrieve a list of all books
8. Retrieve a specific book by ID
9. Update a book
10. Delete a book
11. Retrieve a list of all books written by a specific author

### Minimum Requirements

* Implement all CRUD operations for authors and books
* Implement the "list books by author" functionality
* Use appropriate HTTP methods and status codes
* Implement basic input validation
* Authors and books do not need to persist across server shutdown/startup (i.e., setting up a DB isn't necessary - server memory should suffice)
* Provide clear API documentation (can be in the README)

If you have additional time, consider spending it on testing, error handling, or implementing more advanced features like searching, sorting, or filtering.

## Evaluation Criteria

We will be evaluating your submission based on the following:

1. Functionality: Does the API work as described?
2. Code quality: Is the code clean, well-organized, and following best practices?
3. API design: Are the endpoints intuitive?
4. Data modeling: How well are the relationships between authors and books represented?
5. Error handling: How does the application handle invalid inputs or errors?
6. Technical choices: Are the chosen technologies appropriate for the task?
7. Documentation: Is the code well-commented and the README clear?

## Deliverables

Please fill out the sections below in the _README.md_ of your project and submit according to the instructions you received with this project. Your code can be sent as a zip file or a link to a repository containing your project.

---

## Implementation Details

<!-- Provide a short description of your implementation (technologies used, brief overview of project architecture, etc.) -->

## How to Run

<!--
- Include instructions on how to run your implementation locally. Be sure to include any necessary setup steps, such as installing dependencies, as well as the commands to start the application.
-->

## API Documentation

<!--
- Provide clear documentation for your API endpoints, including:
  - HTTP method
  - URL
  - Request parameters (if any)
  - Request body format (if applicable)
  - Response format
  - Example curl commands or Postman collection (optional but appreciated)
-->

## Testing

<!-- Describe how you tested your solution (automated testing, manual testing process, etc.) -->

## Tools Used

<!--
- Describe any tools you used in developing your solution (e.g. ChatGPT for generating ideas)
- Note: The use of AI tools is not discouraged, but they should be used judiciously.
-->

---

Good luck, and we look forward to reviewing your submission!
