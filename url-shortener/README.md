# URL Shortener Take-Home Exercise (Fullstack)

## Instructions

Your task is to create a URL shortener web application (similar to [bitly](https://bitly.com/) or [TinyURL](https://tinyurl.com/)). This exercise is intentionally open-ended, and you are welcome to implement your solution using the language and tech stack of your choice. If you are familiar with React & Next.js, please use those for your submission. The core functionality of the application should be expressed through your own original code.

You should aim to spend no more than 2 hours on this project. If you don't complete everything in 2 hours, please submit what you have - we value your time and want to see your prioritization skills.

### Application Description

At the root path (e.g., http://localhost:8080/), a user should be presented with a form that allows them to input a URL. When a user submits that form, it should convert the input URL to a shortened version and present that to the user.

The shortened URL should be in the format: http://localhost:8080/{slug}, where `{slug}` is a unique identifier for the original URL.

When a user navigates to the shortened URL, they should be redirected to the original URL that was used to generate this shortened URL.

### Minimum Requirements

* Format and method of generating slugs for shortened URLs are up to you
* Shortened URLs do not need to persist across server shutdown/startup (i.e., setting up a DB isn't necessary - server memory should suffice)
* Only allow valid http(s) URLs

If you have additional time, consider spending it on testing or UI improvements as opposed to supplemental features.

## Evaluation Criteria

We will be evaluating your submission based on the following:

1. Functionality: Does the application work as described?
2. Code quality: Is the code clean, well-organized, and following best practices?
3. Error handling: How does the application handle invalid inputs or errors?
4. Technical choices: Are the chosen technologies appropriate for the task?
5. Documentation: Is the code well-commented and the README clear?

## Deliverables

Please fill out the sections below in the _README.md_ of your project and submit according to the instructions you received with this project. Your code can be sent as a zip file or a link to a repository containing your project.

---

## Implementation Details

<!-- Provide a short description of your implementation (technologies used, brief overview of project architecture, etc.) -->

## How to Run

<!--
- Include instructions on how to run your implementation locally. Be sure to include any necessary setup steps, such as installing dependencies, as well as the commands to start the application.
-->

## Testing

<!-- Describe how you tested your solution (automated testing, manual testing process, screenshots, etc.) -->

## Tools Used

<!--
- Describe any tools you used in developing your solution (e.g. ChatGPT for generating ideas and styles)
- Note: The use of AI tools is not discouraged, but they should be used judiciously.
-->

---

Good luck, and we look forward to reviewing your submission!
