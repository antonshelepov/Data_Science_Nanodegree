## Testing
### Testing and Data Science
* Problems that could occur in data science aren’t always easily detectable; you might have values being encoded incorrectly, features being used inappropriately, or unexpected data breaking assumptions.
* To catch these errors, you have to check for the quality and accuracy of your analysis in addition to the quality of your code. Proper testing is necessary to avoid unexpected surprises and have confidence in your results.
* Test-driven development (TDD): A development process in which you write tests for tasks before you even write the code to implement those tasks.
* Unit test: A type of test that covers a “unit” of code—usually a single function—independently from the rest of the program.
### Resources
* [Four Ways Data Science Goes Wrong and How Test-Driven Data Analysis Can Help](https://www.predictiveanalyticsworld.com/machinelearningtimes/four-ways-data-science-goes-wrong-and-how-test-driven-data-analysis-can-help/6947/)
* [Getting Started Testing by Ned Batchelder](https://speakerdeck.com/pycon2014/getting-started-testing-by-ned-batchelder?slide=13)
### Unit Tests
The advantage of unit tests is that they are isolated from the rest of your program, and thus, no dependencies are involved. They don't require access to databases, APIs, or other external sources of information. However, passing unit tests isn’t always enough to prove that our program is working successfully. To show that all the parts of our program work with each other properly, communicating and transferring data between them correctly, we use integration tests. In this lesson, we'll focus on unit tests; however, when you start building larger programs, you will want to use integration tests as well.
[Integration Testing](https://www.fullstackpython.com/integration-testing.html)
[Unit Testing Tools](https://docs.pytest.org/en/latest/getting-started.html)
### Test-driven Development and DS
* *Test-driven development*: Writing tests before you write the code that’s being tested. Your test fails at first, and you know you’ve finished implementing a task when the test passes.
* Tests can check for different scenarios and edge cases before you even start to write your function. When start implementing your function, you can run the test to get immediate feedback on whether it works or not as you tweak your function.
* When refactoring or adding to your code, tests help you rest assured that the rest of your code didn't break while you were making those changes. Tests also helps ensure that your function behavior is repeatable, regardless of external parameters such as hardware and time.
[Data Science TDD](https://www.linkedin.com/pulse/data-science-test-driven-development-sam-savage/)
[Pivotal Engineering Journal](https://tanzu.vmware.com/content/pivotal-engineering-journal)
[Test Driven Development is essential for good data science. Here’s why.](https://medium.com/uk-hydrographic-office/test-driven-development-is-essential-for-good-data-science-heres-why-db7975a03a44)
[Testing Your Code](https://docs.python-guide.org/writing/tests/)
## Logging
### Log Messages
Logging is the process of recording messages to describe events that have occurred while running your software. Let's take a look at a few examples, and learn tips for writing good log messages.
### Tips
* Be professional and clear
```
Bad: Hmmm... this isn't working???
Bad: idk.... :(
Good: Couldn't parse file.
```
* Be concise
```
Bad: Start Product Recommendation Process
Bad: We have completed the steps necessary and will now proceed with the recommendation process for the records in our product database.
Good: Generating product recommendations.
```
* Provide any useful information
```
Bad: Failed to read location data
Good: Failed to read location data: store_id 8324971
```
![logging](/screenshots/logging.png "quiz logging")
