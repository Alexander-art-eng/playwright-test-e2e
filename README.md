# Playwright Testing Project

This project demonstrates the use of the Playwright framework to perform end-to-end testing on web applications. The tests are designed to validate the functionality and user interface of a simple Todo application and other web pages.

## Project Overview

The project consists of several test suites written in TypeScript using the Playwright testing framework. These tests cover various aspects of web application functionality, including navigation, user interactions, and data persistence.

### Key Features

- **Automated UI Testing**: Tests are automated to simulate user interactions with the web application, ensuring that the UI behaves as expected.
- **Cross-Browser Testing**: Playwright supports testing across different browsers, enhancing the reliability of the tests.
- **Data Persistence Verification**: Tests include checks to ensure that data is correctly stored and retrieved from local storage.
- **Responsive Design Testing**: The tests verify that the application is responsive and functions correctly on different screen sizes.

## Test Suites

### 1. Todo Application Tests

Located in `tests-examples/demo-todo-app.spec.ts`, this suite tests a Todo application with the following scenarios:

- Adding new todo items and verifying their presence in the list.
- Marking items as completed and verifying their state.
- Editing and deleting todo items.
- Ensuring data persistence across page reloads.

### 2. Google Homepage Test

Located in `tests/first-test.spec.ts`, this test verifies the title of the Google homepage:

### 3. Playwright Documentation Tests

Located in `tests/example.spec.ts`, this suite tests the Playwright documentation site:

- Verifying the page title contains "Playwright".
- Navigating to the "Get started" page and checking for the "Installation" heading.

## How to Run the Tests

1. **Install Dependencies**: Ensure you have Node.js installed, then run `npm install` to install the necessary packages.

2. **Run Tests**: Use the command `npx playwright test` to execute the test suites.

3. **View Results**: Test results will be displayed in the console, and you can view detailed reports in the Playwright Test Report.

## Conclusion

This project demonstrates the use of Playwright for comprehensive web application testing. The tests ensure that the application functions correctly and provides a seamless user experience. By automating various scenarios, the project highlights the effectiveness of Playwright in ensuring software quality and reliability.

---

Feel free to explore the test files and modify them to suit your testing needs. Contributions and feedback are welcome!
