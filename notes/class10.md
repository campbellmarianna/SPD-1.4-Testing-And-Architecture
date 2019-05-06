        # Debugging & Refactoring
## A 30 Minute Guide to Assuming Your Code is the Problem
###Agenda
- Learning Outcome
- Activity 1: What is Debugging?
- TT
- Interactive Debugging Demo
##Inspiration
"The bug is not moving around in your code, trying to evade you. It is just siting doing the same wring thing over and over again."
- Nick

# Activity 1
Debugging is _______.
- Investigating where
- finding where code is not running all way through as planned and understanding the error the computer is giving your
* IMPORTANT
- Debugging is the most valuable skill of a software engineer
- Fast debugging
    - You are the MVP when you debug things you've never done before
- Forming Your Debugging Process
    - Process: The foundation of effective debugging
    - Experience: Gain experience with code and tools
    - Intuition: Develop your intuition
# Junior Developers: Make Your Lives Easier
- 1. The Usual Suspects
        - Clear caches
        - Reinstall dependencies
- 2. Doubt? Print it Out!
        - console.log("wtf")
- 3. Stuck? Ask!
        - Colleagues/ Friends/ StackOverflow/ Google
# Bugs Are Logical...
    ..so take a systematic approach to solving bugs!
    1. Gather Information
        - BEST SKILL:
            - Expected vs Actual Behavior
            - Error Messages
            - Stack Traces
            - Screenshots
            - Environment Information
                - Operating System
                - Browser
            - Date & Time
            - Logs
    2. Replicate the Issue
        - Figure out how to reproduce the issue with 100% certainty.
    3. Identify the Culprit
        - Be methodical
        - Make 0 assumptions
        - Understand the bug!
    4. Make a Change to Fix It Right
        - Attempt to Replicate again
            - Make sure the steps are written down
        - No Temporary Workarounds
            - Add technical debt
            - Tend to introduce other issues
            - Rarely get replaced later on with true solutions
    5. Mitigate Future Occurrences
        - Add an automated test
        - Share your new knowledge
            - Project documentation
            - Blog post
            - StackOverflow
            - Automated Test (Holy Grail)
        - Submit a patch
            - Or merge your code upstream to master
# Long Term Benefits
- Gain experience points
- Learn how the system works
- Boost confidence

# Tools & Techniques
## Two Essential Tools
- Integration Development Environment (IDE)
    - Minimum Features Required
        - Syntax Highlighting
        - Autocompletion
        - Fast code navigation
        - Debugger
    - Interation Debugger
        - Pause code execution
        - Step through the execution of the code
        - Examine variables
        - Explore
# Techniques
- Trace Backward
    - Do this when the error is thrown from a known location
- Trace Forward
    - Start at beginning and go the opposite direction when the problem
- Divide & Conquer
    - Identify different code sections
    - Set breakpoints at the boundaries
    - Isolate
## Debugging Dev tools
## Additional Techniques
- Get Help
    - RTFM/RTFD
    - Project forums or issue queue
    - StackOverflow
    - IRC - Oldest Backend Web Protocal
    - Ask a Colleague
        - Expert in that area
        - Senior developer
    - Rubber Debugging
- Take a Break
    - Clear your ind and start fresh
    - Forget invalid assumptions
    - Recharge your batteries
    - Let your subconscious work

### Your already there you just have to believe future you can do it!
