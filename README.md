# Code Assesment.

Please find the solution links:
Longest word:
https://codeinterview.io/FNOSTTEZFY
Shortest Word:
https://codeinterview.io/OSNCLVNIJV

Question Asked:
/*
Write a method or function in the major programming language of your choice that returns the 
longest word in a sentence and its length.For example, “The cow jumped over the moon.” 
should return “jumped” and 6.
Write unit tests, reworking code as needed
Add a method that returns the shortest word and length with unit tests
Create a README documenting any assumptions you made and including instructions on how to build and execute your tests.
Share your code using GitHub or similar.*/

PS: I have coded this out of https://codeinterview.io/ so the results were pasted to word docs and uploading the same.
**********************************************************************************************************
Readme for Longest word solution:

/** Assumptions:
* Assumed that the return type can be an array with first element as the longest word 
* and second element as it's length, the result will be like [word, length].
* Also assumed that there will be atleast one word which has larger length in the sentence than others and there are no two largest words with equal length, incase there are two words whose length is equal and more than rest of the words ,I intend to return the first word that matches my criterion.
*/
/*
Unit Tests:
1. Check the argument is a string if not return invalid input.
2.Checking for invalid length of sentence.
3.Check if input is valid : “The cow jumped over the moon.” The out put should be valid result : [jumped, 6]
*/
************************************************************************************************************
Readme for Finding Shortest word solution:


/**1.Though I tweaked the first solution to return shortest word, I have also submitted an Alternative/fastest way to find the shortest word by using a compare function similar to Java’s Comparator interface and passing that function to Arrays.sort();
I feel this solution as more elegant and shorter than the first one:
*/


/** Assumptions:
* Assumed that the return type can be an array with first element as the longest word 
* and second element as it's length, the result will be like [word, length].
* Also assumed that there will be atleast one word which has shorter length in the sentence than others
*Assumed there will not be any  empty string of tabs and considered it a word like "" ' '" rest of the sentence"
If need be we can add an additional check not to return if its an empty string.
*Assumed to return first shortest word that matches if there are more than one word of same short length
*/
/*
Unit Tests:
1. Check the argument is a string if not return invalid input.
2.Checking for invalid length of sentence.
3. can also check if return result is not an empty string if needed.
4.Check if input is valid : “The cow jumped over on the moon.” The out put should be valid result : [on, 2]

*/

/** How to Run
* Open codeinterview.io and clcik on TryDemo which opensup an editor
* select Javascript(node) as programming language, copy paste the below code
* Click Run should give you result array
*/
