# Anagram Detector

Write a program that, given a word and a list of possible anagrams, selects the correct one(s).

In other words, given: `"listen"` and `["enlists", "google", "inlets", "banana"]` the program should return "inlets".

Think about: What are some scenarios we should test for?

What makes something an anagram? The two words have the same letters...
How can we check to see if they have exactly the same letters?

Is "Clint Eastwood" really an anagram of "Old West Action"?
Is "Eleven plus two" = "Twelve plus one"?
Is "Western Union" an anagram of "No Wire Unsent"?
Does "The Morse Code" have the same letters as "Here come dots"?
How about "The Great New York Rapid Transit Tunnel" and "Giant work in street, partly underneath"?

You tell us.

Hint:

Write a method that checks if two words are anagrams.  It should return true/false.  Use this to check the list.

```
def anagram?(word1, word2)

end
```

Bonus:

- Make a nice from end.  Allow the use to enter two phrases, indicate if they are anagrams of each other.
- If not, show where they differ.
