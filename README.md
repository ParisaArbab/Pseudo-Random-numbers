# Pseudo-Random-numbers
create a pseudo-random number generator (PRNG) using the text file "war-and-peace.txt,"
The WarAndPeacePseudoRandomNumberGenerator class is defined, which can take an optional seed value during initialization.
Inside the random method, the text file "war-and-peace.txt" is opened and read.
A random index within the length of the text is generated.
The character at the randomly chosen index is retrieved from the text.
The character is converted to its Unicode code point (using ord()) and normalized to a floating-point number between 0 and 1 by dividing it by 255.
This normalized number is returned as the pseudo-random number.
10,000 pseudo-random numbers are generated using the PRNG object.
The minimum, maximum, and mean of these numbers are calculated and printed.
Regarding how the pseudo-random numbers are produced:

The PRNG uses characters from the text file "war-and-peace.txt" to generate pseudo-random numbers.
It selects characters randomly from the text and converts them to numbers between 0 and 1.
Since the characters in the text are chosen randomly, the resulting sequence of pseudo-random numbers should exhibit properties of randomness.
After generating 10,000 pseudo-random numbers, you can examine their minimum, maximum, and mean values to assess their distribution and whether they make sense based on the method of generation.
