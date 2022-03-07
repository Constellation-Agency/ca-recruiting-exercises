# Constellation Agency > Software Engineering > Take-Home Project

## Introduction

This take-home project is called the **Condition Builder**. This tool allows you to load an array of data and layer in _and_/_or_ conditions to filter the data. The goal of this take-home project is to test the following:

- Ability to create a UI of an web application based on provided specifications.
- Understanding of requirements and attention to detail.
- Ability to work with complex react conditional logic.
- Ability to handle error states within an application.

[Condition Builder](https://ca-recruiting-exercises.vercel.app/)
![demo](./images/demo.gif)

## Features

1. User should be able to load array of data from an url.
2. User should be able to build **or** conditions concatenated with **and** conditions.
   - For an example, any `c{n}` resolved to be a boolean (ex. name equals to "something"), then the condition can be formed as `(c1 || c2 || c3) && (c4 || c5)`.
3. User should be able to add `or` condition by pressing the plus button at the end of each row.
4. User should be able to add `and` condition by pressing the and button below each card container.
5. User should be able to see list of loaded data on the bottom of the page.
6. User should be able to see filtered data list when valid conditions are built.

## Supported condition operators

Each condition should have few comparisons.

- Equals
- Greater than
- Less than
- Contain
- Not Contain
- Regex

In the end, these conditions should filter out the list of data.

## What you should do?

### Requirements

- Condition builder UI (Top section)
  ![Condition Builder UI](./images/condition_builder_ui.png)
- Result section (Can be choice of yours. Does not have to be in table. Can be simple as a text. Ex. Out of 1000 rows, 10 filtered out., etc...)
  ![Result UI](./images/result_ui.png)
- Input validations
  - For comparison operators (Greater Than, Less Than), the entered value must be number. Visually indicate this invalid input value.

### Nice to have

The following is optional. These are nice to have options, but not requirements. However, if you are able to do those, it certainly would help us to make better decision on your skillset.

- Visual feedback on where new `or` condition will be inserted when user hover over plus button (optional)
  ![Visual Feedback](/images/row_feedback.gif)
- Input validations
  - For comparison operators (Greater Than, Less Than), the entered value must be number. Visually indicate this invalid input value.
- Cypress tests (optional)
- Unit test (optional)

## How to submit?

In order to submit your take-home project, please create new **private repository** and add the following members.


- [Nauman Hafiz](github.com/canisvulgaris)
- [Jonathan Parsons](github.com/jmparsons)
- [Edward Chung](github.com/munjo5746)
- [Yoelvis Mulen](github.com/ymulenll)