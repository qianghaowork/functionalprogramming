# Functional Programming Fun Codes
Scala programs from coursera functional programming

## 1. Recursions
   Pascal’s Triangle
   
   Parentheses Balancing
   
   Coin Change
   
## 2. Functional Sets

   Define a function singletonSet which creates a singleton set from one integer value
   
   Define the functions union,intersect, and diff, which takes two sets, and return, respectively, their union, intersection and differences. diff(s, t) returns a set which contains all the elements of the set s that are not in the set t.
   
   Define the function filter which selects only the elements of a set that are accepted by a given predicate p. The filtered elements are returned as a new set.

## 3. Object Oriented Sets

   Implement an abstract class TweetSet with two concrete subclasses,Empty which represents an empty set, and NonEmpty(elem: Tweet, left: TweetSet, right: TweetSet), which represents a non-empty set as a binary tree rooted at elem. The tweets are indexed by their text bodies: the bodies of all tweets on the left are lexicographically smaller than elem and all bodies of elements on the right are lexicographically greater.

## 4. Huffman Coding

Huffman coding is a compression algorithm that can be used to compress lists of characters.

A Huffman code can be represented by a binary tree whose leaves represent the characters that should be encoded. The code tree below can represent the characters A to H.


