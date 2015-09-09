# JavaScript: The Good Parts
### Random learnings from *JavaScript: The Good Parts*, by Douglas Crockford

## Chapter 1: Good Parts

> JavaScript is a language with more than its share of bad parts. It went from non-existence to global adoption in an alarmingly short period of time...  JavaScript's popularity is almost completely independent of its qualities as a programming language.
> Fortunately, JavaScript has some extraordinarily good parts. In JavaScript, there is a beautiful, elegant, highly expressive language that is buried under a steaming pile of good intentions and blunders.

 > JavaScript is built on some very good ideas and a few very bad ones.
 >The very good ideas include functions, loose typing, dynamic objects, and an expressive object literal notation. The bad ideas inclue a programming model based on global variables.

 ##Chapter 2: Grammar

 JavaScript has a single number type and there is no seperate integer type, so 1 and 1.0 are the same. According to Crockford, this is a good thing because problems of overflow of short integers are avoided, and all you need to know is that a number is a number.

 NaN is not equal to any value, including itself.