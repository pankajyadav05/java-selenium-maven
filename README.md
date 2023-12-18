### Take-Home Assignment: Selenium WebDriver Testing with Maven and Reporting

## Objective

Develop an automated test suite using Selenium WebDriver in Java, managed with Maven, to perform geolocation testing and Login Functionality Testing. [BONUS] Generate JSON reports for each test case.

## Tasks

1. **Geolocation Testing Using Selenium with Chrome DevTools**:

   - Implement tests using Selenium 4 and Java for geolocation emulation [Use this demo site](https://my-location.org)
   - Include tests for specific geolocation scenarios, utilizing Selenium 4's DevTools integration.

2. **Login Functionality Testing on OrangeHRM**:

   - Automate the login process for the [OrangeHRM open-source demo site](https://opensource-demo.orangehrmlive.com).
   - Test both successful login and handling of invalid credentials.

3. **Maven Integration**:

   - Structure your project as a Maven project with appropriate `pom.xml` configuration.
   - Include dependencies for Selenium, WebDriverManager, any reporting tools, and other required libraries.

4. **Documentation**:

   - Provide a `README.md` file with instructions on how to:
     - Set up the project (including any prerequisites).
     - Build and run the tests using Maven commands.

5. **Submission**:
   - Submit the project URL as a **PRIVATE** Git repository (also provide access) to prithvi@smartdino.tech and cc roshan@smartdino.tech, pankajyadav.code@gmail.com.
   - Ensure code quality and organization are in line with best practices.

## Bonus

- **JSON Report Generation**: Set up report generation to output detailed information for each test execution in JSON format.

## Evaluation Criteria

- **Code Quality**: Clean, well-organized, maintainable code.
- **Test Coverage**: Comprehensive tests covering stated scenarios.
- **Maven Integration**: Proper use of Maven for dependency management and project build.
- **Reporting**: Accurate and informative JSON reports for each test.
- **Documentation**: Clear, concise instructions in the `README.md`.
- **If you're not able to implement all parts of the task, partial submissions are welcome.**
- Check full details about Evaluation criteria here [marks.md](marks.md)

## Example Maven Commands for README.md

- **To Build the Project**:

  ```
  mvn clean install
  ```

  This command will compile the project and run any tests.

- **To Run Tests**:

  ```
  mvn test
  ```

  This will execute the test cases.

- **Viewing Reports**:
  Provide instructions on where to find the JSON reports generated after test execution (e.g., in the `target` directory or a custom specified path).
