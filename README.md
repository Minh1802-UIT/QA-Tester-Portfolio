<<<<<<< HEAD
# Effective software testing

![example workflow](https://github.com/effective-software-testing/code/actions/workflows/tests.yml/badge.svg)

This repository contains the code examples of the _Software Testing: A Developer's Guide_ book, by [Maurício Aniche](https://www.mauricioaniche.com).

Each folder contains the code examples of their respective chapter:

* Chapter 1: Effective and systematic software testing
* Chapter 2: Specification-based testing
* Chapter 3: Structural testing and code coverage
* Chapter 4: Design by Contracts
* Chapter 5: Property-based testing
* Chapter 6: Test doubles and mocks
* Chapter 7: Designing for testability
* Chapter 8: Test-Driven Development
* Chapter 9: Larger tests
* Chapter 10: Test code quality

Each folder is an independent maven project. You should be able to import the project directly in your favorite IDE (e.g., InteliiJ, Eclipse). You can also run all the tests via `mvn test`.

To run code coverage in chapter 3, go to the ch3 folder and type `mvn clean test jacoco:report`. Then, open the `target/site/jacoco/index.html` file to see the report. If you want to run the mutation coverage, type `mvn clean compile test-compile pitest:mutationCoverage`. The report will be generated in the `target/pit-reports/**/index.html`, where `**` is a string that represents the date time that you ran the report. For Linux or Mac users, I provide bash scripts `coverage.sh` and `mutation.sh` that run the commands above for you.

To run the web tests of chapter 9, you first should run the [Spring PetClinic](https://github.com/spring-projects/spring-petclinic) application. For convenience, we provide a compiled jar here. To run the web app, just go to the ch9 folder and type `java -jar *.jar`.

## Contributing to PRs

Maybe you found a test I missed or a better way to implement the code. You are most welcome to submit your PRs! 

If you do so, I ask you to create another file, with the same name as the original plus some suffix, and add a comment explaining what you did there. I do not want to touch the original files as they match with the code snippets in the book; we do not want readers to get lost.

## License and reuse

You are free to reuse and modify the code provided in this repository, for personal or business purposes, as long as the book is always explicitly mentioned as reference. For example, if you are providing training or workshops, you are required to have a dedicated slide with the picture of the book in each of the slide decks that make use of examples from here.
=======
# QA-Tester-Portfolio
Personal repository showcasing my testing skills for NAB application
>>>>>>> d4855de1b9ebebd883f9c14f7da35e5445dab42d
