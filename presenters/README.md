# Notes for presenters

This kata is great for those with at least some coding experience but less TDD experience. The problem is sufficiently complex that a naive implementation not using TDD can easily result in a fairly complicated solution, especially when implementing the subtractive cases (e.g. IV, IX, XL, etc.). 

Participants can implement the different test cases in any order they want, but the instructions provide the cases in a specific order to help with the decomposition of the problem. The instructions also leave the subtractive cases until the very end so that participants will have already refactored from simple conditional statements to a lookup-based solution. In that case adding the subtractive cases is a simple matter of adding entries to the lookup.

The primary intent of this kata is to help participants see that using TDD can result in a much simpler solution than might otherwise be arrived at. If you want to ensure that this point gets across take a few minutes at the beginning to ask the participants to think of what their solution might look like before starting the problem. Ask what kinds of checks they might have to do to cover all the cases in a naive solution, especially the subtractive cases. At the end make sure to show that adding the subtractive cases can be as simple as adding entries to a lookup for those that might not have gotten that far.

## Challenges while presenting

For those less experienced with coding or TDD it can be a challenge to get far enough in the kata during a 50-60 minute session to get to the "ah-ha" moment of adding the subtractive cases. While the primary learning objective won't be met in that case, the kata can still be a good TDD practice. It can be helpful to implment or partially implement the solution with the participants to help them follow the TDD process while following the steps in the instructions. You should have some "second oven" code ready in case the participants run out of time. This code should be implemented up through Test 8 in the instructions. Then you can show the participants that adding the subtractive cases is just a matter of adding entries to a lookup.

## Learning objectives

The primary learning objective of this kata is to show participants that using TDD can result in a simpler solution than might otherwise be arrived at. It can also be used as an introduction to the TDD process because the instructions help show the decomposition process that TDD facilitates. This kata can also be a good opportunity to explore a testing framework's ability to provide test data in a tabular format (e.g. Nunit's `TestCase` attribute).