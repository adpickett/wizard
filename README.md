# wizard
A mulitstep form or "wizard"

I have made a multistep form that allows you to have several forms put together organized as steps. 
For this repo, stepOne would be for adding a provider. StepTwo would add a practice and an option to add a location if one was not already attached to a given practice. Steps 3 through 5 are just filled with dummy data so you can see what the form would look like with more than 2 steps.

Included in this repo:

* A dynamic progress bar that counts your completion of the form by percentages based on how many steps there are. There are currently five steps so each steps value would be calculated as 20%.

* The parent component step-wizard where all of the steps will be called.

* StepOne that allows the user to in this example add an insurance provider.

* StepTwo that allows the user to add a practice that would be associated to this insurance provider as well as attach locations to the practice if the location didn't already exist.

* Steps 3,4,5 are just extra steps so the user can see how the multistep form would work with more than 2 steps.

