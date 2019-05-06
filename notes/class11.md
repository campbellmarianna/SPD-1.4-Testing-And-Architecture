# Ticket Writing
# Activity Link:
https://drive.google.com/drive/u/1/folders/1X8IAuMv846e_NTyb5ZXL67NGFbo-y2kx

## You're a software engineer at a startup..
    - You get a ticket
    - Delete Data in the Database

## But what about ...
-

## What did I just see?!
- A terrible example of how to write a feature ticket

## What is a ticket?
- Write a User Story

## A Well Written Feature Ticket
1. User Story: concise statement on what we're building and why
    - Should convey why we're building this feature. What
    - Suggested Format:
        - As a [user persona] I want to [interation_with_feature] so that I can [end_user goal]
        - Example:
            - As a small business owner using inventory organizer I want to create an account so that I can only see my products and product data.
2. Requirements: What are you building
    - Describes what the feature is and how it should behave
    - Below are examples of what to capture in requirements:
        - Should be detailed with all known behaviors captured
        - Should describe all states
    - Example:
        - One Login in view with 2 input fields, one for username and another for password. There should also be one submit button.
        - One Signup View with 4 input fields for name, email, username, password.
        - There should be two button links in the dashboard: Signup and Login.
            - When you're logged in in you should see sign up and vice versa.
        - We also need a user model
        - Sprinkle the user object throughout the program

3. Business Value
- A concise, 1-2 sentence statement as to why we're building this feature, and what value it adds to the company.
- A non-technical person(executive, board members, etc.) should be able to read this statement and understand why it's necessary.
    - Example: A user would probably not what their inventory information online for everyone to see, a user would like their inventory information kept private.

4. Edge Cases (they will creep up that is just how these things work)
- Along with requirements, if
    - Example: Invalid Input - Numbers, Emoji's when there should be a alphanumeric password

5. Risks (not always applicable)
- Risks should be noted and ROAMed:
- Resolve: Risk has been answered/avoided/eliminated
- Own: Risk is now owned by someone who's responsible for handling it
- Accept: Risk is accepted, and nothing will be done
- Mitigate: The impact/likelihood of the risk has been decreased through actions by the team
    - Example of Risk: Technology brand new to the team
    - Example: Risk: Login In As The Wrong User Own the Risk

## Writing Tickets take time. It may take longer than writing your first one during this class, it should take longer because the

## Writing Clear Bug Tickets
    - Summary: 1-2 sentence describing the issue
    - Diagnostic Info: Platform, OS Version, Browser Version, SDK version, etc.
    - Repro Steps: Sequential Steps


My Overall Ticket Example:
User Story
    As a small business owner using inventory organizer I want to create an account so that I can only see my products and product data.
Requirements:
    - One Login in view with 2 input fields, one for username and another for password. There should also be one submit button.
    - One Signup View with 4 input fields for name, email, username, password.
    - There should be two button links in the dashboard: Signup and Login.
        - When you're logged in in you shouldn't see sign up and vice versa.
    - We also need a user model
    - Sprinkle the user object throughout the program
Business Value
    A user would probably not what their inventory information online for everyone to see, a user would like their inventory information kept private.
Edge Case
    Invalid Input - Numbers, Emoji's when there should be a alphanumeric password

## Summary
    - Break tickets up into iterative deliverables (MVP -> Final Product)
    - Provide enough detail that any engineer can read it and understand what's needed and why we're
