# Feature guild

Make sure that you understand

## Overview

The following is a list of guidelines and principles every engineer must follow for the implementation of the features.

## Read the requirements

1. Make sure that you understand every sentence and every word in both functional and non-functional requirements defined for the task.

2. Communicate and address every questions and potential misunderstanding you have before starting the coding.

   Make sure that you have everything that you need to complete the implementation before starting on it.

3. Suggest workarounds and try to make your own decision if some non-critical information is not explicitly defined in the requirements.

   Requirements are not code; they will always contain some level of ambiguity and gaps.

   It is your job as an engineer to convert natural language definition (text) into a formal one (code).

4. Capture all your all questions, workarounds and decision in the task tracker.

   Do not capture your conversations, only issues and their solutions or other decisions on the implementation approach.

5. Be able to explain how you are going to confirm that the features address all requirements, both functional, non-functional and architectural.

6. Suggest simpler implementation or changes in requirements to simplify the implementation if it does not contradict client’s goals.

7. does not contradict client’s goals.

   Do not capture your conversations, only issues and their solutions or other decisions on the implementation approach.

## Implement the feature

1. The code shall cover both positive and negative scenarios

2. The code shall work properly with edge cases of the potential input

3. In case of errors the system shall either continue to work and write error information into logs or shutdown and provide a clear response to user with the explanation of the source of error.

4. The code shall log the necessary information for potential troubleshooting in a non-local environment.

5. Reproduce the issue and understand the root cause before fixing it.

6. Look for ways to automate your work and avoid creating repetitive boilerplate code.

7. Push the code at least daily etc

8. Create good UI when it is not defined explicitly using best practices and UI frameworks.

9. Update the technical documentation of the system

## Communicate

1. If some dependency for the complete and successful implementation is not working (backend API, infrastructural configuration, etc.) it is your responsibility to communicate with the owner of the dependency (backend developer, devops engineer, project manager, etc.) to push your feature to the completion.

2. Add helpful information for the QA team on how to better test the implementation to the ticket tracker (potential impact in the complex system, which areas may be affected, how to access the functionality that does not have UI, etc.)

3. Provide updates for the feature implementation in a ticket tracker if it takes more than a day.

4. Notify lead engineer or project manager if the implementation takes longer that you planned.

5. Ask for help if you stuck and do not know how to proceed with the implementation.

6. Communicate any configuration or other dependencies necessary for production release of the feature (infrastructure configuration updates, adding new parameters to the build, running one-time migrations or other scripts, etc.) and capture that information in the ticket.

7. It is your responsibility to test your code and provide production ready implementation.

   QA is not for cleaning up the mess after the engineers.

8. Make sure the code builds without any errors and warnings (including coding guidelines style checks).

9. Do not push the code that you did not run.

10. Test all positive and negative scenarios.

11. Test edge cases and error handling.

12. Verify non-functional and architectural requirements.

13. Verify integration with other components and dependencies.

14. Verify that your changes do not break the build in CI server.

15. Test the feature in a non-local environment after the push.
