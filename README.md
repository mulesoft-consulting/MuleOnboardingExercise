# MuleSoftOnboarding
The API is purposefully kept simple here. The idea is not to evaluate indepth Mule expertise but more focused around best practices and setup. 
Review the app to understand the components.

You can choose to replace the API being called with any of the other Anypoint APIs found here
https://anypoint.mulesoft.com/apiplatform/anypoint-platform/#/portals

If you have not already created one, create a CloudHub trial account ( remember trail expires in 1 month)

Following are expected as a part of the exercise
•	Mavenize the project as per standards.
•	Make sure all parameters and credentials are externalized into properties and secured as per best practices.
•	Ensure right log for entry, exit and exception scenario ( handling scenarios where multiple requests could be coming in).
•	Make sure all naming conventions are followed. Rename if necessary.
•	Change the API being used from anypoint platform to a different one and return the data back as a CSV or any easily interpretable format ( HTML, CSV,Excel etc). You have to use data weave to do this part.
•	Deploy the app to the dev environment as per standards and settings that need to be followed.
•	Create a MUnit test case for atleast 1 flow.
•	Create properties in a multi environment scenario.
•	Include basic error handling so you return a meaningful message when there is a failure.
