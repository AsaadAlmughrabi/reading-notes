
## Principles of Object-Oriented Programming (OOP)

1. **Encapsulation**: 
   - **What?** Bundling data and functions into a single unit (object).
   - **Why?** Keeps data safe and organized.
   
2. **Abstraction**:
   - **What?** Simplifying complex systems by focusing on the essentials.
   - **Why?** Makes code easier to understand and maintain.

3. **Inheritance**:
   - **What?** Letting one class inherit properties and behaviors from another.
   - **Why?** Promotes code reuse and makes it easier to manage related classes.

4. **Polymorphism**:
   - **What?** Objects can take on different forms and behaviors.
   - **Why?** Adds flexibility and simplifies code by allowing objects to be treated uniformly.

5. **Composition**:
   - **What?** Building complex objects by combining simpler ones.
   - **Why?** Encourages code reuse and makes systems modular and easier to extend.

## Classes and Objects

- **Classes in Python** provide a blueprint for creating objects.
- **Objects** are instances of classes, encapsulating variables and functions.
- Each class **defines the structure and behavior** of its objects.

## Instantiation

- When a class is instantiated, an **object is created**.
- Accessing variables and functions within objects is done using **dot notation**.

## Independence of Objects

- Objects created from the same class have **independent copies of variables**.
- Modifying one object's variable doesn't affect others.

## Initialization

- The `__init__()` function is a special method called when a class is instantiated.
- It allows for **initialization of variables**.



## Advantages

- Classes and objects facilitate structured organization and encapsulation of data and functionality.
- They promote **code reusability and maintainability**.



---


## Python Testing with pytest: Fixtures and Coverage

**Fixtures**: These are objects or data needed for tests. The `@pytest.fixture` decorator is used to define fixtures, which are then invoked in tests as function arguments. Fixtures are flexible and can be set to execute once per test or only once for multiple tests using the `scope` parameter.

**Code Coverage**: This refers to the extent to which code has been tested. The article suggests using the `pytest-cov` package to measure code coverage with pytest. By running tests with the `--cov` option and specifying the program(s) to test, you can generate coverage reports. The report highlights areas of code that lack coverage, helping ensure thorough testing.





