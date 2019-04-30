# How to Approach Testing
- Test requirements
- Test designs
- Test edge
## How much of percentage of time should be spent writing Test?
- 8-25%

## All the Tests!
1. Unit Test - Overall functionality of the code
2. Integration Test - Backend connecting to your frontend actually checks UI
3. System Tests - testing integration of systems and packages, adding third party github package
4. Component tests - Testing replaced with real
5. Regression tests -

1. Unit: Unit testing is the execution of a complete class, routine, or small program
Ex: test multiplication - testing one thing and one thing
2. Integration: Combined execution of two or more classes, packages, components,
or subsystems that have been created by multiple programmers
3. Component: Execution of a class, package, small program, or other program element
that involves the work of multiple programmers or programming teams, which is
tested in isolation from the more complete system
4. System: Execution of the software in its final configuration
5. Regression: Repetition of previously executed test cases for the purpose of
finding defects in software that previously passed the same set of tests
- We don't write these, there isn't a syntax thing

## Basis Testing
- Testing the execution of all possible paths of a program
- It is really important as an engineer to test the decision you tell the machine to make

## Test Data and Control Flow
### Data Flow: 3 Main States
- Defined
- Used
- Killed

### Control Flow: Test

## Equivalence Partitioning
- A good test case covers a large part of the possible input data.
- Be as DRY you are in your code in your tests

## Error Guessing
- Creating test cases based upon
- Gut check yourself for when you need to test

## Boundary Guesses

## Bad Data vs Good Data
### Bad Data

### Good Data
- they want their old stuff to work
- make up the number that's relevant

## Common Errors
- Find your problematic classess/methods: usually not an even distribution
- General breakdown of errors:
    - 25.18% Structural
    - 22.44% Data
    - 16.19% Functionality as implementated
    - 9.88% Construction
    - 8.98% Integration
    - 8.12% Functional requirements
-
## Food for Thought
What can you do to reduce the number of test case errors?
- Software Construction
- Validation
- Seeing and comparing different ways to do the same thing
- Create a Boilerplate for Test to start with
- Make simple
- Keep your test cases
- Plug unit tests into a test framework (provides readable out and log that output)
- Code Review

## How do you know things are working overtime
- By keeping records
### What Records to Keep
- Critital, High, Medium, Low
- Origin of the defect: requirements, design, coding, or testing
- Subclassification of coding defect: off-by-one, bad assignment, bad array,

- Administrative description of the defect (the date reported )
- You can do so using Trello Github Projects
### Great tickets change developers lives

## What data would you track to look at the data of your project?
- size
- speed (constant, or going down) - equation time of execution by any mechnicism
- badges (shields.io)
- how often people commit
- how long does it take to find the bug
- administrative description of the defect (the date reported)
- reported it, a title or description
- full description of the problem
