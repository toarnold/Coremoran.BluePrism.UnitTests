# Coremoran - Blue Prism - UnitTests
- [License](LICENSE)

Templates and assert actions to make simple unit tests for [BluePrism](https://www.blueprism.com/) VBOs.

The templates acts as the well known AAA (Arrange, Act, Assert) pattern.

## Coremoran - Unit - Assertions

This VBO contains actions to assert test results. Each action throws an exception in case of a wrong detected value.

This actions can be used in the assert step of each single unit test.

## Coremoran - Unit Test Template (Tests)

This is a process template to test a single action (action under test).

Create a page for each test and join them together on the main page

There a two example test actions
- simple positive test
- exception test

## Coremoran - Unit Test Template (Testsuite)

This is a process template to combine all tests to a suite.

Al least publish this suite to the control room to allow cyclic test (e.g. with the help of the scheduler)

## Dependencies

The ```Coremoran - Unit - Assertions``` VBO needs ```Coremoran - Utility - Json``` this VBO can be found [here](https://github.com/toarnold/Coremoran.BluePrism.Json).