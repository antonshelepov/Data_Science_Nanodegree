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
