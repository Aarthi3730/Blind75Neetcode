Group Anagram Process Flow (Text):
--------------------------------------------------------------
Start
>first count letters it the letter count is same then go to next step or else end
> Input list of words → Example: [cat, tac, dog, god, act].
Take First Word
> Create Group A with first word → ['cat'].
Check Next Word Available?
> No → Go to Final Result Array and End.
> Yes → Move to comparison.
Compare with Group A Representative
> Strings Match? (are they anagrams?)
> Yes → Add to Group A.
> No → Go to "Compare with Other Groups?".
Compare with Other Groups?
> Yes → If match, Add to that Group (e.g., Group B).
> No → Create a New Group with this word.
Check Next Word
> Go back to Step 3.
> Repeat until no words are left.
Final Result Array
> Collect all groups into one array.
> Example Output: [[cat, tac, act], [dog, god]].
End
i dont want to sort the string instead i want to compare the string
