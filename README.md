# Scala Project: Regular expression matcher

## What is Regular expression 
A sequence of characters that define a search pattern.
Or
Expression used to specify a set of strings required for a particular purpose.

(a|b)* denotes 
{ε, "a", "b", "aa", "ab", "ba", "bb", "aaa", ...} 

## What is Parser
It is a
1. a function
2. that takes some input in form of a raw sequence (like a string of characters)
3. returns some meaningful data built from the raw input

## Parser combinatory in Scala
A Parser Combinator implements a grammar using a structure of parser objects. There are two aspects to the result of a parser:
success or failure
the result
These parsers are constructed from primitive parsers and composition operators, such as sequencing, alternation, optionality, repetition.
P1 ~ P2
P1 | P2

## References

1. Regular expression retrieved from  https://en.wikipedia.org/wiki/Regular_expression on 2th Dec 2019
2. Parser retrieved from 
   https://www.scala-lang.org/api/2.12.2/scala-parser-combinators/scala/util/parsing/combinator/Parsers.html No date
3. Parser combinatory retrieved from 
   https://martinfowler.com/dslCatalog/parserCombinator.html No date



